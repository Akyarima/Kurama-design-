# Kurama Interior & Exterior Finishing

A professional website for **Kurama Interior & Exterior Finishing** — a Nigeria-based building finishing company specializing in wall screeding, POP ceiling installation, painting, wallpaper, and general building finishing.

## Live Site

- **Published URL:** [https://kuramadesign.lovable.app](https://kuramadesign.lovable.app)
- **Custom Domain:** [http://kuramadesign.name.ng](http://kuramadesign.name.ng)

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| [TanStack Start](https://tanstack.com/start) | Full-stack React framework (SSR + API routes) |
| [React 19](https://react.dev) | UI library |
| [TypeScript](https://typescriptlang.org) | Type-safe JavaScript |
| [Tailwind CSS v4](https://tailwindcss.com) | Utility-first styling |
| [TanStack Router](https://tanstack.com/router) | File-based routing |
| [TanStack Query](https://tanstack.com/query) | Server state management |
| [Vite](https://vitejs.dev) | Build tool & dev server |
| [shadcn/ui](https://ui.shadcn.com) | UI component primitives |

## Project Structure

```
├── src/
│   ├── routes/              # Page routes (file-based routing)
│   │   ├── index.tsx        # Home page
│   │   ├── about.tsx        # About page
│   │   ├── services.tsx     # Services page
│   │   ├── portfolio.tsx    # Portfolio page
│   │   ├── testimonials.tsx # Testimonials page
│   │   └── contact.tsx      # Contact page
│   ├── components/          # Reusable components
│   │   ├── SiteHeader.tsx   # Navigation header
│   │   ├── SiteFooter.tsx   # Footer with contact info
│   │   └── ui/              # shadcn/ui components
│   ├── styles.css           # Tailwind CSS + design tokens
│   ├── router.tsx           # Router configuration
│   └── routes/__root.tsx    # Root layout (head meta, shell)
├── public/                  # Static assets
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org) 18+ (or [Bun](https://bun.sh))
- A package manager (`npm`, `yarn`, `pnpm`, or `bun`)

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/kurama-design.git
cd kurama-design

# Install dependencies
bun install
# or: npm install
```

### Development

```bash
# Start the dev server
bun dev
# or: npm run dev
```

The site will be available at `http://localhost:3000`.

### Build for Production

```bash
# Production build
bun run build
# or: npm run build

# Preview the production build locally
bun preview
# or: npm run preview
```

## Pages

| Page | Route | Description |
|------|-------|-------------|
| Home | `/` | Hero, services overview, portfolio preview, CTA |
| About | `/about` | Company story, mission, team |
| Services | `/services` | Detailed service offerings |
| Portfolio | `/portfolio` | Project gallery |
| Testimonials | `/testimonials` | Client reviews |
| Contact | `/contact` | Contact form, phone, WhatsApp, email |

## Contact Information

- **Phone:** [0708 477 2196](tel:+2347084772196)
- **WhatsApp:** [https://wa.me/2347084772196](https://wa.me/2347084772196)
- **Email:** [kurama1655@gmail.com](mailto:kurama1655@gmail.com)
- **Website:** [http://kuramadesign.name.ng](http://kuramadesign.name.ng)
- **Facebook:** [https://www.facebook.com/kuramadesign](https://www.facebook.com/kuramadesign)

## SEO & Meta Tags

The site includes:
- Open Graph tags for social sharing
- Twitter Card metadata
- JSON-LD structured data (LocalBusiness schema)
- Semantic HTML for accessibility
- Responsive viewport meta tag

## Customization

### Updating Contact Details

Edit these files to update contact information across the site:

- `src/components/SiteFooter.tsx` — Footer contact links
- `src/routes/contact.tsx` — Contact page details
- `src/routes/__root.tsx` — Schema.org telephone number

### Adding Portfolio Images

Replace placeholder images in `src/routes/portfolio.tsx` with your actual project photos.

### Changing Colors

Design tokens are defined in `src/styles.css` using CSS custom properties. Update the `--primary`, `--secondary`, `--accent`, and other variables to match your brand.

## Deployment

This project was built with [Lovable](https://lovable.dev). To deploy elsewhere:

1. **Vercel:** Connect your GitHub repo to [Vercel](https://vercel.com) — TanStack Start works out of the box.
2. **Netlify:** Use the Vite build output (`dist/` or `.output/`).
3. **Custom Server:** Build and serve the output from any Node.js or edge-compatible host.

## License

This project is private and proprietary — built for Kurama Interior & Exterior Finishing.

---

**Built with ❤️ for Kurama Interior & Exterior Finishing | Nigeria**
