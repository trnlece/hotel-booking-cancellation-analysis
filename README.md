# Hotel Booking Cancellation Analysis (Otel Rezervasyon İptal Analizi)

Bu proje, **UCI Machine Learning Repository** üzerinden alınan otel rezervasyon verileri kullanılarak gerçekleştirilmiş bir Keşifçi Veri Analizi (EDA) çalışmasıdır.

# Proje Amacı
Otel otomasyon ve bulut PMS sistemleri (Elektraweb vb.) süreçlerine paralel olarak; rezervasyonların iptal edilme dinamiklerini, sezonluk yoğunlukları ve erken rezervasyon sürelerinin iptal oranlarına etkisini analiz etmek.

# Kullanılan Teknolojiler
* **Dil**: Python
* **Kütüphaneler**: Pandas, NumPy, Matplotlib, Seaborn
* **Geliştirme Ortamı**: JupyterLab

# Öne Çıkan Bulgular
* **Otel Türü**: Şehir otellerindeki iptal oranlarının kıyı otellerine göre daha yüksek olduğu gözlemlenmiştir.
* **Lead Time (Erken Rezervasyon)**: Giriş tarihinden çok daha önce yapılan rezervasyonların iptal edilme olasılığı belirgin şekilde artmaktadır.
* **Sezonluk Trend**: Yaz aylarında (Temmuz - Ağustos) doluluk tavan yaparken, paralel şekilde toplam iptal sayıları da en yüksek seviyeye ulaşmaktadır.

# Proje Yapısı
* `01_hotel_booking_analysis.ipynb`: Veri temizleme, ön işleme ve görselleştirme kodları.
* `README.md`: Proje açıklama belgesi.
*