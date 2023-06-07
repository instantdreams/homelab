# Instant Dreams Home Network

Details of my home network, for sharing.


## History

I started self-hosting in 2011 with Windows Server Essentials, and used Windows exclusively to manage my fileshares. It was a good exercise in learning technology as well as managing my own hosting.

This grew as time went on into using Raspberry Pi devices as ad-blockers, which meant I had to learn Linux. I realised that a good way to manage my services was through containers, and so I moved my stack to Docker. I've experimented with various docket networking modes, dabbled with kubernetes for my self hosted services, but at the moment my infrastructure and topography are relatively stable.


## Network Layout

I use my 1G fibre internet connection to connect 5 servers, 2 workstations, and various networking and IoT devices using wired networking:
![Network-Physical](assets/id-network-2023-Network-Physical.png)

My pi-hole devices manage my DHCP reservation and allocation, and I manage the ranges for my wireless devices:
![Network-Wireless](assets/id-network-2023-Network-Wireless.png)


## Servers

![Servers](assets/id-network-2023-Servers.png)


### Edge Servers

I have two Raspberry Pi 4Bs acting as edge servers. They 

![Services-id-edge1](assets/id-network-2023-Services-91-id-edge1.png)


![Services-id-edge2](assets/id-network-2023-Services-92-id-edge2.png)


## Services Server

![Services-id-services](assets/id-network-2023-Services-93-id-services-sanitised.png)


## Security Server

![Services-id-security](assets/id-network-2023-Services-94-id-security.png)


## Media Server

![Services-id-media](assets/id-network-2023-Services-95-id-media.png)



# External Access

![External-Access](assets/id-network-2023-External-Access.png)


# Conclusion

Little finish bit
