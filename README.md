# Wi-Fi-encrypted-traffic-classification
Implement a machine-learning classifier able to distinguish what kind of activity a user is performing with his/her smartphone/laptop by sniffing traffic in monitor mode. The system should perform 
the following operations: <br/>
a. Sniff traffic in monitor mode from a known MAC address  <br/> 
b. extract statistical features from the traffic every W seconds. The following 
traffic features can be extracted: number of packets up/down, average and 
variance of the packet size, average and variance of the inter-arrival packet 
times etc. <br/>
c. use a pre-trained machine-learning classifier of your choice to recognize the 
user activity among at least the following: idle, web browsing, YouTube
streaming. <br/>
d. Report the accuracy of the approach through a confusion matrix <br/>
Reference: https://ieeexplore.ieee.org/abstract/document/8543584
