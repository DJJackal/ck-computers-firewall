# CK Computers Firewall

A Windows network monitor and threat watcher by [CK Computers](https://ckcomputers.com.au) – Expert IT Solutions & Repairs, Adelaide.

![See who's knocking](ads/CK-ad-1.png)

## What it does

- **Live connections** – every program talking to the internet, where it's connecting, and how much it sends and receives.
- **Blocked attempts** – port probes and scans stopped by Windows Firewall (needs dropped-packet logging, which the app can switch on for you).
- **Failed sign-ins** – watches Windows sign-in attempts and flags repeated failures or remote logins.
- **Devices on your network** – finds everything on your LAN and flags devices you haven't seen before.
- **Threat lists** – checks connections against public lists of known-bad addresses (Feodo Tracker, Spamhaus DROP, Emerging Threats, IPsum, CINS Army).
- **Optional auto-block** – can block botnet command servers automatically using real Windows Firewall rules. Off by default, and every block can be undone from the Blocklist tab.
- **Health report** – one click creates a branded, printable HTML security report.
- **Ignore alerts** – right-click any alert to ignore it so it no longer affects the status or the report. Undo any time from Alerts > Ignored.

## Requirements

- Windows 10 / 11 (64-bit)
- Run as Administrator (the app asks for it; it needs it to read firewall logs and manage firewall rules)

## Download and run

Download `CKFirewall.exe` and run it. No installer, no extra runtime needed. The app keeps running in the system tray when you close the window.

Windows SmartScreen may warn about an unrecognised publisher, because the file isn't code-signed. Choose **More info → Run anyway** if you trust the source.

## Notes

- This is a monitoring aid, not a guarantee of security.
- IP geolocation by DB-IP.com. Device makers from the Wireshark OUI list.

## Contact

CK Computers – [ckcomputers.com.au](https://ckcomputers.com.au)
