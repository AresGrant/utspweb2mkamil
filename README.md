# 📌 UTS Pemrograman Web 2 - Task Manager API

## 👤 Identitas
**Nama:** Muhammad Kamil Marzuqi Aziz  
**Mata Kuliah:** Pemrograman Web 2  
**Kelas:** TIF K 23B  
**NIM:** 25552012061  

## 📖 Deskripsi
Project ini merupakan implementasi REST API menggunakan Express.js dengan database PostgreSQL.  
API ini digunakan untuk mengelola data tugas (Task Manager) dan mendukung operasi CRUD (Create, Read, Update, Delete).  

Selain itu, sistem juga dilengkapi dengan:
- Middleware logging untuk mencatat request
- Validasi input pada endpoint POST
- Error handling (status 400 & 404)

## ⚙️ Teknologi yang Digunakan
- Node.js  
- Express.js  
- PostgreSQL  
- pg (Node.js PostgreSQL client)  
- dotenv  
- nodemon  

## 🚀 Endpoint
- GET /tasks  
- GET /tasks/:id  
- POST /tasks  
- PUT /tasks/:id  
- DELETE /tasks/:id  
