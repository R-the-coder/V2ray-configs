# Best V2Ray Clients — Android / iOS / Windows

_Quick, simple guide for getting started with V2Ray clients on mobile and PC._  
**Use only in ways that are legal where you are.** See Safety note at the end.

---

## Quick picks (links)
- **Android**
  - [Clash for Android](https://github.com/MetaCubeX/ClashMetaForAndroid) — advanced, rules & routing.  
  - [V2RayNG](https://github.com/2dust/v2rayNG) — simple, lightweight.
- **iOS**
  - [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) — paid, full-featured.  
  - [Kitsunebi](https://apps.apple.com/us/app/kitsunebi-proxy-utility/id1446584073) — V2Ray-native option.
- **Windows**
  - [Clash for Windows](https://github.com/clashdownload/Clash_for_Windows) — advanced rule-based client.  
  - [v2rayN](https://github.com/2dust/v2rayN) — simple, popular Windows GUI.

---

## Before you begin (what you need)
A V2Ray server subscription or single-server config (from your trusted provider) that includes:
- server address (IP or hostname)  
- port  
- protocol (VMess / VLESS / Trojan)  
- **UUID / user id** (for vmess/vless) or credentials the provider gives  
- network/transport (tcp / ws / h2 / quic) and path (if websocket)  
- whether TLS is required

> Most clients accept either a **subscription URL** (often starts with `http(s)://` or `vmess://`/`vless://`) or a **QR code**. If you have a subscription URL, import it; that’s the easiest.

---

## Android — Simple: V2RayNG
[Get V2RayNG](https://github.com/2dust/v2rayNG).  

**Super-simple steps**
1. Install the APK from the GitHub releases link.  
2. Open V2RayNG → tap `+` (or `Import`) → **Import subscription URL** or **scan QR**.  
3. Select a server from the list → tap **Connect**.  
4. Verify: open a browser → go to `https://whatismyipaddress.com` or a geolocation site to confirm your IP changed.

**If you prefer manual add**
- Tap `+` → choose VMess (or VLESS) → paste server address, port, UUID, transport (ws/tcp), path, and TLS on/off → Save → Connect.

**Tip:** If something fails, check the app log (inside the client) to confirm the UUID/protocol and transport match the server settings. :contentReference[oaicite:3]{index=3}

---

## Android — Advanced: Clash for Android
[Get Clash for Android](https://github.com/MetaCubeX/ClashMetaForAndroid).  

**Simple usage**
1. Install from the repo releases / Play store build.  
2. Open app → `Profiles` → **Import** subscription URL (often called “config” or `.yaml` link) or local YAML file.  
3. Switch the profile on and choose a mode (Global / Rule / Direct).  
4. Use the built-in rules to route traffic per domain or app.

**Why use Clash:** advanced routing (per-app/domain), supports many protocols and complex routing rules. Good if you want fine control. :contentReference[oaicite:4]{index=4}

---

## iOS — Paid & reliable: Shadowrocket
[Get Shadowrocket (App Store)](https://apps.apple.com/us/app/shadowrocket/id932747118).  

**Simple usage**
1. Buy/download from App Store.  
2. Open → `Configuration` → `Add` → choose VMess/VLESS/Trojan etc. OR import subscription URL (often provided by your server provider) or scan QR.  
3. Enable the profile (toggle the switch).  
4. Verify with a web check (whatismyip).

**Notes:** Shadowrocket is paid but widely used and supports VMess/VLESS and many transports. :contentReference[oaicite:5]{index=5}

---

## iOS — Free-ish alternative: Kitsunebi (and others)
[Kitsunebi on App Store](https://apps.apple.com/us/app/kitsunebi-proxy-utility/id1446584073).  

**Steps** are similar: install → import subscription or scan QR → enable. Kitsunebi is V2Ray-native and supports multiple transports. :contentReference[oaicite:6]{index=6}

---

## Windows — Simple: v2rayN
[v2rayN (GitHub)](https://github.com/2dust/v2rayN).  

**Simple steps**
1. Download the release ZIP → extract → run `v2rayN.exe`.  
2. `Servers` → `Import` → paste subscription URL or add server manually (Address, Port, UUID, Transport, Path, TLS).  
3. Click `Start` → set system proxy mode (if asked) or configure browser/system to use the proxy.  
4. Verify with an IP/geolocation check.

**Note:** v2rayN is a Windows GUI built specifically for V2Ray core. :contentReference[oaicite:7]{index=7}

---

## Windows — Advanced: Clash for Windows
[Clash for Windows (GitHub)](https://github.com/clashdownload/Clash_for_Windows).  

**Simple usage**
1. Install the app from releases.  
2. `Profiles` → import subscription YAML or file.  
3. Toggle **Start** and pick a mode (Global/Rule/System Proxy).  
4. Use the UI to choose nodes and routing rules.

**Why use Clash:** advanced rule engine, supports multiple protocols, profile management, and GUI for switching policies. Great for power users. :contentReference[oaicite:8]{index=8}

---

## Troubleshooting — quick checklist
- Wrong credentials? Re-check UUID / port / protocol.  
- Transport mismatch? If server uses WebSocket with a path, make sure the path is set.  
- TLS issues? Toggle TLS on/off depending on server.  
- Logs: always open the client logs — they show connection errors.  
- System proxy vs app VPN: some clients provide an OS-level VPN mode (iOS, Android), others use system proxy — pick according to your needs.

---

## Safety & Legal
- These tools can be used to increase privacy, but laws and acceptable use vary by country and network. **Do not use to perform illegal activity**. Use only services and servers you legally own or are allowed to use.

---

## Links / sources used for this README
- V2RayNG — https://github.com/2dust/v2rayNG  
- Clash for Android — https://github.com/MetaCubeX/ClashMetaForAndroid  
- Shadowrocket (App Store) — https://apps.apple.com/us/app/shadowrocket/id932747118  
- Kitsunebi (App Store) — https://apps.apple.com/us/app/kitsunebi-proxy-utility/id1446584073  
- v2rayN — https://github.com/2dust/v2rayN  
- Clash for Windows — https://github.com/clashdownload/Clash_for_Windows

