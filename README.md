# SFR EnRoute Traffic Hub V.1.0.2

A real-time traffic camera wall and map designed for incident response. This tool is a **Progressive Web App (PWA)**, allowing it to be installed on mobile devices for a native, fullscreen experience.

---

# url: https://gksfr.github.io/EnRoute/

##  Installation Instructions

### iPhone (iOS)
1. Launch **Safari** and navigate to https://gksfr.github.io/EnRoute/
2. Tap the **Share** button (square icon with an upward arrow) at the bottom center.
3. Scroll down and tap **Add to Home Screen**.
4. Name the app "Patrol Hub" and tap **Add**.
5. Launch the app from your home screen for a fullscreen view without browser bars.

### Android
1. Launch **Chrome** and navigate to https://gksfr.github.io/EnRoute/
2. Tap the **three vertical dots** (menu) in the top-right corner.
3. Tap **Install app** or **Add to Home Screen**.
4. Confirm by tapping **Add**.
5. The app will now be available in your app drawer and home screen.

### Other mobile browsers may work. Instructions are simular, but may vary.


### Windows (Desktop Icon / App Window)
This option creates a desktop icon that opens EnRoute in its own app-style window (no tabs/address bar) and starts **maximized** while keeping the Windows taskbar visible.

1. **Right-click** on your desktop → **New** → **Shortcut**
2. For the location, paste:
    #**"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --app="https://gksfr.github.io/EnRoute/" --user-data-dir="%LOCALAPPDATA%\EnRouteApp" --start-maximized**
3. Click **Next**
4. Name it: **SFR EnRoute** (or whatever you prefer)
5. Click **Finish**
   
---

##  Features
* **Live Camera Grid**: HLS streams for the MMBT and I-664 corridor.
* **Integrated Street Map**: Simple, high-contrast street map with verified GPS locations.
* **Auto-Reset Map**: Every time the **MAP** tab is clicked, it clears active videos and recenters the view.
* **One-Touch Locate**: Tap the **LOCATE** button on any camera card to instantly jump to that pin on the map.
* **Sync Button**: Tap the red **SYNC** button to force a hard refresh of all video feeds if they freeze.

---

##  Troubleshooting
* **Black Boxes on Map**: Ensure you close the current map video before clicking another pin (though the code is designed to auto-kill previous streams).
* **Buffering**: If video freezes during tower handoffs while driving, tap the **SYNC** button in the bottom nav.
* **Map Not Loading**: Ensure you have an active data connection; the map tiles require internet access to render.

---
*Created for SFR Operations.*
