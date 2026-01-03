---
layout: default
title: What's homelabbing?
nav_order: 2
---
<!-- 
@file /docs/01-introduction-homelabbing.md 
@author juscghwe ([Github](https://github.com/juscghwe))
@brief What i though homelabbing was and what it tourned out to be.
-->
[← Personnal background](00-personal-background.md) · [→ First Setup](02-first-setup.md)

# What’s homelabbing?

To be completely clear upfront: throughout this documentation, I’ll use **homelabbing** and **self-hosting** almost interchangeably.

The reason is simple: so far, I haven’t found a clean, practical distinction between the two. Sometimes *homelabbing* is described as a pure experimentation lab, while *self-hosting* focuses on running real services — but in practice, most setups do both at the same time.

If a clear distinction emerges later, I’ll happily revisit this.

## What I thought homelabbing was

Before getting started, I watched a lot of YouTube videos, read Reddit threads and skimmed various blog posts. The most common explanation I kept running into was something like this:

!!! quote
    A homelab is a sandbox to test high-traffic applications and networking hacks.

That conclusion turned out to be pretty discouraging.

If that was all a homelab was, my immediate question was:  
**Why not just use virtualization tools like VMware?**

At that point, homelabbing sounded expensive, overly complex and - honestly - not very appealing as a hobby.

## How that world view changed
At some point, I wanted to build a small MVP for a routing problem at work. I’m not an IT expert and I wanted to validate my idea before presenting it — ideally without getting laughed out of the office.

I tried several tools to simulate the setup:

- [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer)  
- [VMWare](https://www.vmware.com/)

Cisco Packet Tracer was actually a fun learning experience, but for this specific problem, it quickly became clear that either the tool - or more likely *me* - wasn’t advanced enough yet.

VMware, on the other hand, turned into a complete nightmare.

Between environment variables, BIOS settings and virtualization conflicts, things spiraled fast. At some point, it even broke my [WSL](https://learn.microsoft.com/en-us/windows/wsl/about) setup — which killed my [Docker Desktop](https://www.docker.com/products/docker-desktop/) environment. What followed was a cascade of unrelated errors that had nothing to do with the original problem.

!!! note
    This is not a rant about these tools.  
    They’re powerful and widely used — I just wasn’t able to use them effectively given my learning curve, abilities, and patience at the time.

## What homelabbing actually turned out to be

!!! tip
    ... to be continued. This chapter isn't finished yet.



[← Personnal background](00-personal-background.md) · [→ First Setup](02-first-setup.md)