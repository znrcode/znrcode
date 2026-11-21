# Projelerim

Bu sayfada yazılım, gömülü sistem ve IoT alanlarında geliştirdiğim veya üzerinde çalıştığım projeler yer alıyor. Projelerin mevcut durumları ayrıca belirtilmiştir.

---

## 1. JPEG X-Ray — JPEG Metadata Parser

**Alan:** C programlama · Dosya biçimleri · Metaveri analizi  
**Durum:** GitHub deposu mevcut

JPEG X-Ray, JPEG dosyalarının ikili yapısını incelemek ve dosya içindeki çeşitli metaverileri ayrıştırmak amacıyla geliştirilmiş bir C aracıdır.

- JPEG işaretleyicilerini ve segment yapısını inceleme
- Görüntü boyutları ve JFIF çözünürlük bilgilerini okuma
- Desteklenen EXIF alanlarını ayrıştırma
- GPS, XMP, ICC ve diğer metaveri segmentlerini kontrol etme
- DQT tablolarından yaklaşık kalite tahmini yapma

**Kaynak kodu:** [znrcode/JPEG-X-Ray](https://github.com/znrcode/JPEG-X-Ray)

---

## 2. Smart Store Monitoring System

**Alan:** IoT · ESP32 · Sensör sistemleri  
**Durum:** Kaynak kodu GitHub'da yayınlandı

Mağaza giriş-çıkış hareketlerini sensörlerle takip ederek temel mağaza izleme ve gün sonu kontrol işlevlerini gerçekleştirmeyi amaçlayan bir IoT prototipidir.

- ESP32 ve HC-SR04 ultrasonik sensör ile geçiş algılama
- OLED ekranda geçiş ve tahmini müşteri sayısını gösterme
- Gün sonu butonu ile kontrol senaryosunu başlatma
- Tek sayıda geçişte içeride müşteri kalmış olabileceğine dair alarm
- Servo motorla kepenk kapatma komutu ve Telegram raporu

**Kaynak kodu:** [znrcode/Smart-Store-Monitoring](https://github.com/znrcode/Smart-Store-Monitoring)

---

## 3. ESP32 Smart Trash Bin

**Alan:** Gömülü sistemler · ESP32 · Elektronik  
**Durum:** Kaynak kodu GitHub'da yayınlandı

ESP32, HC-SR04 ultrasonik sensör ve servo motor kullanarak temassız kapak kontrolü sağlayan akıllı çöp kutusu prototipidir.

- 15 cm altındaki yaklaşmayı algılama
- Servo motor ile kapağı açma ve belirlenen süre sonunda kapatma
- Yeşil/kırmızı LED'lerle kapak durumunu gösterme
- Wi-Fi üzerinden Telegram bildirimi gönderme

**Kaynak kodu:** [znrcode/ESP32-Smart-Trash-Bin](https://github.com/znrcode/ESP32-Smart-Trash-Bin)

---

## 4. ARGUS — LoRa Tabanlı Afet Haberleşme ve Acil Durum Bildirim Sistemi

**Alan:** LoRa · Kablosuz haberleşme · Gömülü sistemler · Afet teknolojileri  
**Durum:** Tasarım ve sistem mimarisi aşaması

ARGUS, GSM, internet veya şebeke elektriğinin kullanılamadığı afet koşullarında kısa acil durum mesajlarının iletilmesini hedefleyen LoRa tabanlı bir haberleşme sistemidir. Mevcut haberleşme altyapılarının yerine geçmekten ziyade, kesinti durumlarında tamamlayıcı bir iletişim kanalı oluşturmayı amaçlar.

- LoRa üzerinden düşük güç tüketimli kısa mesaj iletimi
- Acil yardım taleplerinin merkezi bir noktada toplanması
- Yardım türüne göre bildirimlerin sınıflandırılması ve önceliklendirilmesi
- Sabit ve taşınabilir kullanıcı düğümlerinin değerlendirilmesi
- Haberleşme menzili ve sinyal güvenilirliğinin öncelikli olarak ele alınması

**GitHub deposu:** Henüz yayınlanmadı. Proje tasarım aşamasındadır.

---

## Proje yaklaşımım

Projelerimde yazılım ve donanımın birlikte çalışmasına, gerçek bir ihtiyaca çözüm üretmesine ve teknik kararların test edilebilir olmasına önem veriyorum. Geliştirme sürecindeki ilerlemeleri ilgili depolarda güncelleyeceğim.

[GitHub profilime dön](https://github.com/znrcode)
