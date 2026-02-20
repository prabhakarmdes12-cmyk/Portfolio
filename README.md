# Prabhakar Kumar — Portfolio

A responsive portfolio website for UX Designer Prabhakar Kumar, featuring dark/light mode, photography and painting pages, and mobile-friendly navigation.

---

## 1. How to Preview Locally

### Option A: Open directly in browser (simplest)
1. Open File Explorer and go to the project folder.
2. Double-click `index.html` — it will open in your default browser.
3. **Note:** Some features (e.g. smooth scroll to anchors) may behave differently when opening files directly vs. from a server.

### Option B: Use a local server (recommended)
1. Open terminal/command prompt in this folder.
2. Run one of these:

   **With Node.js (if installed):**
   ```bash
   npx serve .
   ```
   Then open http://localhost:3000 in your browser.

   **With Python 3:**
   ```bash
   python -m http.server 8080
   ```
   Then open http://localhost:8080 in your browser.

   **With Python 2:**
   ```bash
   python -m SimpleHTTPServer 8080
   ```

### Option C: Live Server extension (VS Code / Cursor)
1. Install the **Live Server** extension (by Ritwick Dey).
2. Right-click `index.html` in the file explorer.
3. Click **Open with Live Server**.
4. The site will open in the browser and auto-refresh when you save files.

### Option D: Chrome launch config
Your `.vscode/launch.json` is set for `http://localhost:8080`. Start a local server first (e.g. `python -m http.server 8080`), then press **F5** or use **Run > Start Debugging** to open Chrome.

---

## 2. How to Host Online

### GitHub Pages (free)
1. Create a GitHub account (if needed) and a new repository.
2. Push your project files into that repository.
3. Go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Click **Save**. Your site will be at `https://yourusername.github.io/your-repo-name/`.

### Netlify (free)
1. Go to [netlify.com](https://www.netlify.com) and sign up.
2. Drag and drop this project folder onto the Netlify dashboard, or connect your Git repo.
3. Netlify will deploy and give you a URL (e.g. `random-name.netlify.app`).
4. In **Domain settings** you can add a custom domain if you have one.

### Vercel (free)
1. Go to [vercel.com](https://vercel.com) and sign up.
2. Click **Add New → Project** and import your repository or upload the folder.
3. Deploy; Vercel will provide a URL.
4. You can add a custom domain in project settings.

### Cloudflare Pages (free)
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com).
2. Connect your Git repository or upload the project folder.
3. Deploy; your site will be available at `your-project.pages.dev`.

---

## Project structure

```
├── index.html        # Main homepage
├── photography.html  # Photography gallery page
├── painting.html     # Painting portfolio page
├── theme.js          # Dark/light mode toggle
├── images/           # Add project screenshots here (see images/README.md)
└── README.md         # This file
```

## Features

- **Responsive design** — Works on desktop, tablet, and mobile
- **Dark / light mode** — Toggle in the nav; preference saved in browser
- **Mobile menu** — Hamburger menu on small screens
- **Custom cursor** — Disabled on touch devices for better UX
- **Photography & Painting pages** — Dedicated pages for creative work
- **Selected Projects** — UX case studies from [Wix portfolio](https://prabhakardavinci.wixsite.com/uxdesign): Orry, LXRGuide, LXR SEO, Cook Bot, Incident Management, Design Workshops
