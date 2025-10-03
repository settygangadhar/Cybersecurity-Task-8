# Cybersecurity-Task-8

## 🛡️ VPN Setup and Privacy Assessment (macOS)

### 📌 Objective
This project demonstrates the setup and evaluation of a free VPN client on macOS to understand how VPNs protect online privacy, encrypt traffic, and mask IP addresses. It includes screenshots, setup steps, and a summary of VPN benefits and limitations.

---

### 🖥️ System Details
- **Device**: MacBook (macOS Sonoma 15.7)
- **VPN Client**: ProtonVPN (Free Tier)
- **Browser**: Safari
- **IP Verification Tool**: [whatismyipaddress.com](https://whatismyipaddress.com)

---

### ⚙️ Setup Steps

1. **Account Creation**  
   Signed up for a free ProtonVPN account and verified email.

2. **Download & Installation**  
   Downloaded the macOS client for Ventura or newer. Installed via `.dmg` and granted permissions in **System Settings > Privacy & Security**.

3. **VPN Connection**  
   Connected to the nearest free server (India/Singapore). Verified successful connection.

4. **IP Address Verification**  
   - Before VPN: Original IP visible  
   - After VPN: IP changed to VPN-assigned address  
   Verified using [whatismyipaddress.com](https://whatismyipaddress.com)

5. **Traffic Encryption Check**  
   Browsed HTTPS-enabled websites and confirmed encrypted traffic via Safari’s padlock icon and Web Inspector.

6. **Disconnect & Comparison**  
   Disconnected VPN to compare browsing speed and IP reversion.

---

### 🔐 VPN Features Explored

| Feature              | Description                                      |
|----------------------|--------------------------------------------------|
| Encryption Protocols | AES-256 with OpenVPN/WireGuard                   |
| No-Log Policy        | ProtonVPN enforces strict no-log practices       |
| DNS Leak Protection  | Enabled by default                               |
| Kill Switch          | Available in settings                            |
| macOS Integration    | Uses native network extension framework          |

---

### 📸 Screenshots

- ✅ ProtonVPN macOS client showing “Connected” status  
- 🌐 Safari window displaying changed IP on [whatismyipaddress.com](https://whatismyipaddress.com)

*(Screenshots are stored in the `/screenshots` folder)*

---

### 🧠 Summary: VPN Benefits & Limitations

#### ✅ Benefits
- Masks IP address for anonymity
- Encrypts traffic to prevent surveillance
- Secures public Wi-Fi usage
- Bypasses geo-restrictions

#### ⚠️ Limitations
- Free tier may throttle speed or limit servers
- Some websites block VPN traffic
- VPN doesn’t protect against malware/phishing
- Slight reduction in browsing speed

---

### 📁 Repository Structure

```
vpn-privacy-assessment-macos/
├── README.md
├── screenshots/
│   ├── vpn_connected.png
│   └── ip_verification.png
└── vpn_report.pdf
