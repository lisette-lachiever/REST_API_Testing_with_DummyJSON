
---

# REST API Testing with Postman – Assignment

## Overview

This repository contains a Postman collection and supporting documentation for testing RESTful APIs using **DummyJSON** as the target API.
The project demonstrates **authentication**, **CRUD operations**, **environment variables**, and **automated testing** using Postman.

---

## API Information

* **API Provider:** DummyJSON
* **Base URL:** `https://dummyjson.com`
* **Authentication:** Token-based (Bearer Token)
* **API Documentation:** DummyJSON Docs

---

## Repository Contents

```
├── README.md
├── Documentation.pdf             # Detailed assignment documentation
├── DummyJSON_Collection.json     # Postman collection export
└── DummyJSON_Environment.json    # Postman environment export
```

---

## Environment Variables

| Variable Name   | Description                            |
| --------------- | -------------------------------------- |
| `base_url`      | API base URL (`https://dummyjson.com`) |
| `auth_token`    | Auto-saved access token                |
| `refresh_token` | Auto-saved refresh token               |
| `post_id`       | Auto-saved id
---

## Implemented Endpoints

### Authentication

* **POST** `{{base_url}}/auth/login`
  → User login and token generation

### CRUD Operations on Posts

* **POST** `{{base_url}}/posts/add`
  → Create a new post

* **GET** `{{base_url}}/posts/1`
  → Retrieve a post by ID

* **PATCH** `{{base_url}}/posts/1`
  → Update an existing post

* **DELETE** `{{base_url}}/posts/1`
  → Delete a post *(simulated)*

---



