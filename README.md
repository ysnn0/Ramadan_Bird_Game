# 🌙 Hafız Havada — Ramazan Özel

![Durum](https://img.shields.io/badge/Durum-Tamamland%C4%B1-success?style=for-the-badge)
![Teknoloji](https://img.shields.io/badge/Teknoloji-HTML5%20Canvas%20%7C%20ES6%2B-blue?style=for-the-badge)
![Tema](https://img.shields.io/badge/Tema-Ramazan-gold?style=for-the-badge)

**Hafız Havada**, Ramazan ayına özel olarak tasarlanmış, HTML5 Canvas teknolojisi üzerine kurulu, modern ve atmosferik bir arcade oyunudur. Flappy Bird mekaniklerinden esinlenilen bu oyun, özel İslami motifler, altın varaklı arayüz tasarımları ve akıcı fizik motoru ile geliştirilmiştir.

---

## 🎮 Oynanış ve Özellikler

Bu proje, standart bir web oyununun ötesinde, kullanıcı deneyimini (UX) ve görsel estetiği ön planda tutar.

* **Ramazan Teması:** Koyu lacivert, zümrüt yeşili ve altın renk paletiyle (Design Tokens kullanılarak) tasarlanmış atmosferik arayüz.
* **Responsive Tasarım:** Hem masaüstü (Mouse/Klavye) hem de mobil dokunmatik ekranlarda (Touch Events) kusursuz çalışır.
* **Gelişmiş Fizik Motoru:** Yerçekimi, süzülme (lift) ve çarpışma testleri (hitbox) içeren özel fizik hesaplamaları.
* **Yüksek Skor Sistemi:** Oyuncunun en yüksek skorunu tarayıcı hafızasında (`localStorage`) saklar.
* **Asset Loader:** Görseller yüklenmeden oyunun başlamasını engelleyen, `Promise` tabanlı güvenli yükleme sistemi.
* **Fallback Sistemi:** Eğer görseller yüklenemezse, oyun otomatik olarak Canvas çizimleriyle (renkli kutular) çalışmaya devam eder.

---

## 🛠️ Kullanılan Teknolojiler

Proje herhangi bir oyun motoru (Unity, Phaser vb.) kullanılmadan, tamamen **Vanilla JavaScript** ile geliştirilmiştir.

* **Core:** HTML5 Canvas API
* **Dil:** JavaScript (ES6+ Classes)
* **Stil:** CSS3 (CSS Variables, Flexbox, Keyframe Animations)
* **Ses:** HTML5 Audio API

---

## 📂 Proje Yapısı

Oyunun kod mimarisi Nesne Yönelimli (OOP) prensiplere göre modüler parçalara ayrılmıştır:

```text
HafizHavada/
│
├── index.html          # Tüm oyun kodu (HTML/CSS/JS) tek dosya yapısındadır.
├── rt.png              # Arka plan görseli (Seamless Loop)
├── dragon.png          # Karakter görseli (Hafız/Kuş)
├── br.png              # Engel/Boru görseli
└── müzik.mp3           # Arka plan müziği
