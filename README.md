# Shop API

A simple Django + Stripe shop project running in Docker.  
It lets you browse items, create orders, add items, apply discounts/taxes, and pay using Stripe Checkout.

---

## How to Run

1. Make your own `.env` file based on `.env.example`.

2. Start the project:

```
docker-compose up --build
```

3. Create a superuser

```
docker-compose exec shop_api python manage.py createsuperuser
```

This will automatically:
- install dependencies  
- run migrations  
- fill the database with sample data  
- start the server on **http://localhost:8000**


