# T-1000: Body of Steel - Deployment to Vercel

## Files Ready to Upload

I've created all the files you need. Here's what to do:

---

## STEP 1: Create GitHub Repository

1. Go to **github.com/new**
2. Name it: `t-1000-fitness`
3. Make it **Public**
4. Click **Create Repository**

---

## STEP 2: Upload Files to GitHub

In your new repository:

### A) Create Folder Structure

GitHub will let you create folders as you upload files.

**Folder structure needed:**
```
t-1000-fitness/
├── package.json
├── public/
│   └── index.html
└── src/
    ├── index.jsx
    ├── index.css
    └── ironlog-pro.jsx
```

### B) Upload Files

Click **"Add file" → "Upload files"**

**Upload these files in this order:**

1. **package.json** (root)
   - From: `/mnt/user-data/outputs/package.json`

2. **public/index.html**
   - From: `/mnt/user-data/outputs/public-index.html`
   - Rename to: `index.html`

3. **src/index.jsx**
   - From: `/mnt/user-data/outputs/src-index.jsx`
   - Rename to: `index.jsx`

4. **src/index.css**
   - From: `/mnt/user-data/outputs/src-index.css`
   - Keep name: `index.css`

5. **src/ironlog-pro.jsx**
   - From: `/mnt/user-data/outputs/ironlog-pro.jsx`
   - Keep name: `ironlog-pro.jsx`

---

## STEP 3: Deploy to Vercel

1. Go to **vercel.com**
2. Sign in (you already have an account)
3. Click **"+ New Project"**
4. Under "Import Git Repository", click **GitHub**
5. Search for: `t-1000-fitness`
6. Click **Import**
7. Vercel auto-configures everything
8. Click **Deploy**

**Wait 1-2 minutes...**

✅ **DONE!** You'll get a URL like:
```
https://t-1000-fitness.vercel.app
```

---

## STEP 4: Use on Phone

1. Open the URL in browser
2. **Bookmark** it
3. (Optional) Add to home screen:
   - iOS: Tap Share → Add to Home Screen
   - Android: Tap ⋮ → Install app

---

## Data Persistence

Your workout data is stored in **browser localStorage** — it stays on your device and syncs across browsers automatically.

- 🔒 Private (not sent to any server)
- 📱 Works offline
- 🔄 Syncs if you open on multiple devices

---

## Troubleshooting

### "404 NOT_FOUND" Error
This means the files aren't structured correctly. Make sure:
- `package.json` is in root
- `public/index.html` exists
- `src/index.jsx`, `src/index.css`, `src/ironlog-pro.jsx` exist

### Vercel Deployment Fails
Check the **Vercel Dashboard → Logs**. Most common:
- Missing files
- Typo in file names
- Folder structure wrong

### Still Not Working
Try this:
1. Delete the Vercel project
2. Re-upload files to GitHub (making sure folder structure is correct)
3. Create new Vercel project from GitHub repo

---

## Quick Checklist

- [ ] Create GitHub repo `t-1000-fitness`
- [ ] Upload `package.json` to root
- [ ] Create `public/` folder, upload `index.html`
- [ ] Create `src/` folder, upload `index.jsx`, `index.css`, `ironlog-pro.jsx`
- [ ] Go to Vercel, click "New Project"
- [ ] Select GitHub repo `t-1000-fitness`
- [ ] Click "Import" and wait for deployment
- [ ] Get your URL
- [ ] Open on phone, bookmark it
- [ ] Done! 🚀

---

## Questions?

If anything doesn't work, check:
1. File names (case-sensitive on Linux)
2. Folder structure (public/ and src/)
3. GitHub repo visibility (must be Public)
4. Vercel build logs (shows errors)

Good luck! Your T-1000 app will be live in minutes. 💪⚙️🦾
