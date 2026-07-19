# 🚀 Takım FinNexus AI - FinancialCoPilot

## 📌 Takım Rolleri 
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
* **Backlog Panosu:** https://miro.com/app/board/uXjVH-sWIok=/?share_link_id=409487541434

---

## 🏃‍♂️ SPRINT 1 RAPORU (19 Haziran 2026 - 5 Temmuz 2026)

### 1. Sprint Hedefi ve Yol Haritası
* Sprint 1 Hedefi: Projenin temel teknik altyapısını kurmak, 3 modülü besleyecek ortak veri ön işleme boru hattını oluşturmak ve XGBoost + SHAP + DiCE / Isolation Forest motorlarını yerel arayüzde (Streamlit MVP) şeffaf risk skorlarıyla uçtan uca çalışır hale getirmektir.

### 2. Backlog Düzeni ve Story Seçim Mantığı
* Backlog'umuz projenin 6 haftalık planına uygun olarak düzenlenmiştir.
* Sprint başına tahmin edilen puan sayısını geçmeyecek şekilde story seçimleri yapılmıştır.
* Story başına çıkan tahmin puanı, toplam efor puanının yarısından az tutulmuştur.
* Story'ler (mavi kartlar), geliştiricilerin paralel çalışabilmesi için net alt task'lere (kırmızı kartlar) bölünmüştür. Her developer, kendi modülünün veri ön işleme adımını üstlenmiştir.

### 3. Daily Scrum Notları
* Zaman yönetimi ve ekip üyelerinin yoğunlukları göz önüne alınarak Daily Scrum toplantılarının **Google Meeeting ve Whatsapp üzerinden asenkron** olarak yürütülmesine karar verilmiştir.

### 4. Sprint Board Güncellemeleri
* **Sprint 1 Board Durumu:** Planlanan Story ve Task'lerin çoğu başarıyla In Progress aşamasından Done aşamasına taşınmıştır.
* *Sprint board update: Sprint board screenshotları:*
> <img width="1156" height="807" alt="image" src="https://github.com/user-attachments/assets/0c6a1a2a-b962-4f12-ba18-e51358a646e7" />


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


### 6. Sprint Review
* Kredibilite XAI Modülü: Sıfırdan kurulan XGBoost modeli 5-Fold Stratified CV'de 0.937 AUC skoru üreterek hedeflenen başarımın çok üstüne çıkmıştır. SHAP entegrasyonu başarıyla tamamlanıp hangi faktörün riski ne kadar etkilediği şeffaflaştırılmış, DiCE motoru ile de KOBİ'ler için "ne yapsan onaylanırdın" odaklı 3 alternatif karşıt durum (counterfactual) senaryosu üretilmiştir. Streamlit arayüzünde temel akış (profil girişi, risk skoru ve XAI açıklamaları) tam çalışır durumdadır.
  
* ChurnLens Modülü: B2B SaaS müşteri kaybı modeli 0.9635 AUC başarımıyla projenin 0.85 olan başarı eşiğini ezip geçmiştir. En kritik aşama olan mantıksal kısıt mimarisi başarıyla kurgulanmış (örn: giden zaman geri alınamaz mantığıyla Abonelik_Suresi_Ay özelliğinin DiCE üzerinde sabit kilitlenmesi) ve müşteriyi kurtaracak 3 net reçete kartı üretilmiştir. Streamlit UI ve Plotly Gauge grafiği sorunsuz çalışmaktadır.
  
* FinAnomaly Modülü: Sprint 1 kapsamında CSV tabanlı muhasebe/gider verisi şeması, anomali kuralları ve Isolation Forest modelinin mimarisi kurgulanmıştır. Ortaya somut kod çıktısı çıkmamış olsa da, modelin sadece anomali bulma değil, veri temizleme ve anlamlı özellik (feature engineering) çıkarma adımlarını barındıran teknik altyapı tasarımı tamamlanmıştır.
  
* Genel Karar: Kredibilite ve Churn modülleri canlıya/demoya hazır haldedir. Sonraki sprintte FinAnomaly modülünün kodlama sürecinin hızlandırılmasına karar verilmiştir.
  
