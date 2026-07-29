# 🖥️ Windows-ad-homelab-
A self hosted home lab simulating IT infrastructure like Windows Server Active Directory deployed on VMware Workstation, covering domain services, user/group management, and GPOs.

## 🎯 Goals
- 🏗️ Set up and configure Active Directory Domain Services ✅
- 👥 Practice user, group, and OU management ✅
- 📋 Configure Group Policy Objects (GPOs) ✅
- 🎫 Build a ticket-based troubleshooting system
- 📝 Document the build process step by step ✅ (ongoing)

## 🛠️ Tools
- 📦 VMware Workstation (free/personal use)
- 🪟 Windows Server 2022 (evaluation edition)

## 📊 Status
🚧 In progress — AD, OUs, Groups, and GPOs are complete. Ticket system planned next.

## 📅 Log
- 7/23/2026 - 🚀 Started project, installed VMware Workstation
- 7/23/2026 - 💿 Downloaded Windows Server 2022 ISO (Microsoft Evaluation Center)
- 7/23/2026 - 🖥️ Created VM and installed Windows Server
- 7/23/2026 - 🏗️ Installed Active Directory Domain Services, promoted to domain controller (usertubro.local)
- 7/23/2026 - 📁 Created Organizational Units (USA, Europe, Asia)
- 7/23/2026 - 👥 Created security groups (IT, Accounting, HR, Sales, Management) and user accounts
- 7/26/2026 - 📋 Configured Password Policy GPO (14 char minimum, complexity enabled, 90 day max age)
- 7/27/2026 - 🖥️ Created custom GPO for Drive Mapping

## 📄 Detailed Documentation
See [docs/ad-setup-steps.md](docs/ad-setup-steps.md) for full step-by-step setup with screenshots.
