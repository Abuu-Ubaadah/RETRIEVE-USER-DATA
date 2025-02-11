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

sql```
GET http://127.0.0.1:8000/api/user
```

---
