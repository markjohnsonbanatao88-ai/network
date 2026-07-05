# Combined Chat Archives

Static Vercel-ready project containing:

- `/` — landing page
- `/janine-joven.html` — Janine Tan & Joven Del Rosario Ong readable chat viewer
- `/melodee-arevalo.html` — Melodee Arevalo & Me readable chat viewer

Melodee CSV parsed: 37,459 messages from Nov 20, 2016 – Jul 14, 2017.

## Deploy

```bash
npm i -g vercel
vercel --prod
```

To update the existing `janinetan.vercel.app` project, deploy this folder and select the same Vercel project when prompted.

## Privacy

This project sets `noindex` headers and `robots.txt`, but the site is still publicly accessible if deployed without Vercel protection.
Enable Vercel Deployment Protection / password protection if these chats should remain private.
