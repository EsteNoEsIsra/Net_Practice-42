*This project has been created as part of the 42 curriculum by israetor.*

#  NetPractice

A networking exercise project where you configure small-scale networks by solving 10 levels of increasing difficulty, covering IP addressing, subnet masks, and routing tables.

##  Description

NetPractice is a system administration project from the 42 curriculum that introduces the fundamentals of **TCP/IP networking** through practical, hands-on exercises. In each level, you are given a broken network diagram that must be fixed by correctly assigning IP addresses, subnet masks, and routing information so that all devices can successfully communicate.

The project is carried out through a browser-based training interface, meaning no coding is required. The completedlvl directory contains 10 JSON files with the exported configurations for each solved level.

### How to execute in linux system
```
    cd net_practice

    ./run.sh
```
### Key Concepts

- **IP addressing** — understanding how IPv4 addresses identify hosts on a network
- **Subnet masks** — defining network boundaries and determining which hosts can communicate directly
- **CIDR notation** — compact representation of subnet masks (e.g. `/24` = `255.255.255.0`)
- **Routing tables** — configuring default gateways and specific routes so packets reach the correct destination
- **Network vs. host** — distinguishing the network portion from the host portion of an IP address
- **Special addresses** — knowing reserved ranges (`127.x.x.x`, `0.0.0.0`, `255.255.255.255`) and private ranges (`10.x`, `172.16-31.x`, `192.168.x`)

- **Switch** — A switch connects devices within the same network

- **Router** — A router connects different networks and directs traffic between them

##  Project Structure

```
net_practice
│  
├── css
│   └── netpractice.css
├── end.html
├── img
│   ├── host.png
│   ├── icon.png
│   ├── internet.png
│   ├── router.png
│   ├── site-bg.png
│   └── switch.png
├── index.html
├── js
│   ├── intro.js
│   ├── level10.js
│   ├── level1.js
│   ├── level2.js
│   ├── level3.js
│   ├── level4.js
│   ├── level5.js
│   ├── level6.js
│   ├── level7.js
│   ├── level8.js
│   ├── level9.js
│   ├── show.js
│   └── sim.js
├── level10.html
├── level1.html
├── level2.html
├── level3.html
├── level4.html
├── level5.html
├── level6.html
├── level7.html
├── level8.html
├── level9.html
├── License
└──  run.sh          #Test to evaluate the proyect

completeed_lvl
├── level1.json  	# Simple direct connection between two hosts
├── level2.json  	# Subnet mask matching between hosts
├── level3.json  	# Switch connecting multiple hosts
├── level4.json  	# Router connecting two networks
├── level5.json  	# Routes and default gateways
├── level6.json  	# Internet routing through a gateway
├── level7.json  	# Multiple subnets with two routers
├── level8.json  	# Complex routing with Internet access
├── level9.json  	# Four networks, two routers, Internet
├── level10.json 	# Final challenge — full topology
```

##  Resources

- [IP Addressing and Subnetting](http://apuntesdenetworking.blogspot.com/2011/09/subredes-ip-ip-subnetting.html) — 
- [Subnet Calculator](https://www.calculator.net/ip-subnet-calculator.html) — Useful tool for verifying subnet calculations
- `man ip-route` — Linux routing table documentation
 
- [youtube tutorials] (https://www.youtube.com/watch?v=s_Ntt6eTn94&list=PLCXqoZAc8-tzD5N5oCyIyEcMg_NDs6o7C) — Tutorials 

###  AI Usage

The use of AI in this project consisted of explaining the required concepts and providing a brief summary of topics such as IP, networks, subnet masks, and CIDR.
