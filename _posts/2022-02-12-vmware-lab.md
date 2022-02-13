---
layout: post
title: 🖥️ VMware Lab Part 1 - Design and Plans
description: Tearing down the homelab and starting from scratch. This post details some cool ideas I have for it.
---

Throughout 2022, I want to focus more on VMware technologies in my homelab, with the intent on sitting the VCP-DCV exam later in the year. I'll admit that this site has not has as much content as I initially hoped when I first created it. With this new homelab I hope to try and put out a new post every month detailing what's going into the lab, what I'm tinkering with and findings from it, as well as sharing any tricks and scripts that I write during the process of everything.

But how are we going to work with this? A new server cluster of course! *Alongside the power bill that will go with it.* Whilst it's not the best one I've seen in the VMware space (looking at you Marc Huppert), there's certainly a lot of breathing room with this new lab. 32 CPU cores and over 400GB of RAM. 

![Overview of the Homelab, three nodes, thirty two CPU cores and over four hundred gigabytes of RAM.](/public/lab-screenshot.png){:class="img-responsive"}

The three physical hosts consist of two Dell PowerEdge R620s and a single Dell PowerEdge R420. 

- esxi-01.kotatsu.cloud - 6C, 96GB RAM
- esxi-02.kotatsu.cloud - 2x 8C, 272GB RAM
- esxi-03.kotatsu.cloud - 2x 8C, 64GB RAM

My only complaints are the lack of storage and lack of distributed storage. We'll more than likely see another post very soon about a new 20PB SSD vSAN setup (I wish). vSAN is definitely on the list of things to do for the lab.

Homelab Development Roadmap
- vSAN 
- NSX-T for all networking 
- Horizon for VDI infrastructure including Remote Access
- Tanzu for Kubernetes workloads in a DevOps pipeline
- More to come!
