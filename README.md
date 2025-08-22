# Traefik VM Deployment Log

This repository documents the setup and configuration of a Traefik reverse proxy to manage multiple Dockerized services on a self-hosted virtual machine. It includes configurations, architecture, deployment steps, authentication layers, and HTTPS setup across projects like:

- [n8n](https://n8n.io/) – Workflow automation tool
- [DocuSeal](https://www.docuseal.com/) – Open-source document signing
- [Plane](https://plane.so/) – Open-source project planning tool

---

## 🌐 Purpose

To create a secure, maintainable reverse proxy setup using Traefik that:
- Routes multiple services via subdomains
- Secures access with HTTPS using Let's Encrypt
- Supports SSO via Authelia (or other providers)
- Logs setup and config changes for future reference and VM migration

---

