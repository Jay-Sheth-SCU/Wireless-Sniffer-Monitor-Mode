# Wireless-Sniffer-Monitor-Mode
This repo is mainly associated with C - wireless sniffing programs in monitor mode. After a lot of research and trying wireless sniffers in the monitor mode, I could not find any C program which deals with sniffing in monitor mode. The main reason being that in the monitor mode, the wireless driver add a RADIOTAP header to the all the packets sniffed. Hence the parsing requires offsetting. Additionally, we provide the counters, which enlists the number of data frames, probe request/responses, beacons, etc.. sniffed.   
