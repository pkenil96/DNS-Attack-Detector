# DNS-Attack-Detector
This mini project is done as part of the assignment for the course CSE508 - Network Security. There are two tools: dnspoision and dnsdetect. The former is used to poison the DNS cahce of the victim by capturing the DNS request going from the victim's machine and putting it's own IP in the response packet, thereby taking control of all the communication taking place from the victim's machine. The latter tool monitors for such malicious transactions and raises an alert as soon as an attempt is made to forge the DNS response packet.
