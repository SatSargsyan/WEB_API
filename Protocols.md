#
### [Internet Protocols]()
The Internet Protocol family contains a set of related (and among the most widely used network protocols. Beside Internet Protocol (IP) itself, higher-level protocols like [TCP](), [UDP](), [HTTP](), and [FTP]() all integrate with IP to provide additional capabilities. Similarly, lower-level Internet Protocols like ARP and ICMP also co-exist with IP. In general, higher level protocols in the IP family interact more closely with applications like Web browsers while lower-level protocols interact with network adapters and other computer hardware.


### SMTP, POP3 and IMAP are TCP/IP protocols used for mail delivery. If you plan to set up an email server such as hMailServer, you must know what they are used for. Each protocol is just a specific set of communication rules between computers.
#### [SMTP](http://www.omnisecu.com/tcpip/smtp-simple-mail-transfer-protocol-how-smtp-works.php)
 The objective of Simple Mail Transfer Protocol (SMTP) is to transfer
   mail reliably and efficiently.

   [SMTP](http://www.ietf.org/rfc/rfc788.txt) is independent of the particular transmission subsystem and   requires only a reliable ordered data stream channel.  Appendices A,
   B, C, and D describe the use of SMTP with various transport services.
   A Glossary provides the definitions of terms as used in this
   document.

   An important feature of SMTP is its capability to relay mail across
   transport service environments.  A transport service provides an
   interprocess communication environment (IPCE).  An IPCE may cover one
   network, several networks, or a subset of a network.  It is important
   to realize that transport systems (or IPCEs) are not one-to-one with
   networks.  A process can communicate directly with another process
   through any mutually known IPCE.  Mail is an application or use of
   interprocess communication.  Mail can be communicated between
   processes in different IPCEs by relaying through a process connected
   to two (or more) IPCEs.  More specifically, mail can be relayed
   between hosts on different transport systems by a host on both
   transport systems.

SMTP stands for Simple Mail Transfer Protocol. SMTP is used when email is delivered from an email client, such as Outlook Express, to an email server or when email is delivered from one email server to another. SMTP uses port 25.
POP3

POP3 stands for Post Office Protocol. POP3 allows an email client to download an email from an email server. The POP3 protocol is simple and does not offer many features except for download. Its design assumes that the email client downloads all available email from the server, deletes them from the server and then disconnects. POP3 normally uses port 110.
IMAP

IMAP stands for Internet Message Access Protocol. IMAP shares many similar features with POP3. It, too, is a protocol that an email client can use to download email from an email server. However, IMAP includes many more features than POP3. The IMAP protocol is designed to let users keep their email on the server. IMAP requires more disk space on the server and more CPU resources than POP3, as all emails are stored on the server. IMAP normally uses port 143. Here is more information about IMAP.
Examples

Suppose you use hMailServer as your email server to send an email to bill@microsoft.com.
You click Send in your email client, say, Outlook Express.
Outlook Express delivers the email to hMailServer using the SMTP protocol.
hMailServer delivers the email to Microsoft's mail server, mail.microsoft.com, using SMTP.
Bill's Mozilla Mail client downloads the email from mail.microsoft.com to his laptop using the POP3 protocol (or IMAP).

#### [Protocol numbers](http://www.omnisecu.com/tcpip/tcp-port-numbers.php)
###### The Well Known Ports are those in the range 0 - 1023. The Well Known Ports are assigned by the IANA (Internet Assigned Numbers Authority) for major protocols.

###### The Registered Ports are those in the range 1024 - 49151.

###### The Private Ports are those in the range 49152 - 65535.



### [Wireless Network Protocols]()

Thanks to Wi-Fi, Bluetooth and LTE, wireless networks have become commonplace. Network protocols designed for use on wireless networks must support roaming mobile devices and deal with issues such as variable data rates and network security.

### [Network Routing Protocols]()

Routing protocols are special-purpose protocols designed specifically for use by network routers on the Internet. A routing protocol can identify other routers, manage the pathways (called routes) between sources and destinations of network messages, and make dynamic routing decisions. Common routing protocols include EIGRP, OSPF and BGP.

### []()
### []()

