# Electronics Lab — iPhone PWA

1. Open https://dash.cloudflare.com/ and create a free Cloudflare account.
2. Open Workers & Pages > Create application > Pages > Upload assets / Drag and drop.
3. Upload the ZIP archive as-is, or the contents of the electronics-lab folder. Ensure index.html is at the site root.
4. Open your new https://...pages.dev address in iPhone Safari.
5. Wait for the first load to finish. Use Share > Add to Home Screen > Open as Web App.
6. Launch from Home Screen. The service worker caches all app files for offline use. Test once in Airplane Mode.

Data is saved in the app's localStorage on the iPhone. Use the Sync tab to export a JSON backup and import ChatGPT-edited progress. It does not automatically synchronize across devices or with ChatGPT. Do not clear website data without backing up.

Cloudflare hosts the public app code, not your progress data. Offline mode works after a successful initial online load and cache installation; iOS may evict stored website data.
