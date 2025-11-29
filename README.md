# Telco Customer Churn Prediction

**Model klasifikasi churn pelanggan untuk perusahaan telekomunikasi**  
Menggunakan:  
- Preprocessing (StandarScaller + one-hot encoding)  
- Resampling data dengan ADASYN untuk menangani ketidakseimbangan kelas  
- Model klasifikasi yang dipilih: Logistic Regression + ADASYN


---

## Deskripsi Proyek

Perusahaan telekomunikasi sering menghadapi masalah customer churn (pelanggan berhenti berlangganan). Churn ini berdampak langsung pada pendapatan dan stabilitas bisnis. Proyek ini bertujuan membangun sistem prediksi churn berdasarkan fitur pelanggan (durasi layanan, jenis kontrak, layanan internet, dsb), sehingga perusahaan bisa:

- Mengidentifikasi pelanggan yang berisiko churn secara dini  
- Melakukan strategi retensi atau penawaran ulang layanan secara proaktif  
- Mengurangi biaya akuisisi pelanggan baru  
- Meningkatkan loyalitas dan profitabilitas  

Model dibangun dengan preprocessing → resampling  → klasifikasi → dievaluasi.

---

## Struktur Proyek

```text
telco-customer-churn-classification/
├── data/
│   └── data_telco_customer_churn.csv      
├── models/
│   ├── churn_prediction_model.joblib   
│   └── churn_prediction_model.pkl          
├── notebooks/
│   ├── ml_classification_telco_customer_churn.ipynb   
│   └── pipeline.ipynb                      
├── README.md                               
└── requirements.txt
```

---

## Menjalankan Proyek

**1. Clone Repository**

```text
git clone https://github.com/Zepfort/telco-customer-churn-classification.git
cd telco-customer-churn-classification
```

**2.pip install -r requirements.txt**

```text
pip install -r requirements.txt
```

**3.Jalankan Notebook**
```text
notebooks/ml_telco_customer_churn_classification
```
