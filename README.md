# SFR EnRoute Traffic Hub & EV/HEV Vehicle Rescue
#V.1.2.4

A real-time traffic camera wall, map, and EV rescue guide library designed for incident response. This tool is a **Progressive Web App (PWA)**, allowing it to be installed on mobile devices or desktop for a native, fullscreen viewing.

---

# url: https://gksfr.github.io/EnRoute/

##  Installation Instructions

### iPhone (iOS)
1. Launch **Safari** and navigate to https://gksfr.github.io/EnRoute/
2. Tap the **Share** button (square icon with an upward arrow) at the bottom center.
3. Scroll down and tap **Add to Home Screen**.
4. Name the app "EnRoute" and tap **Add**.
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
2. Depending on file path, for the location, paste:
    ### "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --app="https://gksfr.github.io/EnRoute/" --user-data-dir="%LOCALAPPDATA%\EnRouteApp" --start-maximized
   ## or
   ### "C:\Program Files\Google\Chrome\Application\chrome.exe" --app="https://gksfr.github.io/EnRoute/" --user-data-dir="%LOCALAPPDATA%\EnRouteApp" --start-maximized
4. Click **Next**
5. Name it: **SFR EnRoute** (or whatever you prefer)
6. Click **Finish**

   #### *File path may differ
---

##  Features
* **Home screen**: Opens on the EnRoute logo. Choose **Cameras** or **EV Rescue**. **HOME** returns to this screen.
* **Live Camera Grid**: HLS streams for the MMBT and I-664 corridor.
* **Integrated Street Map**: Simple, high-contrast street map with verified GPS locations.
* **Auto-Reset Map**: Every time the **MAP** tab is clicked, it clears active videos and recenters the view.
* **One-Touch Locate**: Tap the **LOCATE** button on any camera card to instantly jump to that pin on the map.
* **EV Rescue**: Sort by make, then sedan / SUV / truck (only types that exist for that make), then model and year. Opens the matching emergency response guide or rescue sheet.
* **PDF viewer**: Zoom with **−** / **+** / **Fit**. On PC, **Ctrl + mouse wheel** or **−** / **+** keys. Phone screens render at device resolution so text stays readable.
* **Sync Button**: In Cameras, reloads the current video wall. In EV Rescue, reloads the guide list.

---

##  Troubleshooting
* **Black Boxes on Map**: Ensure you close the current map video before clicking another pin (though the code is designed to auto-kill previous streams).
* **Buffering**: If video freezes during tower handoffs while driving, tap the **SYNC** button in the bottom nav.
* **Map Not Loading**: Ensure you have an active data connection; the map tiles require internet access to render.
* **EV Rescue not loading**: Needs an active data connection. Tap **SYNC** on the EV screen, or go **HOME** and open EV Rescue again.
* **Installed app looks old after an update**: Fully close EnRoute (swipe it away on Android / iPhone) and reopen it. If it still looks stale, remove it from the home screen and Add to Home Screen again.

---
*Created for SFR Operations.*