### 7. Sprint Retrospective:
* İyi Gidenler: Kredibilite ve Churn developerları teknik takılmalarda (encode sonrası dtype uyumsuzlukları, NaN temizliği, pandas DataFrame index kaymaları ve DiCE'ın senaryo üretememe sorunları) çok hızlı reaksiyon gösterip tüm "Problems" sekmelerini sıfırlamışlardır.

* Geliştirilmesi Gerekenler: Modüller arası efor hızı dengesi şaşmıştır. FinAnomaly modülü teorik tasarım aşamasında kalarak kod geliştirme tarafında gecikmiştir.

* Alınan Aksiyonlar:

   * Ekip İçi İletişim: Kişisel yoğunluk kaynaklı süreçte aksamalar gerçekleşmiştir. İletişimi ve planı dinamik tutarak süreci kolaylaştırma hedeflenmektedir.

   * Somut Çıktı Odaklılık: Sprint 2'de FinAnomaly modülü için "tasarım" değil, doğrudan şüpheli harcamaları listeleyen ilk çalışan MVP hedeflenecektir.

---

## 🏃‍♂️ SPRINT 2 RAPORU (6 Temmuz 2026 - 19 Temmuz 2026)

### 1. Sprint Hedefi ve Yol Haritası
* **Sprint 2 Hedefi:** FinancialCoPilot platformunu jüri önünde 5 dakikalık kesintisiz demoya hazır hale getirmek; Ollama ile yerel LLM açıklama katmanını kurmak, ağ bağımsız çalışan "Demo Sahnesi" modlarını entegre etmek, toplu CSV analizlerini devreye almak ve hibrit risk skorlama altyapısını oluşturmak.

### 2. Bu Sprintte Tamamlanan Ana Modüller ve Yenilikler

#### 🧠 Yerel LLM Katmanı (Ollama Entegrasyonu)
* Bulut API'lerin yaratacağı veri gizliliği risklerini önlemek adına tamamen yerel çalışan **Ollama (llama3.2 / Mistral)** altyapısı entegre edilmiştir.
* `llm_explainer.py` modülü sayesinde SHAP ve DiCE algoritmalarının ürettiği teknik çıktılar, KOBİ yöneticilerinin ve Müşteri Başarı (Customer Success) temsilcilerinin anlayacağı 2-3 cümlelik Türkçe aksiyon planlarına dönüştürülmüştür.
* **UI Fallback Sistemi:** Ollama sunucusunun kapalı olma ihtimaline karşı `try/except` blokları eklenmiş; sistemin çökmesi engellenerek statik fallback mesajları ("Yapay Zeka şu an meşgul") tanımlanmıştır.

#### ⚡ Tek Tıkla Offline Demo Sahnesi Modu
* Jüri sunumu esnasında yaşanabilecek olası ağ/internet kopması risklerine karşı, tamamen offline çalışan **"Demo Modunu Başlat"** butonu arayüze eklenmiştir.
* **Kredibilite Demo:** Butona basıldığında 12.000€ kredili, %68-75 yüksek riskli "Tekstilci Ahmet Bey" profili anında yüklenmekte ve DiCE kurtarma reçeteleri üretilmektedir.
* **ChurnLens Demo:** 8 ay abonelik süreli ve %82 yüksek terk riskli "A Şirketi" profili tek tıkla simüle edilmektedir.

#### 📊 CSV Toplu Analiz & Eşik (Threshold) Optimizasyonu
* `st.file_uploader` entegrasyonu ile kullanıcıların CSV formatında toplu müşteri/mizan verisi yüklemesi ve katı veri tipi (dtype) doğrulaması yapması sağlanmıştır.
* Yüklenen verilerin risk skorlaması yapıldıktan sonra sonuçların dışa aktarılabilmesi için **"Sonuçları/Kurtarma Planını İndir"** butonu (CSV export) aktif edilmiştir.
* Sınıflandırma modellerinde Precision-Recall eğrileri incelenerek F1-max ve Recall maksimizasyonu için eşik değeri (threshold tuning) optimizasyonu tamamlanmış, `train.py` güncellenmiştir.

#### 🔍 FinAnomaly Hibrit Risk Skoru ve Kural Motoru
* **Autoencoder Modeli:** Derin öğrenme tabanlı ikinci bir anomali modeli (`autoencoder.py`) kurulmuş ve Sprint 1'deki Isolation Forest skoru ile karşılaştırma raporları çıkarılmıştır.
* **Kural Tabanlı Motor:** `rules_engine.py` geliştirilerek; tekrarlı işlem, hafta sonu/mesai dışı işlem, departman ortalamasının çok üstünde gider ve şüpheli kelime kontrolleri devreye alınmıştır.
* **Hibrit Skorlama:** ML anomali skoru ile kural ihlali skoru birleştirilerek tek bir risk skoru üretilmiş; arayüze denetçiler için kural rozetleri ve **"Neden Şüpheli?"** açıklama kartları eklenmiştir.

### 3. Sprint Board Güncellemeleri ve Daily Scrum
* **Sprint Board:** Hafta 3-4 planlamasında belirlenen tüm Story ve bunlara bağlı Task'ler başarıyla `Done` aşamasına getirilmiştir.
* **Daily Scrum Notları:** Daily Scrum toplantıları Whatsapp belgeleme ise Drive üzerinden devam etmiştir. WhatsApp'da sıklıkla süreç ve gelişmeler hakkında konular konuşulmuştur. Drive üzerinden ise gerekli ve herkesin görmesi gereken belgeler, görseller vb. düzenli olarak yüklenmiştir. Belgeleme ise Google Docs üzerinde yapılmıştır.
  * 📄 [**Sprint 2 Daily Scrum Notlarını İncelemek İçin Tıklayın**](https://docs.google.com/document/d/1HWCWmwfLFRj0z3ep6LcF1r_fARuVyZOE2VUrfswzPEI/edit?usp=sharing)

#### Sprint 2 Pano Görseli
> <img width="1918" height="910" alt="image" src="https://github.com/user-attachments/assets/04d81a97-ebd6-4d65-ba27-49b933999a4d" />
> <img width="1918" height="915" alt="image" src="https://github.com/user-attachments/assets/f06a07e4-cf64-4819-b079-b355b8b05309" />

### 4. Ürün Durumu (Geliştirilen Arayüz Ekran Görüntüleri)

#### Kredibilite XAI - LLM Açıklaması ve Demo Sahnesi
> <img width="1913" height="977" alt="sprint2_arayüz" src="https://github.com/user-attachments/assets/4ba3ac89-5600-43fc-be94-41e64ac664a0" />


#### ChurnLens - Toplu CSV Analizi ve KPI Dashboard
> <img width="2518" height="1143" alt="Ekran görüntüsü 2026-07-18 130432" src="https://github.com/user-attachments/assets/bb7d4f0a-4937-44ea-bd91-2b6b64a5012c" />
> <img width="2029" height="1226" alt="Ekran görüntüsü 2026-07-18 130732" src="https://github.com/user-attachments/assets/28d43a79-3dbb-494d-8139-e201e3c7399b" />
> <img width="2142" height="1188" alt="Ekran görüntüsü 2026-07-18 130750" src="https://github.com/user-attachments/assets/a04d1a26-b2f9-4676-8d26-c927ac6c2ede" />
> <img width="2152" height="774" alt="Ekran görüntüsü 2026-07-18 130755" src="https://github.com/user-attachments/assets/918874d5-4a3a-4d30-9a20-8d7eff920634" />
> <img width="2090" height="1136" alt="Ekran görüntüsü 2026-07-18 130838" src="https://github.com/user-attachments/assets/1e915fff-162b-4def-a0dd-955560f0664a" />
> <img width="2136" height="1052" alt="Ekran görüntüsü 2026-07-18 130807" src="https://github.com/user-attachments/assets/9b9cfc92-c6a9-4240-9d99-e371d9805db5" />


#### FinAnomaly - Hibrit Anomali Rozetleri ve İşlem Detayı
> <img width="1440" height="1100" alt="image" src="https://github.com/user-attachments/assets/93f73141-0659-4cd4-a36e-4dd5bf3fec62" />
> <img width="1440" height="1100" alt="image" src="https://github.com/user-attachments/assets/4111c67f-352e-4c83-8231-247feaf88750" />
> <img width="1440" height="1100" alt="image" src="https://github.com/user-attachments/assets/5dd7c064-30fe-4983-99c9-1b2e8d6e6784" />


### 6. Sprint Review
* ChurnLens (Müşteri Kaybı Önleme):
   * Toplu Risk Taraması (M5): Sistemi kilitleme riski olan LLM yükü bu aşamadan çıkarılarak anlık XGBoost skorlaması devreye alındı. Yüklenen CSV dosyalarındaki toplu müşteri verileri milisaniyeler içinde taranarak kurumsal tablolara ve KPI kartlarına anında yansıması sağlandı.
   * Lokal LLM Entegrasyonu: Bulut API'lere bağımlılık olmadan, tamamen yerel çalışan Ollama (Llama 3.2/Mistral) entegrasyonu tamamlandı. DiCE algoritmasından çıkan karmaşık karşıt durumlar, müşteri temsilcilerinin anında aksiyon alabileceği Türkçe ve motive edici strateji planlarına dönüştürüldü.
   * Veri Bilimci Arayüzü (M6): Model başarısını görünür kılmak için AUC-ROC eğrisi ve interaktif Threshold Tuning slider'ı eklendi. Böylece Recall (yakalama oranı) ile False Positive (yanlış alarm) dengesinin Confusion Matrix üzerinden anlık yönetilmesi sağlandı.

* Kredibilite XAI (Kredi Risk Simülatörü):
   * İnternetsiz Tam Otonom Çalışma: Ollama entegrasyonu ile internet bağlantısına gerek kalmadan yerel LLM üzerinden Türkçe kredi değerlendirmesi üretebilen yapı kuruldu.
   * Offline Demo Sahnesi: Jüri sunumu esnasında yaşanabilecek ağ risklerine karşı "Tekstilci Ahmet Bey" profili tek tıkla yüklenebilir hale getirildi.
   * Model Optimizasyonu: Birden fazla KOBİ profilinin aynı anda işlenebildiği toplu analiz ekranı aktif edildi ve threshold optimizasyonu sayesinde F1 skoru 0.66'dan 0.76'ya yükseltildi.

* FinAnomaly (Usulsüzlük ve Anomali Tespiti):
   * Bütünsel Akış: Makine öğrenmesi modeli, kural tabanlı denetim kontrolleri, açıklanabilirlik ve UI katmanları tek bir test edilmiş puanlama akışı altında birleştirildi.
   * Denetçi MVP'si: Kurumsal denetçilerin CSV yükleyerek şüpheli harcamaları ve anomali nedenlerini anında görebildiği uçtan uca çalışan demo tamamlandı.

* Kapsam Değişiklikleri ve Çevik Adaptasyonlar 
  * CSV Kolon Uyumu Doğrulaması İptali: ChurnLens M5 modülü için planlanan karmaşık kolon uyumu doğrulama algoritmaları yazmaktan vazgeçildi. Bunun yerine, kullanıcı deneyimini çok daha pratik hale getiren indirilebilir "Örnek CSV Şablonu" arayüze eklenerek müşteri onboarding süreci sadeleştirildi.
  * M4 İnternetsiz Demo Sahnesi İptali: ChurnLens için ayrıca tasarlanan offline demo modülüne, mimarimiz zaten tamamen on-prem (yerel) çalıştığı için ihtiyaç kalmadı ve efor tasarrufu amacıyla kapsamdan çıkarıldı.

### 7. Sprint Retrospective:
* İyi Gidenler:
   * Erken Hata Tespiti: Sprint 1 retrospektifinde aldığımız "gözden geçirme süreçlerini sıklaştırma" kararı sayesinde, muhasebe verilerindeki kritik tarih formatlama hatası çok erken aşamada tespit edilip tüm modüllerde düzeltildi.
   * Otomatik ve Görsel Testler: Teslimat öncesinde devreye aldığımız otomatik senaryo testleri ve görsel kontroller sayesinde, arayüzdeki yüzde formatlama hataları canlıya çıkmadan engellendi.

* Karşılaşılan Zorluklar ve Çözümler:
   * Teknik Entegrasyon Pürüzleri: Sprint esnasında Ollama port çakışması, DiCE modülünde önbellek (cache) kaynaklı senaryo üretim hatası ve ortamlar arası model dosyasının (.pkl) taşınmasında yaşanan bozulmalar gibi engellerle karşılaşıldı. Ekip içi eşli kodlama (pair programming) ve hızlı debug oturumlarıyla her üç sorun da kalıcı olarak çözüldü.
   * Sentetik Veri ve Model Kalibrasyonu (FinAnomaly): En büyük zorluğumuz, küçük ve sentetik etiketli verilerle model kalibrasyonu yapmak oldu. Modelin şüpheli işlemleri yakalama oranı çok yüksek olsa da yanlış pozitif (false positive) alarmları tamamen sönümlemek için gerçek denetçi geri bildirimlerine ve daha geniş temsil edici verilere ihtiyaç duyulduğu tespit edildi.

* Sprint 3 (Final Sprint) Aksiyon Kararları:
   * Arayüz (UI) ve Render İyileştirmeleri: DiCE modülünde kalan son görsel render pürüzlerinin giderilmesi ve 3 modülün ortak temada pürüzsüz çalışması sağlanacak.
   * FinAnomaly Kalibrasyonu: Yanlış pozitifleri azaltmak adına kural ağırlıkları ve anomali eşik değerleri (threshold) yeniden kalibre edilecek.
   * Jüri Savunma Paketi: Ürünün geliştirme süreci tamamlandığı için odak tamamen sunuma kaydırılacak; Pitch Deck (sunum dokümanı), 3 dakikalık tanıtım videosu çekimi ve olası teknik sorular için Jüri Soru-Cevap (Q&A) Bankası oluşturulacak.
  
