# IceBreaker

**IceBreaker** adalah permainan board-game digital berbasis web untuk kegiatan *team building*. Seorang **Host** membuat sesi permainan, lalu **Peserta** bergabung via QR code atau kode ruangan. Tim-tim bergantian melempar dadu, bergerak di papan, dan menyelesaikan tantangan (_challenge_) bertipe **Move**, **Talk**, **Create**, atau **Wildcard**.

## Instalasi & Setup
### 1. Clone Repository

```bash
git clone <URL_REPOSITORY>
cd ice_breaker
```

### 2. Setup Database (PostgreSQL)
#### a. Buat database baru

```bash
# Masuk ke psql
psql -U postgres

# Di dalam psql, buat database
CREATE DATABASE icebreaker;

# import db.sql
psql -U postgres -d icebreaker -f "path/to/project/folder/db.sql"
```

### 3. Setup Backend

```bash
# Masuk ke folder backend
cd backend

# Install dependencies
npm install

# Kembali ke root
cd ..
```

### 4. Setup Frontend (UI)

```bash
cd ui
npm install
cd ..
```

---

## ▶️ Menjalankan Aplikasi

### Frontend (Development Mode)

```bash
cd ui

# Menggunakan npm
npm run dev

# ATAU menggunakan pnpm
pnpm dev
```

Frontend akan berjalan di **http://localhost:3000**
