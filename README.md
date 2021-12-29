# Writing-Wireshark-Filter-Expressions-for-Packet-Capture

Wireshark is an open-source packet analyzer, which is used for education, analysis, software development, communication protocol development, and network troubleshooting.
It is used to track the packets so that each one is filtered to meet our specific needs. It is commonly called as a sniffer, network protocol analyzer, and network analyzer. It is also used by network security engineers to examine security problems. 


### Objective

Write the exact packet capture filter expressions to accomplish the following: 

1.	Capture all TCP traffic to/from Facebook, during the time when you log in to your Facebook account.
2.	Capture all HTTP traffic to/from Facebook when you log in to your Facebook account.
3.	Find a popular YouTube video and play it while capturing all traffic to/from YouTube.

After running Wireshark with the above capture filters and collecting the data:
1.	Write a DISPLAY filter expression to count all TCP packets (captured under item #1) that have the flags SYN, PSH, and RST set. Show the fraction of packets that had each flag set. 

2.	Use a DISPLAY filter expression to separate the packets sent by your computer vs. received from Facebook and YouTube in items #2 and #3 above. Show the fractions for each type.
