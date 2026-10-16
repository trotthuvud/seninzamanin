# ⏱️ seninzamanın — ÖSYM Geri Sayım & Deneme Zamanlayıcı

<div align="center">

[![Canlı Web Sitesi](https://img.shields.io/badge/Canl%C4%B1%20Site-seninzamanin.netlify.app-4f6ef7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://seninzamanin.netlify.app/)
[![Netlify Status](https://img.shields.io/badge/Netlify-Yay%C4%B1nda-00c7b7?style=for-the-badge&logo=netlify&logoColor=white)](https://seninzamanin.netlify.app/)
[![PWA Ready](https://img.shields.io/badge/PWA-Destekli-5a0fc8?style=for-the-badge&logo=pwa&logoColor=white)](https://seninzamanin.netlify.app/)
[![License](https://img.shields.io/badge/Lisans-Telif%20Hakk%C4%B1%20Sakl%C4%B1d%C4%B1r-red?style=for-the-badge)](LICENSE)

<br/>

### 🎯 Sınavlara kalan süre, saniye saniye. Odaklan, çöz, başar.

**[🚀 Canlı Uygulamayı Aç ve Kullan](https://seninzamanin.netlify.app/)**

<br/>

</div>

---

## 📌 Proje Hakkında

**seninzamanın**, ÖSYM sınavlarına (YKS, KPSS, ALES, YDS, MSÜ, DGS vb.) hazırlanan öğrencilerin ve adayların sınav sürecini tek bir ekrandan profesyonelce yönetebilmesi için geliştirilmiş modern bir web platformudur.

Harici hiçbir kütüphaneye veya ağır çatıya (framework) bağımlı olmadan, **%100 saf web teknolojileri (Vanilla JS, CSS3, Web Audio API)** ile sıfır gecikmeli, yüksek performanslı ve çevrimdışı (offline) çalışacak şekilde tasarlanmıştır.

---

## ✨ Öne Çıkan Özellikler

### 1. ⏱️ ÖSYM Canlı Geri Sayım & Akıllı Takvim
- **Saniye Hassasiyetinde Geri Sayım**: Yaklaşan sınavlar gün, saat, dakika ve saniye birimleriyle anlık hesaplanır.
- **Akıllı Başvuru & Sonuç Rozetleri**: Başvuru dönemi açılan sınavlar için `🟢 Başvurular Açık`, yaklaşanlar için başvuru tarihleri ve sonuç günleri otomatik listelenir.
- **Sınav Detayları Kılavuzu**: Tek tıkla soru sayısı, sınav süresi, oturum bilgileri ve hazırlık notlarını içeren detaylı modal pencere.
- **Kişisel Sınav Ekleme**: Kullanıcı kendi okul/kurum deneme sınavlarını takvime ekleyebilir.

### 2. 🎵 Web Audio Ambient Odak Sesleri (Arka Plan Sesleri)
- **Sıfır Veri Transferi**: Harici mp3/ses dosyası indirmez; doğrudan tarayıcının ses sentezleyicisi (Web Audio API) ile ses dalgalarını gerçek zamanlı üretir.
- **6 Farklı Ses Modu**:
  - 🌧️ **Yağmur**: Huzurlu yağmur damlaları ve esinti tınısı
  - 🌊 **Okyanus**: Nefes ritimli meditatif dalga salınımları
  - ☕ **Kafe**: Odaklanmayı artıran hafif ortam gürültüsü
  - 🔥 **Şömine**: Çıtırdayan odun sesleri
  - 🌳 **Orman**: Esinti ve aralıklı kuş cıvıltıları
  - 📻 **Beyaz Gürültü**: Çevredeki dikkat dağıtıcı sesleri maskeleyen sabit frekans
- **Zamanlayıcıyla Senkron**: Kronometre veya Pomodoro başladığında otomatik çalar, mola verildiğinde durur.

### 3. 📝 Çalışma Görev Listesi (To-Do) & Aktif Görev Kartı
- Günlük çözülecek soru veya ders hedeflerini kaydetme.
- **"🎯 Odaklan" Butonu**: Görevi sayacın üstündeki büyük odak kartına bağlar.
- Tamamlandığında tek tıkla işaretleme ve otomatik kutlama.

### 4. 🎊 Kutlama & Konfeti Animasyonu
- Hafif, canvas tabanlı konfeti motoru.
- Süre dolduğunda, Pomodoro seansı bittiğinde veya hedef nete ulaşıldığında kullanıcıyı motive eden kutlama efekti.

### 5. 📅 Son 30 Günlük Çalışma Heatmap'i & İstatistikler
- GitHub tarzı 30 günlük çalışma yoğunluğu haritası (0dk, 30dk, 1sa, 2sa+ renk tonlaması).
- "Bugün", "Toplam Süre", "Oturum Sayısı" ve "Günlük Seri (Streak)" göstergeleri.

### 6. 🏆 Başarı Rozetleri (Gamification)
- Öğrencinin çalışma disiplinini ödüllendiren 8 özel başarım rozeti:
  - 🌱 *İlk Adım* · 🔥 *3 Günlük Seri* · ⚡ *Haftalık Zafer* · 🏆 *Aylık Şampiyon*
  - 🍅 *Pomodoro Ustası* · ⏱️ *Maratoncu* · 🦉 *Gece Kuşu* · 🎯 *Hedef Vurucu*

### 7. 🔢 Net Hesaplayıcı & Puan Tahmini
- ÖSYM (4 yanlış 1 doğru) ve LGS (3 yanlış 1 doğru) düzeltme kuralı.
- TYT, AYT (SAY, EA, SÖZ, DİL) ve KPSS P3 puan simülatörü.
- Diploma notu (OBP) ve kırık OBP katsayı desteği.

---

## 🛠️ Kullanılan Teknolojiler

| Alan | Teknoloji | Açıklama |
|---|---|---|
| **Arayüz (UI)** | HTML5, Modern CSS3 | CSS Değişkenleri, Flexbox, CSS Grid, Responsive Tasarım |
| **Mantık & Motor** | Vanilla JavaScript (ES6+) | Sıfır harici kütüphane, yüksek hız, ultra düşük bellek kullanımı |
| **Ses Motoru** | Web Audio API | Gerçek zamanlı matematiksel ses sentezleme (Ambient sesler) |
| **Çevrimdışı (PWA)** | Service Worker & Manifest | İnternetsiz tam işlevsel çalışma ve telefona uygulama olarak kurulabilme |
| **Barındırma & Dağıtım** | Netlify Edge | Global CDN üzerinden SSL korumalı hızlı dağıtım |

---

## 🔒 Lisans ve Telif Hakları

Bu proje **kapalı kaynak kodlu (proprietary)** tescilli bir yazılımdır. Tüm mülkiyet ve fikri hakları **[trotthuvud](https://github.com/trotthuvud)** tarafına aittir.

- Projenin kaynak kodlarının, tasarımının veya herhangi bir bileşeninin izinsiz olarak kopyalanması, çoğaltılması, dağıtılması veya başka bir adreste yeniden barındırılması (host edilmesi) yasaktır.
- Detaylı bilgi için [LICENSE](LICENSE) dosyasını inceleyebilirsiniz.

---

## 💬 Geri Bildirim ve İletişim

Sitede görmek istediğiniz yeni bir özellik veya sınav takvimi güncellemesi için [GitHub Issues](https://github.com/trotthuvud/seninzamanin/issues) sekmesinden öneri açabilir veya doğrudan iletişime geçebilirsiniz.

<div align="center">
  <sub>Geliştirici: <b><a href="https://github.com/trotthuvud">trotthuvud</a></b> · 2026</sub>
</div>
