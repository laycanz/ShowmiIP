A simple browser extension to quickly check your public IP address without needing to visit ad-cluttered websites. Just click the icon!
Created by **laycanazo** for anyone needing a fast, clean way to see their public IP. 

This extension is built using Manifest V3 and standard WebExtension APIs.
* **Officially Supported / Tested On:**
    * Google Chrome
    * Brave Browser
* **Should Also Work On (Chromium-based):**
    * Microsoft Edge (latest versions)
    * Opera
    * Vivaldi
    * Other browsers based on Chromium that support Manifest V3 extensions.
* **Not Tested / May Require Changes:**
    * Mozilla Firefox (While based on WebExtensions, specific APIs or Manifest V3 implementation might differ. Not packaged or tested for the Firefox Add-ons store.)
    * Safari (Requires conversion via Xcode and uses a different distribution model.)

Preview
![image](https://github.com/user-attachments/assets/3c70ac8e-3055-4b4e-857c-1f0a8c0ff08a)


Why?
Tired of opening a new tab, searching for "what's my IP", and landing on websites filled with ads and trackers just to see your public IP? This extension solves that. It gives you your IP instantly in a clean popup with zero distractions.

Features
* **One-Click Access:** Get your public IP (IPv4 or IPv6) instantly.
* **Clean Interface:** No ads, no tracking, no unnecessary clutter.
* **Matrix Theme:** Features a cool, retro hacker terminal look (black background, green text).
* **Lightweight & Fast:** Does one job quickly and efficiently.
* **Privacy Focused:** Does not collect or store any user data.

## Installation
1. From Chrome Web Store (Recommended)**
Install the extension directly from the Chrome Web Store:
    [**Link to be added here after publication**]
2. Manual Installation 
* Download or clone this repository.
* Open Chrome/Brave and navigate to `chrome://extensions/` or `brave://extensions/`.
* Enable "Developer mode" (usually a toggle in the top right).
* Click "Load unpacked".
* Select the directory where you downloaded/cloned the extension files.
Usage
1.  Click the "Show My IP" icon in your browser's toolbar (it might be hidden under the puzzle piece icon initially).
2.  A small popup will appear displaying your current public IP address.
Technology Used
* HTML
* CSS
* JavaScript (Vanilla)
* Fetches IP address from the reliable [api.ipify.org](https://www.ipify.org/) service.
Privacy
This extension respects your privacy.
* It only contacts `api.ipify.org` when you click the icon to fetch your IP for display.
* It does **not** collect, store, or share any user data.
* You can view the full [Privacy Policy](link-to-your-hosted-privacy.html) here. *(<- Add the link to your privacy.html file here)*
Author
* Developed by @laycanazo
