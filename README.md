To conduct the different simulations, the default Contiki-3.0 folder was duplicated:
The original folder was used to implement the proposed solution. The legitimate nodes were inserted from this folder. The only modified file was rpl-icmp6.c.
The second folder was named contikivnattack. It contained the attack implementation, rpl-icmp6MAL.c, and the malicious client node was inserted from this folder.
