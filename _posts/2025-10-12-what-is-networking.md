---
layout: post
title: 'TryHackMe Room: What is Networking?'
date: 2025-10-12
---

This week I started my **TryHackMe Pre-Security path**, and I’m completely hooked. What started as curiosity about cybersecurity has turned into a full-on grind to complete each room successfully.  
Every challenge feels like leveling up in a game, and today’s quest, **“What is Networking”** was such a fun introduction to how devices communicate across the Internet.  
I wrapped up the room feeling like I just unlocked the first big piece of the puzzle, and honestly, I’m obsessed.

Here’s what I learned:

<h2>$ mission brief <span class="cursor"></span></h2>

Room: [What is Networking?](https://tryhackme.com/room/whatisnetworking)  
Path: Pre-Security

**Goal:**
Explore how computers, routers, and other devices communicate to form the networks we use every day.

<h2>$ mission log <span class="cursor"></span></h2>

Networking keeps the digital world alive. Every message, stream, and file is just **data moving between devices** using shared rules (protocols).

<h2>$ internet : network of networks <span class="cursor"></span></h2>

Alice links Bob, Jim, Zayn and Toby — she becomes the connector/translator.  
The Internet = billions of small networks connected so data can move worldwide.

---

<h2>$ device identity <span class="cursor"></span></h2>

| Human       | Device                         |
| :---------- | :----------------------------- |
| Name        | IP address (can change)        |
| Fingerprint | MAC address (hardware, stable) |

**IP** = temporary address for communications  
**MAC** = permanent hardware fingerprint

> Note: MAC addresses can be spoofed, so MAC filtering alone is not a secure control.

---

<h2>$ ipv4 vs ipv6 <span class="cursor"></span></h2>

| Version | Quick                                  |
| :------ | :------------------------------------- |
| IPv4    | ~4.3 billion addresses — running low   |
| IPv6    | 340 trillion+ addresses — future-proof |

---

<h2>$ ping : basic check <span class="cursor"></span></h2>

Ping is one of the most fundamental network tools available to us.  
It uses **ICMP (Internet Control Message Protocol)** packets to measure how reliable a connection is between two devices.

The time taken for packets to travel is measured through ICMP’s _echo_ and _echo reply_ messages.  
You can ping local devices or websites. It’s built into Linux, macOS, and Windows.

**Syntax:**

ping <IP-address-or-hostname>

<h2>$ history : nutshell <span class="cursor"></span></h2>
1960s → ARPANET (first computer network)
1989  → World Wide Web (Tim Berners-Lee)
Today → Billions of networks linked into the Internet

<h2>$ cyber takeaway <span class="cursor"></span></h2>
Understanding how devices identify and connect is the foundation of cybersecurity.
