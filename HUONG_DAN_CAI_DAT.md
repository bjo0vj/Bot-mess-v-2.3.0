# HƯỚNG DẪN CÀI ĐẶT MÔI TRƯỜNG CHẠY BOT

---

## BƯỚC 1 — CÀI NODE.JS

1. Vào: https://nodejs.org/en/download
2. Tải bản **LTS** (Windows Installer .msi) → chạy file cài
3. **Tick chọn "Add to PATH"** (rất quan trọng)
4. Kiểm tra:
   ```
   node -v
   npm -v
   ```

---

## BƯỚC 2 — CÀI PYTHON

1. Vào: https://www.python.org/downloads/
2. Tải bản mới nhất → chạy file cài
3. **Tick "Add Python to PATH"** (rất quan trọng)
4. Kiểm tra: `python --version`

---

## BƯỚC 3 — CÀI GIT
"Bước này bỏ qua các bạn hoàn toàn ko cần nha"
1. Vào: https://git-scm.com/download/win
2. Tải → cài → nhấn Next hết
3. Kiểm tra: `git --version`

---

## BƯỚC 4 — CÀI VISUAL STUDIO BUILD TOOLS

1. Tải: https://aka.ms/vs/17/release/vs_BuildTools.exe
2. Tick **"Desktop development with C++"** → Install

---

## BƯỚC 5 — CÀI DEPENDENCIES CHO BOT

Mở CMD, chạy lần lượt:
```cmd
cd "C:\Users\rbux7\Downloads\Bot-mess-v-2.3.0-main\Bot-mess-v-2.3.0-main\BOT\000"
npm install --ignore-scripts
npm rebuild better-sqlite3
npm rebuild sqlite3
```

> Lệnh 1: cài tất cả package (bỏ qua compile canvas)
> Lệnh 2-3: build riêng các module database

---

## BƯỚC 6 — CHẠY BOT

```cmd
npm start
```

---

> ⚠️ Key admin mặc định: **2803** (trong file key.txt) — toàn quyền, không cần nhập lại.
