# InformationGathering
Information Gathering Techiques

DEVELOPED BY: SRIRAM ARUN S

REGISTE NUMBER: 212225040429

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/59465aea-9a8b-46fc-ab4d-6a6fd66b5f2e" />



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

##output
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/302d995c-5aad-430f-98f4-be6b73e87818" />



## Finding Hosting Company
get further detail by using ip2location.com website.

##output
<img width="1711" height="811" alt="Screenshot 2026-10-29 221653" src="https://github.com/user-attachments/assets/dd0de70e-bbb1-4b2b-880e-ec327706e018" />




## History of the website:
## output
https://web.archive.org/
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/551abd65-bbd6-4fea-b55c-ff9df8178c52" />



# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

##output:
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/45705057-dcc9-4c4f-9602-c96286749b15" />


## nmap:
###output
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/98fb448e-1b2e-4aee-bfcf-f5e6fc10664a" />


## Whatweb
### output
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/15c3288d-54a3-4644-a189-6c642ce25011" />


## httprint
### output
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/40d2a165-6f74-470e-a6f3-721721acc2e4" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/26c66098-3c4d-4800-b686-346c6aa068b9" />



## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/dadd1c53-9f41-4e2d-a208-14e9165ba7be" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/057560c6-36e8-471f-88b0-e63e9df6b582" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
