# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
```
Developed by:Kabil S
Register no:212222040067
```
# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

## Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion








## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 
  
  

# nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
## site:

![Screenshot 2025-03-15 143635](https://github.com/user-attachments/assets/2e707bd7-8124-46d6-aa4b-19a7fa5436ef)






## filetype:
![Screenshot 2025-03-15 143648](https://github.com/user-attachments/assets/5a0d7a37-ad23-461e-a94e-a5b828899330)






## intext:

![Screenshot 2025-03-15 143744](https://github.com/user-attachments/assets/286a7ce2-52df-4fb4-b236-7b72c87a27c5)







## inurl:

![Screenshot 2025-03-15 143910](https://github.com/user-attachments/assets/dcc3b17a-22c7-4545-87bc-b203216cfdcd)



## link:


![Screenshot 2025-03-15 143956](https://github.com/user-attachments/assets/c5146682-7dcf-43ed-8b17-56872a27d940)



## cache:
![Screenshot 2025-04-21 175221](https://github.com/user-attachments/assets/b287126b-3636-4983-992d-8db8b18d3973)



## DNS Enumeration:
## DNS Recon:
![Screenshot 2025-03-15 144546](https://github.com/user-attachments/assets/937904c5-e8bd-4e32-ba95-67e5af409b82)




## dnsenum:

![Screenshot 2025-03-15 144824](https://github.com/user-attachments/assets/d33078cf-d0cd-467d-a374-f14f18bbd54c)



## smtp-user-enum:


![Screenshot 2025-03-17 101546](https://github.com/user-attachments/assets/bffd8939-d14d-482e-9e21-fbfa9fa44a0c)

![Screenshot 2025-03-17 101856](https://github.com/user-attachments/assets/82d6e0cf-cf94-4085-90fb-85b9b7687f7f)


## nmap –script smtp-enum-users.nse :
![Screenshot 2025-03-27 102500](https://github.com/user-attachments/assets/0bf0ae77-1027-4300-9fea-fe5cbf8e5ca1)




## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully.

