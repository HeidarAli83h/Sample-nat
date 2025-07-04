# Sample-nat
# 🌐 NAT Configuration Project

A simple project to demonstrate how **Network Address Translation (NAT)** works in a small network using Cisco routers.

## 📌 Goals
- Configure **Static NAT**
- Test internal and external connectivity
- Understand real-world use cases

---


## ⚙️ Configuration Files

All configuration files are inside the `config/` directory:
- `router1.txt` – NAT setup on the router
- `router2.txt` – NAT setup on the router
- `pcs.txt` – IP addresses of internal clients

---

## 🧪 How to Test
- Ping from inside PC to public IP
- Use `show ip nat translations`
- Use `debug ip nat`

---

## 📚 Notes

Check `notes.md` for detailed explanation of NAT, how it works, and troubleshooting tips.

---

# 📷 Photos

<p align="center">
  <img src="images/nat.jpg" width="500" alt="Diagram" />
</p>

## 🛠 Tools Used
- Cisco Packet Tracer
- GNS3 (optional)
