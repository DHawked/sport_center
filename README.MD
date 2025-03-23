# sport_center


# PowerFull Sport Center

[English](#english-documentation) | [Türkçe](#turkish-documentation)

## English Documentation

This project is a responsive website developed for a sport center called "PowerFull". It features various interactive elements including class selection tabs, BMI calculator, trainer profiles with hover effects, and Google Maps integration.

### Live Demo

[Click here to view the live demo](https://sunny-kelpie-3a82ac.netlify.app/)

### Screenshots

#### Desktop View
![Desktop View](screenshots/desktop.png)

#### Mobile View
![Mobile View](screenshots/mobile.png)

### Features

- Responsive design (specially optimized for 576px width devices)
- Mobile menu with toggle functionality
- Interactive class selection tabs
- BMI (Body Mass Index) calculator
- Google Maps integration
- Trainer cards with hover effects
- Fixed navbar during scroll
- Smooth scrolling between sections

### Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Google Maps API
- Font Awesome
- Google Fonts (Montserrat & Poppins)

### Project Requirements and Implementation

1. *Class Buttons*: All buttons under "Our Classes" are functional and show the appropriate content for each sport type.

2. *Hover Effect*: The trainer cards in the "Our Best Trainers" section have hover effects that display additional information when users hover over them.

3. *BMI Calculator*: Users can enter their height and weight to calculate their BMI using the formula BMI = kg/m². The result is visually indicated with an arrow.

4. *Navbar*: The navigation bar remains fixed during scrolling and changes its background color to #355592. All links correctly direct to their respective sections.

5. *Google Maps*: An active Google Maps is integrated in the Contact section.

6. *Responsive Design*: The page has been specially designed for 576px width, following the required responsive layout.

### Installation

1. Clone the repository to your computer:

   ```bash
   git clone https://github.com/DHawked/sport_center.git
   ```

2. Navigate to the project folder:

   ```bash
   cd sport_center
   ```

3. Open the index.html file in your browser or view the project using a local server.

### Google Maps API Usage

To use Google Maps:

1. Get an API key from [Google Cloud Console](https://console.cloud.google.com/)
2. Add the API key to the script tag in the index.html file:

   ```html
   <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>
   ```

### Project Structure

```
sport-center/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # CSS styles
├── js/
│   └── script.js       # JavaScript functions
├── img/                # Image files
│   ├── logo.png
│   ├── hero-man.jpg
│   ├── bmi-index.jpg
│   └── ... (other images)
├── screenshots/        # Project screenshots
│   ├── desktop.png
│   └── mobile.png
└── README.md           # Project documentation
```

### Known Issues

- Google Maps API key needs to be added
- May not be fully optimized for mobile devices outside of 576px width

### Future Enhancements

- Responsive adjustments for more screen resolutions
- Online class reservation system
- Member login and profile pages
- Online payment system

---

## Turkish Documentation

Bu proje, "PowerFull" adlı bir spor merkezi için geliştirilen responsive bir web sitesidir. Sınıf seçim sekmeleri, BMI hesaplayıcı, hover efektli eğitmen profilleri ve Google Maps entegrasyonu gibi çeşitli interaktif öğeler içerir.

### Canlı Demo

[Canlı demoyu görüntülemek için tıklayın](https://sunny-kelpie-3a82ac.netlify.app/)

### Ekran Görüntüleri

#### Masaüstü Görünümü
![Masaüstü Görünümü](screenshots/desktop.png)

#### Mobil Görünümü
![Mobil Görünümü](screenshots/mobile.png)

### Özellikler

- Responsive tasarım (özellikle 576px genişliğindeki cihazlar için optimize edilmiş)
- Açılır-kapanır mobil menü
- İnteraktif sınıf seçim sekmeleri
- BMI (Vücut Kitle İndeksi) hesaplayıcı
- Google Maps entegrasyonu
- Hover efektli eğitmen kartları
- Scroll sırasında sabit kalan navbar
- Bölümler arası yumuşak geçiş

### Kullanılan Teknolojiler

- HTML5
- CSS3
- JavaScript (Vanilla)
- Google Maps API
- Font Awesome
- Google Fonts (Montserrat & Poppins)

### Proje Gereksinimleri ve Uygulama

1. *Sınıf Butonları*: "Our Classes" altındaki tüm butonlar aktif çalışıyor ve her spor türü için uygun içeriği gösteriyor.

2. *Hover Efekti*: "Our Best Trainers" bölümündeki eğitmen kartları, kullanıcılar üzerine geldiğinde ek bilgi görüntüleyen hover efektlerine sahip.

3. *BMI Hesaplayıcı*: Kullanıcılar boy ve kilo bilgilerini girerek BMI = kg/m² formülü ile BMI değerlerini hesaplayabilirler. Sonuç, ok işareti ile görsel olarak gösterilir.

4. *Navbar*: Navigasyon çubuğu scroll sırasında sabit kalır ve arka plan rengi #355592 olarak değişir. Tüm linkler doğru bölümlere yönlendirir.

5. *Google Maps*: İletişim bölümünde aktif bir Google Maps haritası entegre edilmiştir.

6. *Responsive Tasarım*: Sayfa, gerekli responsive düzeni takip ederek özellikle 576px genişlik için tasarlanmıştır.

### Kurulum

1. Repoyu bilgisayarınıza klonlayın:

   ```bash
   git clone https://github.com/DHawked/sport_center.git
   ```

2. Proje klasörüne gidin:

   ```bash
   cd sport_center
   ```

3. index.html dosyasını tarayıcınızda açın veya bir yerel sunucu kullanarak projeyi görüntüleyin.

### Google Maps API Kullanımı

Google Maps'i kullanabilmek için:

1. [Google Cloud Console](https://console.cloud.google.com/)'dan bir API anahtarı alın
2. API anahtarını index.html dosyasındaki ilgili script etiketine ekleyin:

   ```html
   <script src="https://maps.googleapis.com/maps/api/js?key=API_ANAHTARINIZ&callback=initMap" async defer></script>
   ```

### Bilinen Sorunlar

- Google Maps API anahtarı eklenmeli
- 576px dışındaki mobil cihazlar için tam olarak optimize edilmemiş olabilir

### Gelecek Geliştirmeler

- Daha fazla ekran çözünürlüğü için responsive ayarlamalar
- Online sınıf rezervasyon sistemi
- Üye girişi ve profil sayfaları
- Online ödeme sistemi

