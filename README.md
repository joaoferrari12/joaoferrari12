# Hi, I'm João Victor

I build and run production software with AI agents. Founding engineer of Ferra, Computer Systems student at BCIT,
based in Vancouver. Open to developer roles in Vancouver and remote.

## Ferra · [ferraia.com](https://ferraia.com)

One operations app for many small service businesses in Brazil: orders, cash, stock and the end of day close, for
places that still run on paper and WhatsApp. Built solo since July 2026. The product code is private, but the product is not:
[ferraia.com](https://ferraia.com) shows the real screens, and seven fictional businesses are live with their public
customer pages, no account needed, for example [app.ferraia.com/p/forno-nove](https://app.ferraia.com/p/forno-nove). What's behind it:

- **Front end:** React 19, Vite, TanStack Query, shadcn/ui, installable PWA
- **Data:** Supabase Postgres, row level security keeping every company's data apart, 133 versioned migrations, Edge Functions
- **Quality:** 300+ test files, CI on GitHub Actions, a deploy pipeline built so an update never takes the live app down
- **Next:** the first three real businesses go live in person in December 2026

## How I build with AI agents

Claude Code is my engineering method, not autocomplete. Every decision is written down (208 architecture decision
records so far), scripted guards refuse to deploy when a rule breaks, and test runs walk the whole flow with fictional
businesses, logging what's right and what's wrong. Subagents get a model per task: cheap to read, stronger to build,
strongest to review. In September 2026 that added up to 1,231 commits across the Ferra repositories.

## Blindagem Digital · [joaoferrari12.github.io/blindagem-digital](https://joaoferrari12.github.io/blindagem-digital/)

A 10-minute digital security check-up for everyday people, in Portuguese and English: a score, an action plan, and a
leaked-password test that never sends the password (k-anonymity against the Have I Been Pwned range API). Vite +
TypeScript, no backend, 29 Vitest tests, 0 axe violations across 38 screens, 55.7 kB gzipped on first load.
[Source](https://github.com/joaoferrari12/blindagem-digital).

## Games

Small games in Godot 4, published early and measured with real players. Olympian Descent is in closed testing on
Google Play ([privacy policy](https://github.com/joaoferrari12/olympian-descent-privacy)).

## Earlier work

- [**cambio**](https://github.com/joaoferrari12/cambio): daily Canadian dollar rates from the Bank of Canada, with
  history charts, a converter and favourites. React 19, TanStack Query, Recharts, 16 tests, axe clean
  ([live](https://joaoferrari12.github.io/cambio/))
- [**Civitas**](https://github.com/joaoferrari12/civitas) (archived): a community decision app with an AI layer on the
  Anthropic API that explains instead of persuading. NestJS, Postgres, Redis, Expo. What came before Ferra.
- [**angular-movie-browser**](https://github.com/joaoferrari12/angular-movie-browser): Angular 19 movie browser with
  signals, an accessible poster-first UI and a Cloudflare Worker keeping the API key off the browser
  ([live](https://joaoferrari12.github.io/angular-movie-browser/))
- [**property-agency-api**](https://github.com/joaoferrari12/property-agency-api): Spring Boot REST API over the
  [java-property-agency](https://github.com/joaoferrari12/java-property-agency) domain
- [**blog-database-sql**](https://github.com/joaoferrari12/blog-database-sql): MySQL schema and 14 analytical queries
- [**petvida-website**](https://github.com/joaoferrari12/petvida-website): seven-page site for Pet Vida, my family's
  pet business in Salvador: plain HTML, CSS and JS, mobile-first, axe-core clean, WebP images cut from ~18 MB to
  under 2 MB ([live](https://joaoferrari12.github.io/petvida-website/))

## Stack

TypeScript · React · Angular · PostgreSQL / Supabase · Java / Spring Boot · SQL · Godot (GDScript) · Cloudflare ·
GitHub Actions · Claude Code

Também falo português.

También hablo español.
