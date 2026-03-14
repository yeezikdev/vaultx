# Private Vault — GitHub Pages Site

## File Structure
```
index.html           ← Login page
home.html            ← Browse / linktree
nicole-aniston.html  ← Nicole Aniston — Netflix-style page
brandi-love.html     ← Brandi Love — Netflix-style page
cory-chase.html      ← Cory Chase — Netflix-style page
```

## Login Credentials
- **Username:** bbsyx
- **Password:** kingkong

## Deploy on GitHub Pages
1. Create a new repository on GitHub
2. Upload all HTML files
3. Go to **Settings → Pages**
4. Source: **Deploy from branch → main → / (root)**
5. Save → live at `https://yourusername.github.io/repo-name/`

## How to Add a Telegram Link
In each actress HTML file, find this line:
```html
<a class="btn-tg" href="https://t.me/YOURCHANNEL_HERE" ...>
```
Replace `YOURCHANNEL_HERE` with your actual Telegram channel username.
Each page has its **own separate link**.

## How to Add Videos
In each actress page, find the comment block that says "HOW TO ADD A VIDEO"
and copy-paste the video card HTML for each video you want to add.

> ⚠️ Credentials are visible in the client-side HTML source code.
