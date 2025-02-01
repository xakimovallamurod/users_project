# CSV va JSON Ma'lumotlarini Boshqarish Funksiyalari

## Functions

- **`read_csv(file_path)`**  
  - **Vazifa**: CSV faylini o‘qish va uning tarkibini `DictReader` yordamida lug‘at (dictionary) shaklida qaytarish.  
  - **Izoh**: Ushbu funksiya CSV faylini o‘qish uchun ishlatiladi va har bir satrni lug‘at sifatida qaytaradi.

- **`csv_to_json(file_path, data)`**  
  - **Vazifa**: CSV formatidagi ma'lumotlarni JSON formatiga o‘zgartirish.  
  - **Izoh**: CSV faylini JSON faylga saqlash uchun ishlatiladi. CSV ma'lumotlari dictionary formatida JSON faylga yoziladi.

- **`json_data_all(file_path)`**  
  - **Vazifa**: JSON faylini o‘qish va barcha foydalanuvchi ma'lumotlarini qaytarish.  
  - **Izoh**: JSON faylidan barcha foydalanuvchi ma'lumotlarini o‘qib, ularni lug‘at (dictionary) sifatida qaytaradi.

- **`first_name_all(data)`**  
  - **Vazifa**: Barcha foydalanuvchilarning **first_name** (ism)larini olish.  
  - **Izoh**: Foydalanuvchilarning ismlarini ro‘yxat sifatida qaytaradi.

- **`last_name_all(data)`**  
  - **Vazifa**: Barcha foydalanuvchilarning **last_name** (familiya)larini olish.  
  - **Izoh**: Foydalanuvchilarning familiyalarini ro‘yxat sifatida qaytaradi.

- **`gender_male_count(data)`**  
  - **Vazifa**: Erkak foydalanuvchilarni sanash.  
  - **Izoh**: Foydalanuvchilar orasida erkaklarning sonini hisoblaydi.

- **`gender_female_count(data)`**  
  - **Vazifa**: Ayol foydalanuvchilarni sanash.  
  - **Izoh**: Foydalanuvchilar orasida ayollarning sonini hisoblaydi.

- **`get_all_domen_name(data)`**  
  - **Vazifa**: Domen nomlarini olish va takrorlanmas domenlar ro‘yxatini qaytarish.  
  - **Izoh**: Har bir foydalanuvchining email manzilidan domen nomini ajratib, faqat takrorlanmas domenlarni qaytaradi. Masalan: `username@gmail.com` -> `gmail`.

- **`get_job(data, job)`**  
  - **Vazifa**: Kasbi ma'lum bo‘lgan foydalanuvchilarni olish.  
  - **Izoh**: Foydalanuvchilarning kasbi berilgan qiymatga teng bo‘lganlarni qaytaradi. Masalan, agar `job = "Engineer"`, u holda barcha "Engineer" kasbiga ega foydalanuvchilar qaytariladi.

---
