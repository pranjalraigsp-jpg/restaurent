# Velouté & Spice — Luxury Dining & Restaurant Platform

A modern luxury restaurant web application built with React 19, TypeScript, Vite, and Tailwind CSS. Featuring cinematic video atmospheres, multi-brand restaurant switching, dynamic dietary filtering, live cart and customizer modal, reservation booking, WhatsApp direct ordering, multi-currency support (INR/USD), and an administrative control panel.

---

## 🌟 Key Highlights

- **Cinematic Visual Identity**: Muted ambient restaurant video backgrounds in Hero and Dining Atmosphere sections with high-fidelity poster fallbacks.
- **Multi-Brand Switcher**: Instantly switch between luxury dining concepts (e.g., *Velouté & Co. French Haute Cuisine*, *Aura Royale Indian Gastronomy*, *Kintsugi Japanese Omakase*).
- **Interactive Menu Catalogue**: Filter by category, vegetarian/non-vegetarian, spice intensity, gluten-free, and chef specials.
- **Customization & Cart System**: Modify spice levels, dietary add-ons, portion sizes, and place delivery or takeaway orders with instant totals and coupon codes.
- **WhatsApp Concierge & Reservations**: Direct 1-tap WhatsApp message formatting with full order details, plus live table reservation scheduling.
- **Integrated Admin Dashboard**: Toggle dish availability, manage incoming orders, review reservations, and customize brand details in real time.

---

## 🚀 Quick Start (Local Development)

```bash
# 1. Clone your repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

# 2. Install dependencies
npm install

# 3. Start local development server
npm run dev
```

Visit `http://localhost:3000` in your browser.

---

## 📦 Production Build

```bash
npm run build
```

The production output will be generated inside the `dist/` directory, optimized for deployment.

---

## 🌐 Deploying to GitHub Pages

This repository includes an automated GitHub Actions deployment workflow at `.github/workflows/deploy.yml`.

### Option A: Automatic Deployment via GitHub Actions (Recommended)

1. Create a new repository on [GitHub](https://github.com/new).
2. Push your project code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Luxury restaurant web platform"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
3. In your GitHub repository:
   - Go to **Settings** → **Pages**.
   - Under **Build and deployment** > **Source**, select **GitHub Actions**.
4. The workflow will automatically build and publish your site!

### Option B: Deploying with Vercel or Netlify

- **Vercel**: Import the GitHub repository at [vercel.com/new](https://vercel.com/new). Build command: `npm run build`, Output directory: `dist`.
- **Netlify**: Connect your GitHub repository at [app.netlify.com](https://app.netlify.com). Build command: `npm run build`, Publish directory: `dist`.
