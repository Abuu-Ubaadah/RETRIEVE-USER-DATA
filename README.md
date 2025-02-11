# README: Macam Mana Get Data User Gunakan Bearer Token ?

Tengok Ni Betul-betul!

## **Struktur Folder Juga File Penting**

```
├── app
│   └── Http
│         └── Controllers
│                      └── Api
│                           └── AuthController.php
└── routes
    └── api.php 
```

---

## **Caranya**

### **1. Controller: `AuthController.php`**
Tambah File Baru Tuk Dapat Data User Yang Tengah Login Kat `AuthController.php`.. Pada Case Ni, Ana Guna Method me().

### **2. Route: `api.php`**
Tambahlah Route Tuk User Kat `routes/api.php`:

---

## **Testing Guna Insomnia**
1. Gunakan Bearer Token untuk setiap permintaan ke endpoint CRUD dan user.
2. Contoh endpoint:
   - `GET /api/categories` untuk mendapatkan semua kategori.
   - `POST /api/categories` untuk membuat kategori baru.
   - `PUT /api/categories/{id}` untuk memperbarui kategori.
   - `DELETE /api/categories/{id}` untuk menghapus kategori.
   - `GET /api/user` untuk mendapatkan data user yang sedang login.

---

sql```
GET http://127.0.0.1:8000/api/user
```
