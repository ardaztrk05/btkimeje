<div align="center">

<img src="images/og.png" alt="İMEJE Harp" width="620">

<br>

### Bağımsız Öğrenci Mühendislik Takımı · Elektronik Harp Sistemleri

Takımın tek sayfa tanıtım sitesi — **BTK Akademi Yapay Zeka Eğitimi** kapsamında hazırlanmıştır.

<br>

![BTK Akademi](https://img.shields.io/badge/BTK%20Akademi-Yapay%20Zeka%20E%C4%9Fitimi-AE1526?style=for-the-badge)
![GENÇ2030](https://img.shields.io/badge/GEN%C3%872030-Dijital%20Yetkinlikler-0D6E77?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Vercel-Yay%C4%B1nda-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Statik](https://img.shields.io/badge/Statik-S%C4%B1f%C4%B1r%20ba%C4%9F%C4%B1ml%C4%B1l%C4%B1k-131A22?style=for-the-badge&logo=html5&logoColor=E34F26)

**[🌐 imejeteam.com](https://imejeteam.com)** · **[📷 @imejeteam](https://www.instagram.com/imejeteam/)** · **[💼 LinkedIn](https://linkedin.com/company/imejeteam)** · **[✉️ imejeteam@gmail.com](mailto:imejeteam@gmail.com)**

</div>

---

## Bu site neden var?

Bu depo, **BTK Akademi Yapay Zeka Eğitimi** için hazırlanan bitirme çalışmasıdır. Eğitimde
öğrenilen üretken yapay zekâ ve istem mühendisliği yetkinlikleri, İMEJE takımını anlatan
gerçek bir ürüne dönüştürülerek uygulanmıştır.

Eğitim, Gençlik ve Spor Bakanlığı’nın yürüttüğü **GENÇ2030 — Dijital Yetkinlikler ve Yapay
Zekâ Atölyesi** programı kapsamındadır. Program 81 ildeki gençlik merkezlerini yapay zekâ
atölyelerine dönüştürmeyi ve 2030’a kadar 100 bin yapay zekâ girişimcisi yetiştirmeyi
hedefler; eğitim içerikleri BTK Akademi iş birliğiyle sağlanır.

## İMEJE kimdir?

Arda Öztürk liderliğinde, üniversitemizde yeterli teknik çalışma alanı bulunmaması üzerine
kendi çabalarıyla bir araya gelen ve kurduğu atölye imkânlarıyla doğrudan **askeri elektronik
harp sistemleri** geliştirmeye odaklanan bağımsız bir öğrenci mühendislik takımıdır.

Gazi Mustafa Kemal Atatürk’ün akıl ve bilimi rehber kılan vizyonunu temel alan ekip;
TEKNOFEST ve EFES Tatbikatı gibi platformlarda yer almayı, milli savunma teknolojilerine
atölye masasından somut katkı sunmayı hedefler.

> **“Pressure makes diamonds”** — çalışma kültürümüzün merkezindeki felsefe.

### Birim yapısı

| Birim | Sorumluluk | Yürütücü |
| :--- | :--- | :--- |
| **RF ve Aviyonik Sistemleri** | Yüksek frekans ve aviyonik mimariler | Naim Furkan Şahin |
| **Otonom Sistemler ve İstihbarat** | Yazılım ve taktik istihbarat sistemleri | Emirhan Harput · Osman Fadıl Eliyatkın |
| **EH Doktrin ve Araştırma** | Literatür, taktik doktrin, sistem analizi | Doğrudan yönetim |

### Başarılar

| Platform | Derece |
| :--- | :--- |
| TUA ASTRO Hackathon · Trabzon | 🥈 **İkincilik Ödülü** |
| Climate iDEAthon 2026 · Trabzon | 🥇 **MAVERA ile COP31 bölge birinciliği** |
| Protokol ziyareti | Takım masasında bakanlık düzeyinde proje tanıtımı |

<div align="center">

<img src="images/astro-ikincilik.jpg" alt="TUA ASTRO Hackathon ikincilik ödülü" width="240">
<img src="images/cop31.jpg" alt="Climate iDEAthon COP31 bölge birinciliği" width="400">

</div>

---

## Site hakkında

Tek sayfa, kaydırmalı tanıtım sitesi. **Derleme adımı yok, bağımlılık yok, çerçeve yok** —
tek bir `index.html` içinde HTML, CSS ve sade JavaScript.

**Bölümler:** Kimlik · Takım görselleri · Vizyon · Birim yapısı · Başarılar · BTK Akademi ve GENÇ2030 · İletişim

| Özellik | Açıklama |
| :--- | :--- |
| 🌗 **Açık / koyu tema** | Ziyaretçinin cihaz temasına göre otomatik |
| 📱 **Mobil uyumlu** | Açılır menü, galeride parmakla kaydırmalı şerit |
| 📲 **Ana ekrana eklenebilir** | `manifest.webmanifest` ile uygulama gibi açılır |
| 🔗 **Paylaşım kartı** | WhatsApp ve sosyal medyada logolu önizleme |
| ♿ **Erişilebilir** | Klavye odağı, görsel alternatif metinleri, hareket azaltma desteği |

### Dosya yapısı

```
index.html             tüm sayfa — HTML + CSS + JS
manifest.webmanifest   mobilde "ana ekrana ekle" tanımı
images/                takım fotoğrafları, arma ve ikonlar
```

### Çalıştırma

```bash
git clone https://github.com/ardaztrk05/btkimeje.git
cd btkimeje
```

`index.html` dosyasını tarayıcıda aç — kurulum gerekmez.

### Yayınlama

Statik site olduğu için Vercel'de ayar gerektirmez:

1. **vercel.com → Add New → Project →** `btkimeje` reposunu içe aktar
2. Framework Preset **Other**, Build Command ve Output Directory boş
3. **Deploy**

> [!IMPORTANT]
> Paylaşım kartı mutlak adres kullanır. Yayın adresi değişirse `index.html` içindeki
> `og:url`, `og:image` ve `twitter:image` değerlerini gerçek alan adıyla güncelle.
> Tanımlı adres: `https://btkimeje.vercel.app/`
> WhatsApp önizlemeyi önbelleğe alır; güncelledikten sonra linkin sonuna `?v=2` ekleyerek test et.

---

<div align="center">

<img src="images/arma.webp" alt="İMEJE arması" width="78">

**İMEJE** · Bağımsız Öğrenci Mühendislik Takımı

<sub>BTK Akademi Yapay Zeka Eğitimi · GENÇ2030</sub>

</div>
