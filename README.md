# 🚀 Postman API Testing Project

This repository contains a collection of **API testing projects created in Postman**, covering a wide range of real-world testing scenarios.  
The goal of this project is to demonstrate practical skills in:

- API testing (manual + automated)
- API chaining
- Authorization methods
- Dynamic data generation
- Pre-request scripting
- JSON Schema validation
- File upload testing
- Environment variables
- CRUD operations
- Working with mock data

All collections are exported directly from Postman as `.json` files and can be imported into any Postman workspace.

---

# 📂 Repository Structure

```
postman-api-testing/
├── collections/
│   ├── API Chaining.json
│   ├── Gorest Chaining.json
│   ├── Authorization Types.json
│   ├── File Upload.json
│   ├── CRUD ReqRes.json
│   ├── Mock Data Generation.json
│   ├── Variables.json
│   └── Pre-request Scripts.json
└── environments/
    ├── QA test.postman_environment.json
    └── reqres-demo-env.postman_environment.json
```

---

# 📦 Collections Overview

## 🔗 **1. API Chaining**
Demonstrates:
- Creating a resource (POST)
- Saving the returned ID to environment variables
- Retrieving the same resource (GET)
- Deleting the resource (DELETE)
- Automated tests:
  - status codes  
  - headers  
  - response time  
  - JSON schema validation  
  - value validation  

This simulates a real backend testing workflow.

---

## 🧪 **2. Gorest Chaining**
Advanced chaining using the GoREST API.

Features:
- Dynamic email & username generation
- Pre-request scripts
- Environment variables
- Full CRUD flow:
  - Create user  
  - Get user  
  - Update user  
  - Delete user  
- Automated validation of returned values

This collection shows strong understanding of API automation logic.

---

## 🔐 **3. Authorization Types**
Covers multiple authentication mechanisms:

- Basic Auth  
- Digest Auth  
- Bearer Token  
- API Key  
- OAuth 2.0 (authorization flow)

This demonstrates knowledge of real-world API security.

---

## 📁 **4. File Upload**
Tests file upload endpoints:

- Single file upload  
- Multiple file upload  
- multipart/form-data handling  

Useful for testing systems that accept attachments.

---

## 🧱 **5. CRUD Operations (ReqRes API)**
Classic REST operations:

- GET  
- POST  
- PUT  
- DELETE  

Shows understanding of RESTful API structure and request/response validation.

---

## 🎲 **6. Mock Data Generation**
Uses Postman dynamic variables (Faker.js):

- Random names  
- Random addresses  
- Random credit card numbers  
- Random booleans, integers, GUIDs  
- Pre-request scripts for transforming data  
- Cookie validation tests  

Great for testing with unpredictable data.

---

## 🧩 **7. Variables**
Demonstrates:

- Local variables  
- Environment variables  
- Global variables  
- Pre-request variable assignment  
- Using variables in URLs and bodies  

---

## ⚙️ **8. Pre-request Scripts**
Shows execution order of scripts:

- Collection-level  
- Folder-level  
- Request-level  

Useful for advanced automation and setup logic.

---

# 🌍 Environments

## **QA test**
Contains:
- API URLs  
- IDs  
- tokens  
- dynamic email variables  

## **reqres-demo-env**
Contains:
- API key for ReqRes demo environment  

---

# 🧠 What I Learned

- How to test REST APIs using Postman  
- How to chain requests using environment variables  
- How to write automated tests in JavaScript  
- How to validate JSON schemas  
- How to work with different authorization types  
- How to generate dynamic test data  
- How to use pre-request scripts  
- How to test file uploads  
- How to structure API testing projects  

---

# ▶️ How to Use

1. Clone the repository  
2. Import any `.json` collection into Postman  
3. Import the matching environment file  
4. Run requests manually or via Collection Runner  
5. Observe automated tests and chaining logic  

---

# 📌 Summary

This project demonstrates practical, real-world API testing skills using Postman.  
It includes everything from basic CRUD operations to advanced chaining, authorization, dynamic data, and automation.

