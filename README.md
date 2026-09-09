# FINBUCKS Finance

FINBUCKS is a local-first personal finance workspace for transactions, accounting sheets, receipt imports, automation, and CSV exports.

## Windows desktop application

Install Node.js and Rust, then run:

```powershell
npm install
npm run tauri build
```

The generated Windows installers are written to `src-tauri\target\release\bundle\`.

For development:

```powershell
npm run tauri dev
```

The app stores its working data in the local WebView browser storage. No finance data is sent to a server.
