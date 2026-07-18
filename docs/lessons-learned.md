# Lessons Learned

> A personal engineering journal documenting what I learn while building Aincrad.

---

# 2026

## Foundation

### Linux

- Linux servers are designed to run continuously without a monitor or keyboard.
- SSH allows a server to be managed entirely remotely.
- Most administration can be done from another computer.

---

### Networking

- Installing Ubuntu Server without internet can lead to missing packages such as NetworkManager.
- Temporary USB tethering can simplify the installation process when Wi-Fi setup becomes difficult.
- Tailscale removes the need for port forwarding while still providing secure remote access.

---

### Security

- SSH keys are both more secure and more convenient than passwords.
- Passwordless authentication still relies on cryptography—it does **not** mean authentication is disabled.
- A firewall should explicitly allow required services before being enabled.

---

### Documentation

- Good documentation explains *why*, not just *how*.
- Recording problems and solutions is often more valuable than recording commands.
- Building in public encourages better engineering practices.

---

### Personal Reflection

This project started with an old laptop that was no longer being used.

The goal isn't simply to self-host applications.

The goal is to understand the technologies behind them and build confidence by solving real problems along the way.