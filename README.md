# Aurora Coffee Co. (Alder & Co.) — Web Developer Assignment

A responsive, high-aesthetic specialty coffee storefront and subscription marketing experience built for the Weststacks Web Developer Take-Home Assignment.

---

## 1. Chosen Brief
- **Brief 1: Aurora Coffee Co.** — A specialty coffee subscription brand (presented under the luxury editorial identity *Alder & Co. — Coffee For Calm Mornings*).
- **Architecture**: Single-page application with 100% browser-side state management; no external backend required.

---

## 2. Tech Stack
- **Framework**: React 18 with Vite
- **Styling**: Vanilla CSS3 design system (CSS variables/tokens, Flexbox, CSS Grid, 3D perspective transforms)
- **Typography**: Google Fonts (*Fraunces* serif & *Plus Jakarta Sans*)
- **Animations & Effects**: Native RequestAnimationFrame Parallax Engine, IntersectionObserver 3D reveals, CSS keyframe floating loops
- **Tooling & Build**: Vite with relative asset bundling (`base: './'`) for instant local execution

---

## 3. Interactive Features Built (9+ Features)

1. **Dark / Light Theme Toggle**: Persistent theme switcher with instant CSS variable swap; preference saved in `localStorage`.
2. **Live Instant Filter & Search**: Real-time product search with keyword matching across origins/tasting notes and roast category tabs (`All`, `Light`, `Medium`, `Dark`). Includes keyboard shortcut (`/`) to focus.
3. **Cart Drawer with Live Subtotal**: Add to bag, increment/decrement quantities, dynamic subtotal calculation, and auto-persistence to `localStorage`.
4. **Monthly / Yearly Subscription Pricing Toggle**: Switcher dynamically recalculates plan pricing with a 15% annual savings discount.
5. **Interactive Coffee Finder Quiz (Configurator)**: 3-step interactive recommendation engine matching brew methods and flavor profiles to the optimal roast, with one-click "Add match to bag".
6. **Scroll Parallax & Floating Single Beans**: Layered scroll-reactive physics with photographic single coffee beans that rotate and tilt with cursor movement; top reading progress bar.
7. **Form Validation & Dynamic Feedback**: Contact form with HTML5 field validation, submission state prevention, and interactive toast feedback alerts.
8. **Accessible Slide-out Modal Drawer**: Cart drawer with backdrop overlay, smooth spring slide-in transition, and `Escape` keyboard dismissal.
9. **Animated Stat Counters on Scroll**: Live counter animation triggered when numbers scroll into view via IntersectionObserver (e.g. 2,400+ cups, 12,000+ subscribers).

---

## 4. Free & Open-Source Asset Credits
- **Photography**: Free high-resolution editorial photography from [Unsplash](https://unsplash.com) (credits: Nathan Dumlao, Demi DeHerrera, Visual Stories).
- **Bean Assets**: Photorealistic macro single coffee bean cutouts with transparent backgrounds.
- **Typography**: Google Fonts (*Fraunces* & *Plus Jakarta Sans*) under SIL Open Font License.

---

## 5. How to Run

### Option A: Direct Double-Click (No Setup Needed)
Open the pre-built standalone file directly in any modern browser:
- Open `aurora-coffee-react/dist/index.html` (or `dist/index.html`)

### Option B: Development Server
```bash
# From the project root or aurora-coffee-react folder:
npm install
npm run dev
# Open http://localhost:5173 or http://localhost:5174
```

### Option C: Production Build
```bash
npm run build
```
