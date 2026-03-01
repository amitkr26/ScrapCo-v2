# ScrapCo Platform

ScrapCo is a full-scale two-sided scrap marketplace platform designed for hyperlocal operations (Narnaul, Gorakhpur, Singhana) and scalable to multi-city expansion.

This repository contains the complete production infrastructure:

- 🌐 Web (Next.js)
- 📱 Mobile (Expo)
- 🔐 Backend API (NestJS)
- ⚙️ Worker (BullMQ Dispatch Engine)
- 🗄 PostgreSQL (Supabase)
- 🚀 Redis Queue
- 🔄 Event-driven architecture
- 🔒 Secure & role-based access control

---

## 🏗 Architecture Overview

Seller → Create Pickup  
→ Dispatch Job Enqueued  
→ Worker selects vendor  
→ Offer Created  
→ Vendor Accepts  
→ Assignment Saved  
→ Pickup Lifecycle Tracked  
→ Transaction Finalized  

No in-memory dispatch logic.
No polling-based updates.
Horizontally scalable.

---

## 🧱 Monorepo Structure
