# Computer_Networks_and_Security_Reports
Lab and Final Reports for Computer Networks and Security class
###### Instructor:
Dr. Enis KARAARSLAN

## Final Report - Cyber Attack Demo:
###### Attack Machine:
Kali Linux, Release 2020.3
###### Victim Machine:
Windows 10 Pro, Build 14393.0
###### Used Tools:
Nmap (V7.91): To search the network for connected computers
Metasploit (V6.0.48): To probe systematic vulnerabilities and use exploits to send meterpreter
payloads.
###### Used Exploit:
MS17-010 exploit is caused by a flaw in Windows SMB (Server Message Block) version 1. This exploit was developed by NSA (National Security Agency) and leaked to the public after NSA got hacked in 2017. These exploits have enormous power on Windows systems that doesn’t have the patch against the MS17-010 exploit. Since its discovery, this vulnerability has been used to launch a global range of ransomware attacks. The biggest one of these attacks was the famous WannaCry ransomware attack. A successful attack that targets the MS17-010 exploit with meterpreter payload results in access to targeted system by returning a reverse shell on the attacker. In our demonstartion, we used the Metasploit framework to launch our attack

 

