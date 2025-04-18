#  Drosera Auto Bot

![Drosera Deploy GIF](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbXZzMms3a2h0NmdkMjl3eTU0ZG8wbDhiZndlbXg4enMyZ3BkYzVjZiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/RJKHjCuwOS9nq/giphy.gif)

![IMG_20250417_231212_603](https://github.com/user-attachments/assets/62552949-62a1-4222-bd28-e425c77d34d3)

---

## 🚀 About This Project

Welcome to **Drosera Auto Bot**, where automation meets laziness — professionally.  
Why click a million buttons when a script can do it for you?

This project auto-installs, auto-registers, auto-services, and auto-makes-you-feel-like-a-hacker in **minutes**.

Forget manual deployment. **Be smarter. Not harder.**

---

## 🛠️ What This Script Will Do

- Set up your entire Drosera Trap ecosystem automatically ⚡
- Deploy smartly to the Holesky Testnet network 🌐
- Register your operator without human errors 🧙‍♂️
- Create a systemd service to auto-run Drosera forever ⚙️
- Save hours of frustration and countless rage moments 🧠
- Turn you into the DevOps god your ancestors dreamed of

---

## ⚡ How to Install in One Shot

Run this absolute masterpiece of a command:

```bash
bash <(curl -s https://raw.githubusercontent.com/Kazuha787/Drosera-Auto-Bot/main/drosera.sh)
```

If you don’t copy-paste this, you’re doing life wrong.

---

## 🧠 Pro Gamer Move: Change Your Ethereum RPC (HIGHLY Recommended)

Using a **public RPC** is like using McDonald's Wi-Fi for hacking. Not smart.

Instead, grab a good RPC from [Alchemy](https://www.alchemy.com/) or [Blast.io](https://blast.io/).

### ✍️ Here's how to swap the RPC:

```bash
sudo systemctl stop drosera
sudo nano /etc/systemd/system/drosera.service
```

- Find the `--eth-rpc-url` line
- Replace it with your personal RPC URL

Like a boss.

### 🔁 Then reload and restart the service:

```bash
sudo systemctl daemon-reload
sudo systemctl start drosera
```

**Boom. Done.**

---

## 📟 Watch Logs Like Mr. Robot

Stay updated on what's happening inside your Drosera trap:

```bash
journalctl -u drosera.service -f
```

Real-time hacker vibes.

![Hacker GIF](https://media.giphy.com/media/2fQ1FyzXA2v1y/giphy.gif)

---

## ⚠️ Warning Section (You Will Cry If Ignored)

- You **NEED** Holesky ETH to deploy traps. No ETH = No deployment.
- You **MUST** send **Bloom Boost** before using `dryrun`.
- You **WILL** rage-quit if you skip a step. Respect the process.

No shortcuts, no excuses.

---

## 🌟 Cool Extras

- **Built for Linux/Ubuntu servers.** (Because real devs don't use Windows for this.)
- **Lightweight and fast** install. You could literally do this half-asleep.
- **Highly customizable.** You’re in full control after setup.

---

## 👋 Made With Blood, Sweat, and Bash

By [Kazuha787](https://github.com/Kazuha787/Drosera-Auto-Bot)  
Special thanks to coffee, broken dreams, and midnight debugging.

![Thank You GIF](https://media.giphy.com/media/l0MYB8Ory7Hqefo9a/giphy.gif)

---

# ⭐ Drop A Star If This Helped You Out!
Help a fellow coder out and smash that ⭐ button on the repo!
