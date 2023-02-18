---
layout: post
title: Rebuilding my HomeLab
description: information about homelabs
summary: my thoughts on upgrading and rebuilding my homelab
tags: [homelab]
---

This is just going to be a quick brain dump on the future state I want for my home lab. I'll detail the current set up in another post.

* Provision new VMs to desired state using yml files. I'm sure there is a way to do this but I'll need to do some research.
* Manage dns for lab VMs dynamically and update appropriate nameservers automatically
* Set expiration time for throwaway VMs so they're up for $x amount of time and then go away, cleaning up all artifacts (dns, dhcp reservation, etc)
* Web frontend with health stats for all VMs and hypervisors
* Daily/Weekly snapshots of permanent VMs
  * Ansible controller
  * AWX instance
  * DHCP/PXE server
  * DNS servers
  * Plex server (not a lab server per se but it runs on my lab hypervisor)
* Monitoring/Graphs for all permanent VMs

Ok, that's all I have in my head right now. I'm sure this will get updated as I think of new features I want.
