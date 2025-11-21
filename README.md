# Bot Website

Modern, animated, and clean website for your multi-purpose Discord bot.

**Tech Stack:** Next.js + Tailwind CSS + Framer Motion  
**Hosting:** GitHub Pages (via `/docs` folder)

---

## 🚀 Quick Setup

1. **Install dependencies:**
    ```
    npm install
    ```

2. **Run locally:**
    ```
    npm run dev
    ```

3. **Build static site for GitHub Pages:**
    ```
    npm run build
    ```
    - Static files will output to `/docs`

4. **Deploy to GitHub Pages:**
    - Push all code to your repository.
    - On GitHub, go to repository Settings → Pages.
    - Set Pages source to `/docs` folder on the `main` branch.

## 🛠 File Structure

- `package.json` — dependencies and scripts
- `next.config.js` — static export settings
- `tailwind.config.js` — Tailwind config
- `postcss.config.js` — For Tailwind
- `public/` — assets (logo etc.)
- `src/styles/globals.css` — Tailwind CSS
- `src/components/FeatureCard.js` — Feature cards
- `src/pages/_app.js` — Global styles
- `src/pages/index.js` — Animated homepage

## 🎨 Customization

- Add your logo or images to `/public`
- Tweak content in `index.js` and `FeatureCard.js` for your bot info

## ⚡️ Want auto-deployment with GitHub Actions?  
Ask me to add a `.github/workflows/deploy.yml` file to deploy automatically when you push changes!
