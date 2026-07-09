# patchfund.app

Marketing site and legal pages for [Patch Fund](https://patchfund.app) — a parent-facing allowance tracker for iOS.

Built with [Astro](https://astro.build). Static output, no backend required.

## Pages

| Path | Purpose |
|------|---------|
| `/` | Marketing homepage |
| `/privacy` | Privacy Policy (App Store Connect) |
| `/terms` | Terms of Service |
| `/delete-data` | Account and data deletion instructions |

## Development

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Build

```bash
npm run build
npm run preview
```

## Deploy

This site is a static Astro build. Deploy to Vercel, Netlify, or Cloudflare Pages:

1. Push this repo to GitHub.
2. Import the project in your host of choice.
3. Build command: `npm run build`
4. Output directory: `dist`
5. Point `patchfund.app` DNS to the host.

### App Store Connect URLs

Once deployed:

- **Privacy Policy URL:** `https://patchfund.app/privacy`
- **Support URL:** `https://patchfund.app` or `mailto:contact@nicoll.co`
- **Account deletion:** `https://patchfund.app/delete-data`

## Configuration

Site metadata lives in `src/config/site.ts` (company name, contact email, domain).

## License

Private — © Nicoll LTD Co
