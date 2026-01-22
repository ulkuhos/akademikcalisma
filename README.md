#| **2024/2026 Yüksek Lisans Tezi** | 

## "MAKİNE ÖĞRENMESİ YÖNTEMLERİ İLE E-TİCARETTE MÜŞTERİ KAYBI TAHMİNİ" 

## Genel Bakış

Bu depo, **"Makine Öğrenmesi Yöntemleri ile E-Ticarette Müşteri Kaybı Tahmini"** başlıklı yüksek lisans tez çalışmasının kodlarını ve veri setini bilgisini içermektedir.  Çalışmada, e-ticaret sektöründe müşteri kaybını tahmin etmek için sınıflandırma yaklaşımlı makine öğrenmesi yöntemleri ve kapsamlı istatistiksel doğrulama yöntemleri kullanılmaktadır. XGBoost, Random Forest, Bagging ve KNN algoritmaları karşılaştırılmış, İstatiksel testler ve Optuna ile hiperparametre optimizasyonu yapılmış, SHAP/LIME ile model açıklanabilirliği sağlanmıştır. 

**En İyi Model:** XGBoost (AUC=0.988, F1=0.915)  
**Kritik Özellikler:** Tenure, Complain, CashbackAmount, DaySinceLastOrder

## Veri Seti Bilgileri Hakkında
Çalışmada kullanılan veri seti, Kaggle platformundan alınan, "E-Commerce Customer Churn Analysis and Prediction" isimli Ankit Verma tarafından 2020 yılında paylaşılan açık kaynaklı bir e-ticaret müşteri veri setidir (Verma, 2020). 

Verma, A. (2020). E-Commerce Customer Churn Analysis and Prediction [Kaggle Veri Seti].
Erişim adresi: https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction/data 


