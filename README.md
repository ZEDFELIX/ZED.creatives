# Legacy ZED Gift Shop Copy

This repository is retained as a historical/legacy ZED Gift Shop implementation.

**Canonical Gift Shop repository:** [ZEDFELIX/zed-gift-shop](https://github.com/ZEDFELIX/zed-gift-shop)

Do not split new Gift Shop development between this repository and the canonical repository.

## Legacy stack

This copy uses Next.js + React + TypeScript + Tailwind with Prisma/PostgreSQL-oriented architecture and PWA support.

Production integrations must never fake success: database, authentication, M-PESA credentials/callbacks, persistent orders, inventory and uploads require real deployment configuration.

For all new Gift Shop development, use `ZEDFELIX/zed-gift-shop`.
