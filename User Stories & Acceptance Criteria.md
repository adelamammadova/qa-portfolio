# User Stories & Acceptance Criteria – ParaBank

---

## 1. Registration

### User Story
Mən istifadəçi olaraq, qeydiyyatdan keçmək istəyirəm ki, bank sisteminə daxil ola bilim.

### Acceptance Criteria
- İstifadəçi qeydiyyat səhifəsində olmalıdır
- Bütün məcburi sahələr (ad, soyad, ünvan, telefon, username, password və s.) doldurulmalıdır
- Username unikal olmalıdır
- Password və Confirm Password uyğun olmalıdır
- Hesab uğurla yaradılmalıdır
- İstifadəçi avtomatik login olunub Account Overview səhifəsinə yönləndirilməlidir

---

## 2. Login

### User Story
Mən qeydiyyatlı istifadəçi olaraq, öz hesabıma daxil olmaq istəyirəm ki, bank əməliyyatlarımı idarə edə bilim.

### Acceptance Criteria
- İstifadəçi ana səhifədə username və password daxil etməlidir
- Doğru məlumatlarla daxil olduqda Account Overview səhifəsinə yönləndirilməlidir
- Yanlış məlumatlarla daxil olmaq mümkün olmamalıdır
- Yanlış giriş zamanı uyğun error mesajı göstərilməlidir

---

## 3. Account Overview

### User Story
Mən istifadəçi olaraq, bütün hesablarımı və balanslarımı bir yerdə görmək istəyirəm.

### Acceptance Criteria
- İstifadəçi login olmalıdır
- Bütün hesablar siyahı şəklində göstərilməlidir
- Hər hesabın balansı düzgün göstərilməlidir
- Hesab nömrəsinə klikləndikdə həmin hesabın detalları açılmalıdır

---

## 4. Open New Account

### User Story
Mən istifadəçi olaraq, yeni hesab açmaq istəyirəm ki, əlavə maliyyə imkanlarımı genişləndirim.

### Acceptance Criteria
- İstifadəçi login olmalıdır
- “Open New Account” səhifəsinə daxil olmalıdır
- Hesab növü (Checking/Savings) seçilməlidir
- Mövcud hesabdan ilkin məbləğ köçürülməlidir
- Yeni hesab uğurla yaradılmalı və nömrəsi göstərilməlidir

---

## 5. Transfer Funds

### User Story
Mən istifadəçi olaraq, öz hesablarım arasında pul köçürmək istəyirəm ki, vəsaitlərimi idarə edə bilim.

### Acceptance Criteria
- İstifadəçi login olmalıdır
- “Transfer Funds” səhifəsinə daxil olmalıdır
- Göndərən və qəbul edən hesab seçilməlidir
- Məbləğ düzgün formatda daxil edilməlidir
- Məbləğ mövcud balansdan çox olmamalıdır
- Köçürmə uğurla tamamlanmalı və hər iki hesabın balansı yenilənməlidir

---

## 6. Bill Pay

### User Story
Mən istifadəçi olaraq, kommunal və digər hesablarımı onlayn ödəmək istəyirəm ki, vaxtımı qənaət edim.

### Acceptance Criteria
- İstifadəçi login olmalıdır
- “Bill Pay” səhifəsinə daxil olmalıdır
- Payee (ödəniş alıcısı) məlumatları doldurulmalıdır
- Ödəniş məbləği daxil edilməlidir
- Balans kifayət olduqda ödəniş uğurla tamamlanmalıdır
- Balans kifayət olmadıqda ödəniş rədd edilməlidir

---

## 7. Find Transactions

### User Story
Mən istifadəçi olaraq, keçmiş əməliyyatlarımı axtarmaq istəyirəm ki, xərclərimi izləyə bilim.

### Acceptance Criteria
- İstifadəçi login olmalıdır
- “Find Transactions” səhifəsinə daxil olmalıdır
- Tarix, məbləğ və ya digər meyarlar üzrə axtarış aparıla bilməlidir
- Uyğun əməliyyatlar siyahı şəklində göstərilməlidir
- Nəticə tapılmadıqda uyğun mesaj göstərilməlidir

---

## 8. Update Contact Info

### User Story
Mən istifadəçi olaraq, əlaqə məlumatlarımı yeniləmək istəyirəm ki, bank mənimlə düzgün əlaqə saxlaya bilsin.

### Acceptance Criteria
- İstifadəçi login olmalıdır
- “Update Contact Info” səhifəsinə daxil olmalıdır
- Ad, ünvan, telefon və s. sahələr redaktə edilə bilməlidir
- Məcburi sahələr boş buraxıla bilməməlidir
- Məlumat uğurla yenilənməli və təsdiq mesajı göstərilməlidir

---

## 9. Request Loan

### User Story
Mən istifadəçi olaraq, kredit sorğusu göndərmək istəyirəm ki, əlavə maliyyə resursu əldə edim.

### Acceptance Criteria
- İstifadəçi login olmalıdır
- “Request Loan” səhifəsinə daxil olmalıdır
- Loan Amount və Down Payment məbləğləri daxil edilməlidir
- Sistem krediti “Approved” və ya “Denied” statusu ilə cavablandırmalıdır
- Nəticə istifadəçiyə aydın şəkildə göstərilməlidir

---

## 10. Log Out

### User Story
Mən istifadəçi olaraq, sistemdən təhlükəsiz çıxmaq istəyirəm ki, hesabım qorunsun.

### Acceptance Criteria
- İstifadəçi login olmalıdır
- “Log Out” düyməsinə klik etdikdə sessiya bağlanmalıdır
- İstifadəçi ana səhifəyə yönləndirilməlidir
- Çıxışdan sonra “Back” düyməsi ilə hesab məlumatlarına giriş mümkün olmamalıdır
