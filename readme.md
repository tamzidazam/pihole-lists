# Pi-hole Lists

A curated collection of text-based blacklists and whitelists to enhance your Pi-hole network-wide ad blocking and privacy setup. 

## ⚠️ Disclaimer & Credits

**Please note:** The URLs and domains contained within these whitelist and blacklist files were collected from various public sources across the web. I am not the original owner, creator, or maintainer of these domains or the upstream lists. 

This repository simply serves as a centralized compilation for easier deployment. All credit goes to the original list maintainers and the open-source community (such as StevenBlack, anudeepND, blocklistproject, and others) who continuously work to keep the web clean and functional.

## 📁 Repository Structure

This repository is organized into two main categories:

* **`blacklist/`**: Contains lists aimed at blocking advertisements, tracking domains, coin miners, and specific services. Examples include general ad servers, Facebook tracking, and strict host files.
* **`whitelist/`**: Contains domains that are frequently caught by aggressive ad-blockers but are necessary for normal web browsing, app functionality, or referral links.

## 🚀 How to Use

To add any of these lists to your Pi-hole configuration, you will need the **Raw URL** of the file.

1. Browse to the list you want to use (e.g., `blacklist/simple_ad.txt`).
2. Click the **"Raw"** button at the top right of the file view on GitHub.
3. Copy the URL from your browser's address bar (it should start with `https://raw.githubusercontent.com/...`).
4. Log into your Pi-hole Web Interface.
5. Go to **Adlists** (for blacklists) or **Domains** (for whitelists).
6. Paste the copied Raw URL and click **Add**.
7. Once added, navigate to **Tools > Update Gravity** and click **Update** to apply the changes.

## 🤝 Contributing

Contributions are completely open and welcome from everyone! The web is constantly changing, and keeping these lists accurate requires community effort. 

Whether you want to add a new set of tracking domains, remove dead links, or suggest domains for the whitelist to fix a broken website, your help is appreciated.

**How to contribute:**
1. Fork this repository.
2. Create a new branch: `git checkout -b feature/update-lists`
3. Make your changes (add new domains or remove obsolete ones).
4. Commit your changes: `git commit -m 'Added new tracking domains' or 'Fixed broken whitelist'`
5. Push to the branch: `git push origin feature/update-lists`
6. Submit a Pull Request.

Please ensure any domains you add are tested to avoid breaking legitimate web services.

---
*Maintained by Tamzid Azam Priyo*
