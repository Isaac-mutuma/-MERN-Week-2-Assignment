# Express.js Product API

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file based on `.env.example` and add your API key.
4. Start the server:
   ```
   node server.js
   ```

## API Endpoints

### GET /api/products
- Optional query params: `?category=electronics&page=1&limit=5`

### GET /api/products/:id

### POST /api/products
```json
{
  "name": "Phone",
  "description": "Smartphone",
  "price": 500,
  "category": "electronics",
  "inStock": true
}
```

### PUT /api/products/:id

### DELETE /api/products/:id

### GET /api/products/search?q=phone

### GET /api/products/stats

## Headers
- `x-api-key`: Your API key