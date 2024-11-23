# Kalman Filtresi ile 3D Robot Hareketi Simülasyonu

Bu proje, Kalman filtresi kullanarak bir robotun 3D hareketini ve hata oranını simüle eden bir Python animasyonu sunar. Robotun x, y ve z eksenlerinde hareketi gerçek zamanlı olarak izlenirken, Kalman filtresi sensör gürültüsünü azaltarak tahminler yapar ve hata oranını ölçer.

## Özellikler

- **3D Hareket**: Robotun x, y ve z eksenlerinde gerçek ve tahmini hareketi animasyonla gösterilir.
- **Hata Oranı Grafiği**: Her eksen için tahmin hataları zamanla izlenir.
- **Dinamik Eksen Ayarları**: Grafik eksenleri dinamik olarak maksimum değerlere göre ayarlanır.
- **Hata Sınırlaması**: Tahmin hataları 0.5 ile sınırlandırılır.

## Kurulum

Bu projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### Gerekli Kütüphaneler

Projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyacınız var:

- **numpy**: Matematiksel hesaplamalar için
- **matplotlib**: Grafikler ve animasyonlar için
- **IPython**: Jupyter Notebook ortamında animasyonları görüntülemek için

Kütüphaneleri yüklemek için aşağıdaki komutu çalıştırabilirsiniz:

```bash
pip install numpy matplotlib ipython
```
