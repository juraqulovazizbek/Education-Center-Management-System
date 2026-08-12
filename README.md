# 🎓 Education Center Management System

> **Modern and comprehensive management system for educational centers**

Education Center Management System — bu o‘quv markazlarining kundalik faoliyatini raqamlashtirish va boshqarishni avtomatlashtirish uchun ishlab chiqilayotgan zamonaviy web-platforma.

Tizim orqali **o‘quvchilar, ustozlar, kurslar, guruhlar, davomat, to‘lovlar, reytinglar va boshqa jarayonlarni** yagona platformadan boshqarish mumkin.

Loyihaning asosiy maqsadi — o‘quv markazidagi ma'lumotlarni tartibli saqlash, boshqaruv jarayonlarini soddalashtirish va har bir foydalanuvchiga o‘z roliga mos imkoniyatlarni taqdim etish.

---

## 🚀 Asosiy imkoniyatlar

Tizim **3 ta asosiy rol** asosida ishlaydi:

* 👨‍🎓 **Student** — O‘quvchi
* 👨‍🏫 **Teacher** — Ustoz
* 👨‍💼 **Admin** — Administrator

Har bir rol uchun alohida imkoniyat va permissionlar mavjud.

---

# 👨‍🎓 Student Panel

O‘quvchi tizimga shaxsiy **login va parol** orqali kiradi.

O‘quvchiga markaz tomonidan account yaratiladi va unga maxsus **Student ID** beriladi.

### Student ma'lumotlari

O‘quvchi profili faqat kerakli ma'lumotlarni o‘z ichiga oladi:

* 🆔 Student ID
* 👤 F.I.Sh.
* 📅 Tug‘ilgan yil
* 📱 O‘zining telefon raqami
* 👨‍👩‍👦 Ota-onasi F.I.Sh.
* 📞 Ota-onasi telefon raqami
* 🏠 Yashash manzili
* 🖼️ Profil rasmi
* 🔐 Login va parol
* 🟢 Faol / 🔴 Nofaol status

> Passport, JSHSHIR va boshqa ortiqcha shaxsiy ma'lumotlar tizimda saqlanmaydi.

### Student quyidagilarni ko‘ra oladi:

* 👤 Shaxsiy profili
* 📚 O‘zining kurslari
* 👥 Guruh ma'lumotlari
* 👨‍🏫 Ustoz ma'lumotlari
* 🗓️ Dars jadvali
* 🕐 Davomat
* 💰 To‘lovlar
* ⚠️ Qarzdorlik
* ⭐ Reyting / baholar
* 📊 O‘zining umumiy statistikasi

Student boshqa o‘quvchilarning ma'lumotlarini ko‘ra olmaydi.

---

# 👨‍🏫 Teacher Panel

Ustoz tizimga kirganda faqat **o‘ziga biriktirilgan kurs va guruhlar** bilan ishlaydi.

### Teacher imkoniyatlari

* 📚 O‘z kurslarini ko‘rish
* 👥 O‘z guruhlarini ko‘rish
* 👨‍🎓 O‘quvchilar ro‘yxatini ko‘rish
* 🕐 Davomat belgilash
* ⭐ O‘quvchilarga baho/reytинг qo‘yish
* 📊 O‘quvchilar natijalarini ko‘rish
* 🗓️ Dars jadvalini ko‘rish

### Teacher cheklovlari

Ustoz:

* ❌ To‘lovlarni boshqara olmaydi
* ❌ Boshqa ustozlarning guruhlarini boshqara olmaydi
* ❌ Admin funksiyalaridan foydalana olmaydi
* ❌ Tizimdagi barcha ma'lumotlarni ko‘ra olmaydi

---

# 👨‍💼 Admin Panel

Admin tizimning barcha qismlarini boshqaradi.

Admin uchun alohida kengaytirilgan dashboard mavjud.

### Admin Dashboard

