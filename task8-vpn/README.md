# Task 8 - VPN Setup and Privacy Check

## Objective
To understand the role of VPNs in protecting privacy and secure communication.

## Steps Followed
1. Installed **ProtonVPN Free** client on Windows.
2. Checked initial network configuration using `ipconfig`.
3. Verified public IP at [whatismyipaddress.com](https://whatismyipaddress.com) before VPN connection.
4. Connected to ProtonVPN (Netherlands server).
5. Re-ran `ipconfig` to confirm new VPN adapter and private IP.
6. Verified changed public IP at [whatismyipaddress.com](https://whatismyipaddress.com) after VPN connection.

## Screenshots
### 1. IPConfig Before VPN
![ipconfig before](./screenshots/ipconfig-before.png)

### 2. Public IP Before VPN
![IP before](./screenshots/ip-before.png)

### 3. IPConfig After VPN
![ipconfig after](./screenshots/ipconfig-after.png)

### 4. Public IP After VPN
![IP after](./screenshots/ip-after.png)

## Findings
- Before VPN:  
  - Local IP: `192.168.1.3`  
  - Public IP: `103.147.208.74` (Kerala, India)

- After VPN:  
  - VPN adapter IP: `10.2.0.2`  
  - Public IP: `212.8.243.39` (Netherlands)

## Conclusion
The VPN successfully:
- Masked my real public IP.  
- Created a secure encrypted tunnel.  
- Routed my traffic through a foreign server.  

This shows how VPNs protect privacy, though they cannot guarantee full anonymity and may affect browsing speed.

---
**Internship Task 8 Completed ✅**
