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
    
   
모든 패킷을 다 보고 싶으시다면, 300줄에 clear 함수를 제거하시면 됩니다.   
clear 함수가 주석처리 되어 있지 않다면, 화면은 깔끔하게 출력되지만 실행 도중 cmd 창을 건드리시면 제데로 된 출력(packet number)가 나오지 않을 수 있습니다.   
   
