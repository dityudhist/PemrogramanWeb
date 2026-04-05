# LAB PEMROGRAMAN WEB

## Teknologi yang Digunakan

Project ini menggunakan teknologi berikut:

* Next.js 
* React
* TypeScript
* Tailwind CSS
* PostgreSQL
* Vercel Postgres
* Heroicons
* clsx

---


## Fitur yang Sudah Diimplementasikan

### Chapter 1–3 (UI)

Fitur yang telah dibuat:

* Setup project Next.js
* Implementasi Tailwind CSS
* Optimasi font menggunakan next/font
* Optimasi image menggunakan next/image
* Responsive design
* Custom typography

---

### Chapter 4 (Creating layouts and Pages)

Fitur:

* Nested routing
* Dashboard layout
* Sidebar navigation
* Customers page
* Invoices page
* Reusable layout system

Routing yang tersedia:

```
/dashboard
/dashboard/customers
/dashboard/invoices
```

---

### Chapter 5 (Navigation System)

Fitur:

* Client-side navigation menggunakan Next Link
* Active navigation state
* Dynamic sidebar navigation
* Conditional styling menggunakan clsx
* usePathname hook

---

### Chapter 6 (Database Setup)

Fitur:

* PostgreSQL database integration
* Environment variables configuration
* Database seeding
* Initial data setup

Database berisi:

* Customers
* Invoices
* Revenue data

---

## Cara Menjalankan Project

### 1 Install dependencies

```
pnpm install
```

---

### 2 Setup environment variables

Buat file:

```
.env.local
```

Isi dengan:

```
POSTGRES_URL=
POSTGRES_USER=
POSTGRES_PASSWORD=
POSTGRES_HOST=
POSTGRES_DATABASE=
```

---

### 3 Jalankan development server

```
pnpm dev
```

Buka:

```
http://localhost:3000
```

---

### 4 Seed database

Buka:

```
http://localhost:3000/seed
```

---

## Pembelajaran yang Didapat

Melalui project ini dipelajari:

* Modern Next.js architecture
* App Router system
* Server vs Client components
* File-based routing
* Layout pattern
* Database integration
* SQL query fundamentals
* Component modularization

---
