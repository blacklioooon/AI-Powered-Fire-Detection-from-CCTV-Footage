# 🔥 FIRE DETECTION FROM CCTV

Bu proje , güvenlik kameralarından (CCTV) alınan görüntülerde **yangın** ve **duman** 

tespitini gerçekleştiren bir yapay zeka sistemidir.



##  Kullanılan Modeller

-  [MobileNetV2]

-  [EfficientNetB0]

Her iki model de transfer öğrenme (transfer learning) ile eğitilmiştir.

##  Klasör Yapısı

project/
data/ # Eğitim ve test verileri (fire, smoke, default)
train/
test/
EfficientNetB0/
ahmed.ipynb # Eğitim ve test kodu
MobileNetV2/
AHMED.ipynb # Eğitim ve test kodu
requirements.txt
README.md



⚠️ Not : `data` klasörü ve model ağırlıkları GitHub'a dahil edilmemiştir.



##  Dataset

Veri seti Kaggle'dan alınmıştır:

[Fire Detection from CCTV - Kaggle]

(https://www.kaggle.com/datasets/ritupande/fire-detection-from-cctv)

Veri kümesi üç sınıfa ayrılmıştır:

- fire
- smoke
- default (yangın/duman olmayan normal görüntüler)



##  Nasıl Çalıştırılır?

1. Gerekli kütüphaneleri kur:

```bash

pip install -r requirements.txt

2. Kaggle veri setini indir ve data/ klasörüne yerleştir.

3. AHMED.ipynb veya 
   ahmed.ipynb dosyasını çalıştırarak modeli eğit ve test et.

Geliştirici

AHMET 

🚀 Bir yapay zeka meraklısı , durmadan deniyorum ve gelişiyorum 

📫 LinkedIn'de Beni Takip Et : www.linkedin.com/in/ahmet-h-b37867241





