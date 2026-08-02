<div align="center">

# ⚡ 4-in-1 ESC Kartı — TÜBİTAK 2209-A

*İHA sistemleri için entegre güç yönetimi ve akım ölçümü özellikli 4-in-1 Elektronik Hız Kontrolcü Kartı*

</div>

---

## 📌 Proje Hakkında

Bu proje, İnsansız Hava Araçları için geleneksel ESC'lerin ötesine geçen, yüksek entegrasyonlu bir 4-in-1 Elektronik Hız Kontrol Kartı geliştirmeyi hedeflemektedir. Motor kontrol işlevine ek olarak dahili **5V ve 12V regülatör devreleri** ile **şönt direnç tabanlı akım ölçüm devresi** doğrudan kart üzerine entegre edilmiştir.

Bu sayede harici güç modüllerine olan ihtiyaç azaltılarak daha az kablolama, daha düşük ağırlık ve daha yüksek sistem güvenilirliği elde edilmesi amaçlanmaktadır.

> 🏆 **TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri Destekleme Programı**  
> **Danışman:** Prof. Dr. Bahattin TÜRETKEN  
> **Üniversite:** Kocaeli Üniversitesi

---

<div align="center">

## 📄 Proje Raporu

TÜBİTAK 2209-A kapsamında hazırlanan proje raporunu aşağıdaki bağlantıdan görüntüleyebilir veya indirebilirsiniz.

<a href="mert_uzun_insansiz_hava_araclarinda_entegre_guc_dagitimi_ve_akim_olcumu_ozellikli_4in1_elektronik_hiz_kontrolcu_karti.pdf">
  <img src="https://img.shields.io/badge/PDF-Proje_Raporunu_Görüntüle-red?style=for-the-badge&logo=adobeacrobatreader" alt="Proje Raporu">
</a>

<br><br>

[📥 Proje Raporunu Görüntüle / İndir](mert_uzun_insansiz_hava_araclarinda_entegre_guc_dagitimi_ve_akim_olcumu_ozellikli_4in1_elektronik_hiz_kontrolcu_karti.pdf)

</div>

---

## ⚙️ Donanım

| Bileşen | Model | Görev |
|---|---|---|
| MCU | AT32F421K8U7 | Ana mikrodenetleyici |
| Gate Driver | FD6288Q | MOSFET sürücü |
| Power Stage | NTMFS5C410NLT3G | Motor sürme MOSFET'i |
| DC-DC Buck | TPS54360DDAR | 6S batarya gerilimini 5V ve 12V seviyelerine dönüştürme |
| LDO Regülatör | MCP1700-3.3V | 5V gerilimi 3.3V seviyesine dönüştürme |
| Akım Sensörü | INA199A1DCKR | Şönt direnç üzerindeki gerilimi ölçme |
| Şönt Direnç | CS25FTER100 | Toplam sistem akımını ölçme |
| TVS Diyot | SMDJ28CA | Ani gerilim darbelerine karşı koruma |

---

## ✨ Özellikler

- ✈️ Dört adet BLDC motorun bağımsız ve eş zamanlı kontrolü
- 🔋 6S Li-Po batarya desteği
- ⚡ Dahili 5V ve 12V DC-DC regülatör çıkışları
- 🔌 Harici BEC ihtiyacını azaltan entegre güç dağıtım yapısı
- 📊 Şönt direnç üzerinden ±%5 hedef hassasiyetle toplam akım ölçümü
- 📡 Ölçülen akım bilgisinin ADC üzerinden uçuş kontrolcüsüne iletilmesi
- 🔄 Üç fazlı MOSFET köprü devresiyle yüksek verimli motor sürme
- 🛡️ TVS diyot ile ani gerilim darbelerine karşı güç hattı koruması
- 📦 Kompakt ve yüksek entegrasyonlu PCB tasarımı

---

## 🎯 Proje Hedefleri

- 5V ve 12V DC-DC dönüştürücü devrelerini ESC kartına entegre etmek
- Güç hattına şönt direnç yerleştirerek **±%5 hata payı** hedefiyle toplam akım ölçümü gerçekleştirmek
- Ölçülen akım bilgisini MCU ADC birimi üzerinden uçuş kontrolcüsüne iletmek
- 6S Li-Po batarya ile uyumlu bir güç yapısı oluşturmak
- Dört BLDC motoru eş zamanlı olarak kontrol edebilen kompakt bir kart geliştirmek
- Gerilim regülasyonu ve akım ölçüm performansını saha testleriyle doğrulamak
- Harici güç modüllerine olan ihtiyacı ve sistemdeki kablo sayısını azaltmak

---

## 🖼️ Görseller

### 📐 Şematik — Güç Regülasyonu ve Akım Ölçümü

![Güç regülasyonu ve akım ölçümü şeması](guc.png)

---

### 📐 Şematik — Güç ve Kontrol Bölümleri

![Güç ve kontrol bölümleri şeması](kontrol.png)

---

### 💻 PCB Tasarımı

> 🔄 PCB tasarımı devam etmektedir. Tasarıma ait görseller tamamlandıktan sonra bu bölüme eklenecektir.

---

### 🏭 Üretim ve Test

> 🔄 Kartın üretim ve test süreçleri tamamlandıktan sonra üretim görselleri ve test sonuçları bu bölüme eklenecektir.

---

## 📌 Proje Durumu

- [x] Sistem gereksinimlerinin belirlenmesi
- [x] Bileşen seçimi
- [x] Güç regülasyon devrelerinin tasarlanması
- [x] Akım ölçüm devresinin tasarlanması
- [x] Motor sürücü devresinin hazırlanması
- [ ] PCB tasarımının tamamlanması
- [ ] Kart üretimi
- [ ] Devre testleri
- [ ] Motor testleri
- [ ] Akım ölçüm kalibrasyonu
- [ ] Saha testleri

---

<div align="center">

## 👤 Proje Yürütücüsü

**Mert Uzun**  
Kocaeli Üniversitesi  
Elektronik ve Haberleşme Mühendisliği

[<img src="https://img.icons8.com/color/48/linkedin.png" width="40" height="40" alt="LinkedIn"/>](https://www.linkedin.com/in/mert-uzun-b74459308)

</div>
