# StratGO Consulting — Website

Single-page consulting website with content admin panel. Hosted on GitHub Pages.

## Files

| File | Purpose |
|---|---|
| `index.html` | Main website (public) |
| `admin.html` | Content admin panel (private) |
| `content.json` | Site content — this is what you edit & re-upload to update the live site |

---

## Setup: GitHub Pages

1. Create a new GitHub repository (e.g. `stratgo-website`)
2. Upload all three files to the repository root
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your site will be live at `https://yourusername.github.io/stratgo-website/`

---

## Admin Panel

**URL:** `yoursite.com/admin.html` (or `localhost/admin.html`)  
**Password:** `stratgo@2024`

> ⚠️ To change the password, open `admin.html` and find the line:
> `const PASS = 'stratgo@2024';` — change the string to your new password.

### How to update your live website

1. Open `admin.html` in your browser
2. Sign in with the admin password
3. Make edits in any section and click **Save**
4. Go to **Export / Import** → click **Download content.json**
5. Go to your GitHub repo → click `content.json` → click the ✏️ edit icon → paste the new content (or drag-drop upload the file)
6. Commit the change — GitHub Pages redeploys in ~60 seconds

---

## Google Form Setup

1. Go to [forms.google.com](https://forms.google.com) and create a new form
2. **Recommended fields:**
   - Full Name *(required)*
   - Company Name *(required)*
   - Job Title *(required)*
   - Business Email *(required)*
   - Area of Interest: Strategy / Operations / Analytics / Transformation / IT / Management / Other *(dropdown)*
   - Estimated Project Timeline *(short answer)*
   - Brief Description of Your Challenge *(paragraph)*
   - How did you hear about us? *(optional)*
3. Click **Send → Link icon** → copy the short URL (e.g. `https://forms.gle/abc123`)
4. In admin panel → **Contact** → paste the URL → Save → Download content.json → upload to GitHub

---

## Customization Quick Reference

| What to change | Where |
|---|---|
| Stats numbers | Admin → Stats |
| Services text | Admin → Services |
| Founder bios | Admin → About & Founders |
| Google Form URL | Admin → Contact |
| Footer tagline | Admin → Footer |
| Admin password | Edit `const PASS` in `admin.html` |

---

*Built for GitHub Pages — no backend or database required.*
