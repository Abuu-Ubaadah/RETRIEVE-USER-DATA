# README: Macam Mana Get Data User Gunakan Bearer Token ?

Tengok Ni Betul-betul Ya..

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

## **Langkah-langkahnya:**

### **1. Controller: `AuthController.php`**
Tambah File Baru Tuk Dapat Data User Yang Tengah Login Kat `AuthController.php`.. Pada Case Ni, Ana Guna Method me().

### **2. Route: `api.php`**
Tambahlah Route Tuk User Kat `routes/api.php`:

---

## **Testing Guna Insomnia:**

- Kat URL:
```sql
GET http://127.0.0.1:8000/api/user
```

- Kat Headers:
```makefile
Authorization: Bearer <your-token>
Accept: application/json
```

---

```css
Disusun oleh [Abuu Ubaadah a.k.a Muhammad Yaziid Ash-Shabriyy]
```
