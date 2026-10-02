# UBEYDULLAH DOĞAN — PORTFOLIO

Cyberpunk temalı kişisel portfolyo sitesi. TR / DE / EN üç dil desteği.

## Özellikler

- **3 Dil Desteği**: Türkçe, Almanca (Deutsch), İngilizce (English)
- **Resim Galerisi**: Bamsı, Ben, Arkadaşlar kategorileri (tıkla büyüt, tekrar tıkla küçült)
- **Sertifika & Ehliyet Görselleri**: Altında seçilen dilde açıklama
- **Saha Tecrübeleri**: Timeline formatında deneyimler
- **WhatsApp İletişim**: +90 530 244 74 48
- **Hızlı ve Hafif**: Three.js veya ağır kütüphaneler yok, akıcı çalışır

## GitHub Pages'te Yayınlama

1. [github.com](https://github.com) hesabınıza giriş yapın
2. **New repository** butonuna tıklayın
3. Repository adını `kullaniciadi.github.io` olarak belirleyin (örn: `ubeydullahdogan.github.io`)
4. **Create repository** deyin
5. Bu .7z dosyasındaki tüm dosyaları çıkarın
6. Çıkan dosyaları GitHub repository'sine yükleyin:
   - **uploading an existing file** seçeneğiyle sürükle-bırak yapabilirsiniz
   - Veya Git komutlarıyla:
     ```
     git init
     git add .
     git commit -m "Portfolio site"
     git branch -M main
     git remote add origin https://github.com/KULLANICIADI/kullaniciadi.github.io.git
     git push -u origin main
     ```
7. Repository ayarlarında **Settings > Pages** bölümüne gidin
8. **Source** kısmında **Deploy from a branch** seçin
9. **Branch** olarak `main` ve `/ (root)` seçin
10. **Save** deyin
11. 1-2 dakika içinde siteniz `https://kullaniciadi.github.io` adresinde yayında olacak

## Fotoğraf Ekleme

Sertifikalar, ehliyet ve galeri fotoğraflarını eklemek için:

### Sertifika görselleri
`assets/img/certificates/` klasörüne sertifika fotoğraflarını koyun, ardından `index.html` içindeki ilgili `cert-img-wrap` bölümündeki placeholder'ı `<img src="assets/img/certificates/sertifika1.jpg">` ile değiştirin.

### Galeri görselleri
`assets/img/gallery/` klasörüne fotoğrafları koyun, ardından `index.html` içindeki galeri bölümündeki placeholder'ları `<img src="assets/img/gallery/foto1.jpg">` ile değiştirin.

### Avatar
`assets/img/avatar.jpg` dosyasını kendi görselinizle değiştirin.

## Telif Hakkı

Bu site yalnızca kullanıcının kendi görsellerini içerir. Tüm metinler özgün olarak yazılmıştır. Font Awesome, Google Fonts CDN üzerinden kullanılmaktadır (ücretsiz lisans).

## İletişim

- WhatsApp: +90 530 244 74 48
- E-posta: ubixdubi@gmail.com
- Instagram: @UBEYDULLAHDOGAN44
