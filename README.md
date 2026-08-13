# Magnus Kaur

Software developer in Helsinki, Finland. Open to remote roles.

I build full-stack web applications and internal business systems: authentication and role-based access, booking and scheduling, admin and operations tooling, and the database design underneath them. Most of this work is commercial and lives in private repositories, so the summaries below describe what each system does and how it is built.

**Stack:** Next.js, React, TypeScript, JavaScript, PostgreSQL, Supabase, Tailwind CSS, Vercel

---

## Public code sample

**[Booking Conflict Engine](https://github.com/mgndxb/booking-conflict-engine)**  
A focused Next.js and TypeScript scheduling sample demonstrating database-enforced overlap prevention, idempotent booking creation, PostgreSQL constraints and automated tests against PGlite/Postgres.

---

## Selected work

### FlagSales
Field-sales operations platform for a Finnish sales organization.

I built earlier internal FlagSales systems that are used operationally by a field-sales team of roughly 20 people. I am now rebuilding the platform from scratch after auditing the legacy production application and finding security and correctness problems. The rebuild covers employee authentication, shift scheduling, sales logging, field workflows and role-based access, and is in active development rather than deployed.

- Business rules enforced in the database, not only in application code
- Custom tooling for schema migrations
- 707 automated test cases across 25 test files
- Tests run the production SQL migrations against PGlite/Postgres, so schema and database rules are exercised as they actually run

Stack: Next.js, TypeScript, PostgreSQL, Supabase

### CreatorMission
Campaign-aware browser video editor for creators producing paid content. Live at [creatormission.com](https://creatormission.com).

Local-first architecture: source video stays on the user's device, and editing and export run in the browser. The editor checks a creator's work against the requirements of the campaign it belongs to.

- OAuth with PKCE, signed sessions and subscription entitlement checks
- Pro export protected behind entitlement verification
- Deployed to production on Vercel

Stack: Next.js, TypeScript

### Swepth
Full-stack home-cleaning marketplace.

Covers the full loop: customer booking, a cleaner PWA for job management, and an admin and operations interface for the people running the service.

- Stripe payments
- Supabase/PostgreSQL backend shared across all three interfaces

Stack: React, TypeScript, Supabase, PostgreSQL, Stripe

### Ateliva
Full-stack platform for a digital studio. Public site at [ateliva.com](https://ateliva.com); the partner and admin portals sit behind authentication.

- Application workflows with invitation tokens, moving through state transitions backed by the database
- Separate partner and admin portals, plus transactional email
- Deployed and tested in production

Stack: Next.js, TypeScript, Supabase, PostgreSQL

### Additional work
**Lumos Energia:** customer booking and internal scheduling for an energy company, including booking validation, a shared internal calendar and overlap prevention so two bookings cannot claim the same slot. Next.js, TypeScript, Supabase, PostgreSQL.

**First Builder:** product built on a custom design-token system, a reusable component system and custom lint rules. In progress, not launched. Next.js, React, TypeScript.

---

## What I work on

**Built repeatedly:** authentication and session handling, role-based access control, booking and scheduling with conflict prevention, admin and back-office tooling, REST and third-party API integrations, Stripe payments

**Data:** PostgreSQL, Supabase, schema and migration design, business rules enforced at the database level

**Delivery:** Git and GitHub, automated testing, Vercel, verifying behavior in production after deploy

---

## Contact

Magnus Kaur<br>
Helsinki, Finland<br>
[magnuskaur.dev@gmail.com](mailto:magnuskaur.dev@gmail.com)

Open to remote software development roles.
