<p align="center">
  <img src="assets/infra-banner.svg" alt="Terminal-inspired banner introducing Muhammad Hakim as an aspiring platform engineer" width="100%">
</p>

<p align="center">
  <strong>ASPIRING PLATFORM ENGINEER</strong> · Cloud Engineering · Site Reliability Engineering
  <br>
  Diploma in Information Technology student at Universiti Tun Hussein Onn Malaysia (UTHM)
</p>

<p align="center">
  <code>Build → Deploy → Break → Observe → Fix → Document → Improve</code>
</p>

I learn by building and operating practical systems: Linux workloads, containerized services, network designs, monitoring, and automation. My goal is to grow into platform engineering by understanding not only how systems are deployed, but how they behave when something fails.

## Engineering projects

### StudexHub — self-hosted application platform

A full-stack academic management app deployed on a self-hosted Linux server. Its public repository includes a Docker Compose application and PostgreSQL service; project documentation describes the Nginx and Cloudflare Tunnel deployment path. A companion repository contains the Prometheus monitoring stack.

- Docker Compose, PostgreSQL, Nginx, Cloudflare Tunnel
- Prometheus, Grafana, Alertmanager, and Blackbox Exporter
- Operational runbooks and a separate Python control-plane project for health checks, controlled service operations, and database backups
- The public StudexHub repository currently has no checked-in GitHub Actions workflow, so CI/CD is not presented as an implemented feature

[StudexHub](https://github.com/Xaknm-Hakim/StudexHub) · [Monitoring stack](https://github.com/Xaknm-Hakim/Monitoring) · [Control plane](https://github.com/Xaknm-Hakim/mini-control-plane)

### Enterprise campus network — simulated design

A Cisco Packet Tracer campus-network design documented with a topology image and project report. It is a simulation, not a claim of operating a production enterprise network.

- Three-tier core, distribution, and access architecture
- VLANs, OSPF, HSRP, DHCP and relay, ACLs, and Cisco CME/VoIP
- Documented failover and troubleshooting scenarios

[Network design and report](https://github.com/Xaknm-Hakim/Network-Campus-Topology)

### Cloud and infrastructure labs — learning track

I am developing practical AWS and Terraform skills around EC2, security groups, Linux workloads, and reproducible infrastructure. **I do not currently have a public AWS/Terraform project to link**, so these are learning areas rather than portfolio claims.

### Infrastructure control and automation

The public `mini-control-plane` project is a Python Telegram interface for host/service health checks and controlled StudexHub operations. Its code includes confirmation-oriented administrative actions, structured logging, service restart and PostgreSQL backup operations; the repository also includes a runbook. Bash is part of my broader automation toolkit, not a capability this project specifically demonstrates.

[Review the implementation](https://github.com/Xaknm-Hakim/mini-control-plane)

## Technical stack

Badges show technologies used in projects or tools I work with; learning-stage areas are called out separately below.

**Linux & Infrastructure**<br>
`Linux` `Fedora` `systemd` `KVM/libvirt`

**Cloud & IaC**<br>
`AWS · learning` `Terraform · learning` `Cloudflare Tunnel`

**Containers & Platform**<br>
`Docker` `Docker Compose` `Nginx` `PostgreSQL`

**Automation & CI/CD**<br>
`Python` `Bash` `GitHub Actions · familiarity`

**Observability**<br>
`Prometheus` `Grafana` `Alertmanager`

**Networking**<br>
`VLANs` `OSPF` `HSRP` `ACLs` `DHCP`

**Programming & Databases**<br>
`Python` `TypeScript / JavaScript` `SQL` `PostgreSQL` `Prisma`

## Current engineering focus

These are active learning and home-lab goals, not claims of production Kubernetes or cloud experience:

- Terraform and reproducible infrastructure
- KVM/libvirt home lab and Linux system administration
- AWS architecture and cloud networking fundamentals
- Container orchestration, with Kubernetes as a learning area
- Platform automation, observability, and reliability engineering

## GitHub activity

I have left out third-party contribution and language widgets. GitHub's native profile activity and repository language views are the more direct references, without adding fragile external statistics services.

## Contact

[LinkedIn](https://www.linkedin.com/in/muhammad-hakim-zaaba) · [Email](mailto:hakimz.7117@gmail.com)
