# passgen

Secure password & passphrase generator for the terminal. No dependencies.

## Install

```bash
curl -L https://raw.githubusercontent.com/neuralmint/passgen/main/passgen -o /usr/local/bin/passgen
chmod +x /usr/local/bin/passgen
```

## Usage

```bash
passgen                          # 20-char random password
passgen -l 32                    # Custom length (32 chars)
passgen -s                       # Include symbols
passgen -n 5                     # Generate 5 at once
passgen phrase                   # Memorable 4-word passphrase
passgen phrase -w 6              # 6-word passphrase
passgen pin                      # 6-digit PIN
passgen pin -l 8                 # 8-digit PIN
```

### Examples

```bash
$ passgen
aK3xR9mZpL7qW2nY5vB8
(132.8 bits of entropy)

$ passgen phrase
Dolphin-Rocket-Jungle-Coffee

$ passgen -s -l 30
xR#9mK2pL7qW!nY5vB8aD3fG6hJ1kT4
```

## Entropy Reference

| Type | Example | Bits |
|------|---------|------|
| 20-char password | `aK3xR9mZpL7qW2nY5vB8` | ~132 |
| 4-word phrase | `Dolphin-Rocket-Jungle-Coffee` | ~52 |
| 6-digit PIN | `483921` | ~20 |

## Requirements

- Python 3.6+
- No external dependencies
- Cryptographically secure (`secrets` module)

## License

MIT

---

**Donations:** `0x643E158D7615d19F1f0105B0cc5a1D976B456e4A` (ETH)
