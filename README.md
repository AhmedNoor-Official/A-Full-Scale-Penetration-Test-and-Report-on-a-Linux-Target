# Penetration-Test-and-Report-on-a-Linux-Target

The goal of this project was to conduct a penetration test on a target computer system, 
with the purpose of finding vulnerabilities and then trying to exploit them to show how vulnerable or secure the system is. 

The project consisted of several tasks, which aimed at testing a computer system on the target machine according to a pre-prepared plan 
that involves scanning an enumeration including manual discovery, threat modelling, vulnerability analysis, exploitation, 
post exploitation and then reporting. 

The results of both the manual and the OpenVAS vulnerability scans on the target showed that there were a few high-risk vulnerabilities 
that were exploitable including port 22 SSH, port 80 http, port 3306 MySQL and some others. 
Four vulnerabilities were chosen to be exploited using the Metasploit Framework and other methods. 

The result of the exploits and the mitigation for each of them were that some of the chosen vulnerabilities were exploited and we managed 
to gain access to the target system and some failed, in the end I managed to even bring down the server with a DOS (Denial of Service) attack. 

Furthermore, all will be explained in detail in the report. 
The conclusions that were then drawn from this penetration project were that with proper care, mitigation and improved system security 
with the latest updates, vulnerabilities, and attacks like these can be prevented or at the least made harder to commit for unethical hackers.