```text
┌─────────────────────────────────────┐
│ 👨‍🎓 Students          356           │
├─────────────────────────────────────┤
│ 👨‍🏫 Teachers           24           │
├─────────────────────────────────────┤
│ 📚 Courses            18           │
├─────────────────────────────────────┤
│ 👥 Groups             42           │
├─────────────────────────────────────┤
│ 💰 Revenue            85.4 mln      │
├─────────────────────────────────────┤
│ ⚠️ Debts              12.7 mln      │
└─────────────────────────────────────┘
```

### Admin quyidagilarni boshqaradi:

#### 👨‍🎓 Students

* O‘quvchi qo‘shish
* O‘quvchini tahrirlash
* O‘quvchini faol/nofaol qilish
* O‘quvchini qidirish
* Filterlash
* Guruhga qo‘shish
* Guruhdan chiqarish
* Profilini ko‘rish
* Student ID yaratish
* Login/parol yaratish va boshqarish

#### 👨‍🏫 Teachers

* Ustoz qo‘shish
* Ustoz ma'lumotlarini tahrirlash
* Kurs biriktirish
* Guruh biriktirish
* Faol/nofaol qilish

#### 📚 Courses

* Kurs yaratish
* Kursni tahrirlash
* Kurs narxini belgilash
* Kurs davomiyligini belgilash
* Kurs boshlanish/tugash sanasini belgilash
* Kursni faol/nofaol qilish

#### 👥 Groups

* Guruh yaratish
* Kurs biriktirish
* Ustoz biriktirish
* O‘quvchilarni biriktirish
* Xona belgilash
* Dars jadvalini belgilash
* Boshlanish/tugash sanasi
* Guruh statusini boshqarish

#### 💰 Payments

* To‘lovlarni boshqarish
* Oylik to‘lovlarni nazorat qilish
* To‘langan summani ko‘rish
* Qarzdorlikni hisoblash
* To‘lov tarixini ko‘rish
* Umumiy tushumni ko‘rish
* Oylik tushumni ko‘rish

---

# 🆔 Student ID System

Har bir o‘quvchiga tizim tomonidan avtomatik va unikal ID beriladi.

Masalan:

```text
STU-000001
STU-000002
STU-000003
STU-000124
```

Student ID orqali o‘quvchini tezda topish mumkin.

Masalan:

```text
Search: STU-000124
```

Natijada tegishli o‘quvchining profili chiqadi.

---

# 🔎 Search & Filter System

Tizimda qulay qidiruv tizimi mavjud bo‘ladi.

### Student qidirish

```text
STU-000124
```

yoki:

```text
Azizbek
```

yoki:

```text
+99890...
```

### Course qidirish

```text
Python
```

### Filterlar

* Kurs bo‘yicha
* Guruh bo‘yicha
* Ustoz bo‘yicha
* Faol / nofaol
* Qarzdor o‘quvchilar
* To‘lov holati

---

# 📚 Course Management

Kurs quyidagi ma'lumotlarni o‘z ichiga oladi:

* 🆔 Course ID
* 📚 Kurs nomi
* 📝 Description
* ⏳ Kurs davomiyligi
* 💰 Kurs narxi
* 📅 Boshlanish sanasi
* 📅 Tugash sanasi
* 👨‍🏫 Ustoz
* 👥 Guruhlar
* 🟢 Active
* 🔴 Inactive

### Course Status

```text
🟢 ACTIVE
🔴 INACTIVE
🟡 UPCOMING
🔵 COMPLETED
```

---

# 👥 Group Management

Real o‘quv markazida **Course va Group alohida tushuncha** sifatida ishlatiladi.

Masalan:

```text
Python Backend
│
├── PY-01
├── PY-02
└── PY-03
```

Har bir guruhda:

* Kurs
* Ustoz
* O‘quvchilar
* Xona
* Dars kunlari
* Dars vaqti
* Boshlanish sanasi
* Tugash sanasi
* Maksimal o‘quvchilar soni
* Status

saqlanadi.

---

