## Overview / Genel Bakış
Java Swing application for managing industrial crane and lifting equipment sales processes.  
Endüstriyel vinç ve kaldırma ekipmanları satış süreçlerini yönetmek için Java Swing uygulaması.

## Key Features / Temel Özellikler
- Product categories management / Ürün kategorileri yönetimi
- Customer order processing / Müşteri sipariş işleme
- Payment information handling / Ödeme bilgilerinin yönetimi
- Admin/employee login systems / Yönetici/çalışan giriş sistemleri
- Supplier lists / Tedarikçi listeleri
- Delivery tracking / Teslimat takibi
- Reporting / Raporlama

## Technical Specifications / Teknik Özellikler
- **Technology Stack**: Java Swing, UCanAccess (MS Access), JDBC  
  **Teknoloji Yığını**: Java Swing, UCanAccess (MS Access), JDBC
- **Database**: MS Access with two main tables:  
  **Veritabanı**: İki ana tablolu MS Access:
  - `KISILER` (Customer/order data) / (Müşteri/sipariş verisi)
  - `TESLIM` (Delivery information) / (Teslimat bilgisi)

## Usage Guide / Kullanım Kılavuzu
1. **Main Screen** / **Ana Ekran**: Select product category / Ürün kategorisi seçin
2. **Order Process** / **Sipariş Süreci**:
   - Choose product / Ürün seçin
   - Click "Order" / "Sipariş Ver"e tıklayın
   - Enter customer/payment details / Müşteri/ödeme bilgilerini girin
   - Confirm order / Siparişi onaylayın
3. **Admin Login** (username: any, password: 123) / **Yönetici Girişi** (kullanıcı adı: herhangi bir değer, şifre: 123):
   - Access reports / Raporlara erişim
   - View supplier lists / Tedarikçi listelerini görüntüleme
4. **Employee Login** (username: any, password: 123) / **Çalışan Girişi** (kullanıcı adı: herhangi bir değer, şifre: 123):
   - Enter delivery information / Teslimat bilgilerini girin

## Installation / Kurulum
1. Requires Java JDK / Java JDK gereklidir
2. Add UCanAccess libraries / UCanAccess kütüphanelerini ekleyin:
   - ucanaccess-5.0.1.jar
   - commons-lang3-3.8.1.jar
   - commons-logging-1.2.jar
   - hsqldb-2.5.0.jar
   - jackcess-3.0.1.jar
3. Place `database2023.accdb` in specified path / `database2023.accdb` dosyasını belirtilen yola yerleştirin
