# Sorelle Studio — Website

Official website for **Sorelle Studio**, a design-led web studio based in London & Madrid.

🌐 Live site: _add your Vercel URL here once deployed_

---

## 📁 Project Structure

```
sorelle-studio/
├── index.html       ← The entire website (single HTML file)
├── logo.png         ← Studio logo mark
└── README.md        ← This file
```

That's it — no build tools, no dependencies, no Node.js required. Pure HTML, CSS, and JavaScript.

---

## 🚀 How to Deploy on Vercel (Step by Step)

### Step 1 — Create a GitHub account
If you don't have one: go to [github.com](https://github.com) and sign up. It's free.

### Step 2 — Create a new repository
1. Click the **+** icon in the top right → **New repository**
2. Name it `sorelle-studio` (or anything you like)
3. Set it to **Public**
4. **Don't** tick "Add a README" (you already have one)
5. Click **Create repository**

### Step 3 — Upload your files
On the next screen, you'll see an empty repo. Click **"uploading an existing file"** (the link in the middle of the page).

Drag and drop these three files:
- `index.html`
- `logo.png`
- `README.md`

Then scroll down and click **Commit changes**.

### Step 4 — Connect Vercel
1. Go to [vercel.com](https://vercel.com) and sign up / log in **with your GitHub account**
2. Click **"Add New Project"**
3. You'll see your GitHub repos listed — click **Import** next to `sorelle-studio`
4. Vercel will auto-detect it's a static site — no settings to change
5. Click **Deploy**

⏱️ It takes about 30 seconds. You'll get a live URL like `sorelle-studio.vercel.app`.

---

## 🌍 Setting a Custom Domain (Optional)

If you own a domain (e.g. `sorellestudio.org`):

1. In your Vercel project dashboard → **Settings** → **Domains**
2. Type your domain and click **Add**
3. Vercel will give you DNS records to add at your domain registrar (GoDaddy, Namecheap, etc.)
4. Once DNS propagates (usually 10–30 min), your custom domain is live

---

## ✏️ How to Update the Website

Whenever you want to change something on the site:

1. Edit `index.html` on your computer
2. Go to your GitHub repo → click `index.html` → click the **pencil icon** (Edit)
3. Make your changes and click **Commit changes**

Vercel detects the change and **automatically redeploys** within ~30 seconds. No manual steps needed.

Alternatively, you can use [GitHub Desktop](https://desktop.github.com/) for a visual interface if you prefer not to use the browser editor.

---

## 💡 Tips

- **Favicon**: The logo (`logo.png`) is already set as the browser tab icon
- **SEO**: The `<meta name="description">` tag in `index.html` is what Google shows in search results — edit it to be descriptive
- **Analytics**: To add free visitor tracking, sign up at [vercel.com/analytics](https://vercel.com/analytics) — it integrates with zero code changes
- **Email**: The contact buttons use `mailto:` links — they open the visitor's email app. If you later want a proper contact form, look into [Formspree](https://formspree.io) (free tier available)
- **Mobile**: The site is fully responsive and tested for mobile

---

## 📬 Contact

- Email: [sales@sorellestudio.org](mailto:sales@sorellestudio.org)
- Phone: +34 679 513 022
- Instagram: [@sorellestudioweb](https://instagram.com/sorellestudioweb)
- London & Madrid
