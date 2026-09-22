# Solergy

Company website for Solergy Systems, a solar energy provider based in Hajipur, Bihar. Built to give the client a proper online presence for their residential and commercial solar work.

## Live

https://solergy.in/

## Sections / Features

- **Home** — full-screen hero carousel, mission highlights, and a services overview
- **About** — a note from the director, office address, phone/email, social links, and an embedded Google Map
- **Blog** — a searchable, sortable grid of solar energy news and updates
- **Services** — EPC (engineering, procurement, construction), O&M, solar water heaters, UPS/inverters, and residential & commercial project categories
- **Enquiry form** — captures name, phone, email, address, and requirements, and emails the lead to the business via a Netlify serverless function (Nodemailer over Gmail SMTP)
- **PM Surya Ghar promo modal** — a one-time popup pushing the government's rooftop solar subsidy scheme, with a CTA into the enquiry form
- **Floating call button** — persistent click-to-call widget for mobile visitors
- **Sticky header/nav** with scroll-aware styling and a mobile menu

## Tech stack

- Nuxt 4 (Vue 3) with SSG/SSR
- Tailwind CSS
- Swiper for the hero carousel
- @nuxt/image for image optimization, plus a custom `optimize-images.mjs` script
- @nuxtjs/seo for meta/SEO handling
- Netlify Functions (TypeScript) + Nodemailer for the contact form backend
- Deployed on Netlify

---

**Ankit Singh**
[LinkedIn](https://www.linkedin.com/in/ankit-singh-117925249/)
