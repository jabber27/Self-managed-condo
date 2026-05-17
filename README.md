# Self-managed-condo
Free open-source toolkit for owner-run condo associations — self-manage fees, voting, budgets &amp; more
# 🏝️ JacoBay Condo Manager

An open-source, mobile-first condo management system with a resident-facing app and an admin dashboard, powered by [Supabase](https://supabase.com).

## Apps

| File | Description |
|------|-------------|
| `resident.html` | Resident portal — authorize visitors, manage vehicles, report issues |
| `admin.html` | Admin dashboard — manage all units, fees, maintenance, announcements |
| `schema.sql` | Supabase database schema + sample data |

## Features

- 🪪 Authorize visitors (one-time, permanent, employee, vocational)
- 🚗 Register vehicles with Quick Pass numbers
- 🔧 Submit and track maintenance requests
- 📢 Community announcements
- 💳 Fee tracking and delinquency management
- 🏢 Multi-building unit management
- 🌐 Bilingual (English / Spanish)

## Setup

### 1. Supabase
1. Create a free project at [supabase.com](https://supabase.com)
2. Go to **SQL Editor** and run `schema.sql`
3. Go to **Project Settings → API** and copy your Project URL and anon key

### 2. Connect the apps
Open `resident.html` or `admin.html` in a browser. Enter your Supabase URL and anon key on the setup screen.

### 3. Demo mode
Both apps work in **Demo Mode** without a database — great for testing.

## Tech Stack

- React 18 (via CDN, no build step)
- Supabase (Postgres + REST API)
- Vanilla CSS-in-JS

## License

MIT — free to use, modify, and distribute.