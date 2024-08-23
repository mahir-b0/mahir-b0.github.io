---
layout: post
title: portswigger web academy
date: 2024-08-22 19:15:00
description: my progression through the web security labs on portswigger
tags: learning
categories: 
tabs: true
---

Thought I'd use this blog to keep track of my progress throughout the PortSwigger Web Academy, where I'm aiming to learn about common web vulnerabilities and how to exploit them. Shoutout to my mate <a href="https://www.linkedin.com/in/abdul-haadi-siddique-0b4455247/">Abdul</a> for showing me this resource.

# Server-side vulnerabilities

## SQL Injection

### What is an SQLi?

Put simply, it's a web vulnerability that lets an attacker input a malicious query to access sensitive data inside a database. It could also enable them to perform <a href="https://www.cloudflare.com/learning/ddos/glossary/denial-of-service/">denial-of-service attacks</a>. 

### What are the impacts of an SQLi?

SQLi's can compromise PII and SPII such as:

- passwords
- credit card details
- personal user info (e.g. DOB, home address)