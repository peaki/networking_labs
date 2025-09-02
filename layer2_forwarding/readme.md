🔹 Objectives

Practice basic Layer 2 switching behavior.

Observe differences between unicast, broadcast, and multicast traffic.

Understand how MAC address learning and aging works on switches.

🔹 Key Tasks

Configured hostnames, IP addresses, and default gateways on SRV1, SRV2, and SRV3.

Captured packets between R1 and SW1 to study Layer 2 forwarding behavior.

Generated known unicast and unknown unicast traffic from R1.

Compared how unknown unicast floods the network versus known unicast being forwarded directly.

Identified unicast, broadcast, and multicast messages in Wireshark.

Disabled MAC address aging on SW1 to observe impact on MAC table stability.

Statically configured R1’s MAC address on SW1 to reinforce address persistence.

🔹 Key Takeaways

Switches learn MAC addresses dynamically and age them out unless statically configured.

Unknown unicast traffic is initially flooded, unlike known unicast.

Broadcasts are forwarded out all ports except the incoming one.

Packet captures (via CML and Wireshark) make it clear how traffic types differ at Layer 2.
