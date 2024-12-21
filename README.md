I'll help you create a more professional and visually appealing README.md with your Telegram contact. Here's an enhanced version:

# 🤖 Nodepay.ai Auto-Ping Bot

Advanced automation tool for Nodepay.ai utilizing multiple proxy connections for optimal performance.

[![Telegram](https://img.shields.io/badge/Telegram-@zsan0x-blue?style=flat&logo=telegram)](https://t.me/zsan0x)

## ✨ Key Features

- Multiple proxy support for distributed operations
- Account management system
- Automatic ping functionality
- Token-based authentication
- Proxy rotation capabilities

## 📝 Important Updates

- Individual accounts limited to 10 proxy connections
- Multi-account farming support implemented
- Token management via `np_tokens.txt` (one account per line)
- Register at [Nodepay.ai Platform](https://app.nodepay.ai/)

## 🚀 Getting Started

### Token Acquisition

1. Navigate to [Nodepay.ai](https://app.nodepay.ai/) and log in
2. Access Developer Console (F12 or Ctrl + Shift + I)
3. Execute: `localStorage.getItem('np_token');`
4. Copy the returned token to `np_token.txt`

### Proxy Configuration

Add your proxies to `proxies.txt` using the format:
```
http://username:pass@ip:port
```

## 💻 Installation

```bash
# Clone repository
git clone https://github.com/Zlkcyber/nodepay.git

# Navigate to project
cd nodepay

# Install requirements
pip install -r requirements.txt
```

## 🔧 Usage

```bash
python3 main.py
```

### Sample Output
```
[+] Ping successful for IP: 64.137.42.112
```

## 📞 Contact & Support

For assistance or inquiries:
- Telegram: [@zsan0x](https://t.me/zsan0x)

## ⚠️ Disclaimer

This tool is for educational purposes only. Users are responsible for compliance with Nodepay.ai's terms of service.

---
*Made with ❤️ by the community*
