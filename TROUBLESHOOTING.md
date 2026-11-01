# OPT SideSpace — Troubleshooting & FAQ

### 1. Does OPT SideSpace require Administrator privileges?
No. OPT SideSpace runs purely in user-mode using standard Windows Shell APIs (`SHAppBarMessage`).

### 2. What happens when I close OPT SideSpace?
When you click the `✕` close button or choose `Exit` from the system tray, SideSpace unhooks immediately, undocks any open app, and restores 100% of your monitor desktop area instantly.

### 3. Can I dock any application?
Yes! You can dock:
- Any running window via the `Select App (⊞)` button.
- Any installed Windows application from your Start Menu.
- Pre-configured shortcuts for Microsoft Edge, Google Chrome, ChatGPT, or File Explorer.

### 4. Windows SmartScreen warning on first launch?
Since OPT SideSpace is a brand new release that was just compiled, Windows SmartScreen may show an informational message saying "Windows protected your PC".
- Click **"More info"**.
- Click **"Run anyway"**.
You can also verify the SHA-256 hash in [CHECKSUMS.txt](CHECKSUMS.txt) or scan it with [VirusTotal](https://www.virustotal.com) (0/70 clean).

### 5. Multi-monitor setups
OPT SideSpace attaches to the right edge of your **Primary Monitor**. Secondary monitors remain standard desktops.
