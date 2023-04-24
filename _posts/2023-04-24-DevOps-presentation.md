---
toc: true
layout: post
description: DevOps
categories: [week30]
title: DevOps Hacks
---

## KASM Virtual Desktop

1. Virtual desktops allow users to access a complete desktop environment hosted on a remote server or cloud infrastructure, rather than relying on a physical computer. KASM is a cloud-based virtual desktop platform designed for security-sensitive environments, with advanced features like hardware-based security and encrypted data storage. In an AP CSP (Computer Science Principles) environment, virtual desktops like KASM can be utilized to provide students with a consistent and secure computing environment, regardless of the hardware and software available on their local machines.
2. 

## AWS vs. SQL databases

1. (c) SQLite is not an AWS database option
2. (A) Amazon RDS is a RDBMS
3. (C) Amazon Neptune allows you to store and query highly connected databases

## Different AWS databases

1. (A) Relational databases are based on rows and columns and can only be used for structured data
2. (A) Amazon ElastiCache is an example of an in-memory database that can be used for apps like gaming.
3. (B) To show how to query data from a DynamoDB table.

## AWS Development

- There are many outdated NginX/Docker functionalities to address because NginX and Docker are constantly being changed and updated. You can find all deprecated versions of docker in the docker docs [here](https://docs.docker.com/engine/deprecated/)

## DuckDNS

Why do we use DNS? - DNS (Domain Name System) is used to translate human-friendly domain names, such as www.example.com, into IP addresses, which are required for identifying and locating resources on the internet.
How does Duck DNS work? - Duck DNS is a dynamic DNS service that allows users to associate a domain name with their dynamic IP address, allowing them to access their devices or services hosted on the internet even if their IP address changes.
What makes Duck DNS unique? - Duck DNS is unique because it offers a free, easy-to-use dynamic DNS service with support for Let's Encrypt SSL certificates, making it suitable for securing custom domain names for home-based projects or services.
How is Duck DNS useful for our projects? - Duck DNS is useful for projects that require remote access to devices or services hosted on the internet, but have dynamic IP addresses, as it allows users to access them using a static domain name instead of constantly changing IP addresses.
What are the steps to set up Duck DNS? - The steps to set up Duck DNS typically involve creating an account on the Duck DNS website, selecting a domain name, installing a client or script on the server or device that needs to be accessed remotely, and configuring it to update the DNS records with the current IP address.

## Certbot Alternatives

OpenSSL and LibreSSL are two popular open-source cryptographic libraries used for implementing SSL/TLS protocols in various applications. While they share similarities, there are some differences in their security features.

OpenSSL has a larger codebase and has experienced several high-profile security vulnerabilities in the past, such as Heartbleed (CVE-2014-0160) and DROWN (CVE-2016-0800), which were critical vulnerabilities that allowed for remote code execution and information disclosure, respectively.

LibreSSL, on the other hand, is a fork of OpenSSL that was created with the goal of providing a more secure and modern implementation. It has a smaller codebase, with a focus on removing deprecated and legacy code to reduce attack surface. As a result, LibreSSL aims to provide a more secure option compared to OpenSSL.

Both OpenSSL and LibreSSL have active security teams that quickly address vulnerabilities through regular updates and patches. However, it's important to note that no software is completely immune to vulnerabilities, and it's crucial to keep both libraries updated to the latest versions and follow best practices for secure implementation and configuration to mitigate potential risks.

## Certbot

