# GDP_XGBoost_Project
Ülke bazlı GDP verilerini işleyip XGBoost ile tahmin eden Python tabanlı bir makine öğrenmesi projesi.
# GDP XGBoost Tahmin Projesi

Bu proje, ülke bazlı GDP (nominal) verilerini** kullanarak XGBoost algoritması ile GDP tahminleri yapmaktadır. Proje, üniversite 2. sınıf düzeyinde hazırlanmıştır ve temel veri ön işleme, EDA ve makine öğrenmesi adımlarını içerir.

---

## Proje İçeriği

- `GDP_XGBoost.ipynb` : Jupyter Notebook ile tüm veri temizleme, EDA, model eğitimi ve görselleştirme adımları.
- `Global GDP Explorer 2025 (World Bank  UN Data).csv` : Kullanılan veri seti.
- `README.md` : Proje açıklaması ve kullanım rehberi.

---

##  Kullanılan Kütüphaneler

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  

---

## Proje Adımları

1. Veriyi okuma ve kolon isimlerini temizleme  
2. Object kolonları güvenli şekilde sayısala çevirme  
3. Eksik değerleri temizleme  
4. Basit EDA (istatistikler, histogram, korelasyon)  
5. Veri setini eğitim ve test olarak ayırma  
6. XGBoost + GridSearchCV ile model eğitimi  
7. Model performans değerlendirmesi (MAE, RMSE, R²)  
8. Feature Importance görselleştirme

---

## Model Performansı

- MAE  : Çok yüksek (GDP değerleri milyarlarca olduğu için)  
- RMSE : Çok yüksek  
- R²   : 0.96 (Model verinin %96'sını açıklıyor)

---

##  Notlar

- GDP değerleri milyar dolar cinsine çevrilip görselleştirilebilir.  
- Projede Country kolonları one-hot encoding ile sayısala çevrilmiştir.  
- XGBoost kütüphanesi kurulmalıdır: `pip install xgboost`
