# FigBackend-Server

> [!WARNING]
> ⚠️ **Status**: This is project is currently **under software development**.

Backend server build with **Node.js**.

---

# 📦 Requirements

- **Node.js**
- **Domain**
- **Server Host** (VPS / Cloud Server / Dedicated Server)
- **Cloudflare** or any service that can convert **HTTP → HTTPS**

---

# ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/DAmyDev/FigBackend-Server.git
cd FigBackend-Server
```

### 2. Install dependencies

```bash
npm install
```

---

# ▶️ Usage

Start the normally with Node.js:

```bash
npm start
```

---

## 📊 Optional: Run with PM2 

### Install PM2 global

```bash
npm install -g pm2
```

### Start the server with PM2

```bash
pm2 start index.js --name FigBackend-Server
```

### View logs

```bash
pm2 logs FigBackend-Server
```

### Monitor

```bash
pm2 monit
```

### Restart the server

```bash
pm2 restart FigBackend-Server
```

### Stop the server

```bash
pm2 stop FigBackend-Server
```
