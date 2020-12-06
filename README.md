# airodump    
    
sudo qmake
sudo make
    
# usage : 
syntax  : airodump interface    
example : airodump mon0    
    
# example of 80211-sample3.pcap on gilgil
   
sudo tcpreplay -i wlan1 80211-sample3.pcap   
sudo ./airodump wlan1   
   
![80211_sample3_zenoOh](https://user-images.githubusercontent.com/70625751/101280192-126f1e80-380b-11eb-873d-f7adecddcebd.PNG)    
    
