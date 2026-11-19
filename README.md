# IceBreaker

**IceBreaker** adalah permainan board-game digital berbasis web untuk kegiatan *team building*. Seorang **Host** membuat sesi permainan, lalu **Peserta** bergabung via QR code atau kode ruangan. Tim-tim bergantian melempar dadu, bergerak di papan, dan menyelesaikan tantangan (_challenge_) bertipe **Move**, **Talk**, **Create**, atau **Wildcard**.

## Installation & Setup
### 1. Clone Repository

```bash
git clone https://github.com/bryanricaldi1408-oss/ice_breaker.git
```

### 2. Setup Database (PostgreSQL)
#### a. Create new Database

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
# Masuk folder ui
cd ui

# Install dependecies
npm install

# Kembali ke root
cd ..
```

---

## How to Run

```bash
# Masuk folder ui
cd ui

# Menggunakan npm
npm run dev
```

Frontend akan berjalan di **http://localhost:3000**
