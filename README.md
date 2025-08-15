# Around Trade - Dynamic Next.js Clone

A modern, dynamic Next.js application cloning the Around Trade website with server-side rendering capabilities.

## Features

- **Dynamic Next.js App Router** - Latest Next.js 15 with App Router
- **TypeScript Support** - Full TypeScript configuration
- **Tailwind CSS** - Modern utility-first CSS framework
- **shadcn/ui Components** - Beautiful, accessible React components
- **Server-Side Rendering** - Optimized for dynamic content and SEO
- **Netlify Ready** - Configured for dynamic deployment on Netlify

## Pages

- **Homepage** - Hero section, product features, testimonials
- **Company Page** - Mission, story, and contact form
- **Dynamic Routing** - Ready for additional pages and API routes

## Getting Started

```bash
# Install dependencies
bun install

# Run development server
bun run dev

# Build for production
bun run build

# Start production server
bun run start
```

## Deployment

This project is configured for dynamic deployment on Netlify with:
- Automatic builds on push
- Server-side rendering support
- Environment variable support
- Edge function capabilities

## Tech Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Components**: shadcn/ui
- **Package Manager**: Bun
- **Deployment**: Netlify

## Project Structure

```
src/
├── app/
│   ├── page.tsx          # Homepage
│   ├── company/
│   │   └── page.tsx      # Company page
│   ├── layout.tsx        # Root layout
│   └── globals.css       # Global styles
├── components/
│   └── ui/               # shadcn/ui components
└── lib/
    └── utils.ts          # Utility functions
```

## Features Ready for Extension

This dynamic setup enables easy addition of:
- API routes for backend functionality
- Database connections
- Authentication systems
- Dynamic content management
- Real-time features
- Server-side data fetching

---

🤖 Generated with [Same](https://same.new)