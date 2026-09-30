# FashionPOS — o'rnatuvchi va yangilanishlar

Kiyim do'koni uchun kassa dasturi. Bu repoda **faqat tayyor dastur fayllari** turadi.

## O'rnatish

1. [**Releases**](../../releases/latest) bo'limidan oxirgi `FashionPOS-Setup-X.Y.Z.exe` faylini yuklab oling.
2. Do'kondagi asosiy kompyuterda (Windows 10/11, 64-bit) ishga tushiring → "Далее" → "Установить".
3. Ish stolidagi **FashionPOS** belgisini bosing.

PostgreSQL bazasi o'rnatuvchi ichida bor. Internet faqat yangilanishlar uchun kerak.

## Yangilash

Dasturda: **Sozlamalar → Tizim → "Yangilanishni tekshirish" → "Yangilash"**.
Server yangi versiyani shu repodan o'zi yuklab oladi, avval zaxira nusxa oladi va 1 daqiqada qayta ishga tushadi.

## Fayllar

| Fayl | Nima uchun |
|---|---|
| `FashionPOS-Setup-X.Y.Z.exe` | birinchi o'rnatish (yoki ustidan qayta o'rnatish — ma'lumotlar saqlanadi) |
| `fashionpos-update.zip` + `.sha256` | dastur ichidagi avtomatik yangilanish uchun |
