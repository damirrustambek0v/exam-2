# Astrum IT Academy H4ck3rs Blog Platform

Bu loyiha blog platformasi bo'lib, foydalanuvchilar yangi maqolalar qo'shishi va boshqarishi uchun mo'ljallangan. Sayt "Astrum IT Academy H4ck3rs" nomi ostida ishlaydi va quyidagi funksiyalarni taqdim etadi:

## Xususiyatlar
- **Maqolalar qo'shish:** Foydalanuvchilar maqola sarlavhasi, kategoriya, qisqa mazmun, to'liq matn va muallif nomini kiritishi mumkin.
- **Kategoriyalarni tanlash:** Maqolalar mos kategoriya bo'yicha ajratiladi.
- **Foydalanuvchi interfeysi:** Oddiy va intuitiv dizayn.

## Talablar
Ushbu loyihani ishga tushirish uchun quyidagi dasturlar va kutubxonalar kerak:

- Python (3.9 yoki undan yuqori versiya)
- Django (4.0 yoki undan yuqori versiya)
- Bootstrap (frontend uchun)

## O'rnatish
Loyihani o'rnatish uchun quyidagi qadamlarni bajaring:

1. **Repository ni klonlash:**
   ```bash
   git clone https://github.com/damirrustambek0v/exam-2.git
   cd exam-2
   ```

2. **Virtual muhitni yaratish va ishga tushirish:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows uchun: venv\Scripts\activate
   ```

3. **Kerakli kutubxonalarni o'rnatish:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Ma'lumotlar bazasini sozlash:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Serverni ishga tushirish:**
   ```bash
   python manage.py runserver
   ```
   Server localhost:8000 manzilida ishga tushadi.

## Foydalanish
1. Brauzer orqali [http://127.0.0.1:8000](http://127.0.0.1:8000) manziliga o'ting.
2. **"Add New Article"** tugmasini bosing.
3. Maqola ma'lumotlarini to'ldiring:
   - Sarlavha
   - Kategoriya
   - Qisqa mazmun
   - To'liq matn
   - Muallif nomi
4. **"Submit Article"** tugmasini bosing.

## Dizayn
Frontend qora va yashil rang kombinatsiyasi bilan ishlangan, oddiy va futuristik ko'rinishni ta'minlaydi.

## Muammolarni bartaraf etish
Agar sayt ishlamasa, quyidagilarni tekshiring:
- Python va Django versiyalari talabga mos keladimi.
- Kutubxonalar to'g'ri o'rnatilganmi.
- Ma'lumotlar bazasi sozlamalari to'g'ri kiritilganmi.

## Loyiha muallifi
- **Astrum IT Academy**

## Litsenziya
Bu loyiha [MIT License](LICENSE) ostida taqdim etiladi.
