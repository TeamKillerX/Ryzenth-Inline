# Ryzenth-Inline

**Release Date:** March 26, 2026  
**Version:** Trailer 2  
**Developer:** Unknown (Whitelist only – you can't find me)

---

## What's New?

- **Super Fast Compiler**  
  Python modules are compiled to `.so` (shared object) for ultra-fast performance.  
  Perfect for heavy tasks and instant inline commands.

- **Removed Modules**  
  - `Eval` — For security reasons. Eval is not a toy.  
  - `Broadcast` — Disabled to avoid mass message spam.

- **AI Moderation with AntiEvalDevBot**  
  Only approved developers are whitelisted.  
  If you're not me, access denied.

- **Lightweight & Stable**  
  Optimized for low memory usage and low-latency execution.

---

## Installation Guide

**Requirements:**
- Python 3.11+
- Kurigram 2.x
- Linux (Recommended)
- MongoDB
- `clang` / `gcc` for compiling `.so` files

### 1. Clone the Repo
```bash
git clone https://github.com/TeamKillerX/Ryzenth-Inline.git
cd Ryzenth-Inline
````

### 2. Setup Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 3. Build `.so` Modules (optional)

```bash
gcc -O3 -Wall -shared -std=c11 -fPIC src/module.c -o compiled/module.so
```

### 4. Add Your Environment Variables

Create a `.env` file and fill in your values:

```env
API_ID=your_telegram_api_id
API_HASH=your_telegram_api_hash
BOT_TOKEN=your_bot_token
MONGO_URI=your_mongodb_uri
SESSION_STRING=your_session
```

---

## Coming Soon

> Trailer 3? Maybe... if you can even find me.

---

**Note:**
Ryzenth Inline is a private project. Access is limited.
If you found this, you're already ahead.
