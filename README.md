# tourism-frontend-admin

Next.js + shadcn/ui admin-facing frontend for the tourism booking platform. Part of a 3-repo project — see `tourism-be-api/docs/README.md` for the multi-repo picture.

> ⏸ **Status:** plan TBD. Sprint plan for this repo lands after the customer FE proves the FE-side wiring end-to-end. Until then this is a fresh Next.js + shadcn template.

## Quickstart

```bash
pnpm install
pnpm dev            # http://localhost:3002 (suggested — customer FE owns :3001)
```

Backend at `http://localhost:3000` (see `tourism-be-api/docs/runbooks/en/local-dev.md`).

## Read first

- [`docs/README.md`](docs/README.md) — status + where the plan will live
- `tourism-be-api/docs/planning/roadmap.md` § "Frontend phase" — what's expected here

## Adding shadcn components

```bash
npx shadcn@latest add button
```

Components land in `components/ui/`. Import as:

```tsx
import { Button } from "@/components/ui/button";
```
