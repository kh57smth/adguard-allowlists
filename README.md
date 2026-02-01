# AdGuard Home – Master DNS Allowlist  
Maintained by **kh57smth**

This repository contains a consolidated DNS allowlist designed for AdGuard Home.  
It includes domain exceptions for major streaming services, smart home platforms, gaming networks, cloud providers, and essential Canadian services.

The goal is simple:  
**Fix false positives, improve reliability, and ensure all devices and apps function correctly while still using aggressive DNS filtering.**

---

## 📌 How to Use This Allowlist

1. Open your AdGuard Home dashboard  
2. Go to **Filters → DNS Allowlists**  
3. Click **Add allowlist**  
4. Choose **URL**  
5. Paste this link:
https://raw.githubusercontent.com/kh57smth/adguard-allowlists/main/allowlist.txt (raw.githubusercontent.com in Bing)
6. Save  
7. Click **Check for updates** to verify the file loads correctly

AdGuard will now automatically fetch updates from this repository.

---

## 📁 Included Categories

This allowlist includes safe, required domains for:

- Amazon  
- Prime Video  
- Netflix  
- Disney+  
- YouTube  
- Apple  
- SmartThings  
- Kuna  
- Ring  
- Samsung TV  
- LG TV  
- Roku  
- Xbox  
- PlayStation  
- Steam  
- EA  
- Canadian banking  
- CDNs  
- Cloud providers  
- Android  
- iOS  

Each category is clearly separated inside `allowlist.txt` for easy reading and future editing.

---

## 🛠️ File Structure

---

## 🔄 Updating the Allowlist

To update the allowlist:

1. Edit `allowlist.txt`  
2. Commit your changes  
3. AdGuard will automatically pull the latest version on the next scheduled update

---

## 🧩 Compatibility

This allowlist is compatible with:

- AdGuard Home  
- Pi-hole (with regex support)  
- DNS-based firewalls  
- Router-level DNS filtering (OpenWrt, pfSense, OPNsense)

---

## 📬 Questions or Improvements?

If you want to expand the list, add new categories, or split the file into multiple modular allowlists, feel free to update the repo or request changes.

---

**Enjoy a cleaner, faster, and more reliable network!**
