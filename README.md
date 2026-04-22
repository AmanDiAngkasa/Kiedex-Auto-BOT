# 🌅 KieDex BOT

> Automated airdrop farming with multi-account and proxy support


## 🎯 Overview

KieDex BOT is an automated tool designed to airdrop farming across multiple accounts. It provides seamless offers robust proxy support for enhanced security and reliability performance.

**🔗 Get Started:** [Register on KieDex](https://kiedex.app)

> **Important:** signup with google and connect new evm wallet

## ✨ Features

- 🔄 **Automated Account Management** - Retrieve account information automatically
- 🌐 **Flexible Proxy Support** - Run with or without proxy configuration
- 🔀 **Smart Proxy Rotation** - Automatic rotation of invalid proxies
- 🚰 **Daily Faucet** - Automated claim daily USDT faucet
- ⛽ **Daily Bonus** - Automated claim daily OIL
- 📝 **Complete Tasks** - Automated complete available tasks
- 👥 **Multi-Account Support** - Manage multiple accounts simultaneously

## 📋 Requirements

- **Python:** Version 3.9 or higher
- **pip:** Latest version recommended

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/AmanDiAngkasa/Kiedex-Auto-BOT.git
cd Kiedex-Auto-BOT
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# or for Python 3 specifically
pip3 install -r requirements.txt
```

## ⚙️ Configuration

### Account Configuration

<div align="center">
  <img src="images/example.png" alt="KieDex Tokens Example" width="500">
  <p><em>Example of fetching kiedex tokens</em></p>
</div>

Create or edit `accounts.josn` in the project directory:

```json
[
    {
        "email": "your_email_address_1",
        "access_token": "access_token",
        "refresh_token": "refresh_token"
    },
    {
        "email": "your_email_address_2",
        "access_token": "access_token",
        "refresh_token": "refresh_token"
    }
]
```

### Proxy Configuration (Optional)

Create or edit `proxy.txt` in the project directory:

```
# Simple format (HTTP protocol by default)
192.168.1.1:8080

# With protocol specification
http://192.168.1.1:8080
https://192.168.1.1:8080

# With authentication
http://username:password@192.168.1.1:8080
```

### Start the Bot

After running the setup, launch the KieDex BOT:

```bash
python bot.py
# or for Python 3 specifically
python3 bot.py
```

### Runtime Options

When starting the bot, you'll be prompted to choose:

1. **Proxy Mode Selection:**
   - Option `1`: Run with proxy
   - Option `2`: Run without proxy

2. **Auto-Rotation:** 
   - `y`: Enable automatic invalid proxy rotation
   - `n`: Disable auto-rotation

## 💖 Support the Project

If this project has been helpful to you, consider supporting its development:

### Cryptocurrency Donations

| Network | Address |
|---------|---------|
| **EVM** | `0xFfb40F047f7BA0c3fdE14f4aeDd52b2dc50ea909` |
| **SOL** | `9np5Ureem2xGxvwKp6C3QhFjPNTntHGFpwLPVtgworMy` |


<div align="center">


*Thank you for using Kiedex Validator BOT! Don't forget to ⭐ star this repository.*

</div>