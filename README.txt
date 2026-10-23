MANGO PIZZA HUT — MOBILE WEB POS

FEATURES
- Responsive layout for mobile and desktop
- Product search and category filters
- Add products with name/category/price
- Cart quantity controls, order type and payment method
- Checkout saves order, receipt preview and print option
- Daily sales/order count and recent orders
- JSON backup export/import
- Browser local storage; no server/account needed
- Service worker for offline use after first load when served from localhost/HTTPS

EASIEST TEST ON YOUR WINDOWS LAPTOP
1. Extract this ZIP into a folder.
2. Open the folder and double-click index.html. The app will work for local testing and data is saved in that browser profile.
3. For installable home-screen/PWA and reliable offline caching, serve the folder from localhost or HTTPS (not file://). If Python is installed, open Command Prompt in this folder and run:
   python -m http.server 8000
   Then open http://localhost:8000 in Chrome.

OPEN ON ANDROID PHONE
For phone use, put these files on a static HTTPS host such as GitHub Pages, then open the HTTPS site in Chrome and use menu > Add to Home screen / Install app. You can also test on the same Wi-Fi using a local server and laptop IP, but HTTPS hosting is easier for PWA installation.

DATA IMPORTANT
- Products and orders are saved only in this browser's localStorage on this device/browser profile.
- Data does NOT automatically sync with the Windows Python/SQLite POS or other devices.
- Clearing browser data, uninstalling/resetting the browser, or changing browser profiles may remove local data. Use Export backup regularly.
- To move data to another browser/device, export JSON on the old device and import it on the new device.
- For multi-device shared data, a backend/database is required; this version intentionally does not include one.
