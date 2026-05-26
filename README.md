<h1 align="center">🔐 passgen</h1>
<p align="center">
  <b>Secure password & passphrase generator for the terminal. Pure Python, zero deps.</b>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/python-3.6+-blue.svg">
  <img src="https://img.shields.io/badge/dependencies-zero-brightgreen.svg">
  <img src="https://img.shields.io/badge/license-MIT-green.svg">
</p>

## 🚀 Install

```bash
curl -L https://raw.githubusercontent.com/neuralmint/passgen/main/passgen -o /usr/local/bin/passgen
chmod +x /usr/local/bin/passgen
```

## 📋 Usage

```bash
passgen                  # 20-char random password
passgen password         # 20-char with symbols
passgen phrase           # 4-word passphrase (easier to remember)
passgen pin              # 6-digit PIN
passgen -l 32            # Custom length
passgen -c 5             # Generate 5 passwords
passgen --no-symbols     # Alphanumeric only
```

## 💡 Features

- 🎲 Cryptographically secure random generation
- 🔤 Configurable character sets
- 📝 Diceware-style passphrases
- 🎯 No network calls — works offline

## 💝 Donate

**BTC:** `bc1q6ud0w3036ye2vfzkftwywarqswqu3jehs4nqe7`
