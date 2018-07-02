# Wireless-Sniffer-Monitor-Mode
This repo is mainly associated with C - wireless sniffing programs in monitor mode. After a lot of research and trying several wireless sniffers in the monitor mode, I could not find any which deals with sniffing in monitor mode written in C. The main reason being that in the monitor mode, the wireless driver add a RADIOTAP header to the all the packets sniffed. Hence the parsing requires offsetting. Additionally, we provide the counters, which enlists the number of data frames, probe request/responses, beacons, etc.. sniffed.   


Compile using:
gcc sniffer.c -o sniffer -lpcap


Set up interface in monitor mode:
airmon-ng start wlan0

