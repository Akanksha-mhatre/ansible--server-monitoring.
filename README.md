# Automated Server Monitoring with Ansible

## Project Overview
This project uses Ansible to automate basic health checks
for Nginx and Prometheus on a local Ubuntu environment.

## Tools Used
- Ubuntu on Windows Subsystem for Linux (WSL)
- Ansible
- Nginx
- Prometheus
- Node Exporter

## What I Implemented
- Created an Ansible playbook.
- Checked that Nginx and Prometheus services were running.
- Verified the Nginx HTTP response.
- Checked the Prometheus health endpoint.
- Ran an Ansible syntax check.

## Validation
The playbook completed successfully with zero failed tasks.

## Run the Project
```bash
ansible-playbook -i localhost, monitoring.yml --ask-become-pass
```
## Project Screenshots

## 1. Ansible Playbook Execution

![Ansible playbook execution] (screenshots/ansible%20ss.jpg)

## 2. Prometheus Monitoring Status

![Prometheus monitoring status] (screenshots/prometheus%20status.jpg)
