+++
title = "Homelab"
date = "2025-10-20"
draft = false
+++

My homelab is one of the most impactful and practical projects I’ve worked on.  
It started as a small Linux test server and gradually evolved into a full **virtualized, secure and self-hosted infrastructure**, built for learning, experimentation, and reliability.

---

## Core Infrastructure

The entire environment is built on **Proxmox VE**, which I use as the main hypervisor.  
It runs a mix of lightweight LXC containers and full virtual machines, depending on the workload.

Key components include:

- **Proxmox VE** (virtualization layer)
- **LXC containers** for most services
- **VMs** for workloads requiring isolation
- **Tailscale** for secure remote access

---

## Self-Hosted Services

I self-host several applications that I use daily or for experimentation.  
Some of the key ones include:

- **Immich** — Photo and video management  
- **Nextcloud** — Personal cloud, file sync, notes, and calendar  
- **Pi-hole** — Network-wide ad blocking  
- **Development containers** for testing Linux, CI/CD, automation, and security tools

Each service is isolated in its own container or VM for modularity and easy rollback.

---

## Experimenting with Kubernetes

I’m currently evolving my setup by experimenting with **Kubernetes** inside Proxmox.
The goal is to migrate part of my services into a **scalable, declarative and cloud-native environment**, while keeping full control at home.

---

## What I’ve Learned

Building this homelab taught me:

- Linux server administration  
- Virtualization (KVM, LXC) and containerization  
- Networking, DNS, VPNs, firewall rules  
- Storage management, snapshots, backups  
- Monitoring & observability  
- Cloud-native architectures (Kubernetes, CI/CD)

It’s an ongoing and evolving project and probably the best hands-on lab I could have built for myself.
