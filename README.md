# Cloud Ping Demo

This project is part of the i2i Academy CLOUD-EX-01 assignment.

## ✅ Task Description

Create a virtual machine on a cloud platform and ping it from your local machine.

- Cloud Provider: Google Cloud Platform (GCP)
- OS: Debian GNU/Linux 12 (Bookworm)
- Machine Type: e2-medium
- External IP: `173.255.118.176`

## ✅ Files Included

- `ping_output.txt`: Contains the results of the ping test from local terminal to the cloud VM.

## ✅ Sample Output

```bash
PING 173.255.118.176 (173.255.118.176): 56 data bytes
64 bytes from 173.255.118.176: icmp_seq=0 ttl=53 time=152.073 ms
64 bytes from 173.255.118.176: icmp_seq=1 ttl=53 time=149.674 ms
64 bytes from 173.255.118.176: icmp_seq=2 ttl=53 time=163.727 ms
64 bytes from 173.255.118.176: icmp_seq=3 ttl=53 time=154.328 ms

--- 173.255.118.176 ping statistics ---
4 packets transmitted, 4 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 149.674/154.951/163.727/5.328 ms
