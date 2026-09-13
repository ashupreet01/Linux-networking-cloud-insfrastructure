# IP Addressing, DNS and Networking

## Introduction

Networking allows computers and servers to communicate with each other. Linux provides several commands to view and troubleshoot network configuration.

## IP Address

An IP address is a unique address assigned to a device on a network. It helps devices identify and communicate with each other.

During the practical work, the Linux system had the IP address:

10.0.2.15

## Network Interface

A network interface connects a computer to a network.

The following command was used to view network interfaces and IP addresses:

ip addr

The command displayed the network interface and its assigned IP address.

## IPv4

IPv4 is a commonly used Internet Protocol version. An IPv4 address consists of four numbers separated by dots.

Example:

10.0.2.15

## DNS

DNS stands for Domain Name System.

DNS converts human-readable domain names into IP addresses.

For example, instead of remembering an IP address, users can access a website using its domain name.

## Ports

A port identifies a specific service or application running on a computer.

For example, HTTP commonly uses port 80.

## Connectivity Testing

The curl command was used to test the Apache web service.

Local test:

curl http://localhost

IP-based test:

curl http://10.0.2.15

Both tests returned a response from the Apache web server, showing that the service was working.

## Importance of Networking

Networking knowledge is important for cloud computing because cloud servers, applications and services communicate through networks.

## Learning Outcome

I learned the basic concepts of IP addresses, network interfaces, DNS and ports. I also performed connectivity testing using curl and verified that the Apache web service was accessible through the local system and its IP address.
