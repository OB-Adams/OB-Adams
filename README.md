# Ebenezer Obiri Adams (OB)

Linux systems administrator based in Accra, Ghana. I build, break and document multi-host labs on RHEL-family and Ubuntu servers, and I'm looking for a junior Linux administrator, cloud support or infrastructure operations role.

**Certifications:** Red Hat Certified System Administrator (RHCSA) · Oracle Cloud Infrastructure Architect Associate
**Education:** BSc Computer Science, GIMPA (2026)

## Featured labs

| Project | What it shows | Stack |
| --- | --- | --- |
| [glusterfs-replicated-lab](https://github.com/OB-Adams/glusterfs-replicated-lab) | Replicated storage cluster taken through nine recorded drills: failure and recovery, brick rebuild and move, expansion to 2 x 3, mutual TLS with certificate-based client authorisation, and Prometheus/Grafana alerting. Cut the worst client write stall on node failure from 70.3 s to 13.2 s. | CentOS Stream 9, GlusterFS, LVM, XFS, SELinux, TLS, Prometheus, Grafana |
| [ansible-observability-lab](https://github.com/OB-Adams/ansible-observability-lab) | Nine Ansible roles that deploy a full monitoring stack across Ubuntu, Rocky Linux and CentOS, with checksum-verified downloads, configs validated before rollout, a non-root `ansible-admin` account, and CI enforcing `ansible-lint` (production profile). | Ansible, Jinja2, Prometheus, Loki, Grafana, Alloy |
| [linux-ldap-lab](https://github.com/OB-Adams/linux-ldap-lab) | Centralized authentication with 389 Directory Server, a private CA for LDAPS and StartTLS, least-privilege ACIs, SSSD client login over SSH, and scripted backups and health checks. | Rocky Linux 10, CentOS Stream 10, 389-DS, SSSD, TLS |
| [linux-observability-lab](https://github.com/OB-Adams/linux-observability-lab) | Metrics, logs and alerting for a mixed Linux fleet, with instance-down and resource alerts routed to Discord. | Docker Compose, Prometheus, Grafana, Loki, Alertmanager |
| [linux-dns-lab](https://github.com/OB-Adams/linux-dns-lab) | BIND9 authoritative and recursive DNS with forward and reverse zones, forwarding, static networking and `dig`-based troubleshooting. | Ubuntu Server, Rocky Linux, BIND9, UFW |
| [docker-nginx-lb](https://github.com/OB-Adams/docker-nginx-lb) | Three app replicas load-balanced behind an NGINX HTTPS reverse proxy, with a GitHub Actions pipeline building and pushing images. | Docker, NGINX, GitHub Actions |

## Currently working on

- **GlusterFS lab:** an `fio` performance baseline and an Ansible role that rebuilds the lab, then a CephFS build on the same VMs with the same drills
- **Hardening lab:** an Ansible hardening role with OpenSCAP CIS Level 1 scans before and after, on Rocky Linux and CentOS

## Tools I use

Linux (RHEL-family, Ubuntu) · systemd · LVM · SELinux · firewalld · Bash · Ansible · Git · Docker · NGINX · Prometheus · Grafana · Loki · AWS · OCI

## Contact

ebenobiriadams@gmail.com
