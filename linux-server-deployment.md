# Linux Server Deployment

## Introduction

Linux servers are commonly used to host websites, applications and other services. In this practical, a Kali Linux virtual machine was used to understand basic server configuration and web service deployment.

## Virtual Machine

A Kali Linux virtual machine was started using VirtualBox.

The Linux system was checked using basic commands such as:

pwd

whoami

uname -a

These commands were used to verify the working directory, current user and system information.

## Network Configuration

The network configuration was checked using:

ip addr

The Linux system was assigned the IP address:

10.0.2.15

This IP address was used for connectivity testing.

## Package Update

The package information was refreshed using:

sudo apt update

This ensures that the system has updated information about available software packages.

## Apache Web Server

Apache HTTP Server was used as the web service for this practical.

Apache was already installed on the system. Its status was checked using:

sudo systemctl status apache2

Initially, the Apache service was inactive.

The service was started using:

sudo systemctl start apache2

After starting the service, its status showed that Apache was active and running.

## Testing the Web Service

The Apache web service was tested locally using:

curl http://localhost

A response from the Apache server was received, confirming that the web service was working.

## Connectivity Testing

The service was also tested using the Linux machine's IP address:

curl http://10.0.2.15

A response was received from the Apache web server, confirming successful connectivity.

## Deployment Workflow

The practical followed this workflow:

Create VM → Configure Linux → Deploy Service → Test Connectivity

## Tools Used

- Kali Linux
- VirtualBox
- Apache HTTP Server
- Linux Terminal
- curl
- systemctl

## Learning Outcome

I gained practical knowledge of Linux system configuration, network configuration, service management and web server deployment. I also learned how to start a Linux service and test its availability using localhost and an IP address.

## Conclusion

The practical demonstrated the basic process of configuring a Linux environment, deploying an Apache web service and testing network connectivity. This provided a foundation for understanding Linux server administration and cloud infrastructure.
