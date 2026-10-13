# Satır Arası - Edebiyat ve Kitap İnceleme Blogu (Frontend)

Bu proje, edebiyat tutkunları için tasarlanmış, modern ve duyarlı (responsive) bir kitap inceleme blogunun kullanıcı arayüzü (UI) tasarımıdır. 

Şu an projenin **Önyüz (Frontend)** aşaması tamamlanmış olup, modern web standartlarına uygun, temiz bir HTML/CSS mimarisi kurulmuştur. Yakın gelecekte bu statik yapı, Laravel ve MySQL kullanılarak dinamik bir arka plana (Backend) kavuşturulacaktır.

## Proje Özellikleri

* **Duyarlı (Responsive) Tasarım:** Mobil cihazlar, tabletler ve masaüstü ekranlarla %100 uyumlu Bootstrap Grid 12 sistemi.
* **Modern Kullanıcı Arayüzü:** Temiz, göz yormayan, okuma odaklı (Medium tarzı) makale sayfaları.
* **Split-Screen (Bölünmüş Ekran) Formlar:** Giriş ve Kayıt ol sayfalarında ekranı ikiye bölen modern ve estetik görsel yaklaşım.
* **Dinamik UX Dokunuşları:** Vanilla JavaScript ile geliştirilmiş "Şifreyi Göster/Gizle" özellikleri.
* **Semantik HTML:** Arama motoru dostu (SEO) etiketlemeler (`<article>`, `<aside>`, `<blockquote>`).

## Kullanılan Teknolojiler

* **HTML5** 
* **CSS3 & Bootstrap 4.6.2** (Hızlı ve esnek grid sistemi için)
* **Vanilla JavaScript** (DOM manipülasyonu ve UI etkileşimleri için)
* **Font Awesome 5** (Vektörel ikonlar)

## Sayfa Yapıları

1. `index.html` - Ana sayfa, son incelemeler ve dinamik kenar çubuğu.
2. `detay.html` - Makale okuma sayfası ve yorum formu alanı.
3. `login.html` - İkiye bölünmüş ekran mimarisine sahip giriş sayfası.
4. `register.html` - Kullanıcı sözleşmesi ve çift şifre doğrulamalı kayıt sayfası.

## Gelecek Hedefleri (Backend Fazı)
- [ ] Laravel Framework entegrasyonu.
- [ ] MySQL veritabanı tasarımı (Kullanıcılar, Yazılar, Yorumlar, Kategoriler).
- [ ] Yönetici paneli ve dinamik içerik yönetimi.