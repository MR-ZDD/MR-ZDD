# ▓▒░ Master ZeroDayDev Engine v2.0 ░▒▓

This is an advanced terminal automation framework featuring a dynamic random logo generator and a secure interactive control console.

---

## 🚀 How to Install

Run this **single command** directly in your Kali Linux terminal. The tool will be installed seamlessly into your system path:

### Option 1: Quick 1-Command Installatio

```bash
curl -sSL "https://githubusercontent.com" -o /tmp/zerodaydev && sudo mv /tmp/zerodaydev /usr/local/bin/zerodaydev && sudo chmod +x /usr/local/bin/zerodaydev && echo -e "\n\e[1;32m[+] ZeroDayDev Installed Successfully! Just type 'zerodaydev' anywhere.\e[0m"
```

### Option 2: Manual Installation via Git Clone
```bash
git clone https://github.com/mrbrajeshdabi/zerodaydev
cd zerodaydev
chmod +x zerodaydev
./zerodaydev
```
---

## 💻 How to Use

### 1. Launching the Tool
Once installed, open a fresh terminal, type the following command anywhere, and press Enter:
```bash
zerodaydev
```

### 2. Generating the Payload
* As soon as the tool starts, it will prompt you for your **MAGIC IP** (such as your Ngrok domain or local IP) and an output **Payload Name**.
* It will automatically generate a fully obfuscated `.vbs` execution stub and save it in your current working directory.
* It will then ask whether you want to spin up the **Tactical Control Console (Listener)** immediately (`y/n`).

### 3. Tactical Control Console Commands
Once a connection handshake is established with the target machine, you can run the following interactive instructions inside the custom prompt (`zerodaydev-ops$`):

* `help` ➔ Displays the operational settings menu and list of commands.
* `sysinfo` ➔ Profiles target metrics including the current username, hostname, and active network interfaces.
* `screenshot` ➔ Triggers a quiet desktop screen state capture on the target machine.
* `camera` ➔ Initiates native hardware identification and triggers automated camera capture routines.
* `mic` ➔ Maps the destination audio channels to record from the primary microphone hardware.
* `notepad` ➔ Spawns a clean instance of the standard Notepad text editor on the destination screen.
* `type <message>` ➔ Launches a text instance and automatically types out your specified message character-by-character.
* `chat <message>` ➔ Dispatches a single-direction operational alert dialog box onto the target display.
* `talk` ➔ Instantiates a two-way graphic prompt box to exchange text messages back and forth with the console operator.
* `play <URL>` ➔ Launches and plays web presentations or multimedia streaming sources directly on the destination machine.
* `kill` ➔ Safely terminates the network session stream and tears down background listener configurations.
