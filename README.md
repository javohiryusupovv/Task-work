# 🚀 Polygon2 — Users CRUD + Map Polygon Drawing (React + TypeScript)

Ushbu loyiha foydalanuvchilar uchun **CRUD tizimi** va **Leaflet asosida polygon chizish** xarita modullaridan iborat.  
Loyiha to‘liq **React + TypeScript**, **Zustand**, **Shadcn UI**, **IndexedDB** va **Leaflet** yordamida qurilgan.

---

# 📦 Texnologiyalar

| Yo‘nalish | Texnologiya |
|----------|-------------|
| Frontend | React + TypeScript |
| UI Kit   | Tailwind CSS + Shadcn UI |
| State    | Zustand (persist bilan) |
| Storage  | IndexedDB |
| Forms    | React-Hook-Form + Zod |
| Maps     | Leaflet + React-Leaflet |
| Linting  | ESLint + Prettier |
| Build    | Next.js App Router |

---

## ⚙️ O‘rnatish (Installation)

Loyihani ishga tushirishdan oldin **Node.js v20.11.1** versiyasini o‘rnatishingiz kerak.

#### 🔧 Node.js 20.11.1 o‘rnatish (NPM orqali)

```sh
npm install
node version - 20.11.1
```

#### 📥 Repo’ni ko‘chirib olish (Clone)
```sh
git clone https://github.com/javohiryusupovv/Polygon-and-Users---task.git 
cd polygon2
```

### 📦 Paketlarni o‘rnatish
```sh
npm install
```

### ▶️ Development serverni ishga tushirish
```sh
npm run dev
```

### Brauzer orqali ko‘rish:
```sh
http://localhost:3000
```

## 📁 Loyiha Strukturasi

```bash
src/
 ├── app/
 │   ├── users/
 │   │     ├── components/          # User table, modals, search UI
 │   │     └── page.tsx             # Users CRUD sahifasi
 │   │
 │   ├── map/
 │   │     ├── components/          # Polygon drawing UI (Leaflet)
 │   │     └── page.tsx             # Xarita sahifasi
 │   │
 │   └── layout.tsx                 # Root layout (App Router)
 │
 ├── lib/
 │   ├── store.ts                   # Zustand global state
 │   ├── db.ts                      # IndexedDB CRUD helperlar
 │   └── schemas/
 │         └── userSchema.ts        # Zod validatsiya sxemasi
 │
 ├── hooks/
 │   └── useDebounce.ts             # Debounce custom hook
 │
 ├── components/
 │   ├── ui/                        # Shadcn UI komponentlari
 │   └── shared/                    # Skeleton, Spinner, Confirm modal
 │
 └── styles/
     └── globals.css                # Global Tailwind style