# 🕐 Attendance Management

Har bir dars uchun o‘quvchilarning davomatini boshqarish mumkin.

### Davomat holatlari

```text
✅ Present     — Keldi
❌ Absent      — Kelmagan
🟡 Late        — Kechikdi
🟢 Excused     — Sababli
```

Masalan:

```text
Python Backend — PY-01

Azizbek     ✅ 14:02
Sardor      ❌
Ali         🟡 14:17
Jasur       ✅ 13:58
```

Tizim avtomatik ravishda o‘quvchining davomat foizini hisoblaydi:

```text
Attendance: 94%
```

---

# 💰 Payment Management

Tizimda o‘quvchilarning barcha to‘lovlari nazorat qilinadi.

Har bir to‘lov:

* Student
* Course
* Oy
* Summa
* To‘langan summa
* Qarzdorlik
* To‘lov sanasi
* To‘lov usuli
* Status

bilan bog‘lanadi.

### Misol

```text
Python Backend

Avgust:
Course Price: 1 200 000 so‘m
Paid:         1 200 000 so‘m
Debt:                 0 so‘m
Status:              PAID
```

### Payment Status

```text
✅ PAID
⚠️ PARTIALLY PAID
❌ UNPAID
```

---

# ⚠️ Debt Management

Admin qarzdor o‘quvchilarni alohida ko‘ra oladi.

```text
Student              Debt

Ali Valiyev          400 000 so‘m
Sardor Karimov       200 000 so‘m
Jasur Aliyev         600 000 so‘m
```

Dashboardda:

```text
Total Debt: 12 700 000 so‘m
```

ko‘rsatiladi.

---

# ⭐ Rating & Evaluation

Ustozlar o‘quvchilarning natijalarini baholashi mumkin.

Masalan:

```text
Python       92
Django       87
DRF          95
Homework     90

Overall      91
```

O‘quvchi o‘z reytingini Student Panel orqali ko‘ra oladi.

---

# 🗓️ Schedule Management

Har bir guruh uchun dars jadvali belgilanadi.

Masalan:

```text
Python Backend — PY-01

Monday       14:00 - 16:00
Wednesday    14:00 - 16:00
Friday       14:00 - 16:00
```

Student va Teacher o‘zlariga tegishli dars jadvalini ko‘radi.

---

# 🟢🔴 Active / Inactive System

Tizimdagi asosiy obyektlarda status tizimi mavjud:

* Student
* Teacher
* Course
* Group

Masalan:

```text
Student → ACTIVE
Teacher → ACTIVE
Course  → INACTIVE
Group   → ACTIVE
```

Ma'lumotlarni to‘g‘ridan-to‘g‘ri o‘chirib yuborish o‘rniga ko‘p holatda **active/inactive** tizimidan foydalaniladi.

Bu tarixiy ma'lumotlarni saqlab qolish imkonini beradi.

---

# 🔐 Authentication & Authorization

Tizim **Role-Based Access Control (RBAC)** asosida ishlaydi.

```text
                    AUTH
                     │
       ┌─────────────┼─────────────┐
       ↓             ↓             ↓
   STUDENT        TEACHER        ADMIN
       │             │             │
       ↓             ↓             ↓
  Own profile     Own groups     Everything
  Own courses     Attendance     Students
  Payments        Ratings        Teachers
  Attendance                     Courses
  Rating                         Groups
                                 Payments
                                 Reports
```

Har bir foydalanuvchi faqat o‘z roliga ruxsat berilgan ma'lumot va funksiyalardan foydalanadi.

---

# 🏗️ Project Architecture

Loyiha modulli arxitektura asosida quriladi.

```text
education-center/
│
├── config/
│
├── apps/
│   ├── users/
│   ├── students/
│   ├── teachers/
│   ├── courses/
│   ├── groups/
│   ├── enrollments/
│   ├── attendance/
│   ├── payments/
│   ├── exams/
│   ├── certificates/
│   ├── notifications/
│   └── reports/
│
├── templates/
├── static/
├── media/
├── tests/
├── requirements.txt
├── .env
├── .gitignore
└── manage.py
```

