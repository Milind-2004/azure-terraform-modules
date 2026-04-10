# Azure Terraform Modules

Reusable, production-ready Terraform modules for provisioning core Azure infrastructure.

## 📌 Overview
This repository contains modular Terraform configurations for:
- Azure Virtual Machines (Linux)
- Virtual Networks & Subnets
- Network Security Groups
- Storage Accounts & Containers

## 🛠️ Prerequisites
- Terraform >= 1.3
- Azure CLI (`az login`)
- Active Azure Subscription

## 🚀 Quick Start
```bash
cd examples/dev-environment
terraform init
terraform plan
terraform apply
```

## 📁 Module Reference
| Module | Description |
|---|---|
| `modules/vm` | Linux VM with NIC and SSH key auth |
| `modules/vnet` | VNet with configurable subnets |
| `modules/nsg` | NSG with SSH and HTTP rules |
| `modules/storage` | Storage account with private container |

## 🔐 Authentication
```bash
az login
az account set --subscription "<your-subscription-id>"
```

## 📜 License
MIT
