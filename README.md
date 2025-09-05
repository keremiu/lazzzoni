# Lazzoni Custom Closets - Horizon Temasina Ekleme

Bu proje, mevcut Horizon temasina custom closets sayfasi eklemek icin hazirlanmistir.

## Ekleme Dosyalari

```
lazzoni/
├── templates/
│   └── page.custom-closets.liquid    # Ana sayfa template'i
├── sections/
│   ├── custom-closets-hero.liquid    # Hero banner section'i
│   └── closets-category.liquid       # Dolap kategorileri section'i  
├── assets/
│   └── custom-closets.css           # CSS stil dosyasi
└── README.md                        # Bu dosya
```

## Horizon Temasina Ekleme Adimları

### 1. Shopify Admin Paneline Giris
- [https://lazzzoni.myshopify.com/admin](https://lazzzoni.myshopify.com/admin) 

### 2. Horizon Temasinin Code Editor'ini Acin
- **Online Store > Themes** 
- **Horizon temasinda Actions > Edit code**

### 3. Dosyalari Sirayla Ekleyin

#### A) CSS Dosyasini Ekleyin
- **assets** klasorune gidin
- **Add a new asset > Create a blank file**
- **Dosya adi:** `custom-closets.css`
- **assets/custom-closets.css** dosyasinin içeriğini yapiştirin

#### B) Section Dosyalarini Ekleyin
**İlk Section:**
- **sections** klasorune gidin  
- **Add a new section**
- **Dosya adi:** `custom-closets-hero`
- **sections/custom-closets-hero.liquid** içeriğini yapiştirin

**İkinci Section:**
- **Add a new section** 
- **Dosya adi:** `closets-category`
- **sections/closets-category.liquid** içeriğini yapiştirin

#### C) Template Dosyasini Ekleyin
- **templates** klasorune gidin
- **Add a new template**
- **Template type:** page
- **Template adi:** `custom-closets`
- **templates/page.custom-closets.liquid** içeriğini yapiştirin

### 4. Yeni Sayfa Olusturun
- **Online Store > Pages > Add page**
- **Title:** "Custom Closets"
- **Template:** `page.custom-closets` secin
- **Save**

### 5. Sayfayi Test Edin
- Sayfa linki: `https://lazzzoni.myshopify.com/pages/custom-closets`

## Ozellikler

### Dinamik Icerik Yonetimi
- Tum icerikler Shopify admin panelinden yonetilebilir
- Section'lar ile modular yapilandirilmis
- Resim, metin ve link'ler kolayca degistirilebilir

### Responsive Tasarim
- Mobil, tablet ve desktop cihazlarda uyumlu
- Modern CSS teknikleri kullanilmis
- Touch-friendly arayuz

### SEO Dostu
- Semantic HTML yapisi
- Meta tag destegi
- Hizli yukleme sureleri

### Kategori Ozellikleri

1. **Custom Closets** - Ozellestirilmis dolaplar
2. **Vetrina Glass Closets** - Cam panelli dolaplar
3. **Forma Solid Closets** - Solid malzemeli dolaplar  
4. **Spazio Walk-in** - Giyinme odasi cozumleri
5. **Vanity Make-up** - Makyaj masasi entegreli
6. **Murphy Bed** - Yatak entegreli dolaplar
7. **Island Storage** - Ada tipi depolama uniteleri

## Teknik Detaylar

### Kullanilan Teknolojiler
- **Shopify Liquid** - Template engine
- **CSS3** - Stil ve animasyonlar
- **Flexbox & Grid** - Layout sistemi
- **Responsive Design** - Cihaz uyumlulugu

### Browser Destegi
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Ozellestirme

### Renkler Degistirme
`assets/custom-closets.css` dosyasindaki CSS degiskenlerini duzenleyin:

```css
:root {
  --primary-color: #C5621B;
  --secondary-color: #A0501A;
  --text-color: #333;
  --background-color: #f8f8f8;
}
```

### Yeni Kategori Ekleme
1. `templates/page.custom-closets.json` dosyasina yeni section ekleyin
2. Section settings'lerini yapilandirin
3. Resim ve metinleri admin panelinden guncelleyin

## Destek

Herhangi bir sorun yasarsaniz:
1. Liquid syntax'ini kontrol edin
2. CSS dosyalarinin dogru yuklendigini dogrulayin  
3. Shopify theme inspector'i kullanin
4. Browser developer tools ile debug yapin

## Lisans

Bu proje Lazzoni markasi icin ozel olarak gelistirilmistir.
