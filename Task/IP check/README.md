

---

# IP Address Analyzer

A simple Python script to validate, classify, and analyze IPv4 addresses. It determines whether an IP is valid, private or public, and provides detailed network information such as IP class, default subnet mask, network address, broadcast address, total hosts, and usable host range.

---

## Features

- Validates user-input IP address.
- Checks if the IP is private or public.
- Classifies IPv4 addresses into Class A, B, or C.
- Displays default subnet mask based on IP class.
- Calculates network address, broadcast address, total number of hosts, and usable host range.
- Handles invalid IP inputs gracefully.

---

## Requirements

- Python 3.x

The script uses the built-in `ipaddress` module, so no additional installations are required.

---

## Usage

1. Clone or download this repository.
2. Run the script using Python:

```bash
python 'real check ip.py'
```

3. When prompted, enter an IP address (IPv4 or IPv6).

---

## Example

```plaintext
Enter IP address: 192.168.1.10
Valid IP: Yes
Type: Private
Class: C
Default Subnet Mask: 255.255.255.0
Network Address: 192.168.1.0
Broadcast Address: 192.168.1.255
Total Hosts: 254
Usable Host Range: 192.168.1.1 - 192.168.1.254
```

---


---




---

Feel free to customize this README further based on your preferences or add any additional sections such as credits, contact info, etc.

Would you like me to prepare the script file name or any other details?
