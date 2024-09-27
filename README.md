
Kanserli Hücre Tespiti - YOLOv5 & PyTorch

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
    Diğer bağımlılıklar için requirements.txt dosyasına göz atabilirsiniz.

Katkı:

    Proje açık kaynaklıdır ve katkılara açıktır. Her türlü öneri ve geri bildirimi bekliyoruz.
