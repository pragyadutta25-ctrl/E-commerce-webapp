AURA | Modern Lifestyle & Tech Store ⚡
Preview unavailable

A luxury, high-performance e-commerce web application featuring modern aesthetic minimalism, AI-generated brand identity, interactive product showcases, and a seamless simulated checkout pipeline.

✨ Features
🎨 Bespoke AI-Generated Brand Identity: Custom luminous vector icon embedded in navigation, favicon, footer, and invoices.
🎧 Interactive Multi-Product Hero Showcase: Smoothly switch between flagship products (Sonic Pro Studio Headphones, Horizon Titanium Watch, Health Ring) with live finish customizers and floating stat badges.
🍱 Modern Bento Grid Collections: 4-pillar architectural layout for Audio & Tech, Titanium Wearables, Nanotech Apparel, and Sanctuary Living.
🔬 Interactive Engineering Anatomy: Exploded product diagrams with 3 clickable interactive hotspot pins and an animated audio frequency wave simulator.
⚡ Limited Drop Flash Deal: Live JavaScript countdown clock (hours, minutes, seconds) with inventory scarcity meter and 1-click bundle discount.
🔍 Instant Catalog Search & Multi-Axis Filtering:
Live search scanning titles, descriptions, and features.
Price range slider, customer rating filter, in-stock only toggle, and sorting options.
In-card color swatch selector with instant "Added!" checkmark micro-interaction.
🛍️ Slide-Over Cart Drawer:
Free express shipping progress bar ($150 milestone).
Promo code engine (AURA20 for 20% off, WELCOME10 for 10% off, FREESHIP for zero delivery fee).
Real-time recalculation of subtotal, discounts, shipping, and tax.
❤️ Wishlist Drawer: 1-click save with dedicated slide-over panel and "Move All to Cart" action.
💳 Multi-Step Checkout & Order Invoicing:
Step 1: Recipient address with 1-click "Quick Demo Fill" button.
Step 2: Interactive 3D virtual credit card with live typing reflection.
Step 3: Order review with confetti celebration, tracking number, 4-stage delivery tracker, and printable invoice (window.print()).
🌐 Global Preferences: Dark / Light theme toggle and multi-currency converter (USD $, EUR €, GBP £, INR ₹).
💾 Full Persistence: Cart, Wishlist, Currency, and Orders persist across sessions via localStorage.
🛠️ Tech Stack
Framework: React 19
 + TypeScript
Bundler & Dev Server: Vite 6
Styling: Tailwind CSS v4
Icons: Lucide React
Celebration Effects: Canvas Confetti
Typography: Plus Jakarta Sans
🚀 Getting Started
Prerequisites
Make sure you have Node.js
 installed (v18 or higher recommended).

Installation

1.Clone or copy this repository:

bash

git clone <your-repo-url>
cd aura-ecommerce

2.Install dependencies:

bash

npm install

3.Start the local development server:

bash

npm run dev
Open your browser at http://localhost:5173.

Production Build
To compile an optimized production bundle:

bash

npm run build
The output will be generated in the dist/ directory.

To preview the production build locally:

bash

npm run preview
📂 Project Structure

aura-ecommerce/
├── public/
│   ├── aura-logo.png          # High-resolution brand logo & favicon
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── AnnouncementBar.tsx       # Top promotional ribbon
│   │   ├── BentoGrid.tsx             # Curated collection showcase
│   │   ├── CartDrawer.tsx            # Slide-over cart with promo engine
│   │   ├── CheckoutModal.tsx         # 3-step checkout with virtual credit card
│   │   ├── FeaturesBanner.tsx        # Customer guarantees & trust badges
│   │   ├── FilterSidebar.tsx         # Catalog filters (price, rating, stock)
│   │   ├── FlashDealBanner.tsx       # Live countdown timer & flash drop
│   │   ├── Footer.tsx                # Newsletter signup, brand links
│   │   ├── HeroBanner.tsx            # Interactive hero showcase
│   │   ├── InteractiveSpotlight.tsx  # Product anatomy hotspots & sound simulator
│   │   ├── Navbar.tsx                # Sticky glass navigation & counters
│   │   ├── OrderSuccessModal.tsx     # Order celebration & printable receipt
│   │   ├── ProductCard.tsx           # Product card with variant swatches
│   │   ├── ProductDetailModal.tsx    # Multi-angle gallery & full specifications
│   │   ├── ProductGrid.tsx           # Responsive catalog grid with sorting
│   │   ├── SocialProofMarquee.tsx    # Press reviews & design awards
│   │   ├── Toast.tsx                 # Floating notification toasts
│   │   └── WishlistDrawer.tsx        # Slide-over saved favorites
│   ├── context/
│   │   └── ShopContext.tsx           # Central state & localStorage manager
│   ├── data/
│   │   └── products.ts               # Curated products, promo codes, currencies
│   ├── types/
│   │   └── index.ts                  # TypeScript data models & interfaces
│   ├── App.tsx                       # Root layout & component composition
│   ├── index.css                     # Tailwind v4, glassmorphism & keyframes
│   └── main.tsx                      # App entrypoint
├── index.html
├── package.json
├── tsconfig.json
└── vite.config.ts
🚀 Deployment
Vercel: Run npx vercel --prod
Netlify: Run npx netlify deploy --dir=dist --prod or drag & drop dist/ into app.netlify.com/drop
GitHub Pages: Set build output to dist using the Vite static deploy action.

📄 License
MIT License. Free for personal and commercial use.
