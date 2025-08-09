# Nexus CLI - Quick Start Guide (Testnet III)

Simplified installation & usage guide for **Nexus Network Testnet III**.

---

## 🚀 Installation

### 1. Precompiled Binary (Recommended)
```bash
curl https://cli.nexus.xyz/ | sh
```
- Installs latest binary for your OS
- Prompts Terms of Use acceptance
- Starts CLI in interactive mode  
[View install script](https://github.com/nexus-xyz/nexus-cli/)

---

### 2. Non-Interactive Installation
For CI or automation:
```bash
curl -sSf https://cli.nexus.xyz/ -o install.sh
chmod +x install.sh
NONINTERACTIVE=1 ./install.sh
```

---

## 🖥 Running a Node

With existing Node ID:
```bash
nexus-cli start --node-id <your-node-id>
```

Without Node ID:
```bash
nexus-cli register-user --wallet-address <your-wallet-address>
nexus-cli register-node
nexus-cli start
```

Logout:
```bash
nexus-cli logout
```

Help & commands:
```bash
nexus-cli --help
```

---

## 🔗 Resources

**Official Nexus Links**
- 🌐 [Nexus Website](https://nexus.xyz/)
- 🐦 [Nexus on X](https://x.com/NexusLabs)
- 💬 [Nexus Discord Community](https://discord.gg/MdDu4JBn)
- 💬 [Nexus on Telegram](https://t.me/nexus_zkvm)
- 💻 [Nexus on GitHub](https://github.com/nexus-xyz)
- 🔗 [Nexus on LinkedIn](https://www.linkedin.com/company/nexus/)
- 🖼 [Nexus Branding](https://nexus.xyz/media)

**Testnet III**
- 🛠 [Testnet III Troubleshooting Form](https://forms.gle/LCnWvtLX8k1ZB9ks8)
- ❓ [Testnet III FAQs](https://docs.nexus.xyz/layer-1/testnet/faq)
- 🔍 [Testnet III Explorer](https://testnet3.explorer.nexus.xyz/)

**Bug Reports**
- 🐞 [NexusOS Bug Report](https://docs.google.com/forms/d/e/1FAIpQLSfDPGykipbxEhlRNZdodygJ1gdB8Oh0TpB64hPffpOn9a-JMQ/viewform?pli=1)
- 🐞 [Nexus CLI Bug Report](https://github.com/nexus-xyz/nexus-cli/issues)
