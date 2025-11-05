# Ansible_Switch_Playbooks
I developed Ansible playbooks to automate bulk configuration changes across network switches, streamlining the deployment process and reducing manual intervention. These playbooks ensure consistency, accuracy, and efficiency in implementing configuration updates, demonstrating the power of network automation using Ansible.
# 🔧 Network Switch Configuration Automation using Ansible

This repository contains Ansible playbooks designed to automate bulk configuration changes across multiple network switches. The project demonstrates how network automation can simplify large-scale configuration management, ensuring consistency, accuracy, and operational efficiency.

---

## 🚀 Overview

Managing configuration updates across hundreds of network switches manually can be time-consuming and error-prone.  
This project leverages **Ansible** to automate switch configurations — pushing changes, validating states, and ensuring network compliance in a repeatable and controlled way.

### Key Features
- ⚙️ **Bulk Configuration Updates** — Apply configuration changes to multiple switches simultaneously.  
- 🧩 **Modular Playbook Design** — Separate roles for configuration templates, tasks, and variables.  
- ✅ **Pre/Post Checks** — Verify configurations before and after deployment.  
- 🔁 **Rollback Support** — Easily revert to previous configurations if needed.  
- 📋 **Dynamic Inventory Support** — Manage switch groups dynamically via YAML or external sources (NetBox, CSV, etc.).  

---

Before you begin, ensure you have the following:
- **Ansible** v2.12+ installed  
- **Python 3.8+**  
- SSH access to network switches  
- Network devices supporting Ansible connection plugins (e.g., `ansible.netcommon.network_cli`)  

Optional tools:
- `netmiko` or `paramiko` for device connectivity  
- `napalm` for validation tasks  

---

## ⚙️ Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/ansible-switch-automation.git
   cd ansible-switch-automation
