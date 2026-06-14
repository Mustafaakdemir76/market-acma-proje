[README.md](https://github.com/user-attachments/files/28926296/README.md)
# 🛒 Market Açma — Proje Yönetim Yazılımı

> Sıfırdan geliştirilen, market açma sürecine özel web tabanlı proje yönetim uygulaması.

🔗 **Canlı Demo:** [marketacmaproje.github.io](https://mustafaakdemir76.github.io/market-acma-proje/market-acma-proje.html)

---

## 📌 Proje Hakkında

Bu yazılım, bir market açma projesinin tüm aşamalarını (ruhsat, dekorasyon, stok, personel, pazarlama) tek bir arayüzden yönetmek için sıfırdan geliştirilmiştir. Trello veya Asana gibi genel amaçlı araçlar yerine, projeye özel kategoriler, Türkçe arayüz ve bütçe-görev entegrasyonu sunar.

---

## 🖥️ Ekran Görüntüleri

| Genel Bakış | Kanban Panosu |
|---|---|
| Açılışa geri sayım, faz ilerleme, bütçe özeti | 4 sütunlu görev panosu |

| Zaman Çizelgesi | Bütçe Takibi |
|---|---|
| Tüm görevler, ilerleme ve durum | Planlanan vs gerçekleşen harcamalar |

---

## ✨ Özellikler

- **📊 Genel Bakış** — Açılışa geri sayım, faz ilerleme çubukları, bütçe özeti ve son aktiviteler
- **🗂️ Kanban Panosu** — Yapılacak / Devam Ediyor / İncelemede / Tamamlandı sütunları, yeni görev ekleme
- **📅 Zaman Çizelgesi** — Tüm görevler tablo halinde, ilerleme barları ve durum etiketleri
- **👥 Ekip Yönetimi** — Her üye için görev dağılımı ve istatistikleri
- **💰 Bütçe Takibi** — 11 bütçe kalemi, planlanan-gerçekleşen karşılaştırması, renk kodlu durum
- **⚠️ Risk Yönetimi** — 6 risk kartı, önem seviyesi ve azaltma stratejileri
- **➕ Görev Ekleme** — Modal form ile anlık kanban güncellemesi

---

## 🚀 Kurulum ve Kullanım

Herhangi bir kurulum gerekmez. Tek dosyadır, tarayıcıda çalışır.

```bash
# Repoyu klonla
git clone https://github.com/Mustafaakdemir76/market-acma-proje.git

# Dosyayı tarayıcıda aç
cd market-acma-proje
# market-acma-proje.html dosyasını çift tıkla
```

Ya da doğrudan canlı demo linkini ziyaret et:
**[https://mustafaakdemir76.github.io/market-acma-proje/market-acma-proje.html](https://mustafaakdemir76.github.io/market-acma-proje/market-acma-proje.html)**

---

## 🗂️ Proje Yapısı

```
market-acma-proje/
│
├── market-acma-proje.html    # Ana uygulama (tek dosya, bağımlılık yok)
├── README.md                 # Bu dosya
└── Market_Acma_30_Soru.docx  # Proje savunması için 30 soru-cevap
```

---

## 🧰 Teknolojiler

| Teknoloji | Kullanım |
|---|---|
| HTML5 | Sayfa yapısı |
| CSS3 | Koyu tema, animasyonlar, responsive tasarım |
| Vanilla JavaScript | Kanban, modal, veri yönetimi |
| Google Fonts | Syne + DM Sans tipografisi |

Harici framework veya kütüphane kullanılmamıştır. Tüm kod sıfırdan yazılmıştır.

---

## 📋 Proje Verileri

### Görev Kategorileri
| Kategori | Renk | Görev Sayısı |
|---|---|---|
| Ruhsat / İzin | 🔵 Mavi | 4 |
| Dekorasyon | 🟣 Mor | 3 |
| Teknik | 🔴 Kırmızı | 4 |
| Stok / Tedarik | 🟢 Yeşil | 2 |
| Pazarlama | 🟡 Amber | 3 |

### Ekip
| Ad | Rol |
|---|---|
| Ahmet Kaya | Proje Müdürü |
| Fatma Kılıç | Ruhsat Sorumlusu |
| Murat Yıldız | Tedarik Uzmanı |
| Selin Öztürk | Pazarlama |
| Emre Çelik | Teknik Sorumlu |

### Bütçe Özeti
| Kalem | Tutar |
|---|---|
| Toplam Planlanan | ₺155.500 |
| Harcanan | ₺100.700 |
| Kalan | ₺54.800 |

---

## 📅 Zaman Planı

```
Mayıs 2025     →  Ruhsat başvuruları, yazılım kurulumu
Haziran 2025   →  Dekorasyon, stok temini, personel alımı
1 Temmuz 2025  →  🏪 AÇILIŞ
```

---

## 📄 Lisans

Bu proje eğitim amaçlı geliştirilmiştir. MIT Lisansı ile lisanslanmıştır.

---

<p align="center">
  Geliştiren: <strong>Mustafa Akdemir</strong> · 2025
</p>
