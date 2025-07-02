# 🔧 Wi-Fi Deauthentication Tool

A Bash-based Wi-Fi deauthentication tool that allows you to interactively:
- Scan Wi-Fi networks
- Monitor target networks
- Deauthenticate a specific client or all clients from a network

> ⚠️ **For educational and authorized testing purposes only! Do not use on networks you don’t own or have explicit permission to test.**

---

## 📜 Features

- Scan nearby Wi-Fi networks
- Target specific Wi-Fi access points by BSSID and channel
- Deauthenticate individual clients or all connected devices
- Change interface name on-the-fly
- Check adapter status
- Simple, interactive terminal menu
- Colorful UI powered by `lolcat`

---

## 📦 Requirements

- `aircrack-ng` suite (for `airodump-ng`, `aireplay-ng`)
- `iwconfig`
- `lolcat` (for visual effects)
- A Wi-Fi adapter that supports **monitor mode** and **packet injection**
- Root privileges (`sudo`)

---

## 🚀 How to Use

1. **Clone the repository**:

```bash
git clone https://github.com/Keshav8485/Wifi-Deauthentication.git
cd Wifi-Deauthentication
```

2. **Make the script executable**:

```bash
chmod +x wifideauth.sh
```

3. **Run the tool**:

```bash
sudo ./wifideauth.sh
```

4. **Choose from the interactive menu**:

```text
1. Scan for Wi-Fi networks
2. Select a Wi-Fi network for further actions
3. Deauthenticate a client from a Wi-Fi network
4. Deauthenticate all clients from a Wi-Fi network
5. Check Wi-Fi Adapter Status
6. Change Wi-Fi Adapter Interface Name
7. Exit
```

---

## 📸 Demo

![screenshot](demo.png) <!-- Optional: add a screenshot if available -->

---

## 🛡️ Disclaimer

This tool is intended for **ethical hacking, penetration testing, and educational** use only.  
Keshav Kacholiya is **not responsible** for any misuse of this tool.

---

## 👨‍💻 Author

**Keshav Kacholiya**  
🔗 [GitHub](https://github.com/Keshav8485)

---

## 📄 License

MIT License – feel free to modify and use with attribution.
ational purposes
- Interacting with **networks you own** or have **permission to test**

---

## ✨ Features

- 🛰️ **Scan for Wi-Fi networks**: Discover and list nearby Wi-Fi networks and view their details.
- 🛠️ **Select Wi-Fi network**: Choose a specific Wi-Fi network for further actions.
- 🚫 **Deauthenticate client**: Disconnect a specific client from the selected Wi-Fi network.
- 🌐 **Deauthenticate all clients**: Disconnect all connected clients from the selected Wi-Fi network.
- 📶 **Check Wi-Fi adapter status**: Get the current status of your Wi-Fi adapter.
- 🔧 **Change adapter interface name**: Modify the interface name of your Wi-Fi adapter for ease of use.

---

## 📋 Prerequisites

Before running the tool, ensure you meet the following requirements:

- **Linux environment**
- Installed tools: `airodump-ng` and `aireplay-ng`
- Proper permissions to execute the script

### 🛠️ Install `aircrack-ng` (contains both `airodump-ng` and `aireplay-ng`):

- 💣For **Debian-based systems**:
  ```bash
  sudo apt-get install aircrack-ng
  ```
  ### 🚀 Usage Instructions
  ```bash
  git clone https://github.com/vishuchauhan27/Wifi-Deauthentication-Tool.git
  ```
- ♨️Ensure executable permissions for the script
  ```bash
  chmod +x wifideauth.sh
  ```
- 🔥Run the script
  ```bash
  sudo ./wifideauth.sh
  ```

### ⚠️ Important:
- Only use the tool on networks you own or have explicit permission to test. Unauthorized use is both illegal and unethical.
- Any misuse of this tool is solely the responsibility of the user. Respect privacy and adhere to local laws.

 ### ⚠️ Important Notice:
- This tool comes with no guarantees or warranties. The author will not be responsible for any consequences resulting from the misuse of this tool. Use it responsibly and at your own risk.
  ```bash
  This is the full code for the `README.md` file. You can copy this directly into your GitHub repository, and it will render with the emojis and professional 
  formatting !
  ```
