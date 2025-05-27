readme_content = """
# Blog Website

## 👥 Katılımcılar
- Ali Rıza Sarıoğlu
- Sema Akyavuz

## 📌 Proje Özeti
Blog Website, kullanıcıların blog gönderileri oluşturmasını, beğenmesini, yorum yapmasını ve etkileşimde bulunmasını sağlayan bir web uygulamasıdır. Admin paneli ile içerikler kolayca yönetilebilir. Uygulama ASP.NET Core MVC ile geliştirilmiştir.

## 🛠 Kullanılan Teknolojiler
- ASP.NET Core 6 MVC
- Entity Framework Core
- MSSQL
- Identity (Kullanıcı Girişi)
- Docker & Docker Compose

## 🚀 Özellikler
### 1. Veritabanı & CRUD
- Kullanıcılar gönderi ekleyebilir, düzenleyebilir, silebilir.
- Yorumlar ve etiket sistemi mevcuttur.
- EF Core ile veritabanı işlemleri yapılmaktadır.

### 2. Kullanıcı Girişi ve Yetkilendirme
- ASP.NET Identity kullanılarak giriş/çıkış sistemi uygulanmıştır.
- Admin ve normal kullanıcı rolleri mevcuttur.

### 3. Docker & Docker-Compose Desteği
- Uygulama Dockerfile ile container haline getirilmiştir.
- `docker-compose up` komutu ile MSSQL ve web uygulaması ayağa kaldırılır.

## ⚙️ Kurulum

```bash
git clone https://github.com/kullaniciadi/Blog-Website.git
cd Blog-Website
docker-compose up