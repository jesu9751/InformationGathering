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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1886" height="909" alt="image" src="https://github.com/user-attachments/assets/08dc8bca-cb78-4220-ad9c-d76a0957c3e8" />
<img width="1887" height="916" alt="image" src="https://github.com/user-attachments/assets/16d2de5b-cf29-4dd5-a49a-badb1d9881a2" />
<img width="1888" height="915" alt="image" src="https://github.com/user-attachments/assets/73e7ad71-459a-4417-b8d7-8f10f36e480a" />

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="1678" height="758" alt="image" src="https://github.com/user-attachments/assets/719e656a-1edc-49cd-a678-02dbe14dd2a8" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="1881" height="909" alt="image" src="https://github.com/user-attachments/assets/e9bf4a5e-5bc9-49b8-8c18-453d72751b3f" />
<img width="1885" height="793" alt="image" src="https://github.com/user-attachments/assets/075fed6c-b7fb-4715-ab03-1f6ccec2616e" />
<img width="1882" height="915" alt="image" src="https://github.com/user-attachments/assets/650c4c4b-1e02-4211-9d8f-55c244237ac4" />


## History of the website:
## output
https://web.archive.org/
<img width="1886" height="912" alt="image" src="https://github.com/user-attachments/assets/f5d74ae1-a111-41de-b9a2-1fc2c15ea995" />
<img width="1885" height="872" alt="image" src="https://github.com/user-attachments/assets/d23a124d-37aa-4a82-a24b-95ebc7fef054" />
<img width="1879" height="904" alt="image" src="https://github.com/user-attachments/assets/cf4d6fb9-17dc-4da0-b49e-ec4b29636aa9" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="1712" height="619" alt="image" src="https://github.com/user-attachments/assets/08379e9c-6c54-4b2c-a0b7-915821670aae" />



## nmap:
###output
<img width="1636" height="946" alt="image" src="https://github.com/user-attachments/assets/bf50320a-2d9e-41ab-9261-6cad5079b34d" />


## Whatweb
### output
<img width="1916" height="984" alt="image" src="https://github.com/user-attachments/assets/7fb4a0fb-b29a-4a6b-bd58-424f07acedad" />


## httprint
### output
<img width="1919" height="987" alt="image" src="https://github.com/user-attachments/assets/8f733e30-a664-4603-9347-071bc216bca0" />
<img width="1919" height="997" alt="image" src="https://github.com/user-attachments/assets/be7dbb2a-9ffb-433f-ba51-18a8bb058d90" />
<img width="1918" height="988" alt="image" src="https://github.com/user-attachments/assets/218834c7-4d45-4a37-887c-9e50a87bf453" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output


<img width="1269" height="99" alt="image" src="https://github.com/user-attachments/assets/bb7f1106-af16-495f-9c03-6726149a4aeb" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output

<img width="1263" height="547" alt="image" src="https://github.com/user-attachments/assets/ef0b710d-2239-4054-9424-569ea987b028" />

## ICMP Traceroute:
sudo traceroute  www.google.com
## output

<img width="1257" height="552" alt="image" src="https://github.com/user-attachments/assets/f290c035-ae7d-4fd9-9900-97e9240237c9" />







## RESULT:
The information gathering techniques tools/procedure were  identified successfully
