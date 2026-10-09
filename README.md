# Kyocera Printer Manager APT Repository

Signed Debian repository for Ubuntu and Zorin OS.

```bash
curl -fsSL https://m-nader90.github.io/kyocera-printer-manager-apt/kyocera-printer-manager-archive-keyring.gpg \
  | sudo tee /usr/share/keyrings/kyocera-printer-manager-archive-keyring.gpg >/dev/null
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/kyocera-printer-manager-archive-keyring.gpg] https://m-nader90.github.io/kyocera-printer-manager-apt stable main" \
  | sudo tee /etc/apt/sources.list.d/kyocera-printer-manager.list
sudo apt update
sudo apt install kyocera-printer-manager
```
