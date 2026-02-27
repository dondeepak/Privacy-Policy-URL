# Privacy Policy – WifiSend

**Last updated:** February 27, 2025  
**Developer:** Deepak Kumar  
**App:** WifiSend (Android & Windows)

---

## 1. Introduction

WifiSend ("the App") is a local-network file transfer and screen-mirroring application. This Privacy Policy explains what data the App accesses and how it is used.

---

## 2. Data We Do NOT Collect

We do **not** collect, store, or transmit to any server operated by us:

- Personal identification information (name, email, phone number)
- Precise or approximate GPS location
- Device identifiers (IMEI, Advertising ID is handled by AdMob — see §5)
- Contacts, call logs, or messages
- Browsing history or usage analytics gathered by us

---

## 3. Permissions Used and Why

### Android

| Permission | Why |
|---|---|
| `INTERNET` | To serve files over the local WiFi HTTP server and optionally relay via internet |
| `ACCESS_WIFI_STATE` / `CHANGE_WIFI_MULTICAST_STATE` | To discover other WifiSend devices via mDNS on local WiFi |
| `READ_MEDIA_*` / `READ_EXTERNAL_STORAGE` | To let you pick files to send (files are not uploaded anywhere) |
| `CAMERA` | To scan QR codes for device discovery |
| `FOREGROUND_SERVICE` | To keep file transfers running while the app is in the background |
| `POST_NOTIFICATIONS` | To show transfer progress notifications (Android 13+) |

### Windows

The Windows desktop app opens a local HTTP server port to receive files over WiFi. No outbound connections are made except to the sender device you explicitly connect to.

---

## 4. File Transfers

Files are transferred **directly between devices on your local WiFi network** using an encrypted-capable HTTP connection. Files are never routed through our servers.  
When you use the optional **"Share via Internet"** / Localrtunnel relay feature, your file transfer traffic is temporarily routed via a third-party relay endpoint. We do not log or store this traffic.

---

## 5. Advertising (AdMob) – Android Only

The Android app uses **Google AdMob** to display advertisements. Google may collect device information and use cookies/advertising IDs to serve personalised ads, in accordance with [Google's Privacy Policy](https://policies.google.com/privacy).

You can opt out of personalised ads via your device's **Settings → Google → Ads → Opt out of Ads Personalisation**.

---

## 6. Screen Mirroring

The screen-mirroring feature captures your device screen and streams it over your local network as an MJPEG video feed. The stream is accessible only to devices that have the stream URL (which you choose to share). We do not store or process the stream.

---

## 7. Data Security

All file transfer traffic stays on your local network. No user data is uploaded to cloud servers operated by TreeSoft.

---

## 8. Children's Privacy

The App is not directed at children under 13. We do not knowingly collect personal data from children.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. The updated version will be indicated by the "Last updated" date above. Continued use of the App after any changes constitute acceptance.

---

## 10. Contact

For questions about this Privacy Policy, contact:  
**Email:** dondeepakkumar20@gmail.com.com  

