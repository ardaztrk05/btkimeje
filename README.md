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

## Bölümler

Kimlik · Vizyon · Birim yapısı · Başarılar · Galeri · Yapay Zeka · İletişim

## Vercel'e yayınlama

Statik site olduğu için ayar gerekmez:

1. vercel.com → Add New → Project → `btkimeje` reposunu içe aktar
2. Framework Preset: **Other**, Build Command ve Output Directory boş
3. Deploy

## Paylaşım kartı (WhatsApp / sosyal medya)

`images/og.png` (1200×630) link önizlemesinde görünen bannerdır.
Open Graph etiketleri mutlak adres kullanır; **yayın adresi değişirse**
`index.html` içindeki `og:url`, `og:image` ve `twitter:image` değerlerini
gerçek alan adıyla güncelle. Şu an tanımlı adres: `https://btkimeje.vercel.app/`

WhatsApp önizlemeyi önbelleğe alır; güncelledikten sonra linkin sonuna
`?v=2` ekleyerek test edebilirsin.
