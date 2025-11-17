# 🎮 Video Games Analytics & Sales Dashboard  
Bu proje, **1980–2020** yılları arasında piyasaya sürülen video oyunlarının satış performanslarını, platform başarılarını, kullanıcı ve eleştirmen puanlarını, bölgesel dağılımları ve oyuncu tiplerine göre eğilimleri inceleyen kapsamlı bir **Power BI veri analizi** çalışmasıdır.

Kaggle üzerinde yer alan *Popular Video Games Dataset* geliştirilerek; ek veri zenginleştirme, veri temizleme ve modelleme adımları uygulanmıştır. Proje sonunda kapsamlı bir dashboard ve tahmin modeli oluşturulmuştur.

---

## 🧰 Tools & Technologies  

- **Power BI**  
- **Python (Pandas, scikit-learn)** – ML modellemesi için  
- **Google Sheets / BigQuery** – veri ön işleme  
- **DAX Measures**  
- **Theme Customization & Dark Mode UI**  

---

## 📌 Key Insights  

### ⭐ 1. Genel KPI’lar  
- 12 oyun türü  
- 31 platform  
- 10 üretici firma  
- Ortalama Eleştirmen Puanı: **68.97**  
- Ortalama Kullanıcı Puanı: **7.13**

---

### ⭐ 2. Manufacturer Performance  
- Nintendo modern & retro kuşaklarda güçlü performans gösteriyor.  
- Sega retro dönemde öne çıkarken modern dönemde geriliyor.  
- Sony modern dönemde güçlü paya sahip.

---

### ⭐ 3. Retro vs Modern Market  
- **Modern dönem satışları %87.71**,  
- **Retro dönem satışları %12.29** oranındadır.  
Modern konsollar (PS4, Xbox, Switch vs.) global satışları ciddi şekilde artırmıştır.

---

### ⭐ 4. User vs Critic Score Analizi  
- Eleştirmen puanları genel olarak daha yüksek varyansa sahip.  
- Kullanıcı puanları ile eleştirmen puanları çoğu platformda uyumludur.  
- Farklı türlerde puan farkı görülmektedir (Örn: Shooter ve Sports türlerinde yüksek skor uyumu).

---

### ⭐ 5. Bölgesel Satış Analizi  
- Kuzey Amerika en yüksek paya sahiptir.  
- Japonya’da RPG türü aşırı baskın,  
- Avrupa’da Shooter ve Action öne çıkmaktadır.  
- Bölgesel tercih farklılıkları stratejik içgörüler sunmaktadır.

---

### ⭐ 6. Tür & Platform Dinamikleri  
- PS2, X360, PS3 ve Wii en çok satan platformlardır.  
- Oyun türlerine göre satış dağılımı; platformun kullanıcı kitlesi ile güçlü bir ilişki göstermektedir.  
- Racing, Shooter, Sports gibi türler satış hacmini artırmaktadır.

---

### ⭐ 7. ML Tahmin Modeli  
Son sayfada, oyunların **Global Sales** tahminini yapan bir makine öğrenmesi modeli bulunmaktadır.

**Model Performansı:**  
- MAE: **422.024K**  
- R²: **0.377**  
- Model doğruluk oranı ~%37  

**En Etkili Faktörler:**  
1. Average Critic Score  
2. Average User Score  
3. Genre  
4. Region  
5. Typical Player Type  

**Sonuç:**  
Yüksek eleştirmen & kullanıcı puanına sahip oyunlar satışta belirgin şekilde daha başarılıdır.  

---

## 🗂 Dashboard İçeriği

Dashboard 5 ana bölümden oluşmaktadır:

---

### 🎯 **1. Overview Page (KPI Page)**  
- Tür, platform, üretici sayıları  
- Ortalama puan KPI kartları  
- Pac-Man temalı ikon seti

---

### 🎯 **2. Sales Performance & Market Share**  
- Platform satış hacimleri  
- Retro vs Modern satış dağılımı  
- Manufacturer bazlı pazar payı  
- Tür bazlı satış karşılaştırmaları

---

### 🎯 **3. User & Critic Score Analysis**  
- Tür bazlı kullanıcı & eleştirmen skoru karşılaştırması  
- Platform bazlı skor dağılımları  
- Eleştirmen-kullanıcı skor farklarının analizi

---

### 🎯 **4. Regional Analysis**  
- Avrupa / Japonya / Kuzey Amerika / Diğer bölgeler satış dağılımları  
- Tür bazında bölgesel paylar  
- Bölgesel pazar farklılıkları  
- Oyun türlerinin yıllara göre bölgesel gelişimi

---

### 🎯 **5. Machine Learning Insights (Prediction Page)**  
- Oyun satış tahmini (Global Sales Prediction)  
- Özellik önem grafiği  
- Model sonuçları ve yorum  
- Oyun türü, skorlar ve oyuncu tipi bazlı analiz

---

## 📊 Dataset  

Kaggle Dataset:  
https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023  

Ek zenginleştirme sütunları eklenmiştir:  
- Genre grouping  
- Player type mapping  
- Innovation score  
- Story focus score  
- Region normalization  

---

## 💡 Business Recommendations  

1. **Yüksek eleştirmen & kullanıcı puanına sahip oyunlar satışta belirgin şekilde başarılıdır.  
   → Kalite metriğine yatırım yapılmalı.**

2. **Platform seçimi satışları doğrudan etkiliyor.  
   → PS2, X360, PS3, Wii benzeri yüksek başarı gösteren kuşaklar hedeflenmeli.**

3. **Bölgesel pazar farklılıkları önemlidir.  
   → Japonya: RPG  
   → Avrupa/NA: Shooter–Sports**

4. **Modern dönem satışları retro dönemden açık ara yüksek.  
   → Yeni nesil platformlara odaklanmak daha yüksek gelir sağlar.**

5. **ML analizine göre hikâye, inovasyon ve rekabet seviyesi satışlara anlamlı etki ediyor.  
   → Oyun tasarım stratejileri bu faktörlere göre planlanmalı.**

---

## 👩‍💻 Author  
**Gökçe Tür – Data Analyst**  
SQL • BigQuery • Power BI • Python • Machine Learning  
GitHub: gokcetur

