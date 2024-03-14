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


![EHT-EXP-2 1](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/8cc5a760-fb1c-41fe-9640-b791642b94c7)



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in

```
## OUTPUT:



![EHT-EXP-2 2](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/c4b37e56-436e-43f5-922d-f3ccc4642802)


## Finding Hosting Company
get further detail by using ip2location.com website.


## OUTPUT:


![EHT-EXP-2 3](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/0aa33849-4985-4172-87c8-4475963d46dc)



## History of the website:
## Output:




![EHT-EXP-2 4](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/fe777ac4-77e7-4bcc-8ba5-43e2297f1fb8)


## Webserver Fingerprinting:
## Netcat:

```
nc 172.17.52.118 80
```

## OUTPUT:



![EHT-EXP-2 5](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/a580361f-2c41-48ed-869c-8f624356fecd)



## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```


## OUTPUT:


![EHT-EXP-2 6](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/b1ecff25-1281-4db5-9a72-d596175178cb)


## Whatweb:
```
whatweb infosys.com

whatweb zoho.com

whatweb -v -a 3 172.17.52.201
```

## OUTPUT:

![EHT-EXP-2 7](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/0fe259e1-7418-4260-bc63-d44901d4837e)


![EHT-EXP-2 8](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/99679d24-2595-4fd5-9d68-65d64c9e95cc)




## httprint:

```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more

```
## OUTPUT:



![EHT-EXP-2 9](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/f6ea90b4-6755-4641-9bb8-0a809173107a)



## Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## OUTPUT:




![EHT-EXP-2 10](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/5a5553b7-c41c-463e-9965-592e7b600383)




## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## OUTPUT:




![EHT-EXP-2 11](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/47bf60f5-a23d-47fa-b792-d98f899a3a6b)


## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## OUTPUT:


![EHT-EXP-2 12](https://github.com/jagadeeshreddy561/InformationGathering/assets/120623104/da05df56-6917-4380-839b-22242b342720)



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
