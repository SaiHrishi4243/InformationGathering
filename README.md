# InformationGathering
Information Gathering Techiques

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


## OUTPUT:
## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT

![Screenshot 2025-03-10 112041](https://github.com/user-attachments/assets/1e7c3f9a-8a1b-47bd-9540-eba4a8d45851)

## Finding Hosting Company
get further detail by using ip2location.com website.

## OUTPUT

![Screenshot 2025-03-10 112641](https://github.com/user-attachments/assets/4634c4b7-0a55-446d-b6f9-6e3832f2e515)

## History of the website:

## OUTPUT

![Screenshot 2025-03-10 112948](https://github.com/user-attachments/assets/125840e8-fa3a-413a-a6c4-ccb699bb6e11)

## Webserver Fingerprinting:
# Netcat:
```
sudo nc ticfiber.com 80
GET / HTTP/1.1
Host: ticfiber.com
```
## Output:
![image](https://github.com/user-attachments/assets/3a0d762b-92e9-4390-840d-40b2817a638f)
# Nmap:
## Output:
![image](https://github.com/user-attachments/assets/083524f4-8b2e-435e-a230-4247cc532611)
![image](https://github.com/user-attachments/assets/e495efac-6238-47bb-81d1-da044c751806)
# Whatweb:
## Output:
![image](https://github.com/user-attachments/assets/03dca286-28da-4df4-bcc2-967574cd7beb)
## Tracing the Location:
```
TCP Traceroute:
sudo traceroute -T ticfiber.com
```
## Output:
![image](https://github.com/user-attachments/assets/794e1cea-c363-480d-aaea-2dbbf6fb5d77)
# UDP Traceroute:
```
sudo traceroute -U ticfiber.com
```
## Output:
![image](https://github.com/user-attachments/assets/4bf1787c-81a9-4c39-921d-af5fc8f67c3a)
## ICMP Traceroute:
```
sudo traceroute ticfiber.com
```
## Output:
![image](https://github.com/user-attachments/assets/97e5cbcf-af14-4ef4-9ead-7b91905fbd91)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully.
