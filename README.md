This repository was created for homework on the computer networks course (5th semester).

```traceroute.py``` is an analog of the utility of the same name and allows you to track the route to the target node of the network. 

Uses UDP and ICMP protocols.

Needs to be run with ```sudo```.

### Usage

```sudo python3 traceroute.py <destination_name>```

### Example

```sudo python3 traceroute.py ya.ru```

```
Tracing the route to ya.ru (87.250.250.242)
1 XiaoQiang (192.168.31.1) 1.928ms
2 217.197.11.1 (217.197.11.1) 12.018ms
3 172.24.31.5 (172.24.31.5) 3.423ms
4 172.24.25.32 (172.24.25.32) 3.138ms
5 172.24.25.38 (172.24.25.38) 4.416ms
6 vlan3.kronos.pu.ru (195.70.196.3) 6.255ms
7 195.70.206.129 (195.70.206.129) 6.0ms
8 yandex.spb.piter-ix.net (185.1.152.57) 6.471ms
9 *  *  * 
10 *  *  * 
11 ya.ru (87.250.250.242) 20.817ms
```
