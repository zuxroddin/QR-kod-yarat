# TopQir uslubidagi landing sahifa

Ushbu loyiha `topqir.uz`ga o'xshash (lekin to'liq nusxa emas) dizaynda tayyorlangan oddiy landing sahifa.

## Ishga tushirish

```bash
python3 -m http.server 8080
```

Brauzerda oching: `http://localhost:8080`

## Saytni internetga joylash (tezkor yo'l)

### 1) Domen va hosting tayyor bo'lsin
- Domeningiz bo'lsin (masalan, `sizningsaytingiz.uz`)
- Oddiy shared hosting bo'lsa ham yetadi

### 2) Fayllarni serverga yuklang
Ushbu 3 ta faylni yuklang:
- `index.html`
- `styles.css`
- `README.md` (ixtiyoriy)

Agar cPanel ishlatsangiz:
1. `File Manager`ga kiring
2. `public_html` papkasini oching
3. Loyiha fayllarini yuklang
4. `index.html` ildizda tursin

### 3) Domenni hostingga bog'lang
- Domen DNS'ida `A record` ni hosting IP manziliga yo'naltiring
- Odatda 5 daqiqadan 24 soatgacha vaqt oladi

### 4) SSL yoqing
- cPaneldagi `SSL/TLS` yoki `Let's Encrypt` orqali bepul sertifikat yoqing
- Sayt `https://` bilan ochilishi kerak

### 5) Yangilash tartibi
- Dizaynni yangilaganda `index.html` va `styles.css` ni qayta upload qiling
- Keshlangan bo'lsa brauzerda `Ctrl+F5` qiling
