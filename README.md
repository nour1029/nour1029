# Hi, I'm Nour Mohamed

Python / Django backend engineer from Egypt. I design and build multi-tenant SaaS products: the product itself, the architecture and database, the backend, and the servers it runs on.

## What I've built

**Deal CRM**: multi-tenant CRM for real-estate companies, used every day by 20+ companies.
- Co-founder & CTO: designed the product and the architecture from scratch, built most of the backend, own DevOps, and lead the development teams.
- Django + PostgreSQL with schema-per-tenant isolation, role and field-level permissions, Celery/Redis background jobs.
- Facebook Lead Ads and WhatsApp Cloud API integrations, with automatic lead assignment.

**QIO Cloud**: multi-tenant ERP SaaS on ERPNext.
- Built the SaaS layer: plans, Stripe subscriptions, and tenants.
- A separate FastAPI service creates a new ERPNext site for each customer in 2-3 minutes and runs on several servers; calls retry safely and are idempotent.

Both are private client systems. I'm happy to show a live demo on a call.

## Stack
- **Backend:** Python, Django, Django REST Framework, FastAPI, Celery
- **Data:** PostgreSQL, Redis, MariaDB
- **DevOps:** Docker, Docker Compose, Nginx, Linux servers, GitHub Actions CI/CD, AWS (EC2, S3, RDS)
- **Testing:** pytest, pytest-django
- **Integrations:** Stripe, PayPal, WhatsApp Cloud API, Facebook Lead Ads, webhooks, OAuth
- **Frontend:** JavaScript, HTML/CSS, Tailwind CSS, React (basic)

## Contact
[LinkedIn](https://www.linkedin.com/in/nour-mohamed-644343246/)
