# Gothic Timepiece — Netlify-ready

A gothic-styled clock and date widget site.  
Fully static — ready to deploy instantly on Netlify.

## 🚀 Deploy to Netlify

### Option 1 — Through the Netlify Dashboard
1. Go to [https://app.netlify.com/start](https://app.netlify.com/start)
2. Connect your GitHub account.
3. Select your repository.
4. Build settings:
   - **Build command:** *(leave blank)*
   - **Publish directory:** `.`  
5. Click **Deploy Site** — done!

### Option 2 — With the Netlify CLI
```bash
npm install -g netlify-cli
netlify login
netlify init
# choose "Link this directory to an existing site" or "Create & configure a new site"
netlify deploy --prod
