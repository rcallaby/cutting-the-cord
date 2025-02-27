# A Guide to De-Google Your Life

## 🔹 **Why De-Google?**
Google’s ecosystem is deeply integrated into our digital lives, tracking and monetizing user data. De-Googling is about reducing reliance on Google services and switching to privacy-respecting alternatives.

## **1️⃣ Removing Google from Your Life**
### **1.1 Delete Your Google Account (If Feasible)**
Before deleting, consider:
- **Backing up data**: Use `Google Takeout` (https://takeout.google.com) to export emails, contacts, and files.
- **Transferring dependencies**: Move subscriptions, recovery emails, and logins tied to your Gmail.
- **Replacing services**: Ensure you've fully migrated before deleting.

If you **must** keep an account (e.g., for work), **compartmentalize** its use in a sandboxed environment.

---

## **2️⃣ Replacing Google Services**
### **2.1 Search Engines**
| Google Service | Alternative |
|--------------|-------------|
| Google Search | [Brave Search](https://search.brave.com), [SearXNG](https://searxng.org), [Startpage](https://www.startpage.com), [Mojeek](https://www.mojeek.com) |

🔹 **Best self-hosted option:** [SearXNG](https://github.com/searxng/searxng)

---

### **2.2 Web Browsers**
| Google Chrome | Alternative |
|--------------|-------------|
| Chrome | [LibreWolf](https://librewolf.net), [Mull (Android)](https://f-droid.org/en/packages/us.spotco.fennec_dos/), [Brave](https://brave.com), [Ungoogled Chromium](https://ungoogled-software.github.io/) |

**Essential hardening:**
- **Firefox**: Use [Arkenfox user.js](https://github.com/arkenfox/user.js) to configure settings for privacy.
- **Extensions**: `uBlock Origin`, `LocalCDN`, `Cookie AutoDelete`, `Privacy Badger`.

---

### **2.3 Email**
| Gmail | Alternative |
|-------|------------|
| Gmail | [Proton Mail](https://proton.me), [Tutanota](https://tutanota.com), [Mailbox.org](https://mailbox.org) |

🔹 **Self-hosted email:** [Mail-in-a-Box](https://mailinabox.email), [Modoboa](https://modoboa.org/)

---

### **2.4 Cloud Storage**
| Google Drive | Alternative |
|-------------|------------|
| Google Drive | [Proton Drive](https://proton.me/drive), [Nextcloud](https://nextcloud.com), [MEGA](https://mega.io) |

🔹 **Best self-hosted option:** [Nextcloud](https://nextcloud.com)

---

### **2.5 Maps & Navigation**
| Google Maps | Alternative |
|------------|-------------|
| Google Maps | [Organic Maps](https://organicmaps.app), [OsmAnd](https://osmand.net), [OpenStreetMap](https://www.openstreetmap.org) |

🔹 **Best self-hosted option:** [OwnTracks](https://owntracks.org/)

---

### **2.6 Messaging**
| Google Messages, Hangouts, Chat | Alternative |
|--------------------------------|-------------|
| Google Messages, Hangouts | [Signal](https://signal.org), [Session](https://getsession.org), [Matrix (Element)](https://element.io) |

🔹 **Self-hosted option:** [Matrix Synapse](https://matrix.org/), [XMPP](https://xmpp.org/)

---

### **2.7 Video Hosting**
| YouTube | Alternative |
|--------|-------------|
| YouTube | [PeerTube](https://joinpeertube.org), [Odysee](https://odysee.com) |

🔹 **Best option for watching YouTube without tracking:** [Invidious](https://github.com/iv-org/invidious)

---

### **2.8 Android OS**
| Google Android | Alternative |
|---------------|-------------|
| Android | [GrapheneOS](https://grapheneos.org), [CalyxOS](https://calyxos.org), [DivestOS](https://divestos.org) |

🔹 **Best option:** [GrapheneOS](https://grapheneos.org) for maximum security, [CalyxOS](https://calyxos.org) for a balanced approach.

---

### **2.9 App Store**
| Google Play Store | Alternative |
|------------------|-------------|
| Play Store | [F-Droid](https://f-droid.org), [Aurora Store](https://auroraoss.com) |

---

### **2.10 Office Suite**
| Google Docs, Sheets, Slides | Alternative |
|----------------------------|-------------|
| Google Docs | [CryptPad](https://cryptpad.fr), [LibreOffice](https://www.libreoffice.org), [ONLYOFFICE](https://www.onlyoffice.com) |

🔹 **Self-hosted option:** [ONLYOFFICE](https://www.onlyoffice.com), [Nextcloud Office](https://nextcloud.com/office/)

---

### **2.11 Calendar & Contacts**
| Google Calendar | Alternative |
|----------------|-------------|
| Google Calendar | [Proton Calendar](https://proton.me/calendar), [Nextcloud Calendar](https://nextcloud.com) |

🔹 **Self-hosted option:** [Radicale](https://radicale.org/)

---

## **3️⃣ Hardening Your Digital Life**
### **3.1 Firewall & Network Privacy**
- Use **Pi-hole** or **AdGuard Home** to block Google tracking at the network level.
- VPN options: [Mullvad](https://mullvad.net), [IVPN](https://www.ivpn.net).
- Tor for anonymity: [Tor Project](https://www.torproject.org).

---

### **3.2 Hardening Android**
- Install **NetGuard** (firewall) and **TrackerControl** (block app trackers).
- Disable **Google Play Services** and use [MicroG](https://github.com/microg) for app compatibility.
- Use **Shelter** to sandbox apps that require Google dependencies.

---

### **3.3 Self-Hosting for Maximum Privacy**
- **Cloud & File Sync**: Nextcloud, Seafile.
- **Password Manager**: Vaultwarden (self-hosted Bitwarden).
- **RSS Feeds**: FreshRSS instead of Google News.
- **DNS Encryption**: Use DNSCrypt or NextDNS instead of Google Public DNS.

---

## **4️⃣ Advanced Techniques**
- Use **virtual machines (Qubes OS, Whonix)** for isolating online activities.
- Configure **browser fingerprinting mitigation** with Brave, Arkenfox Firefox, or Mullvad Browser.
- **Host your own VPN** using WireGuard or OpenVPN instead of relying on third-party providers.

---

## **5️⃣ Final Steps: Verify Google is Gone**
Run **Google trackers checkers**:
- [Blacklight](https://themarkup.org/blacklight) (scan for trackers on websites)
- [Exodus Privacy](https://exodus-privacy.eu.org) (scan Android apps for trackers)

Forensic tools like **Wireshark** or **Mitmproxy** can inspect traffic for unexpected Google connections.

---

## **Conclusion**
De-Googling your life **isn't about eliminating convenience but regaining control over your data.** This guide provides a solid foundation to **replace every Google service with privacy-respecting alternatives** while maintaining usability.

