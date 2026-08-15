# PiEat-Me · Food Delivery on Pi Network

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![CI](https://github.com/EslaM-X/pi-eats-crypto-now-90/actions/workflows/ci.yml/badge.svg)](https://github.com/EslaM-X/pi-eats-crypto-now-90/actions)

A food delivery marketplace on the Pi Network ecosystem: order from
restaurants or home food providers and pay with Pi cryptocurrency.

> Designed and developed by [EslaM-X](https://github.com/EslaM-X).

---

## What it does

- **Dual marketplace** — separate flows for restaurants and home food providers.
- **Pi payments** — wallet-backed checkout with the Pi SDK.
- **Reward mining** — in-app mining feature.
- **i18n** — multi-language UI (Arabic + English).

## Stack

| Layer | Tech |
| --- | --- |
| UI | React · TypeScript · shadcn/ui |
| Backend | Supabase (services under `src/backend/`) |
| Wallet | Pi Network SDK |

## Quick start

```bash
npm install
npm run dev
```

## Project layout

```
src/
  backend/        backend services (Supabase, integrations)
  components/     UI (cart, restaurant, food-provider, home, mining)
  contexts/       wallet, cart, orders, payment, language
  pages/          app pages
  config/         Pi Network configuration
  services/       API clients
  locales/        translations
```

## License

MIT. See `LICENSE`.
