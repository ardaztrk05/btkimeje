# btkimeje

İMEJE Mühendislik Takımı — tek sayfa tanıtım sitesi.
BTK Akademi Yapay Zeka Eğitimi kapsamında hazırlanmıştır.

## Yapı

```
index.html             tüm sayfa (HTML + CSS + JS tek dosyada)
manifest.webmanifest   mobilde "ana ekrana ekle" desteği
images/                fotoğraflar ve ikonlar
```

Derleme adımı yok, bağımlılık yok. `index.html` dosyasını tarayıcıda açmak yeterli.

## Vercel'e yayınlama

Statik site olduğu için ayar gerekmez:

1. vercel.com → Add New → Project → `btkimeje` reposunu içe aktar
2. Framework Preset: **Other**, Build Command: boş, Output Directory: boş
3. Deploy

## İçerik bekleyen alanlar

Sayfada kesik çizgili çerçeveyle işaretli bölümler doldurulmayı bekliyor:

- 9 temel doktrin metni (D-01 … D-09)
- Proje kayıtları 02 ve 03
- Başarıların kesin tarihleri
- Başvuru süreci bilgisi

## Eksik görseller

Aşağıdaki dosyalar `images/` klasörüne eklendiğinde galeride otomatik görünür:

- `cop31.jpg` — Climate iDEAthon 2026 ödül töreni
- `mavera.jpg` — MAVERA proje sunumu
- `ideathon-ekip.jpg` — Climate iDEAthon yarışma kadrosu
