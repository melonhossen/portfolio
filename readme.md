# 🚀 My Developer Portfolio

PHP & Laravel Developer portfolio — hosted for free on GitHub Pages.

## 🗂️ Project Structure

```
portfolio/
├── index.html              # Main portfolio page
├── assets/
│   ├── css/
│   │   └── style.css       # All styles
│   └── js/
│       └── main.js         # Interactions & animations
└── README.md
```

## ⚡ How to Deploy on GitHub Pages (Free Hosting)

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) → **New Repository**
2. Name it: `your-github-username.github.io`  
   _(Example: `raihanislam.github.io`)_
3. Set it to **Public**
4. Click **Create Repository**

### Step 2: Upload Files
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **(root)**
4. Click **Save**

Your site will be live at: `https://YOUR_USERNAME.github.io` 🎉

---

## ✏️ Customize Before Deploying

Open `index.html` and replace these placeholders:

| Placeholder | Replace With |
|-------------|--------------|
| `YOUR_USERNAME` (Fiverr) | Your Fiverr username |
| `YOUR_GITHUB` | Your GitHub username |
| `your@email.com` | Your email address |
| `Md. Raihan Islam` | Your actual name |

### Update Contact Form
1. Go to [formspree.io](https://formspree.io) → Sign up (free)
2. Create a form → Copy the endpoint ID
3. In `assets/js/main.js`, find `YOUR_FORM_ID` and replace it

### Add Your Real Projects
In `index.html`, find the **Projects** section and update:
- Project names and descriptions
- Tech stack tags
- Live demo links
- GitHub repo links

---

## 🛠️ Tech Used
- Pure HTML, CSS, JavaScript (no build tools needed)
- Google Fonts (Syne + Space Mono)
- Intersection Observer API for scroll animations
- Formspree for contact form

## 📄 License
MIT — feel free to customize for your own use.