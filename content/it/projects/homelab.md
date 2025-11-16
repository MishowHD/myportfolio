+++
title = "Homelab"
date = "2025-10-20"
draft = false
+++

Il mio homelab è uno dei progetti più importanti e formativi che abbia realizzato.  
Nato come un semplice server per testare Linux, oggi è diventato un’infrastruttura **virtualizzata, sicura e completamente self-hosted**, pensata per imparare, sperimentare e migliorare la mia conoscenza dei sistemi.

---

## Infrastruttura Principale

L'intero ambiente si basa su **Proxmox VE**, che utilizzo come hypervisor principale.  
Al suo interno eseguo un mix di container LXC e macchine virtuali a seconda del carico.

Componenti principali:

- **Proxmox VE** (virtualizzazione)
- **Container LXC** per la maggior parte dei servizi
- **VM** per workload che richiedono isolamento
- **Tailscale** per l’accesso remoto sicuro

---

## Servizi Self-Hosted

Eseguo diversi servizi che utilizzo quotidianamente o per sperimentare nuove tecnologie.

Tra i principali:

- **Immich** — Gestione foto e video con AI  
- **Nextcloud** — Cloud personale, note, file e calendario  
- **Pi-hole** — Ad-blocking di rete  
- **Container di sviluppo** per test su Linux, CI/CD, automazioni e strumenti di sicurezza

Ogni servizio è isolato nel proprio container o VM per garantire modularità e rollback immediati.

---

## Sperimentazione con Kubernetes

Recentemente sto evolvendo la mia infrastruttura sperimentando **Kubernetes** direttamente dentro Proxmox. L’obiettivo è migrare parte dei servizi in un ambiente **scalabile, dichiarativo e cloud-native**, mantenendo pieno controllo dall’homelab.

---

## Cosa ho imparato

Questo progetto mi ha insegnato:

- Amministrazione di server Linux  
- Virtualizzazione (KVM, LXC) e containerizzazione  
- Networking avanzato, DNS, VPN e firewall  
- Storage, snapshot e backup affidabili  
- Monitoring e osservabilità  
- Architetture cloud-native (Kubernetes, CI/CD)

È un progetto vivo, in continua evoluzione e il miglior laboratorio pratico che potessi costruire.
