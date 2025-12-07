# Aroma Shop - Müzik Albümü Satış Projesi

Modern, responsive ve kullanıcı deneyimi odaklı bir e-ticaret arayüz projesi.

## Proje Hakkında

**Aroma Shop**, kullanıcıların müzik albümlerini inceleyebildiği, kategorilere göre filtreleme yapabildiği ve modern bir arayüz üzerinden etkileşim sağlayabildiği bir **Front-End (Ön Yüz)** web projesidir.

Proje; ürün listeleme, detay görüntüleme, sepet yönetimi ve görsel bileşenler üzerine odaklanmıştır. **Web Tasarımı** dersi kapsamında geliştirilen bu uygulama, e-ticaret mantığını görsel olarak simüle eder.

**Önemli Not:** Bu proje yalnızca arayüz (UI) geliştirmeye yöneliktir. Arka uç (Back-End), gerçek stok yönetimi veya veritabanı bağlantısı **bulunmamaktadır**. Admin paneli ve satın alma işlemleri tasarımsal bir demo (simülasyon) niteliğindedir.

---

## Kullanılan Teknolojiler

Projenin geliştirilmesinde aşağıdaki modern web teknolojileri ve kütüphaneler kullanılmıştır:

* HTML5
* CSS3
* Bootstrap 4
* JavaScript

---

## Sistem Akış Diyagramı

Projenin sayfa hiyerarşisi ve kullanıcı akışı aşağıdaki gibidir:

![Sistem Akış Diyagramı](https://github.com/tayrubys/aroma-shop/blob/d58a61402b574fa238218c4a599b922f0c1500aa/sistemakisdiyagrami.png)

---

## Dosya Yapısı

Proje dosyaları, bakımın kolay olması ve düzenli bir geliştirme ortamı sağlamak amacıyla aşağıdaki hiyerarşik yapıda düzenlenmiştir:

```text
AROMA-SHOP
│
├── album_img/                 # Albümlere ait ürün görselleri
├── Aroma Shop-doc/            # Proje teknik dokümanları
├── css/                       # Stil dosyaları (style.css vb.)
├── img/                       # Genel site görselleri (Logo, banner vb.)
├── js/                        # JavaScript dosyaları (Slider, sepet mantığı vb.)
├── scss/                      # SCSS kaynak dosyaları
├── vendors/                   # Harici CSS/JS kütüphaneleri (Owl Carousel vb.)
│
├── index.html                 # Ana Sayfa
├── about.html                 # Hakkında Sayfası
├── admin.html                 # Admin Paneli (Simülasyon)
├── cart.html                  # Sepet Sayfası
├── checkout.html              # Ödeme Sayfası
├── confirmation.html          # Sipariş Onay Sayfası
├── contact.html               # İletişim Sayfası
├── login.html                 # Giriş Yap Sayfası
├── register.html              # Kayıt Ol Sayfası
├── duyurular.html             # Duyurular ve Kampanyalar
├── lojistik.html              # Lojistik ve Teslimat Bilgileri
├── musteri-iliskileri.html    # Müşteri İlişkileri ve Destek
├── vizyonmisyon.html          # Vizyon & Misyon
│
├── categoryttumalbum.html     # Tüm Albümler
├── categoryartic.html         # Kategori: Arctic Monkeys
├── categoryt.html             # Kategori: Taylor Swift
├── categorytb.html            # Kategori: Billie Eilish
│
├── single-product.html        # Ürün Detay Sayfası 1
├── single-product2.html       # Ürün Detay Sayfası 2
├── single-product3.html       # Ürün Detay Sayfası 3
├── single-product4.html       # Ürün Detay Sayfası 4
├── single-product5.html       # Ürün Detay Sayfası 5
├── single-product6.html       # Ürün Detay Sayfası 6
│
└── README.md                  # Proje Benioku Dosyası
