# Pagani Utopia — product showcase

A scroll-driven product page for the Pagani Utopia: splash sequence, narrative panels, a 3D model viewer, and a configurator.

**Live:** https://paganiscroll.vercel.app · Next.js · TypeScript

---

## What it is

An exercise in the kind of page a luxury manufacturer actually ships — where the product reveals itself as you scroll rather than sitting in a grid of specifications.

- **Splash screen** into the reveal, so the first frame is composed rather than half-loaded
- **Story panels** that advance with scroll position
- **Model viewer** for rotating the car
- **Configure** and **Discover** routes for specification and detail

## Build

Next.js App Router with TypeScript. UI is built from **Radix UI primitives** — accessible behaviour without inheriting a component library's visual opinions, which matters when the whole point is a bespoke look. Forms use React Hook Form with Zod resolvers.

## Running locally

```bash
npm install
npm run dev
```

---

An independent design exercise. Pagani is not affiliated with this project and all marks belong to them.

Built by [Jeremy Ahamioje](https://github.com/JeremyAhamioje).
