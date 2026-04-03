# How to Push Your Portfolio to GitHub & Go Live

## STEP 1 — Download Your Files

Download all 3 files from this conversation:
- `index.html` (your portfolio)
- `README.md`
- `.gitignore`

Put them in a folder on your computer called `life-in-frames`.

---

## STEP 2 — Create a GitHub Account (skip if you have one)

1. Go to https://github.com
2. Click "Sign up"
3. Use your email: kodathalarakesh@gmail.com
4. Pick a username (e.g., `rakeshkodathala` or `lifeinframesrk`)

---

## STEP 3 — Create a New Repository

1. Go to https://github.com/new
2. Fill in:
   - **Repository name:** `life-in-frames`
   - **Description:** `Cinematic video editing portfolio — Life In Frames by Rakesh Kodathala`
   - **Public** (must be public for free GitHub Pages hosting)
   - Do NOT check "Add a README" (we already have one)
3. Click **"Create repository"**

---

## STEP 4 — Upload Your Files (No-Code Method)

This is the easiest way — no terminal needed:

1. On your new empty repo page, click **"uploading an existing file"** link
2. Drag and drop all 3 files from your `life-in-frames` folder:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. In "Commit changes", type: `Initial commit - portfolio launch`
4. Click **"Commit changes"**

---

## STEP 5 — Enable GitHub Pages (Make It Live)

1. In your repo, go to **Settings** (tab at the top)
2. In the left sidebar, click **Pages**
3. Under "Source", select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes

Your site will be live at:
```
https://YOUR-USERNAME.github.io/life-in-frames
```

---

## STEP 6 (Optional) — Custom Domain

If you ever buy a domain (e.g., lifeinframes.com):

1. In **Settings → Pages**, enter your custom domain
2. At your domain registrar, add a CNAME record:
   - **Name:** `www`
   - **Value:** `YOUR-USERNAME.github.io`
3. Add an A record pointing to GitHub's IPs:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`

---

## ALTERNATIVE — Terminal Method (if you prefer Git)

If you have Git installed on your computer:

```bash
# Navigate to your folder
cd life-in-frames

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - portfolio launch"

# Set the branch name
git branch -M main

# Connect to your GitHub repo (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/life-in-frames.git

# Push
git push -u origin main
```

Then follow Step 5 above to enable GitHub Pages.

---

## AFTER GOING LIVE — Share These Links

Once your site is live, use these links everywhere:

| Platform         | What to Do                                                |
|------------------|-----------------------------------------------------------|
| Fiverr profile   | Add your GitHub Pages URL in your bio and gig descriptions|
| Instagram bio    | Add the portfolio link                                    |
| YouTube banner   | Add the URL to your channel description and banner links  |
| Email signature  | Add: Portfolio: https://YOUR-USERNAME.github.io/life-in-frames |
| LinkedIn         | Add as a "Featured" link on your profile                  |

---

## UPDATING YOUR PORTFOLIO LATER

To update the site after it's live:

1. Go to your repo on GitHub
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Make your changes
5. Click "Commit changes"
6. The site updates automatically in 1-2 minutes

Done! Your portfolio is now live on the internet.
