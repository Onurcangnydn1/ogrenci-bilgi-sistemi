# 🎓 Öğrenci Bilgi Sistemi (ÖBS) Web Uygulaması

Modern, hafif ve tamamen istemci taraflı (client-side) çalışan, rol tabanlı bir Öğrenci Bilgi Sistemi (ÖBS) prototipi. Herhangi bir sunucu veya harici bağımlılık gerektirmeden tarayıcı üzerinde yerel depolama (`localStorage`) ile kalıcı veri yönetimi sağlar.

---

## 🔗 Bağlantılar

- **Canlı Demo (Netlify):** [Projeyi Görüntüle](BURAYA_NETLIFY_LINKINI_YAPISTIR)
- **Kaynak Kod (GitHub):** [GitHub Reposu](BURAYA_GITHUB_REPO_LINKINI_YAPISTIR)

---

## 📸 Ekran Görüntüleri

| Akademisyen Paneli | Öğrenci Transkripti & Notlar |
|:---:|:---:|
| ![Akademisyen Paneli](screenshot1.png) | ![Öğrenci Paneli](screenshot2.png) |

*(Not: Ekran görüntülerini repoya yüklerseniz dosya adlarını yukarıdakiyle eşleştirebilirsiniz)*

---

 Temel Özellikler

👨‍🏫 Akademisyen Paneli
- Ders Açma & Yönetimi: Yeni ders kodu, isim, kredi ve AKTS belirleyerek dinamik müfredat tanımı.
- Not Girişi: Derse kayıtlı öğrencilere Vize (%40) ve Final (%60) notu girme / düzenleme.
- Dinamik Harf Baremi: AA, BA, BB, CB, CC, DC, DD taban puanlarını arayüzden güncelleme ve anlık yeniden hesaplama motoru.
- Devamsızlık Takibi: 10 saati aşan devamsızlıklarda otomatik `DZ (Devamsız)` statüsü ve görsel uyarı.
- Sınıf İstatistikleri: Sınıf not ortalaması, en yüksek/en düşük not ve başarı (geçme) oranı kartları.
- Anlık Arama: Öğrenci adı veya numarasına göre filtreleme.

👨‍🎓 Öğrenci Paneli
- Ders Kayıt / Seçim:Açılan dersler kataloğundan tek tıkla ders ekleme veya bırakma.
- Not & Devamsızlık Takibi: Dönemlik notlar, harf başarı durumları ve devamsızlık saatleri.
- Dönem GNO (GPA) Motoru: Kredi ve harf katsayılarına göre otomatik ağırlıklı not ortalaması hesabı.
- Resmi Transkript Çıktısı: Tek tıkla yazdırılabilir veya PDF olarak kaydedilebilir dönem transkript dökümü (`window.print`).
- Profil Güncelleme:Telefon, e-posta ve adres bilgilerini düzenleme.



🛠️ Kullanılan Teknolojiler

- HTML5 & Semantic Web: Standart ve erişilebilir sayfa yapısı.
-Tailwind CSS (CDN): Responsive, modern ve sade arayüz tasarımı.
- Vanilla JavaScript (ES6+): Çerçeve bağımsız DOM manipülasyonu, event yönetimi ve ilişkisel veri mantığı simülasyonu.
- LocalStorage API: Sayfa yenilense dahi derslerin, notların ve profillerin korunmasını sağlayan tarayıcı tabanlı veri kalıcılığı.
- Font Awesome: Arayüz ikon seti.



🚀 Kurulum ve Çalıştırma

Projeyi çalıştırmak için herhangi bir paket yöneticisi (`npm`, `yarn`) veya yerel backend sunucusu kurmanıza gerek yoktur:

1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git](https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git)
