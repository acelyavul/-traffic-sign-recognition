# Alman Trafik İşaretlerini Tanıma Veri Seti

Bu proje kapsamında, [GTSRB (German Traffic Sign Recognition Benchmark)](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) veri seti kullanılmıştır. GTSRB, farklı trafik işaretlerini sınıflandırmak için hazırlanmış bir veri setidir. Veri setinde çeşitli trafik işaretlerinin görselleri ve bu görsellere ait sınıf etiketleri bulunmaktadır (örneğin, hız sınırı, dur işareti, yön işaretleri). Görseller, farklı çözünürlüklerde ve değişen koşullarda çekilmiştir.

1. Veri Görselleştirme ve Analiz

Sınıf etiketlerini inceleme, sınıf dağılımını bir grafikle görselleştirme
Her sınıftan rastgele görüntü seçip görselleştirme

2. Görsellerin Boyutlandırılması ve Standartlaştırılması

Görselleri sabit bir boyuta (43x43) yeniden boyutlandırılması
Görseller üzerinde StandardScaler ve MinMaxScaler ile ölçekleme

3. Makine Öğrenimi Modelleriyle Çalışma:

- MLP (Multilayer Perceptron) modeli 
- RBF (Radial Basis Function) sinir ağı modeli
  
4. Hiperparametre Optimizasyonu:

GridSearchCV kullanarak en iyi MLP parametrelerini bulma

5. Performans Değerlendirme:

Modellerin doğruluk oranlarını ve sınıflar bazında performansını değerlendirme
Karışıklık matrislerini görselleştirerek model sonuçlarını analiz etme
