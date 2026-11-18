# Inventory Management System - Lab 3 (Alternative)

This version implements the same Assignment 3 requirements with a different folder structure, API naming, field names, validation style, and report responses.

## Run
1. Install Node.js and MongoDB.
2. Open this folder in VS Code.
3. `npm install`
4. Copy `.env.example` to `.env`
5. `npm start`

## Postman
Base URL: http://localhost:3000

POST /api/inventory
GET /api/inventory
GET /api/inventory/:id
PUT /api/inventory/:id
PATCH /api/inventory/:id/stock
DELETE /api/inventory/:id
GET /api/reports/low-stock
GET /api/reports/category-summary

Example POST body:
{
  "productName":"Modern Sofa",
  "code":"SOFA-101",
  "category":"Sofas",
  "price":19999,
  "stock":8,
  "reorderLevel":3,
  "description":"Three-seater fabric sofa"
}
## API Testing Screenshots
<img width="1917" height="1078" alt="Screenshot 2026-11-18 205418" src="https://github.com/user-attachments/assets/9d96ab2e-5d37-4aab-a657-df2cbf8f4594" />
<img width="1917" height="1078" alt="Screenshot 2026-11-18 205333" src="https://github.com/user-attachments/assets/837ff9aa-e6fd-417b-9efe-0e2813bd7bc2" />
<img width="1917" height="1078" alt="Screenshot 2026-11-18 205312" src="https://github.com/user-attachments/assets/009b2e0a-7b7e-4e9f-a8ef-de31a5e81dae" />
<img width="1917" height="1078" alt="Screenshot 2026-11-18 205227" src="https://github.com/user-attachments/assets/b65dfd37-0891-4dd6-ba42-205a5990205b" />
<img width="1917" height="1078" alt="Screenshot 2026-11-18 204957" src="https://github.com/user-attachments/assets/bb9f5eb4-0e49-4d07-a76d-dff1e7723053" />




