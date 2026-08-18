# ParaBank – Test Plan

## 1. Project Name
**ParaBank Website**

---

## 2. Project Description
ParaBank onlayn bank platformasıdır və istifadəçilərə aşağıdakı imkanları təqdim edir:
- Hesab açmaq və idarə etmək
- Hesablar arasında pul köçürmək
- Kommunal və digər hesabları onlayn ödəmək (Bill Pay)
- Keçmiş əməliyyatları axtarmaq və izləmək
- Kredit sorğusu göndərmək

Platforma real bank sistemlərinin əsas funksionallığını simulyasiya edir və istifadəçilərə öz maliyyə əməliyyatlarını təhlükəsiz və rahat şəkildə idarə etmək imkanı verir.

---

## 3. Test Objectives
Saytın funksional və qeyri-funksional xüsusiyyətlərinin tələblərə uyğun işlədiyini, maliyyə əməliyyatlarının dəqiq və təhlükəsiz icra olunduğunu yoxlamaq.

---

## 4. Test Scope
Test ediləcək modullar:
- Registration
- Login
- Account Overview
- Open New Account
- Transfer Funds
- Bill Pay
- Find Transactions
- Update Contact Info
- Request Loan

---

## 5. Out of Scope
- Köhnə brauzerlər (Internet Explorer, köhnə Safari versiyaları)
- Mobil tətbiq (yalnız web versiya test olunur)

---

## 6. Test Team
- QA Tester
- Product Owner
- Developer

---

## 7. Roles & Responsibilities
- **Product Owner:** Tələblərin analiz edilməsi və təsdiqi
- **Developer:** Bug-ların aradan qaldırılması
- **QA Tester:** Test plan hazırlanması, test case və checklist-lərin yazılması, manual testlərin icrası

---

## 8. Test Strategy
- Manual Testing
- Functional Testing
- Non-functional Testing:
  - Compatibility
  - Security
  - Usability

---

## 9. Test Environment
- **Hardware:** Desktop
- **OS:** macOS
- **Browsers:** Chrome
- **URL:** https://parabank.parasoft.com/parabank/index.htm

---

## 10. Test Tools
- Postman (API testing)
- Excel / Word / Markdown (Documentation)
- GitHub (Portfolio və versiya idarəetməsi)

---

## 11. Test Deliverables
- Test Plan
- User Stories & Acceptance Criteria
- Checklist
- Test Cases
- Bug Reports
- Test Summary Report

---

## 12. Entry Criteria
- Tələblər hazırdır
- Test case-lər yazılıb
- Test mühiti hazırdır (sayta giriş mövcuddur)

---

## 13. Exit Criteria
- Testlərin ən azı 90%-i uğurla keçib
- Əsas funksionallıqlar (Login, Transfer Funds, Bill Pay) yoxlanılıb
- Kritik bug-lar sənədləşdirilib
- Nəticələr Test Summary Report-da əks olunub

---

## 14. Risks
- Demo mühit olduğu üçün data hər zaman stabil olmaya bilər
- Bəzi funksiyalarda (məs. validasiya) gözlənilməyən davranışlar ola bilər

---

## 15. Assumptions
- Test istifadəçisi qeydiyyatdan keçə bilir
- Sayt internet bağlantısı ilə fasiləsiz əlçatandır
- Test mühiti real bank sistemi deyil, ictimai demo platformadır

---

## 16. Test Schedule
**19.08.2026 – 26.08.2026**
