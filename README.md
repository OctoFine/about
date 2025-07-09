OctoFine – Financial Management Platform (WIP)
OctoFine is a web-based financial management tool tailored for self-employed professionals and small businesses. It helps track income, expenses, categories, and generate insights for better decision-making.

Currently, we're working on the authentication subsystem as the foundation of the platform.

✅ Features (implemented so far)

- User registration & login

- JWT-based access and refresh tokens

- User fingerprint validation (browser + OS + IP)

- Token refresh endpoint

- Modular FastAPI backend architecture

🔧 Tech Stack
Backend:

- FastAPI (Python)

- SQLAlchemy + PostgreSQL

- python-jose (JWT tokens)

- passlib (argon2 hashing)

- dotenv, user-agents

🔜 Next Steps

- Build core models: Category, Transaction, Budget

- Analytics API for monthly & category-based breakdown

- Upgrade frontend to React SPA

- Export/Import (CSV, Excel)

- Multi-user support with roles

Our Goal:
Create a secure, modern, and intuitive tool for individual professionals and small businesses to track finances, analyze spending, and stay in control of their money.
