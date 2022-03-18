# Source: https://www.youtube.com/watch?v=n7kYogsTkVo&t=878s&ab_channel=ChrisGreer
## The Top 15 Network Protocols and Ports Explained // FTP, SSH, DNS, DHCP, HTTP, SMTP, TCP/IP

- When using Wireshark to look for those ports, use the **PORT NUMBER* instead of their names for **FILTERING**

|TCP/UDP|Port Number|Protocol|Name|Descriptions| More |
|:-:|:-:|:-:|-|-|-|
|TCP| 21                |**FTP**| File Transfer Protocol|Sending packages in clear text|
|TCP| 22                |**SSH**| Secure Shell| Used to REMOTE INTO a device to control it|
|TCP| 23                |**Telnet**| Send data in clear text| Use **Follow Through** function in Wireshark to get the completed text|
|TCP| 25, 586, 465      |**SMTP**| Simple Mail Transfer Protocol|It can be encrypted or unencrypted| Used TLS: Data will be encrypted|
|UDP| 53                |**DNS**| Domain Name System| "Phone book" of the internet|
|UDP| 67,68             |**DHCP**| Dynamic Host Configuration Service| Server (67), client (68)|Wireshark: DHCP Discover, DHCP Offer, DHCP Request, DHCP ACK|
|UDP| 69                |**TFTP**| Trivial file transfer protocol|Moving file, but more simple compared to FTP|
|TCP| 80                |**HTTP**| Hyper Text Transfer Protocol| Sending data in clear text|
|TCP| 110               |**POP**| Post Office Protocol - Unencypted| Sending data in clear text|
|   | 995               |**POP3**| TLS (Tranposrt Layer Security) supports - Encrypted| Data sent is encrypted|
|   | 110               |**POP3**| NO TLS supported - Unencrypted|              
|   | 993               |**IMAP**| Internet Message Access Protocol - Encrypted| Secured with TLS|
|   | 143               |**IMAP**| Unencryped|
|UDP| 123               |**NTP**| Network Time Protocol| Used for synchronization| Mechanism for devices to be able to check in with an authority to set their time accurately| 
|UDP| 161               |**SNMP**| Simple Network Management Protocol| Allows to monitor the network from a central point|
|TCP| 389               |**LDAP**| Lightway Directory Access Protocol| Authentication and directory services|A way of accessing information and authenticating to the system|
|TCP| 443               |**HTTPS**| Hyper Text Transfer Protocol Secure|
|UDP| 443               |**HTTPS**| Over QUIC|
|TCP| 445               |**SMB**| Server Message Block|Moving files, uploading files, sharing files| Several versions of SMB. For example: SMB2|