---

# 🗄️ Database Architecture

Asosiy modellarning o‘zaro bog‘lanishi:

```text
User
 │
 ├── Student
 │
 ├── Teacher
 │
 └── Admin

Student
 │
 └── Enrollment
       │
       └── Group
             │
             ├── Course
             ├── Teacher
             └── Attendance

Student
 │
 ├── Payment
 ├── ExamResult
 └── Rating
```

### Asosiy modellar

```text
User
Student
Teacher
Course
Group
Enrollment
Attendance
Payment
Exam
ExamResult
Certificate
Notification
```

---

# 📊 Dashboard & Statistics

Admin dashboard orqali markazning umumiy holatini ko‘rish mumkin.

### Asosiy statistikalar

* 👨‍🎓 Umumiy o‘quvchilar
* 👨‍🏫 Ustozlar soni
* 📚 Kurslar soni
* 👥 Guruhlar soni
* 🟢 Faol o‘quvchilar
* 🟢 Faol kurslar
* 💰 Bugungi tushum
* 💰 Oylik tushum
* ⚠️ Umumiy qarzdorlik
* 🕐 Bugungi davomat

---

# 📈 Reports

Kelajakda tizim orqali turli hisobotlarni olish imkoniyati qo‘shiladi.

### Student Reports

* O‘quvchilar ro‘yxati
* Faol/nofaol o‘quvchilar
* Kurslar bo‘yicha o‘quvchilar

### Attendance Reports

* Kunlik davomat
* Oylik davomat
* Student attendance percentage

### Payment Reports

* Kunlik tushum
* Oylik tushum
* Qarzdorlar
* To‘langan to‘lovlar

### Export

Hisobotlarni kelajakda:

* Excel
* PDF

formatlarida eksport qilish imkoniyati qo‘shiladi.

---

# 📜 Certificates

Kursni muvaffaqiyatli tugatgan o‘quvchilar uchun sertifikat generatsiya qilish imkoniyati.

Masalan:

```text
This certificate is awarded to

AZIZBEK JURAQULOV

for successfully completing

Python Backend Development
```

Sertifikat PDF formatida generatsiya qilinishi mumkin.

---

# 🔔 Notifications

Kelajakda tizimda notification tizimi ham ishlaydi.

Masalan:

* 💰 To‘lov muddati yaqinlashdi
* ⚠️ Qarzdorlik mavjud
* 🕐 Dars vaqti
* 📚 Yangi kurs
* ⭐ Yangi baho
* 📊 Davomat haqida xabar

---

# 🛠️ Technology Stack

Loyihaning backend qismi quyidagi texnologiyalar asosida ishlab chiqiladi:

```text
Python
Django
Django REST Framework
PostgreSQL
JWT Authentication
Docker
Nginx
Gunicorn
```

Qo‘shimcha ravishda:

```text
Redis
Celery
Swagger / OpenAPI
Pytest
Git / GitHub
```

kabi texnologiyalar loyiha ehtiyojiga qarab qo‘shilishi mumkin.

---

# 🔒 Security

Loyihada xavfsizlikka alohida e'tibor beriladi:

* JWT Authentication
* Role-Based Permissions
* Password Hashing
* Secure API endpoints
* Environment variables
* `.env` orqali maxfiy ma'lumotlarni saqlash
* CORS configuration
* CSRF protection
* Database validation
* Permission checks

---

# 🧪 Testing

Loyiha uchun testlar yoziladi.

Test qilinadigan asosiy qismlar:

* Authentication
* Authorization
* Student CRUD
* Teacher CRUD
* Course CRUD
* Group management
* Enrollment
* Attendance
* Payments
* Debt calculation
* Rating
* Search & filtering

---

# 🚀 Development Roadmap

## Phase 1 — Project Setup

