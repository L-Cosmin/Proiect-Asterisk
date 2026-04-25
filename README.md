# Asterisk VoIP Implementation (PJSIP)

A functional PBX setup developed as part of a telecommunications study project.

## 🛠 Project Overview
This project demonstrates the implementation of a modern VoIP server using Asterisk and the PJSIP stack.

## 🚀 Key Features
- **PJSIP Stack:** Implementation of the modern SIP stack for better scalability and security.
- **Network Integration:** Configured to work in a virtualized environment with full connectivity between Host and Guest systems.
- **Authentication & Security:** Managed secure extension registration using PJSIP Auth and AOR (Address of Record) objects.
- **Dialplan Logic:** Custom call routing defined for seamless communication between endpoints.

## 📂 Configuration Files
- `pjsip.conf`: Defines transport, authentication, and endpoint configurations.
- `extensions.conf`: Contains the dialplan and call routing logic.
- `modules.conf`: Manages module loading for a streamlined server performance.
