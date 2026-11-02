# smecontrols.com

The website of ששון משה הנדסת חשמל בע"מ, built with [Astro](https://astro.build) and hosted on Cloudflare Pages.

- Business details (phone, email, WhatsApp): `src/data/site.ts`
- Pages: `src/pages/`
- Images: `public/images/` (downloaded once from the old Wix site by `.github/workflows/fetch-wix-images.yml`)

## Local development

```
npm install
npm run dev
```

## Cloudflare Pages settings

- Framework preset: Astro
- Build command: `npm run build`
- Build output directory: `dist`
