Secure Network Architecture with Protected DMZ

   1.Objective: Design and implement a three-tier network architecture using a DMZ to host public-facing services while isolating the private LAN.

Architecture:

Zone 1 (Untrusted): Public Internet (WAN).

Zone 2 (Trusted): Corporate LAN with full internal access.

Zone 3 (DMZ): Isolated segment for web services with restricted inbound access via DNAT/Virtual IPs.

  2.Analysis:
The project demonstrates the application of Micro-segmentation, where communication is explicitly denied between the DMZ and the LAN by default. This limits the "Blast Radius" in case of a server compromise.
