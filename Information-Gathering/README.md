## Information Gathering
* [whois](https://www.tecmint.com/whois-command-get-domain-and-ip-address-information/) 
``` 
whois google.com
whois 216.58.206.46
```
* [nbtscan](https://www.darknet.org.uk/2017/09/nbtscan-download-netbios-scanner-for-windows-linux/)
``` 
nbtstat -A 192.168.1.99
nbtscan -f addresses.txt
```
* [fping](https://fping.org/)
``` 
fping 50.116.66.139 173.194.35.35 98.139.183.24
fping -s -g 192.168.0.1 192.168.0.9
fping -g -r 1 192.168.0.0/24
```
* [tcptraceroute](https://linux.die.net/man/1/tcptraceroute)
``` 
tcptraceroute api.opendns.com 443
tcptraceroute -T domainname
```
* [traceroute](https://linux.die.net/man/8/traceroute)
``` 
traceroute example.com
```
* [xprobe2](https://linux.die.net/man/1/xprobe2)
``` 
xprobe2 google.com
xprobe2 -D 11 google.com
```
* [sslyze](https://tools.kali.org/information-gathering/sslyze)
``` 
sslyze --regular bugcrowd.com
```
* [tcpdump](https://opensource.com/article/18/10/introduction-tcpdump)
``` 
tcpdump host 1.1.1.1
tcpdump -i eth0
```
* [tshark](https://www.wireshark.org/docs/man-pages/tshark.html)
``` 
tshark -i wlan0 -w capture-output.pcap
tshark -r capture-output.pcap
```
* [wireshark](https://www.wireshark.org/)
* [subbrute](https://github.com/TheRook/subbrute)
``` 
./subbrute.py target.com
```
* [dnsenum](https://tools.kali.org/information-gathering/dnsenum)
``` 
dnsenum --enum hackthissite.org
dnsenum hackthissite.org
```
* [dnsrecon](https://tools.kali.org/information-gathering/dnsrecon)
``` 
./dnsrecon.py -d <domain>
./dnsrecon.py -d <domain> -t axfr
```
* [dnstracer](https://tools.kali.org/information-gathering/dnstracer)
``` 
dnstracer www.mavetju.org
```
* [enum4linux](https://tools.kali.org/information-gathering/enum4linux)
``` 
enum4linux -v 172.168.0.6
enum4linux -u 192.168.2.55
```
* [hping3](https://tools.kali.org/information-gathering/hping3)
``` 
hping3 -S 192.168.1.10 -p 80
hping3 –traceroute -S {target ip}
```
* [dotdotpwn](https://tools.kali.org/information-gathering/dotdotpwn)
``` 
dotdotpwn.pl -m http -h 192.168.1.1 -M GET
```
* [golismero](https://tools.kali.org/information-gathering/golismero)
``` 
golismero scan http://www.0x00sec.org 
golismero scan http://www.0x00sec.org -o /root/scan.txt 
```
* [netmask](https://chousensha.github.io/blog/2017/07/07/netmask-kali-linux-tools/)
``` 
netmask -c google.com
netmask -r 192.168.217.0/24
```
* [knock](https://kalilinuxtutorials.com/knock-enumerate-subdomains/)
``` 
knockpy domain.com
knockpy domain.com -w wordlist.txt
```
* [lbd](https://tools.kali.org/information-gathering/lbd)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
* [wow](https://www.google.com/)
``` 

```
