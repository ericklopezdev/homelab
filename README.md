![homelab banner](/docs/assets/homelab.png)
# Homelab Project

This project documents the setup and configuration of a homelab server.

## Overview

This homelab project aims to create a secure, hybrid home lab environment combining on-premise and cloud resources. The setup uses Debian as the base operating system and follows security best practices for infrastructure hardening.

## Prerequisites

- Debian stable ISO
- Hardware capable of running Debian (minimum requirements)
- Basic knowledge of Linux command line and networking concepts
- SSH client for remote access

## Getting Started

Follow the stages in sequential order to set up your homelab server. Each stage builds upon the previous one.

## Stages

1. [Stage 01 – Bootstrap Server](docs/stages/01-setup.md): Provide a minimal Debian server as a secure base for a hybrid home lab.

2. [Stage 02 – Security Hardening](docs/stages/02-hardening.md): Secure the Debian on-prem server following baseline hardening practices.

3. [Stage 03 – Network](docs/stages/03-network.md): Design and deploy a private internal DNS for the homelab.

## Architecture

- [Azure](docs/architecture/azure.md)
- [AWS](docs/architecture/aws.md)
- [On-Prem](docs/architecture/onprem.md)
- [Hybrid](docs/architecture/hybrid.md)
