# Project 2 — Inventory and Order Management API

## Purpose
A small business backend that manages products, stock and orders.

## Minimum features
- Create/update/list products.
- Store SKU, name, price, stock quantity and active status.
- Create customers.
- Create orders with one or more order items.
- Calculate totals on the server; never trust a client-supplied total.
- Reject orders if stock is insufficient.
- Reduce stock when an order is successfully placed.
- Use a database transaction so a failed order does not leave partial stock changes.
- List orders and inspect order details.
- Add tests for normal and failure cases.

## Suggested tables
- products
- customers
- orders
- order_items

## Suggested routes
- POST /products
- GET /products
- PATCH /products/{product_id}
- POST /customers
- POST /orders
- GET /orders
- GET /orders/{order_id}

## Acceptance checklist
- [ ] Product CRUD works.
- [ ] Customer creation works.
- [ ] Order totals are calculated server-side.
- [ ] Insufficient stock is rejected.
- [ ] Failed order rolls back stock changes.
- [ ] Tests cover success and failure paths.
- [ ] README explains data model, setup and sample requests.
