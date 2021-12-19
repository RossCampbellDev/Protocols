# Ports and Protocols Cheat Sheet
## Application Layer (7)
`20/21`	FTP.  20 for sending files, 21 for control
`22`	SSH for remote management (or SFTP)
`49`	TACACS+ (Cisco authentication/authorisation/accounting)
`53`	DNS
`67/68`	DHCP
`80`	HTTP
`88`	Kerberos
`110`	POP email.  one-way communcation
`149,993`	IMAP email.  two-way communication
`161/162`	SNMP Simple Network Management.  remote mgmt of network devices
`389`	LDAP manage and communicate with directories on a network
`443`	HTTPS
`636`	LDAPS uses TLS for encryption
`989/990` FTPS (uses TLS).  SFTP is generally better and has more features
`993`	IMAPS (TLS)
`995`	POPS (TLS)
`1812/1813`	RADIUS used to provide AAA for network services
`3868`	Diameter - upgrade to RADIUS
`5004`	SRTP

## Session Layer (5)
`1701`	L2TP layer 2 tunneling protocol.  for things like VPN over UDP, **requires IPSec for encryption**.  is an extension to PPTP

## Transport Layer (4)
`1723`	PPTP point to point tunelling protocol.  deprecated protocol for VPNs
`3389`	RDP

#cheatsheet #networking #protocols #ports
