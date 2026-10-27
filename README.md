# XAUUSD 1:1 Session Signals

## Environment Variables for Vercel

```
TWELVE_DATA_API_KEY=e85cf1bb766e426194fe10e46883a1f9
TELEGRAM_BOT_TOKEN=8764009621:AAEk82ApXmo06eNyGkIeGetf5fg_9Zj_LDg
TELEGRAM_CHAT_ID=-1003855500888
```

## How to Deploy correctly

1. Create a **new** GitHub repository
2. Upload **all files** from this folder (index.html must be in the root)
3. In Vercel:
   - New Project → Import the repo
   - Framework Preset: **Other**
   - Root Directory: leave as `./`
   - **Do not** set Output Directory
   - Add the 3 Environment Variables
   - Click Deploy

After deploy, test:
- https://your-app.vercel.app
- https://your-app.vercel.app/api/data
