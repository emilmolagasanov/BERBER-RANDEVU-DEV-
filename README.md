# MAKASAPP - Berber Randevu Sistemi

Modern ve kullanıcı dostu bir arayüze sahip, **ASP.NET Core MVC** ile geliştirilmiş kapsamlı bir berber randevu yönetim sistemidir.

## 🚀 Proje Özellikleri

### 👤 Müşteri Paneli
- **Online Randevu:** Müşteriler istedikleri berberden, uygun tarih ve saatte kolayca randevu alabilirler.
- **Berberleri Keşfetme:** Salonun berberlerini ve uzmanlık alanlarını görüntüleme.
- **Yorum Sistemi:** Müşteri deneyimlerini paylaşmak için yorum yapabilme özelliği.
- **Hakkımızda & Galeri:** Lüks ve modern salon görselleri ile işletme tanıtımı.

### 🛡️ Yönetici (Admin) Paneli
- **Randevu Yönetimi:**
  - **Onay Bekleyenler:** Gelen randevuları görüntüleme ve tek tıkla onaylama.
  - **Aktif Randevular:** Onaylanmış randevuların listesi.
  - **Otomatik Temizleme:** Geçmiş tarihli randevular sistemden otomatik olarak filtrelenir.
- **Berber Yönetimi:** Yeni berber ekleme, düzenleme ve fotoğraf yükleme işlemleri.
- **Güvenlik:** Yetkili girişi ile korunan yönetim paneli.

## 🛠️ Teknolojiler
- **Backend:** ASP.NET Core 10.0 MVC
- **Veritabanı:** Entity Framework Core (SQL Server / LocalDB)
- **Frontend:** Bootstrap 5, HTML5, CSS3, Javascript
- **Medya:** Dinamik görsel yükleme ve yönetimi

## 📦 Kurulum

1. Projeyi klonlayın.
2. Veritabanını oluşturmak için terminalde şu komutu çalıştırın:
   ```bash
   dotnet ef database update
   ```
3. Projeyi ayağa kaldırın:
   ```bash
   dotnet run
   ```
4. Tarayıcıda `http://localhost:5227` adresine gidin.

## 🔐 Yönetici Giriş Bilgileri
- **Kullanıcı Adı:** admin
- **Şifre:** 123
