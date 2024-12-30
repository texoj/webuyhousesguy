# WeBuyHousesGuy

Dynamic real estate lead generation platform built with Next.js

## Features

- Dynamic city-based pages with SEO optimization
- Lead tracking and analytics system
- Mobile-responsive design
- Market statistics integration
- Automated page generation for new cities

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## Environment Variables

Create a `.env.local` file with the following variables:

```env
GOOGLE_ANALYTICS_ID=your_ga_id
FACEBOOK_PIXEL_ID=your_pixel_id
```

## Project Structure

- `/src/pages` - Next.js pages including dynamic city routes
- `/src/utils` - Utility functions and lead tracking system
- `/src/styles` - Mobile styles and responsive design
- `/src/serverSide` - Server-side page generation tools