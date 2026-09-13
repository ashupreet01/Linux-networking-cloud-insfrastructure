# Linux Processes and Services

## Introduction

A process is a program or task that is currently running on a Linux system. A service is a program that runs in the background and provides a specific function to the system or users.

## Processes

Linux can run many processes at the same time. Each running process has a Process ID (PID).

The ps command can be used to view running processes.

Command: ps

The top command displays processes and system resource usage in real time.

Command: top

## Services

Services are background programs that provide functions such as web hosting, networking and system management.

The systemctl command is commonly used to manage services in Linux.

## Checking Service Status

The following command checks the status of the Apache web server:

sudo systemctl status apache2

The service status can show whether the service is active, inactive or stopped.

## Starting a Service

A service can be started using:

sudo systemctl start apache2

## Stopping a Service

A running service can be stopped using:

sudo systemctl stop apache2

## Restarting a Service

A service can be restarted using:

sudo systemctl restart apache2

## Apache Web Server

Apache is a popular open-source web server. During the practical work, Apache was already installed on the Kali Linux system.

The Apache service was started using systemctl and tested using the curl command.

## Practical Work Completed

- Checked the Apache service status.
- Started the Apache web server.
- Confirmed that Apache was active and running.
- Tested the web server using localhost.
- Tested the web service using the system IP address.

## Learning Outcome

I learned the difference between Linux processes and services and understood how systemctl can be used to manage services. I also gained practical experience with the Apache web server.
