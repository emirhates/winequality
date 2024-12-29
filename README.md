# Şarap Kalitesi Tahmini

  Bu repo, Wine Quality Veri Seti kullanılarak şarap kalitesini tahmin etmeye yönelik bir makine öğrenimi projesini içermektedir. Proje, keşifsel veri analizi (EDA), veri ön işleme, özellik mühendisliği ve çeşitli makine öğrenimi algoritmalarıyla model oluşturma süreçlerini kapsamaktadır.




## Veri Seti
  Wine Quality Veri Seti, UCI Makine Öğrenimi Deposu kaynağından alınmıştır. Veri seti, kırmızı ve beyaz şarap örneklerinin kimyasal özelliklerini ve şarap uzmanları tarafından verilen kalite puanlarını içermektedir.

  

Özellikler:
* Sabit Asitlik (Fixed Acidity),
* Uçucu Asitlik (Volatile Acidity),
* Sitrik Asit (Citric Acid)
* Artık Şeker (Residual Sugar)
* Kloridler (Chlorides)
* Serbest Kükürt Dioksit (Free Sulfur Dioxide)
* Toplam Kükürt Dioksit (Total Sulfur Dioxide)
* Yoğunluk (Density)
* pH
* Sülfatlar (Sulphates)
* Alkol (Alcohol)


Hedef Değişken:
* Kalite (Quality): 3 ile 8 arasında değişen, uzmanlar tarafından verilen şarap kalite puanlarıdır.

## İzlenen Adımlar:
### Keşifsel Veri Analizi (EDA):
 * Aykırı değerlerin ve özelliklerin dağılımlarının incelenmesi.
 * Özellik-hedef ilişkilerinin korelasyon analizi.
 * Sağ çarpık dağılımların düzenlenmesi ve veri yapılarının belirlenmesi.
### Veri Ön İşleme:
 * Eksik değerler ve aykırı değerlerin ele alınması.
 * Algoritmalara uygun olacak şekilde verilerin normalize edilmesi.
 * Kalite tahmininde önemli olan özelliklerin seçimi.
### Modelleme:
 * Aşağıdaki algoritmalar kullanılarak modeller oluşturuldu:
 * Lojistik Regresyon
 * Rastgele Orman (Random Forest)
 * XGBoost
 * K-En Yakın Komşu (KNN)
 * Destek Vektör Sınıflandırıcı (SVC)
 * LightGBM
 * Karar Ağaçları (Decision Tree)
 * Performans, doğruluk, F1-skoru ve karışıklık matrisi gibi metriklerle karşılaştırıldı.

### Model Değerlendirme:
 * Modeller, veri seti üzerinde çapraz doğrulama ve eğitim-test ayrımı ile test edildi.

