# Wireshark Flag Capture

This project contains 5 files that include captured network data with hidden flags. Using Wireshark, I analyzed the files to extract all the flags.

## Files Included

- `challenge_1_traffic.pcap`
- `challenge_2_traffic.pcap`
- `challenge_3_traffic.pcap`
- `challenge_4_traffic.pcap`
- `challenge_5_traffic.pcap`


## How to Use

1. Download and install [Wireshark](https://www.wireshark.org/).
2. Open each `.pcap` file in Wireshark.
3. Analyze the traffic to locate the hidden flags.<br>
   -For some files, flags are visible in packet details or payload.<br>
   -For others, decryption or further analysis is necessary
4. Extract the flags from the packets (usually visible in the packet details or payload).

## Flags

The flags extracted from each file are as follows:

- **File 1:** `FLAG{http_easy_capture}`
- **File 2:** `FLAG_dns_exfiltration`
- **File 3:** `FLAG{tcp_stream_reassembly}`
- **File 4:** `FLAG{smtp_base64}`
- **File 5:** `FLAG{ic_icmp}`



## Notes

- Make sure to filter traffic by protocol or port if needed to locate the flags efficiently.
- Use Wireshark's search feature (Ctrl+F) to find strings or specific patterns related to the flags.


