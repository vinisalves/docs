# NerdHub — Setup Guide

Follow these steps to install and configure NerdHub locally or connect to your organization’s workspace.

---

## 🧰 Prerequisites

Before setting up NerdHub, ensure you have:
- **Node.js** ≥ 18.x  
- **Docker** ≥ 24.x  
- **kubectl** ≥ 1.29  
- **Git** ≥ 2.40  
- Access to a **NerdHub account**

---

## 🪄 Quick Start (Local)

```bash
# Clone your application repository
git clone https://github.com/nerdhub/examples.git my-app
cd my-app

# Install NerdHub CLI
npm install -g @nerdhub/cli

# Log in to NerdHub
nerdhub login

# Deploy your first app
nerdhub deploy
