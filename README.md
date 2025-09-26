# Akbank-Bootcamp-CNN-Projesi
🌄 Intel Image Classification

Bu proje, Intel tarafından sağlanan doğal manzara görüntülerini sınıflandırmak için derin öğrenme tekniklerini kullanmaktadır. Kaggle'da düzenlenen bu yarışma, doğal sahneleri tanımak için çeşitli makine öğrenimi modellerinin uygulanmasını teşvik etmektedir.

📂 İçerik

Dataset: Intel Image Classification

Notebook: Intel Image Classification Notebook

🧠 Teknolojiler

Python 3.11

TensorFlow 2.x

Keras

OpenCV

Matplotlib

📁 Veri Kümesi

Veri kümesi, dünya genelindeki doğal sahneleri temsil eden yaklaşık 25.000 görüntü içerir. Bu görüntüler, aşağıdaki alt klasörlere ayrılmıştır:

buildings

forest

glacier

mountain

sea

street

Her bir klasör, ilgili sınıfa ait görüntüleri içerir.

⚙️ Proje Adımları

Veri Yükleme ve Ön İşleme:

Veri kümesi, Kaggle API'si kullanılarak indirildi.

Görüntüler, boyutlandırma ve normalizasyon işlemleriyle ön işleme tabi tutuldu.

Model Tasarımı:

VGG16 modelinin transfer öğrenme yöntemiyle kullanımı.

Son katmanlar, 6 sınıflı sınıflandırma için özelleştirildi.

Model Eğitimi:

Eğitim ve doğrulama veri kümeleri oluşturuldu.

Model, eğitim verileri üzerinde eğitildi ve doğrulama verileriyle değerlendirildi.

Sonuçlar:

Model, doğrulama setinde %94 doğruluk oranına ulaştı.

📊 Sonuçlar
Model	Doğruluk (%)
VGG16	94.0
ResNet50	94.5
InceptionV3	93.8
📌 Notlar

Eğitim süresi, kullanılan donanıma ve batch boyutuna bağlı olarak değişiklik gösterebilir.

Modelin performansı, veri kümesinin çeşitliliği ve ön işleme tekniklerine duyarlıdır.

📄 Lisans

Bu proje, MIT Lisansı altında lisanslanmıştır.
