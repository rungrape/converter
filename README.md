1.Why the hell do I need this?
You are, if it's necessary to crack your neighbour's WIFI (joking) with the help of hashcat. Conversion to hccap format would be suitable for fan of vintage stuff such as hashcat 3.0, transformation from hccap to hccapx is for haters of the bullshit.
The tool is adapted for Half-WPA cracking

2.Install requirements.
You are to install the pcapfile module (via pip or by any other convenient way for you) to guarantee the correct work of the tool 

3.Tool's abilities.
Format conversion:
       cap -> hccap (usage: ./converter.py input.cap hccap or ./converter.py input.cap hccap essid)
       cap -> hccapx (usage: ./converter.py input.cap hccapx or ./converter.py input.cap hccapx essid)
       hccap -> hccapx (usage: ./converter.py input.hccap hccapx)
