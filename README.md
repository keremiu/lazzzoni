# Lazzoni Custom Closets

Lazzoni markası için geliştirilmiş custom closets ürün showcase sayfası.

## 📁 Dosya Yapısı

```
lazzoni/
├── templates/
│   └── index.liquid                 # Ana sayfa template'i (custom closets içeriği)
├── assets/
│   ├── custom-closets.css          # CSS stil dosyası
│   ├── CustomClosetHead.png        # Hero bölümü ana görseli
│   ├── CustomClosetImage1.png      # Custom closets ürün görseli 1
│   ├── CustomClosetImage2.png      # Custom closets ürün görseli 2
│   ├── CustomClosetImage3.png      # Custom closets ürün görseli 3
│   ├── VertinaGlassClosetImage1.png # Vetrina glass closet görseli 1
│   ├── VertinaGlassClosetImage2.png # Vetrina glass closet görseli 2
│   ├── VertinaGlassClosetImage3.png # Vetrina glass closet görseli 3
│   ├── FermaSolidClosetImage1.png  # Forma solid closet görseli 1
│   ├── FermaSolidClosetImage2.png  # Forma solid closet görseli 2
│   ├── FermaSolidClosetImage3.png  # Forma solid closet görseli 3
│   ├── SpazioOpenClosetImage1.png  # Spazio walk-in görseli 1
│   ├── SpazioOpenClosetImage2.png  # Spazio walk-in görseli 2
│   ├── SpazioOpenClosetImage3.png  # Spazio walk-in görseli 3
│   ├── VanityClosetImage1.png      # Vanity make-up görseli 1
│   ├── VanityClosetImage2.png      # Vanity make-up görseli 2
│   ├── VanityClosetImage3.png      # Vanity make-up görseli 3
│   ├── MurphyClosetImage1.png      # Murphy bed görseli 1
│   ├── MurphyClosetImage2.png      # Murphy bed görseli 2
│   ├── MurphyClosetImage3.png      # Murphy bed görseli 3
│   ├── IslandUnitImage1.png        # Island storage görseli 1
│   ├── IslandUnitImage2.png        # Island storage görseli 2
│   └── IslandUnitImage3.png        # Island storage görseli 3
├── config/
│   ├── settings_data.json          # Tema ayarları
│   └── settings_schema.json        # Tema yapılandırma şeması
├── layout/
│   └── theme.liquid                # Ana tema layout dosyası
├── locales/
│   └── en.default.json             # İngilizce dil dosyası
└── README.md                        # Proje dokümantasyonu
```

## 🎯 Ne Yapıyor

Ana sayfada custom closet ürünlerinin sergilendiği bir showcase. 7 farklı dolap kategorisi gösteriliyor:

1. **Custom Closets** - Özel tasarım dolaplar
2. **Vetrina Glass Closets** - Cam detaylı dolaplar
3. **Forma Solid Closets** - Solid malzemeli dolaplar
4. **Spazio Walk-in** - Açık giyinme odaları
5. **Vanity Make-up** - Makyaj masası entegreli
6. **Murphy Bed** - Yatak entegreli dolaplar
7. **Island Storage** - Ada tipi depolama

## 🔧 Teknik Özellikler

- **Platform:** Shopify Liquid template engine kullanılarak geliştirildi
- **Layout Sistemi:** CSS Grid ve Flexbox ile modern layout yapısı
- **Performance:** Optimize edilmiş CSS, lazy loading görseller ile hızlı yükleme
- **Browser Desteği:** Chrome, Firefox, Safari, Edge (modern versiyonlar)
- **Görsel Optimizasyonu:** PNG formatında optimize edilmiş ürün görselleri
- **Kod Yapısı:** Tek merkezi template ile temiz ve bakımı kolay kod

## 📱 Responsive Tasarım

**Ekran Boyutlarına Göre Düzen:**
- **Mobil (0-480px):** 
  - 1 sütun grid layout
  - Büyük dokunmatik butonlar
  - Dikey scroll navigation
- **Tablet (481-768px):** 
  - 2 sütun grid layout
  - Touch-friendly interface
  - Orta boyut görseller
- **Desktop (769px+):** 
  - 3 sütun grid layout
  - Hover efektleri
  - Büyük görseller ile detaylı görünüm

**Adaptive Özellikler:**
- Görseller ekran boyutuna göre otomatik ölçeklenir
- Buton boyutları cihaza göre optimize edilir
- Text boyutları responsive olarak ayarlanır

## 🎨 Tasarım Detayları

**Renk Paleti:**
- **Primary Orange:** #C5621B (Lazzoni marka rengi - butonlar, vurgular)
- **Hover Orange:** #A0501A (Mouse üzerine gelince buton rengi)
- **Text Color:** #333333 (Ana metin rengi)
- **Light Text:** #666666 (Açıklama metinleri)
- **Background:** #FFFFFF (Ana arkaplan) / #FAFAFA (Alternatif bölümler)

**Typography:**
- **Ana Font:** Century Gothic Light (modern ve şık görünüm)
- **Fallback:** Arial, sans-serif
- **Başlık Boyutları:** H1 (3rem/48px), H2 (2.2rem/35px)
- **Metin Boyutu:** 1.1rem/18px (okunabilirlik için optimize)

**Layout Sistemi:**
- **Hero Section:** Tam genişlik banner + overlay metin
- **Grid System:** Her kategoride 3x1 ürün gösterimi
- **Spacing:** Tutarlı margin/padding sistemi
- **Animations:** Smooth scroll, hover efektleri, fade-in animasyonları

## 🚀 Kurulum

### Shopify Admin Paneline Giriş
- **URL:** https://lazzzoni.myshopify.com/admin
- **Şifre:** lazzonikerem

### Dosyaları Yükleme
1. Shopify Admin → Online Store → Themes
2. Horizon temasında Actions → Edit code
3. Bu projedeki dosyaları ilgili klasörlere yükleyin

---

**Geliştirici:** Kerem İhsan Ulaşan  
**Versiyon:** 1.0  
**Son Güncelleme:** 2024