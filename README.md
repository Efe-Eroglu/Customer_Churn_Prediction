# Müşteri Ayrılma Tahmini Projesi

## Tanıtım
Bu proje, yapay sinir ağlarını kullanarak müşteri ayrılmasını tahmin etmeyi amaçlamaktadır. Müşteri ayrılması veya müşteri kaybı, müşterilerin bir şirketle iş yapmayı sonlandırdığı fenomeni ifade eder. Ayrılma tahmini yapmak, işletmelerin risk altındaki müşterileri belirlemesine ve onları korumak için proaktif önlemler almasına yardımcı olabilir.

## Veri Kümesi
Bu projede kullanılan veri kümesi, müşterilere ait demografik bilgiler, kullanım desenleri ve müşteri memnuniyeti puanları gibi çeşitli özellikleri içerir. Ayrıca, bir müşterinin ayrılıp ayrılmadığını gösteren ikili bir hedef değişkenini içerir.

## Metodoloji
Bu projede yapay sinir ağları (YSA), müşteri ayrılmasını tahmin etmek için kullanılmaktadır. YSAs, verideki karmaşık desenleri yakalayabilen güçlü modellerdir. Veri kümesi eğitim ve test kümelerine bölünür ve YSA, eğitim kümesindeki verileri öğrenmek için eğitilir. Eğitilen model daha sonra performansını değerlendirmek için test kümesinde değerlendirilir.

## Uygulama
Proje, Python ve aşağıdaki kütüphaneler kullanılarak uygulanmıştır:
- Pandas
- NumPy
- Scikit-learn
- TensorFlow/Keras

Uygulamanın ana adımları aşağıdaki gibidir:
1. Veri ön işleme: Veri kümesi eksik değerleri işlemek, kategorik değişkenleri kodlamak ve sayısal özellikleri ölçeklemek için ön işlemden geçirilir.
2. Model oluşturma: Bir YSA modeli, TensorFlow/Keras kullanılarak oluşturulur. Modelin mimarisi, veri kümesinin özel gereksinimlerine ve özelliklerine bağlı olarak değişebilir.
3. Model eğitimi: YSA modeli, uygun optimizasyon algoritmaları ve kayıp fonksiyonları kullanılarak eğitim verisinde eğitilir.
4. Model değerlendirmesi: Eğitilen model, performansını değerlendirmek için test verisinde doğruluk, hassasiyet, duyarlılık ve F1 skoru gibi metriklerle değerlendirilir.
5. Hiperparametre ayarı: YSA modelinin hiperparametreleri, performansını optimize etmek için ayarlanır.

## Sonuçlar
YSA modelinin performansı şu şekildedir:
- Doğruluk: %86
- Hassasiyet: %75
- Duyarlılık: %49
- F1 skoru: %59

Bu sonuçlar, modelin müşteri ayrılmasını tahmin etmede makul bir başarı elde ettiğini göstermektedir. Performansını artırmak için daha fazla optimizasyon ve ayarlama yapılabilir.

## Sonuç
Bu projede, müşteri ayrılmasını tahmin etmek için yapay sinir ağı modeli geliştirdik. Model, ayrılma riski taşıyan müşterileri belirlemede sonuçlar göstermektedir. Bu tür tahmin modellerinden faydalanarak, işletmeler müşterileri korumak ve müşteri memnuniyetini artırmak için proaktif önlemler alabilirler.

## Gelecek Çalışmalar
Bu projede gelecek çalışmalar şunları içerebilir:
- Performansı artırmak için farklı yapay sinir ağı mimarileriyle deneme yapmak.
- Ensemble öğrenme ve özellik mühendisliği gibi ileri teknikleri keşfetmek.
- Tahminleri daha dinamik ve tepkisel hale getirmek için gerçek zamanlı verileri dahil etmek.
- Modeli gerçek dünya uygulamaları için üretime almak.
