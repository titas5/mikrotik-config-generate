# WireGuard Config Generator for MikroTik

Quickly deploy a WireGuard VPN on a MikroTik RouterOS device. Fill in a few fields and get a ready-to-paste router config plus a config file and QR code for every client.

**Live site:** https://titas5.github.io/mikrotik-config-generate/

## Features

- RouterOS script: WireGuard interface, IP address, firewall rules, DNS and peers
- Client configs with unique private and pre-shared keys per client
- QR codes for the WireGuard mobile apps
- One-click download of all configs (`clients.zip`) or QR codes (PNG)
- Editable client names and input validation

## Usage

1. Open the site and set the server address, port, network and number of clients.
2. Click **Generate**.
3. Paste the **Server config** into the MikroTik terminal.
4. Import each client config or scan its QR code in the WireGuard app.

## Privacy

Everything runs in your browser. Keys are generated locally and never sent anywhere.

## Credits

Based on [dbca-wa/wg-webcfg](https://github.com/dbca-wa/wg-webcfg).
