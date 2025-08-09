# Nexus CLI - WSL

Quick guide to running **Nexus CLI** on **Windows**

---

## 1. 🧪 Enter a Dedicated Screen for Nexus
```bash
screen -S nexuscli
```

---

### 2. 🧰 Install the Latest Nexus CLI Inside the Screen
```bash
curl https://cli.nexus.xyz/ | sh
source ~/.bashrc
```

---

## 3. 🚀 Start the Node in a New Screen
```bash
curl https://cli.nexus.xyz/ | sh
source ~/.bashrc
```

---

🔒 Detach the Screen (Keep It Running in the Background)
Press:
```bash
Ctrl + A then D
```

---

## 4. 📋 Check Active Screens
```bash
screen -ls
```

---

## 5. ❌ Close an Old Screen Session (Optional)
```bash
screen -X -S 123.nexuscli quit
```

---

## 6. 🧼 Notes
If your terminal closes, the CLI will keep running inside the screen.
To return and view your node logs at any time:
```bash
screen -r nexuscli
```

---

---


🔗 Resources
- 🌐 [Nexus Website](https://nexus.xyz/)

- 💻 [Nexus on GitHub](https://github.com/nexus-xyz/nexus-zkvm)

- 🐦 [Nexus on X](https://x.com/NexusLabs)

- 💬 [Nexus on Telegram](https://t.me/nexus_zkvm)

- 🖼 [Nexus Branding](https://nexus.xyz/media)

- 🛠 [Testnet III Troubleshooting Form](https://forms.gle/LCnWvtLX8k1ZB9ks8)

- ❓ [Testnet III FAQs](https://docs.nexus.xyz/layer-1/testnet/faq)

- 🔍 [Testnet III Explorer](https://testnet3.explorer.nexus.xyz/)

- 🐞 [NexusOS Bug Report](https://docs.google.com/forms/d/e/1FAIpQLSfDPGykipbxEhlRNZdodygJ1gdB8Oh0TpB64hPffpOn9a-JMQ/viewform?pli=1)

- 🐞 [Nexus CLI Bug Report](https://github.com/nexus-xyz/nexus-cli/issues)

- 💬 [Nexus Discord Community](https://discord.gg/MdDu4JBn)
