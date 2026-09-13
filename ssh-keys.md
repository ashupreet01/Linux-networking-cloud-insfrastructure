# SSH and Secure Remote Access

## Introduction

SSH stands for Secure Shell. It is a network protocol used to securely access and manage a remote computer or server over a network.

## Why SSH is Used

SSH provides secure remote access to Linux servers. It encrypts the communication between the client and the server.

SSH is commonly used by system administrators and developers to manage cloud servers remotely.

## SSH Authentication

SSH can use passwords or SSH key pairs for authentication.

An SSH key pair consists of:

- Public Key: Can be shared with the server.
- Private Key: Must be kept secret and should never be shared.

## SSH Keys

SSH keys provide a secure way to authenticate users without depending only on passwords.

The private key should be stored securely on the user's computer.

## Basic SSH Command

A typical SSH connection uses:

ssh username@server_ip

For example:

ssh user@192.168.1.10

The username and IP address are replaced with the actual server details.

## SSH Security Practices

Important SSH security practices include:

- Keep private SSH keys secret.
- Use strong authentication.
- Disable unnecessary remote access.
- Use firewall rules to restrict access.
- Keep the operating system updated.
- Give users only the permissions they need.

## Learning Outcome

I learned the purpose of SSH and understood how it provides secure remote access to Linux servers. I also learned the difference between public and private SSH keys and the importance of protecting private keys.
