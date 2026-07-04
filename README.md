# 🚀 Takım FinNexus AI - FinancialCoPilot

## 📌 Takım Rolleri ve Elemanları
* **Ayşe Gül KURNAZ:** Scrum Master & İletişim Sorumlusu
* **Sedef AKŞİN:** Product Owner, (Kredibilite XAI Modül Sorumlusu)
* **Azra Nur TABAK:** Developer (Ekip İçi Kontrol Sorumlusu)
* **Furkan ÖZÜDOĞRU:** Developer (ChurnLens Modül Sorumlusu)
* **Ahmet ZELKA:** Developer (FinAnomaly Modül Sorumlusu)

---

## 💡 Ürün İle İlgili Bilgiler

### Ürün İsmi
**FinancialCoPilot:** KOBİ'ler için XAI Destekli Finansal Karar Platformu

### Ürün Açıklaması
FinancialCoPilot, KOBİ CFO'ları ve mali müşavirlerin aynı masada yönetmek zorunda kaldığı 3 temel finansal problemi tek bir çatı altında çözen yapay zeka ve açıklanabilir yapay zeka (XAI) destekli bütünsel bir karara destek platformudur. Parçalı çözümler yerine ortak veri altyapısı üzerinden çalışan modüler bir mimari sunar. Model çıktıları ve teknik parametreler, LLM (GPT API) entegrasyonu sayesinde KOBİ'lerin kolayca anlayacağı doğal dile çevrilir.

### Ürün Özellikleri
* **Kredibilite XAI Modülü:** XGBoost ile risk skoru tahmini yapar; SHAP ve Microsoft DiCE kütüphaneleriyle finansal şeffaflık sağlayarak *"Kısa vadeli borçlar %15 azalsaydı onay ihtimali %25 artardı"* gibi karşıt durum açıklamaları sunar.
* **ChurnLens Modülü:** Sınıflandırma algoritmaları ve DiCE algoritması ile risk skorlaması yapar; müşteriyi sistemde tutmak için *"Müşterinin aktiflik süresi 2 gün artsaydı risk %80 düşerdi"* gibi prescriptive (reçete yazan) aksiyon senaryoları üretir.
* **FinAnomaly Modülü:** Isolation Forest ve Autoencoder modelleriyle kural tabanlı sistemlerin kaçırdığı örüntüleri yakalar ve CSV formatındaki muhasebe verilerinden şüpheli harcamaları listeler.
* **Ortak Dashboard UI:** Streamlit tabanlı tek arayüz üzerinde yan menü kontrollü 3 modül entegrasyonu sağlar.

### Hedef Kitle
* KOBİ CFO'ları ve Finans Yöneticileri
* Mali Müşavirler ve Muhasebe Uzmanları
* Kurumsal Harcama Denetçileri

### Product Backlog URL
* **Backlog Panosu:** [Miro / Trello / GitHub Projects Linki Buraya Eklenecek][cite: 1]

---

## 🏃‍♂️ SPRINT 1 RAPORU (19 Haziran 2026 - 5 Temmuz 2026)

### 1. Sprint Hedefi ve Yol Haritası
* **Sprint 1 Hedefi:**Projenin temel teknik altyapısını kurmak, 3 modülü besleyecek ortak veri ön işleme boru hattını oluşturmak ve XGBoost + SHAP + DiCE / Isolation Forest motorlarını yerel arayüzde (Streamlit MVP) şeffaf risk skorlarıyla uçtan uca çalışır hale getirmektir.

### 2. Backlog Düzeni ve Story Seçim Mantığı
* Backlog'umuz projenin 6 haftalık planına uygun olarak düzenlenmiştir.
* Sprint başına tahmin edilen puan sayısını geçmeyecek şekilde story seçimleri yapılmıştır.
* Story başına çıkan tahmin puanı, toplam efor puanının yarısından az tutulmuştur.
* Story'ler (mavi kartlar), geliştiricilerin paralel çalışabilmesi için net alt task'lere (kırmızı kartlar) bölünmüştür[cite: 1]. Her developer, kendi modülünün veri ön işleme adımını üstlenmiştir.

### 3. Daily Scrum Notları
* Zaman yönetimi ve ekip üyelerinin yoğunlukları göz önüne alınarak Daily Scrum toplantılarının **Google Meeeting ve Whatsapp üzerinden asenkron** olarak yürütülmesine karar verilmiştir.

### 4. Sprint Board Güncellemeleri
* **Sprint 1 Board Durumu:** Planlanan Story ve Task'ler başarıyla In Progress aşamasından Done aşamasına taşınmıştır.
* *Sprint board update: Sprint board screenshotları:*
> `![Sprint 1 Board Screenshot](/screenshots/sprint1_board.png)`

