# Günlük Uygulaması Tasarımı

Bu proje, günlük yazma uygulaması için tasarlanmış bir web arayüzüdür.

## Tasarım Özellikleri

- Modern ve responsive tasarım
- Bootstrap 5 framework kullanımı
- Bootstrap Icons entegrasyonu
- Kullanıcı dostu arayüz
- Kart tabanlı günlük görünümü
- İstatistik kartları
- Kategori etiketleri

## Sayfalar

### Dashboard
- Kullanıcı karşılama alanı
- İstatistik kartları (Toplam günlük, Bu ay, Son günlük, Ortalama)
- Günlük kartları grid görünümü
- Her günlük için düzenleme ve silme butonları
- Kategori etiketleri (Kişisel, İş, Aile, Seyahat)

### Günlük Ekleme
- Form tasarımı
- Başlık, kategori ve içerik alanları
- Kategori seçim menüsü
- Geri dön ve kaydet butonları

## Kullanılan Teknolojiler

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons
- Jinja2 Template Engine

## Proje Yapısı

```
FirstWeek/
├── templates/
│   ├── base.html
│   ├── dashboard.html
│   ├── gunluk_ekle.html
│   ├── gunluk_duzenle.html
│   ├── login.html
│   └── register.html
├── static/
│   ├── css/
│   └── js/
```

## Tasarım Özellikleri

### Renkler
- Primary: Mavi (#0d6efd)
- Success: Yeşil (#198754)
- Info: Açık Mavi (#0dcaf0)
- Warning: Sarı (#ffc107)

### Responsive Tasarım
- Mobil cihazlara uyumlu
- Tablet ve masaüstü için optimize edilmiş görünüm
- Grid sistemi ile esnek yerleşim

### Kartlar
- Gölgeli tasarım
- Hover efektleri
- İkon entegrasyonu
- Badge'ler ile kategori gösterimi 