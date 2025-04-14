🛡️ GrandpaVPN - Personal Cloud VPN on AWS (OpenVPN)

A custom OpenVPN server deployed on an AWS EC2 instance to enable private, secure internet access with full control over connections. Fully tested and connected on macOS and iOS using Tunnelblick and OpenVPN Connect.
🧠 Features
	•	✅ Deployed on AWS EC2 (t2.micro)
	•	✅ OpenVPN with UDP + TCP options
	•	✅ Custom .ovpn profiles for users
	•	✅ iPhone & Mac compatible (Tunnelblick & OpenVPN)
	•	✅ Custom Security Groups (22, 51820, 1194, 4500, etc.)
	•	✅ Verified IP masking (Whoer.net test)
 
 📷 Screenshots
<img width="1440" alt="Screenshot 2025-04-14 at 6 07 26 AM" src="https://github.com/user-attachments/assets/2e3f165d-b287-49d7-b973-cc29a58e5c2e" />
<img width="1440" alt="Screenshot 2025-04-14 at 6 07 15 AM" src="https://github.com/user-attachments/assets/f1c647a9-6f39-4438-9922-494d27e2738f" />
<img width="1440" alt="Screenshot 2025-04-14 at 6 00 52 AM" src="https://github.com/user-attachments/assets/088<img width="1440" alt="Screenshot 2025-04-14 at 5 58 42 AM" src="https://github.com/user-attachments/assets/e8e8c3d0-69f9-4099-abf8-e6343f5a0646" />
f20c2-3ae8-4898-9774-5dc6f983c4fb" />
<img width="1440" alt="Screenshot 2025-04-14 at 6 00 34 AM" src="https://github.com/user-attachments/assets/b9f05867-3228-4957-a2fe-ae61cf23e475" /><img width="1440" alt="Screenshot 2025-04-14 at 5 59 13 AM" src="https://github.com/user-attachments/assets/bd3c6385-15c0-483f-9de9-636d20ebf916" />

<img width="1440" alt="Screenshot 2025-04-14 at 6 08 32 AM" src="https://github.com/user-attachments/assets/de891644-8fe9-49d8-b800-af2798bf2ae4" />
<img width="1440" alt="Screenshot 2025-04-14 at 6 08 03 AM" src="https://github.com/user-attachments/assets/a9e1c305-f019-4350-a9c0-2ce3b822547d" />
<img width="1440" alt="Screenshot 2025-04-14 at 6 07 46 AM" src=<img width="1440" alt="Screenshot 2025-04-14 at 6 07 43 AM" src="https://github.com/user-attachments/assets/d273ad97-f6e7-4f27-b1a9-c8250bb62be3" />

Includes:
	•	EC2 Launch Steps
	•	Security Group Rules
	•	OpenVPN Installation
	•	Generating OVPN Configs
	•	Testing + Troubleshooting
	•	Creating more users

## 🛠️ How to Deploy (Full Guide in `deployment-guide.md`)

1. Launch EC2 instance with Ubuntu 22.04 LTS
2. Configure security group with the following rules:
   - TCP: 22 (SSH)
   - UDP: 51820, 1194, 500, 4500
3. SSH into server & run OpenVPN installation script
4. Generate `.ovpn` config file (e.g., `grandpa.ovpn`)
5. Use config on Tunnelblick (Mac) or OpenVPN Connect (iOS)
6. Test IP change on https://whoer.net

7. 🔐 Built a personal VPN infrastructure (GrandpaVPN) using OpenVPN on AWS EC2. Configured and tested secure tunneling across iOS/macOS, set custom firewall rules, and validated anonymity using public tools. Documented and published on GitHub.
```

---

## 💬 Author
- Twitter: [@cybergrandpa](https://twitter.com/cybergrandpa)
- GitHub: [grandpacltn](https://github.com/grandpacltn)

---

> “When the world spies, Grandpa masks.” 👴🔒

