# Polynomial Regression Project

Bu proje, müşteri memnuniyeti ve teşvik verileri üzerinde polynomial regression modeli uygulayan bir Jupyter Notebook içermektedir.

Veri Seti
- `customersatisfaction.csv` dosyası kullanılmıştır.
- İki sütundan oluşur: `Customer Satisfaction` ve `Incentive`.

Kullanılan Teknikler
- Veri ön işleme (eksik veri kontrolü, gereksiz sütunların çıkarılması)
- Görselleştirme (scatter plot)
- Veri standardizasyonu (`StandardScaler`)
- Polynomial özellik mühendisliği (`PolynomialFeatures`)
- Lineer ve Polynomial Regression modelleri
- Model değerlendirme (`r2_score`, `mean_squared_error`)

Sonuçlar
- Lineer regression modeli: `r2_score ≈ 0.27`
- 2. derece polynomial regression: `r2_score ≈ 0.77`
- 3. derece polynomial regression: `r2_score ≈ 0.76`

 Kullanılan Kütüphaneler
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Nasıl Çalıştırılır?
1. Repoyu klonlayın.
2. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
