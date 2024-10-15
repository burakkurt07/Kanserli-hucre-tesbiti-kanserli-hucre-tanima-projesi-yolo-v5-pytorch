Dataset'i kaggle sayfamdan indirebilirsiniz! link : https://www.kaggle.com/datasets/burakkurt07/kanserli-hucre-tesbiti-dataseti-blood-cancer-data


Kanserli Hücre Tespiti - YOLOv5 & PyTorch
Projenin Detayları Medium Makalemde!
👉🏼👉🏼 https://medium.com/@burak0564/ger%C3%A7ek-zamanl%C4%B1-kanserli-h%C3%BCcre-tespiti-yolov5-ve-pytorch-kanserli-h%C3%BCcre-tan%C4%B1ma-projesi-91e0498bfc81

Bu proje, derin öğrenme tabanlı bir kanserli hücre tespit sistemi geliştirmeyi amaçlamaktadır. YOLOv5 ve PyTorch kullanarak gerçek zamanlı hücre tanıma uygulaması oluşturulmuştur. Proje, kanserli ve temiz hücre görüntülerinin sınıflandırılmasını sağlamaktadır.
Özellikler:

    YOLOv5 mimarisi ile hızlı ve doğru hücre tespiti
    PyTorch ile eğitim ve değerlendirme
    Kanserli ve temiz hücre görüntüleri üzerinde test
    Veri seti yönetimi ve sonuç görselleştirme

Kullanım:

 Gerekli Python paketlerini yükleyin:

    pip install -r requirements.txt

Eğitim ve test verilerini ilgili dizinlere yerleştirin:

    dataset/train/kanserli
    dataset/train/temiz

YOLOv5 modelini eğitmek ve test etmek için aşağıdaki komutları kullanabilirsiniz:

    python train.py --data cancer_cells.yaml --weights yolov5s.pt --epochs 50

Gereksinimler:

    Python 3.7+
    PyTorch
    OpenCV
    Yada CMD ile projenin klasörüne girip "pip install -r requirements.txt" da yazabilirsiniz! Sizin için hepsini otomatik kurar!

Katkı:

    Projem açık kaynaklıdır ve katkılara açıktır. Her türlü öneri ve geri bildirimi bekliyorum!
