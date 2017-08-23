# Cybersecurity Lab 7 - *Into The Packets* 

Time spent: **5** hours spent in total 

## User Stories

The following **required** functionality is completed:

1. [X]  Required: Milestone 0: Networking Toolbox 
2. []  Required: Milestone 1: Security-Flavored Net Tools
3. []  Required: Milestone 2: Grabbing Packets with tcpdump
4. []  Required: Milestone 3: Hello, Wireshark
5. []  Required: Milestone 4: Traffic Analysis — Mike's Computer is Acting Weird 
6. []  Required: Milestone 5: Traffic Analysis — Mystery Meat Malware
7. []  Required: Milestone 6: Wi-Fi Hacking — Crack a Handshake
8. []  Required: Milestone 7: Wi-Fi Hacking — Grab a Handshake

The following advanced user stories are optional:

* []  Bonus 1: Map your home LAN using nmap 
* []  Bonus 2: Wi-Fi Hacking — Sniff Thy Neighbor's Packets

## Answers

Networking Toolbox

ifconfig

What is your primary interface's IP address? Is it different from your public IP? Why or why not?

My primary interface's IP is different from my public IP. The public IP is given by my Internet provider where the interface IP is assigned to one of my adapters. 

ping

Why would the IP address of google.com change between runs or from different locations?

The Ip address can change depending on the location or number of runs. Google has multiple servers all across the world so a clients request is probably directed to the best location. Google also manages the load of requests, if one server is overloaded some requests are sent to another server. 

nslookup 

Does the domain returned from nslookup match? If not, why not?

The domain name from nslookup does not match the domain name use with ping command. This is because a few domain names are assigned to one IP address. 

Core Tools

curl and wget

Identify some differences between the two.

Which would you be more likely to use for interacting with a RESTful API from the command line?

Which support recursive downloading?

Which are you more likely to find pre-installed on a Linux OS?

What is the syntax for each for downloading a file to the current directory?

ssh and scp

Why is key authentication preferred to passwords?
What is the syntax for copying a file from a local folder to a remote one?




## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='walk7_lab.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<img src='walk7_lab2.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes


## License

    Copyright [2017] [Gregory Szymanski]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
