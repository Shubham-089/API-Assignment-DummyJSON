# 💼 Dummy JSON Products API (Postman Collection)

This repository contains a Postman API collection for interacting with the [Dummy JSON Products API](https://dummyjson.com). It includes endpoints for performing CRUD operations such as fetching products, searching, adding, updating, and deleting a product.

---

## 🚀 Getting Started

To get started with this API collection:

1. Clone this repository.
2. Open **Postman**.
3. Import the provided collection file:  
   `Dummy JSON Products API.postman_collection.json`
4. Run the requests and explore/test the API behavior.

---

## 📦 API Endpoints Covered

### 1. 🔍 Get All Products

- **Method:** `GET`  
- **URL:** `https://dummyjson.com/products`  
- **Description:** Returns a list of all products.

---

### 2. 📱 Search Products by Name

- **Method:** `GET`  
- **URL:** `https://dummyjson.com/products/search?q=phone`  
- **Description:** Search for products that match the query string (e.g., `phone`).

---

### 3. 📦 Get Product by ID

- **Method:** `GET`  
- **URL:** `https://dummyjson.com/products/1`  
- **Description:** Get details of a single product with ID `1`.

---

### 4. ➕ Add New Product

- **Method:** `POST`  
- **URL:** `https://dummyjson.com/products/add`  
- **Body (JSON):**
```json
{
  "title": "Wireless Headphones",
  "price": 129,
  "description": "Noise-cancelling over-ear headphones",
  "category": "audio"
---
}
###### 4.🛠 Tools Used
-Postman

-📂 Folder Structure
Dummy-JSON-Products-API/
├── 🗄️ README.md
└── 🗄️ Dummy JSON Products API.postman_collection.json
