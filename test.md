# Analisis Regresi Linier Sederhana

## Data Penelitian

### Variabel Penelitian
- **Variabel X**: Jam Belajar
- **Variabel Y**: Nilai Ujian

### Dataset
| No | X (Jam Belajar) | Y (Nilai Ujian) |
|----|-----------------|-----------------|
| 1  | 4 | 75 |
| 2  | 5 | 80 |
| 3  | 3 | 70 |
| 4  | 6 | 85 |
| 5  | 2 | 65 |
| 6  | 5 | 82 |
| 7  | 4 | 78 |
| 8  | 3 | 72 |
| 9  | 6 | 83 |
| 10 | 2 | 68 |

## Perhitungan Statistik Dasar

### Jumlah dan Rata-Rata
- **n (Jumlah Data)**: 10
- **ΣX (Total Jam Belajar)**: 40
- **ΣY (Total Nilai Ujian)**: 768
- **X̄ (Rata-rata Jam Belajar)**: 4
- **Ȳ (Rata-rata Nilai Ujian)**: 76.8

## Tabel Perhitungan Regresi

| X | Y | (X - X̄) | (Y - Ȳ) | (X - X̄)² | (X - X̄)(Y - Ȳ) |
|---|---|----------|----------|------------|-------------------|
| 4 | 75 | 0 | -1.8 | 0 | 0 |
| 5 | 80 | 1 | 3.2 | 1 | 3.2 |
| 3 | 70 | -1 | -6.8 | 1 | 6.8 |
| 6 | 85 | 2 | 8.2 | 4 | 16.4 |
| 2 | 65 | -2 | -11.8 | 4 | 23.6 |
| 5 | 82 | 1 | 5.2 | 1 | 5.2 |
| 4 | 78 | 0 | 1.2 | 0 | 0 |
| 3 | 72 | -1 | -4.8 | 1 | 4.8 |
| 6 | 83 | 2 | 6.2 | 4 | 12.4 |
| 2 | 68 | -2 | -8.8 | 4 | 17.6 |

## Perhitungan Koefisien Regresi

### Rumus Koefisien
- **Σ(X - X̄)²**: 20
- **Σ(X - X̄)(Y - Ȳ)**: 90

### Koefisien
- **b (Slope)**: 4.5
- **a (Intercept)**: 58.8

## Persamaan Regresi Linier
**Y = 58.8 + 4.5X**

### Interpretasi
- Untuk setiap tambahan 1 jam belajar, nilai ujian diperkirakan naik 4.5 poin
- Jika tidak belajar (X=0), nilai dasar adalah 58.8

## Kesimpulan
Terdapat korelasi positif antara jam belajar dan nilai ujian, di mana semakin banyak waktu belajar, semakin tinggi nilai yang diperoleh.

## Catatan Metodologi
- Metode: Kuadrat Terkecil (Least Squares)
- Variabel Independen: Jam Belajar
- Variabel Dependen: Nilai Ujian

*Dokumen ini dibuat pada: {{ current_date }}*