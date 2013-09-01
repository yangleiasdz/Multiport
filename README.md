Multiport
=========

Multiport is a port scanning utility designed in Python.
It accepts the target and ports (single port, port list and port range) as user input. Then scans the target for the port(s) status using the scanning techniques all at once. The output is displayed in an organized table format.

Multiport v1.0

Example: ./multiport.py 192.168.1.1 -p 80 -pl 53,8080 -pr 21-22