### 5. Ürün Durumu (Ekran Görüntüleri)
* Sprint 1 sonunda temel Streamlit arayüz taslağı ve veri yükleme ekranı çalışır hale getirilmiştir.
* *Kredibilite XAI için:*
> <img width="1912" height="1026" alt="arayuz_1 1" src="https://github.com/user-attachments/assets/4e725a0b-09f7-41fc-913f-561f38066189" />

> <img width="1905" height="1027" alt="arayuz_1 2" src="https://github.com/user-attachments/assets/ca878b31-d903-4a12-b64e-97597d58f9d2" />

> <img width="1917" height="1031" alt="arayuz_1 3" src="https://github.com/user-attachments/assets/49160673-a8ff-4264-adda-d46b30e848b7" />

>  <img width="1917" height="1017" alt="arayuz_1 4" src="https://github.com/user-attachments/assets/4f6677a6-2870-4693-b168-9b271aa1089b" />

* *ChurnLens için:*
>  <img width="2529" height="1118" alt="Ekran görüntüsü 2026-07-03 160841 (1)" src="https://github.com/user-attachments/assets/9746b169-1724-4c9f-a97d-71887e47eb05" />

>  <img width="2536" height="1086" alt="Ekran görüntüsü 2026-07-03 160928" src="https://github.com/user-attachments/assets/86726422-078a-436b-be0a-d6cb649c4601" />

>  <img width="2522" height="1008" alt="Ekran görüntüsü 2026-07-03 160944" src="https://github.com/user-attachments/assets/39190a3a-d19c-4a64-9a75-70e5f4230b5d" />

* *FinAnomaly için:*
>  <img width="1280" height="726" alt="ahmet" src="https://github.com/user-attachments/assets/145dc344-594b-47da-afcb-d4b56bd7e9b8" />


### 6. Sprint Review & Retrospective 
* **Sprint Review:**
* Kredibilite XAI Modülü: Sıfırdan kurulan XGBoost modeli 5-Fold Stratified CV'de 0.937 AUC skoru üreterek hedeflenen başarımın çok üstüne çıkmıştır. SHAP entegrasyonu başarıyla tamamlanıp hangi faktörün riski ne kadar etkilediği şeffaflaştırılmış, DiCE motoru ile de KOBİ'ler için "ne yapsan onaylanırdın" odaklı 3 alternatif karşıt durum (counterfactual) senaryosu üretilmiştir. Streamlit arayüzünde temel akış (profil girişi, risk skoru ve XAI açıklamaları) tam çalışır durumdadır.

* ChurnLens Modülü: B2B SaaS müşteri kaybı modeli 0.9635 AUC başarımıyla projenin 0.85 olan başarı eşiğini ezip geçmiştir. En kritik aşama olan mantıksal kısıt mimarisi başarıyla kurgulanmış (örn: giden zaman geri alınamaz mantığıyla Abonelik_Suresi_Ay özelliğinin DiCE üzerinde sabit kilitlenmesi) ve müşteriyi kurtaracak 3 net reçete kartı üretilmiştir. Streamlit UI ve Plotly Gauge grafiği sorunsuz çalışmaktadır.

* FinAnomaly Modülü: Sprint 1 kapsamında CSV tabanlı muhasebe/gider verisi şeması, anomali kuralları ve Isolation Forest modelinin mimarisi kurgulanmıştır. Ortaya somut kod çıktısı çıkmamış olsa da, modelin sadece anomali bulma değil, veri temizleme ve anlamlı özellik (feature engineering) çıkarma adımlarını barındıran teknik altyapı tasarımı tamamlanmıştır.

* Genel Karar: Kredibilite ve Churn modülleri canlıya/demoya hazır haldedir. Sonraki sprintte FinAnomaly modülünün kodlama sürecinin hızlandırılmasına karar verilmiştir.
* **Sprint Retrospective:**
* İyi Gidenler: Kredibilite ve Churn developerları teknik takılmalarda (encode sonrası dtype uyumsuzlukları, NaN temizliği, pandas DataFrame index kaymaları ve DiCE'ın senaryo üretememe sorunları) çok hızlı reaksiyon gösterip tüm "Problems" sekmelerini sıfırlamışlardır.

* Geliştirilmesi Gerekenler: Modüller arası efor hızı dengesi şaşmıştır. FinAnomaly modülü teorik tasarım aşamasında kalarak kod geliştirme tarafında gecikmiştir.

* Alınan Aksiyonlar:

* Ekip İçi İletişim: Kişisel yoğunluk kaynaklı süreçte aksamalar gerçekleşmiştir. İletişimi ve planı dinamik tutarak süreci kolaylaştırma hedeflenmektedir.

* Somut Çıktı Odaklılık: Sprint 2'de FinAnomaly modülü için "tasarım" değil, doğrudan şüpheli harcamaları listeleyen ilk çalışan MVP hedeflenecektir.

