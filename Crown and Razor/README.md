# Crown & Razor — Barber Lounge

Astro + vanilla CSS/JS. Black and gold, booking goes to WhatsApp.

```
npm install
npm run dev      # local preview
npm run build    # outputs to dist/
```

Deploy to Cloudflare Pages: build command `npm run build`, output directory `dist`.

Before going live, edit the top of `src/pages/index.astro`:
- `WHATSAPP`: the shop's real number (country code, no + or spaces)
- services, prices, barbers, address and hours
- replace the SVG placeholders with real photos when available