* [ ] Django project setup
* [ ] PostgreSQL configuration
* [ ] Environment variables
* [ ] Custom User
* [ ] Role system

## Phase 2 — Users

* [ ] Student
* [ ] Teacher
* [ ] Admin
* [ ] Authentication
* [ ] Permissions
* [ ] Student ID

## Phase 3 — Education Management

* [ ] Courses
* [ ] Groups
* [ ] Enrollment
* [ ] Teachers assignment
* [ ] Schedule

## Phase 4 — Attendance

* [ ] Attendance model
* [ ] Teacher attendance panel
* [ ] Attendance statistics
* [ ] Attendance percentage

## Phase 5 — Payments

* [ ] Payment model
* [ ] Monthly payments
* [ ] Debt calculation
* [ ] Payment history
* [ ] Revenue statistics

## Phase 6 — Rating

* [ ] Exam
* [ ] Exam results
* [ ] Student rating
* [ ] Teacher evaluation system

## Phase 7 — Search & Reports

* [ ] Global search
* [ ] Advanced filtering
* [ ] Reports
* [ ] Excel export
* [ ] PDF export

## Phase 8 — Dashboard

* [ ] Student dashboard
* [ ] Teacher dashboard
* [ ] Admin dashboard
* [ ] Statistics
* [ ] Charts

## Phase 9 — Advanced Features

* [ ] Notifications
* [ ] Certificates
* [ ] Redis
* [ ] Celery
* [ ] Online payments
* [ ] Docker
* [ ] Production deployment

---

# 📌 User Roles Summary

| Feature           | 👨‍🎓 Student | 👨‍🏫 Teacher | 👨‍💼 Admin |
| ----------------- | :-----------: | :-----------: | :---------: |
| Own Profile       |       ✅       |       ✅       |      ✅      |
| Own Courses       |       ✅       |       ✅       |      ✅      |
| Students          |       ❌       |   Own Groups  |      ✅      |
| Teachers          |       ❌       |       ❌       |      ✅      |
| Courses           |    View Own   |    View Own   |      ✅      |
| Groups            |    View Own   |   Own Groups  |      ✅      |
| Attendance        |    View Own   |   Manage Own  |      ✅      |
| Payments          |    View Own   |       ❌       |      ✅      |
| Rating            |    View Own   |     Manage    |      ✅      |
| Reports           |       ❌       |    Limited    |      ✅      |
| Search            |    Own Data   |    Own Data   |   All Data  |
| Dashboard         |    Personal   |    Teacher    |     Full    |
| System Management |       ❌       |       ❌       |      ✅      |

---

# 🎯 Project Goal

Ushbu loyihaning asosiy maqsadi — o‘quv markazlarida ishlatilishi mumkin bo‘lgan **to‘liq, qulay, xavfsiz va kengaytiriladigan boshqaruv tizimi** yaratish.

Platforma yordamida:

> **Student → Teacher → Group → Course → Attendance → Payment → Rating**

jarayonlari yagona tizimga birlashtiriladi.

Natijada o‘quv markazi o‘zining barcha asosiy jarayonlarini yagona platformadan boshqarishi mumkin.

---

# 👨‍💻 Developer

**Azizbek Juraqulov**

Backend Developer — Python / Django / Django REST Framework

GitHub: `juraqulovazizbek`

---

## ⭐ Future Vision

Loyihaning keyingi bosqichlarida tizimni yanada rivojlantirib:

* 📱 Mobile App
* 💳 Online Payment
* 📩 SMS Notifications
* 🤖 Telegram Bot
* 📊 Advanced Analytics
* 🧾 Automated Invoices
* 🏢 Multiple Education Centers
* 🌐 Multi-branch Management

kabi imkoniyatlarni qo‘shish rejalashtirilgan.

---

> **Education Center Management System — o‘quv markazlarini zamonaviy va raqamli boshqarish uchun yaratilgan platforma.** 🎓
# Education-Center-Management-System
