# Classification With KNN

Bu proje, **K-Nearest Neighbors (KNN)** algoritması kullanılarak bir **sınıflandırma (classification)** probleminin çözülmesini amaçlamaktadır. Proje, KNN algoritmasının temel mantığını, veri ön işleme adımlarını, model eğitimi ve performans değerlendirme süreçlerini içeren bir **Jupyter Notebook** çalışmasıdır.

---

## Proje Amacı

Bu çalışmanın amacı, KNN algoritmasının çalışma prensibini anlamak, bir veri seti üzerinde KNN ile sınıflandırma yapmak, model performansını değerlendirmek ve makine öğrenmesinde temel sınıflandırma adımlarını uygulamalı olarak göstermektir.

---

## Kullanılan Algoritma: K-Nearest Neighbors (KNN)

**KNN**, denetimli öğrenme algoritmalarından biridir. Eğitim aşamasında model oluşturmaz, tüm verileri saklar (lazy learning). Test verisinin sınıfı, eğitim verisindeki en yakın **k** komşuya bakılarak belirlenir. Sınıf tahmini çoğunluk oyu (majority voting) ile yapılır ve genellikle **Öklidyen mesafe** kullanılır.

---

## Proje İçeriği

Notebook içerisinde aşağıdaki adımlar yer almaktadır:

- Gerekli kütüphanelerin yüklenmesi  
- Veri setinin yüklenmesi ve incelenmesi  
- Veri ön işleme adımları  
  - Eksik veri kontrolü  
  - Özellik ölçeklendirme  
- Eğitim ve test verilerinin ayrılması  
- KNN modelinin oluşturulması  
- Farklı **k** değerleri ile model eğitimi  
- Model performansının değerlendirilmesi  
- Sonuçların yorumlanması  

---

## Kullanılan Teknolojiler ve Kütüphaneler

- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## Kurulum ve Çalıştırma

Bu projeyi çalıştırabilmek için aşağıdaki adımları izleyiniz.

Repoyu klonlayın:

```bash
git clone https://github.com/isil-ada/Classification-With-KNN.git
````

Proje dizinine girin:

```bash
cd Classification-With-KNN
```

Jupyter Notebook’u başlatın:

```bash
jupyter notebook
```

Ardından `Classification_with_KNN.ipynb` dosyasını açarak hücreleri sırasıyla çalıştırın.

---

## Model Değerlendirme

Model performansı, **doğruluk (accuracy)** metriği kullanılarak değerlendirilmiştir. Farklı **k** değerleri denenmiş ve en uygun komşu sayısının model başarısına etkisi analiz edilmiştir.

---

## K Değerinin Önemi

KNN algoritmasında **k** değeri model performansını doğrudan etkiler. Küçük k değerleri daha esnek karar sınırları oluştururken aşırı öğrenmeye neden olabilir. Büyük k değerleri daha dengeli sonuçlar üretir ancak bazı detayların gözden kaçmasına yol açabilir. Bu nedenle k değeri dikkatli seçilmelidir.

---

## Avantajlar

* Anlaşılması ve uygulanması kolaydır
* Parametrik bir model değildir
* Küçük ve orta ölçekli veri setlerinde etkilidir

---

## Dezavantajlar

* Büyük veri setlerinde hesaplama maliyeti yüksektir
* Özellik ölçeklendirme yapılmazsa performans düşer
* Aykırı değerlere karşı hassastır

---

## Sonuç

Bu proje, KNN algoritmasının sınıflandırma problemlerinde nasıl kullanıldığını gösteren temel ve öğretici bir çalışmadır. Makine öğrenmesine yeni başlayanlar için algoritmanın mantığını kavramaya yardımcı olacak niteliktedir.

📎 **Not:** Bu proje eğitim amaçlı hazırlanmıştır.

