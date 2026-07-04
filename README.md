# 🚀 Takım FinNexus AI - FinancialCoPilot

## 📌 Takım Rolleri ve Elemanları
* **[Ayşe Gül KURNAZ]:** Scrum Master & İletişim Sorumlusu[cite: 1]
* **[Sedef AKŞİN]:** Product Owner[cite: 1], (Kredibilite XAI Modül Sorumlusu)[cite: 1, 2]
* **[Azra Nur TABAK]:** Developer (Ekip İçi Kontrol Sorumlusu)[cite: 1, 2]
* **[Furkan ÖZÜDOĞRU]:** Developer (ChurnLens Modül Sorumlusu)[cite: 1, 2]
* **[Ahmet ZELKA]:** Developer (FinAnomaly Modül Sorumlusu)[cite: 1, 2]

---

## 💡 Ürün İle İlgili Bilgiler

### Ürün İsmi
**FinancialCoPilot:** KOBİ'ler için XAI Destekli Finansal Karar Platformu[cite: 2]

### Ürün Açıklaması
FinancialCoPilot, KOBİ CFO'ları ve mali müşavirlerin aynı masada yönetmek zorunda kaldığı 3 temel finansal problemi tek bir çatı altında çözen yapay zeka ve açıklanabilir yapay zeka (XAI) destekli bütünsel bir karara destek platformudur[cite: 2]. Parçalı çözümler yerine ortak veri altyapısı üzerinden çalışan modüler bir mimari sunar[cite: 2]. Model çıktıları ve teknik parametreler, LLM (GPT API) entegrasyonu sayesinde KOBİ'lerin kolayca anlayacağı doğal dile çevrilir[cite: 2].

### Ürün Özellikleri
* **Kredibilite XAI Modülü:** XGBoost ile risk skoru tahmini yapar; SHAP ve Microsoft DiCE kütüphaneleriyle finansal şeffaflık sağlayarak *"Kısa vadeli borçlar %15 azalsaydı onay ihtimali %25 artardı"* gibi karşıt durum açıklamaları sunar[cite: 2].
* **ChurnLens Modülü:** Sınıflandırma algoritmaları ve DiCE algoritması ile risk skorlaması yapar; müşteriyi sistemde tutmak için *"Müşterinin aktiflik süresi 2 gün artsaydı risk %80 düşerdi"* gibi prescriptive (reçete yazan) aksiyon senaryoları üretir[cite: 2].
* **FinAnomaly Modülü:** Isolation Forest ve Autoencoder modelleriyle kural tabanlı sistemlerin kaçırdığı örüntüleri yakalar ve CSV formatındaki muhasebe verilerinden şüpheli harcamaları listeler[cite: 2].
* **Ortak Dashboard UI:** Streamlit tabanlı tek arayüz üzerinde yan menü kontrollü 3 modül entegrasyonu sağlar[cite: 2].

### Hedef Kitle
* KOBİ CFO'ları ve Finans Yöneticileri[cite: 2]
* Mali Müşavirler ve Muhasebe Uzmanları[cite: 2]
* Kurumsal Harcama Denetçileri[cite: 2]

### Product Backlog URL
* **Backlog Panosu:** [Miro / Trello / GitHub Projects Linki Buraya Eklenecek][cite: 1]

---

## 🏃‍♂️ SPRINT 1 RAPORU (19 Haziran 2026 - 5 Temmuz 2026)[cite: 1]

### 1. Sprint Hedefi ve Yol Haritası
* **Sprint 1 Hedefi:**Projenin temel teknik altyapısını kurmak, 3 modülü besleyecek ortak veri ön işleme boru hattını oluşturmak ve XGBoost + SHAP + DiCE / Isolation Forest motorlarını yerel arayüzde (Streamlit MVP) şeffaf risk skorlarıyla uçtan uca çalışır hale getirmektir.[cite: 2].

### 2. Backlog Düzeni ve Story Seçim Mantığı
* Backlog'umuz projenin 6 haftalık planına uygun olarak düzenlenmiştir[cite: 1, 2].
* Sprint başına tahmin edilen puan sayısını geçmeyecek şekilde story seçimleri yapılmıştır[cite: 1].
* Story başına çıkan tahmin puanı, toplam efor puanının yarısından az tutulmuştur[cite: 1].
* Story'ler (mavi kartlar), geliştiricilerin paralel çalışabilmesi için net alt task'lere (kırmızı kartlar) bölünmüştür[cite: 1]. Her developer, kendi modülünün veri ön işleme adımını üstlenmiştir.

### 3. Daily Scrum Notları
* Zaman yönetimi ve ekip üyelerinin yoğunlukları göz önüne alınarak Daily Scrum toplantılarının **Google Meeeting ve Whatsapp üzerinden asenkron** olarak yürütülmesine karar verilmiştir[cite: 1].

### 4. Sprint Board Güncellemeleri
* **Sprint 1 Board Durumu:** Planlanan Story ve Task'ler başarıyla In Progress aşamasından Done aşamasına taşınmıştır[cite: 1].
* *Sprint board update: Sprint board screenshotları:*
> `![Sprint 1 Board Screenshot](/screenshots/sprint1_board.png)`[cite: 1]

### 5. Ürün Durumu (Ekran Görüntüleri)
* Sprint 1 sonunda temel Streamlit arayüz taslağı ve veri yükleme ekranı çalışır hale getirilmiştir[cite: 2].
* *(Ekran görüntüsü için placeholder:)*
> `![Streamlit UI Screenshot](/screenshots/sprint1_ui.png)`[cite: 1]

### 6. Sprint Review & Retrospective Toplantıları
* **Sprint Review:** Ortak veri altyapısının 3 modülü besleyebildiği doğrulandı[cite: 2]. Sprint 2'de en güçlü kasımız olan Kredibilite XAI ve ChurnLens entegrasyonlarına ağırlık verilecek[cite: 2].
* **Sprint Retrospective:** Ekip içi görev dağılımı verimli işledi[cite: 1]. Bir sonraki sprintte çakışmaları önlemek için Pull Request denetimleri daha sıkı yapılacak.
