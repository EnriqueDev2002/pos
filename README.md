# Ferretería POS

Point of Sale system for a hardware store, built as a real-world project to manage in-store sales, inventory and basic reporting.

## Tech Stack

- **Framework:** Next.js 15 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS + shadcn/ui
- **Database:** PostgreSQL with Drizzle ORM
- **Authentication:** Better-Auth
- **Deployment:** Vercel + Neon

## Status

🚧 Work in progress

## Planned Features

### Phase 1 — Core POS

- [ ] User authentication (admin and cashier roles)
- [ ] Product CRUD with categories, SKU and stock
- [ ] Sales register with cart and checkout
- [ ] Automatic stock deduction on sale
- [ ] Basic sales history

### Phase 2 — Pro Features

- [ ] Customer and supplier management
- [ ] Reports (daily, weekly, monthly)
- [ ] Multiple payment methods
- [ ] Receipt printing
- [ ] Cash register open/close with reconciliation

### Phase 3 — Distinctive

- [ ] Fine-grained roles and permissions
- [ ] Barcode scanning
- [ ] Multi-location support
- [ ] AI assistant for natural-language reports

## Getting Started

```bash
pnpm install
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## License

MIT
