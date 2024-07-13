# BraTS2020-Segnentation-with-SegResNet-and-BasicUNet

Her model için ayrı bir .ipynb dosyası oluşturulmuştur. Veri seti BraTS2020 yarışmasına ait dosyalardır. “BraTS2020_TrainingData” ve “BraTS2020_ValidationData” dosyaları “archive” ismiyle ziplenerek archive.zip dosyası oluşturulur ve brats isimli bir dosyanın içinde GoogleDrive'a yüklenir. Kodlar çalıştırılırken kodların içinde olduğu gibi MONAI framework'ü 1.2 versiyonuyla yüklenmelidir. 40 GB A100 GPU VE 84GB sistem RAM’i için özelleştirmeler yapılmıştır, daha düşük GPU ve/veya RAM'e sahip sistemlerde çalışmayabilir. Modellerin içinde tabloda bulunan mean dice son epochtaki mean dice'ı gösterir. Paper'da kullanılan metrikler epochlar arasındaki en iyi sonuçlardan alınmıştır ve bu sonuçlar kodun içindeki evaulate döngüsünde gözükmektedir.

BraTS 2020 Dataset: https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation
