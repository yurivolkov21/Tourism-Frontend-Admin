# tourism-frontend-admin — docs

Next.js admin-facing frontend for the tourism booking platform. One of three sibling repos:

```structure
C:\Development\09.Projects\
├── tourism-be-api\              NestJS BE — source of truth for API, schema, multi-repo roadmap
├── tourism-frontend-customer\   sibling customer FE
└── tourism-frontend-admin\      ← you are here
```

## Status

> ⏸ **Plan not yet written.** The admin FE plan lands after the customer FE proves the FE-side wiring end-to-end. Until then this repo is a Next.js shadcn template with no project-specific work.

When the plan is ready it will live in [`en/plan.md`](en/) (+ VI parallel).

## Where to start (until plan exists)

| You want to… | Read |
| --- | --- |
| See what's planned next | `tourism-be-api/docs/planning/roadmap.md` § "Frontend phase" |
| Understand the BE surface | `tourism-be-api/docs/reference/en/api-overview.md` + Swagger at `http://localhost:3000/api/docs` |
| Run the dev server | Repo root [`../README.md`](../README.md) |

## Cross-repo coordination

Same model as the customer FE repo: the BE repo owns API/schema/roadmap; each FE repo owns its own plan, screenshots, and FE-specific decisions.
