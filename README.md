# Trendify Academy

A production-ready Next.js prototype for Trendify Academy, a free AI education platform.

## Included

- Responsive Trendify Academy landing page and course catalog
- 12-course catalog across 3 learning tracks
- Course search and track filtering
- Course detail modal with enrollment flow
- Client-side student account and enrollment prototype using browser local storage
- Student dashboard with enrollment progress
- Credential verification prototype
- Keyboard-accessible interactions and reduced-motion support
- No external runtime dependencies apart from Google Fonts

## Important

Account, enrollment, and certificate data are currently client-side prototype functionality. For production, connect these flows to a real authentication provider, database, and certificate issuance service.

## Local development

Install dependencies and start the Next.js development server:

```bash
npm install
npm run dev
```

Open `http://localhost:3000` in your browser.

## Production build

```bash
npm run build
npm run start
```

The application can be deployed to Vercel or another host that supports Next.js. The app entry point is `app/page.js`; `index.html` is not the deployment entry point for this project.
