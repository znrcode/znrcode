# Projelerim

Bu sayfada üzerinde çalıştığım ve geliştirmeyi planladığım yazılım, gömülü sistem ve IoT projelerini bulabilirsiniz. Projelerin durumları özellikle belirtilmiştir; tasarım aşamasındaki çalışmalar tamamlanmış ürün gibi sunulmamıştır.

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
**Durum:** Kaynak kodu mevcut · GitHub deposu henüz yayınlanmadı

Mağaza giriş-çıkış hareketlerini sensörlerle takip ederek temel mağaza izleme işlevlerini gerçekleştirmeyi amaçlayan bir IoT projesidir.

Mevcut kaynak kodunda bulunan işlevler:
- ESP32 ve HC-SR04 ultrasonik sensör ile giriş-çıkış hareketlerini algılama
- Gün sonunda müşteri hareketi olmayan durumları kontrol etme
- Kepenk/kapı kontrolü için sistem entegrasyonu
- Telegram üzerinden günlük durum raporu gönderme

**GitHub deposu:** Henüz yayınlanmadı.

---

## 3. ESP32 Smart Trash Bin

**Alan:** Gömülü sistemler · ESP32 · Elektronik  
**Durum:** Kaynak kodu mevcut · GitHub deposu henüz yayınlanmadı

ESP32, HC-SR04 ultrasonik sensör ve servo motor kullanarak temassız kapak kontrolü sağlayan akıllı çöp kutusu projesidir.

Sensör belirlenen mesafe içinde hareket algıladığında servo motor kapağı açar; belirlenen süre sonunda kapak kapanır. Yeşil/kırmızı LED'ler kapak durumunu gösterir ve Wi-Fi bağlantısı üzerinden Telegram bildirimi gönderilir.

**GitHub deposu:** Henüz yayınlanmadı.

---

## 4. ARGUS — LoRa Tabanlı Afet Haberleşme ve Acil Durum Bildirim Sistemi

**Alan:** LoRa · Kablosuz haberleşme · Gömülü sistemler · Afet teknolojileri  
**Durum:** Tasarım ve sistem mimarisi aşaması

ARGUS, GSM, internet veya şebeke elektriğinin kullanılamadığı afet koşullarında kısa acil durum mesajlarının iletilmesini hedefleyen LoRa tabanlı bir haberleşme sistemidir. Mevcut haberleşme altyapılarının yerine geçmekten ziyade, kesinti durumlarında tamamlayıcı bir iletişim kanalı oluşturmayı amaçlar.

Öne çıkan tasarım hedefleri:
- LoRa üzerinden düşük güç tüketimli kısa mesaj iletimi
- Acil yardım taleplerinin merkezi bir noktada toplanması
- Yardım türüne göre bildirimlerin sınıflandırılması ve önceliklendirilmesi
- Sabit ve taşınabilir kullanıcı düğümlerinin değerlendirilmesi
- Haberleşme menzili ve sinyal güvenilirliğinin öncelikli olarak ele alınması

**GitHub deposu:** Henüz yayınlanmadı. Proje tasarım aşamasındadır.

---

## Proje yaklaşımım

Projelerimde yazılım ve donanımın birlikte çalışmasına, gerçek bir ihtiyaca çözüm üretmesine ve teknik kararların test edilebilir olmasına önem veriyorum. Geliştirme sürecinde yeni ilerlemeler oldukça bu sayfayı ve ilgili proje depolarını güncelleyeceğim.

[GitHub profilime dön](https://github.com/znrcode)
