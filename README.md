# DXP Marketing Engine (Concept Build)

Transform the DXP website into a 24/7 marketing and lead generation engine with campaign landing pages, programme visibility, a content publishing hub, and live analytics.

## 🚀 Quick start

```bash
npm install
npm run start:dev
```

Open `http://localhost:3000`.

## Explore the experience

| Goal | Route | What you’ll see |
| --- | --- | --- |
| Campaign landing pages | `/landing` | Lead capture + downloadable assets |
| Programme showcase | `/programs` | Outcomes, target audience, dates, registrations |
| Thought leadership hub | `/content` | Structured publishing feed |
| Analytics dashboard | `/analytics` | Traffic + lead performance |

## Interactive walkthroughs

1. **Capture a lead**
	- Visit `/landing/leadership-accelerator` and submit the form.
	- View captured leads at `/api/leads`.
2. **Review analytics**
	- Refresh the site a few times and open `/analytics`.
	- Use `/analytics/data` for JSON output.
3. **Publish content**
	- POST to `/content/api` with a new content payload.
	- View the feed at `/content/api/feed`.

## What’s included

- Landing pages with lead capture and downloadable resources.
- Programme catalogue and detail pages with outcomes, target audiences, dates, and registration links.
- Thought leadership publishing system with structured metadata and a JSON feed.
- Web analytics dashboard tracking traffic, engagement, and lead capture.

## Key routes (quick reference)

- `/` – Marketing engine home
- `/landing` – Landing pages with lead capture
- `/landing/:slug` – Individual landing pages
- `/programs` – Programme catalogue
- `/programs/:slug` – Programme detail pages
- `/content` – Thought leadership hub
- `/content/:slug` – Content detail pages
- `/analytics` – Analytics dashboard
- `/analytics/data` – JSON analytics summary
- `/api/leads` – Lead capture data (JSON)
- `/content/api/feed` – Content feed (JSON)
npm run test:e2e
```
