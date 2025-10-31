## Working-with-VPNs
Author: Rajeev More  
Date: October 31, 2025  

## Objective  
To understand how a Virtual Private Network (VPN) protects privacy and secures communication by encrypting data traffic and masking the user’s real IP address.

## Tools Used  
- VPN Client: ProtonVPN (Free Tier)  
- Browser: Google Chrome  
- Verification Sites:  
  - `https://whatismyipaddress.com`
  - `https://speedtest.net` 
  - `https://www.tiktok.com`
- Operating System: Windows 10  

## Steps Performed  

### 1. Account Creation
- Created a free account on `https://protonvpn.com`.  
- Verified email and logged in successfully.  

### 2. Installation and Setup
- Downloaded the official ProtonVPN client for Windows.  
- Installed and launched the VPN, then signed in using my credentials.  

### 3. Checking IP Before VPN
- Visited `https://whatismyipaddress.com` before connecting.  
- My IP showed 49.36.***.**, location Thane, Maharashtra, India (ISP: Reliance Jio Infocomm).  

### 4. Connecting to VPN
- Selected the Oslo (Norway) server from ProtonVPN’s free options.  
- Clicked Connect, and after a few seconds, the connection was successfully established.  

### 5. Verifying IP and Accessing Restricted Site
- After connecting, visited TikTok’s website `https://www.tiktok.com`.  
- TikTok loaded successfully, confirming VPN tunneling and region bypass since it’s blocked in India.  
- This proves that my traffic was routed through ProtonVPN’s foreign server (Oslo).  

### 6. Checking Speed While Connected
- Ran a test at `https://speedtest.net`.  
- Results showed:  
  - Download: 25.90 Mbps  
  - Upload: 27.13 Mbps  
  - Ping: 144 ms  
- Speed dropped slightly, as expected, due to encryption overhead.  

### 7. Disconnecting VPN
- After disconnecting, the IP reverted back to my local Indian IP and normal speed resumed.  

## Observations  

| Test | Before VPN | After VPN | Result |
|------|-------------|-----------|--------|
| IP Address | 49.36.***.** (India) | Oslo, Norway | Changed  |
| TikTok Access | Blocked | Accessible | Successful |
| Encryption | None | Enabled (VPN Tunnel) | Secured  |
| Speed | Normal | Slightly slower | Expected  |

## Understanding VPNs  

### What is a VPN?
A Virtual Private Network (VPN) encrypts your internet traffic and routes it through a remote server. This hides your real IP address and location, ensuring data confidentiality and online anonymity.

### How VPNs Protect Privacy
- Encrypt all data using AES-256 or similar protocols.  
- Hide user’s IP address by masking it with the VPN server’s IP.  
- Prevent ISPs, advertisers, or attackers from tracking your browsing activity.  

### Common VPN Protocols
- OpenVPN — Secure, open-source standard.  
- IKEv2/IPSec — Stable and fast, often used on mobile.  
- WireGuard — Modern, lightweight, and fast protocol (used by ProtonVPN).  

## VPN vs Proxy  

| Feature | VPN | Proxy |
|----------|-----|-------|
| Encryption |  Yes |  No |
| System-wide Protection |  Yes |  No |
| Speed | Slightly slower | Faster |
| Privacy | High | Low |
| Use Case | Security, anonymity | Simple content access |

## Limitations of VPNs  
- Slight reduction in internet speed.  
- Free VPNs may have limited bandwidth or server choices.  
- VPNs cannot guarantee complete anonymity if logs are kept.  
- Some websites detect and block VPN IPs.  

## Conclusion  
Using ProtonVPN successfully demonstrated:  
- IP address masking  
- Secure encrypted tunnel communication  
- Bypassing region restrictions (TikTok test)  

VPNs are essential for secure browsing, privacy protection, and safely using public Wi-Fi networks.

