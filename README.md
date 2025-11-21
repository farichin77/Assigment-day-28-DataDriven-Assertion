# Automation Testing – Data Driven & Assertions (SauceDemo)

Project ini merupakan contoh implementasi automation testing menggunakan:
- Java
- Selenium WebDriver
- TestNG
- Gradle
- Page Object Model (POM)
- Data Driven Testing (Excel)
- Assertions & Validation

Website untuk pengujian:  
https://www.saucedemo.com/

---
## 1. Cara Menjalankan Test

### ▶ Via IntelliJ (GUI)
- Klik kanan `testng.xml`
- Pilih **Run 'testng.xml'

## 2. Fitur Pengujian

### ✔ Login Test (Data Driven)
- Test berbagai kombinasi username & password
- Validasi error message untuk field kosong
- Validasi login gagal & login berhasil

### ✔ Checkout Test (Data Driven)
- Menambahkan product ke cart
- Checkout dengan data berbeda
- Validasi error message (first name / last name / postal code)
- Validasi checkout success

---
## 3. Test Data (Excel)
File berada di:
src/test/resources/Data/LoginData.xlsx
src/test/resources/Data/test_data.xlsx

Sheet:
- `Login_Data`
- `CekOut_Data`

Excel dibaca menggunakan Apache POI.

## 4. Teknologi yang Digunakan
- Java 17
- Selenium WebDriver 4
- TestNG
- AssertJ
- Apache POI
- Log4j2
- ChromeOptions (Incognito Mode)
## 5. Tujuan Project
Project ini dibuat sebagai portfolio untuk:
- Data driven testing
- Assertions & validation
- Struktur Page Object Model
- Pembuatan test suite TestNG
- Logging pada test automation

---

## 6. Catatan
Browser Chrome dijalankan dalam *Incognito Mode* untuk menghindari popup Chrome seperti *“Change Password?”* yang dapat menyebabkan test gagal.

