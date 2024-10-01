# Ping-Scanner-Tool
A Python tool that scans a range of IP addresses by sending ICMP echo requests. It uses multithreading for faster scanning, allows custom IP ranges, and displays response times for reachable hosts.

## Key Features:

Multithreading: The script uses threads to ping multiple IP addresses concurrently, speeding up the scanning process.
Customizable IP Range: You can specify a range of IP addresses to scan.
Response Time Display: For each reachable host, the response time is displayed in milliseconds.

## How It Works:
The script asks for a starting and ending IP address.
It pings each IP within the specified range using multithreading to perform the tasks concurrently.
The response time for each reachable host is calculated and displayed.

![Multithreaded Ping Scanner Tool](ping_scanner.png)
