# IBM Telco Müşteri Analizi

Bu proje, bir telekomünikasyon şirketinin müşteri verilerini analiz etmeyi amaçlamaktadır. Analiz, Kaggle gibi platformlardan elde edilen müşteri verileri kullanılarak gerçekleştirilmiştir.

## 📂 İçerik

Proje aşağıdaki dosya ve klasörleri içermektedir:

- **`telco.csv`**: Müşteri verilerini içeren CSV dosyası.
- **`telco_analys.ipynb`**: Veri analizi ve görselleştirmelerin yer aldığı Jupyter Notebook dosyası.
- **`LICENSE.md`**: Projenin MIT lisansı altında olduğunu belirten lisans dosyası.

## 📊 Analiz Adımları

1. **Veri Yükleme ve İnceleme**:  
   - `telco.csv` dosyasındaki veriler **pandas** kütüphanesi kullanılarak yüklendi.  
   - Temel istatistiksel bilgiler incelendi.

2. **Veri Temizleme**:  
   - Eksik veya tutarsız veriler tespit edilerek uygun yöntemlerle temizlendi.

3. **Veri Görselleştirme**:  
   - **Matplotlib** ve **Seaborn** kullanılarak müşteri davranışları analiz edilerek grafiklerle görselleştirildi.

## 🛠 Gereksinimler

Analizi tekrarlamak veya geliştirmek için aşağıdaki kütüphanelere ihtiyaç vardır:

```bash
pip install pandas numpy matplotlib seaborn
