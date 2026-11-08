# Tugas Manipulasi Data dengan Pandas

Analisis data transaksi POS 2024–2025 menggunakan Pandas: pembersihan data, feature engineering, filtering, sorting, dan agregasi per gerai.

## Struktur
```
.
├── data/paket_a_transaksi_pos_2024_2025.csv
├── Tugas_Manipulasi_Data_Pandas.ipynb
├── requirements.txt
└── README.md
```

## Cara menjalankan
```bash
pip install -r requirements.txt
jupyter notebook Tugas_Manipulasi_Data_Pandas.ipynb
```

## Catatan
- Harga berformat `13.000` diperlakukan sebagai pemisah ribuan (=13000), harga berformat `7500,00` memakai koma desimal.
- `Kontribusi_Gerai_Persen` dihitung terhadap total `Total_Bersih` seluruh transaksi di gerai tersebut.
