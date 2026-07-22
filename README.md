# RD Herz Šmartno Platform

Modularna spletna platforma za rokometni klub RD Herz Šmartno.

## Predvidena arhitektura

- `apps/web` – javna spletna stran
- `apps/admin` – administracijski vmesnik
- `packages/ui` – skupne UI komponente
- `packages/config` – skupne konfiguracije
- `supabase` – podatkovna baza, migracije in začetni podatki

## Tehnologije

- Next.js
- TypeScript
- Tailwind CSS
- Supabase
- Vercel
- pnpm workspaces

## Začetek

```bash
pnpm install
pnpm dev
```

## Prve razvojne naloge

1. Postavitev javne spletne strani
2. Postavitev administracije
3. Supabase prijava
4. Modularni sistem predalčkov
5. Novice, tekme, igralci in sponzorji
