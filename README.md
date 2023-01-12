# Wi-Fi-encrypted-traffic-classification
Machine-learning classifier able to distinguish what kind of activity a user is performing with his/her smartphone/laptop by sniffing traffic in monitor mode. The traffic data has been collected sniffing a known MAC address with Wireshark in monitor mode.
The script extracts statistical features from the traffic every W seconds (number of packets up/down, average and 
variance of the packet size, average and variance of the inter-arrival packet 
times etc.) <br/>.
It has been used Random Forest Classifier from sklearn to recognize the user activity among idle, web browsing and YouTube streaming. <br/>
The report is included in the code.
