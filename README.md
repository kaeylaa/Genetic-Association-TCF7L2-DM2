# Analisis Linkage Disequilibrium dan Asosiasi Genetik SNP rs7903146 dan rs12255372 pada Gen TCF7L2 terhadap Risiko Diabetes Mellitus Tipe 2: Pendekatan Statistik Genetik Epidemiologi

## Deskripsi

Proyek ini merupakan analisis statistik genetik untuk mengevaluasi hubungan SNP rs7903146 dan rs12255372 pada gen TCF7L2 dengan risiko Diabetes Mellitus Tipe 2 (DM Tipe 2). Analisis dilakukan menggunakan bahasa pemrograman R dan disusun dalam format R Markdown.

## Tujuan Analisis

1. Menghitung parameter Linkage Disequilibrium (D, D', dan r²) antara SNP rs7903146 dan rs12255372.
2. Mengestimasi ukuran asosiasi genetik berupa Odds Ratio (OR), Relative Risk (RR), Attributable Risk (AR), dan Population Attributable Fraction (PAF).
3. Melakukan uji Chi-Square dan Fisher's Exact Test.
4. Membangun model regresi logistik dengan penyesuaian usia dan jenis kelamin.
5. Mengevaluasi keberadaan confounding populasi.
6. Membuat visualisasi LD Heatmap menggunakan R.

## Metode

- Linkage Disequilibrium Analysis
- Odds Ratio (OR)
- Relative Risk (RR)
- Attributable Risk (AR)
- Population Attributable Fraction (PAF)
- Chi-Square Test
- Fisher's Exact Test
- Logistic Regression
- Confounding Analysis
- LD Heatmap Visualization

## Software dan Package

Analisis dilakukan menggunakan R dengan package:

- epiR
- epitools
- genetics
- LDheatmap
- DescTools
- knitr

## Struktur Repository

```text
├── Analisis_DM2.Rmd
├── Analisis_DM2.html
├── casecontrol.css
└── README.md
```

## Kesimpulan

Penelitian ini menunjukkan adanya asosiasi signifikan antara SNP rs7903146 pada gen TCF7L2 dengan kejadian Type 2 Diabetes. Analisis linkage disequilibrium antara rs7903146 dan rs12255372 menghasilkan nilai D’ sebesar 0,006453302 dan r² sebesar 3,739272e−05 yang menunjukkan linkage disequilibrium sangat lemah antar kedua SNP. Hasil uji Chi-Square, Fisher Exact, dan regresi logistik menunjukkan bahwa genotipe TT rs7903146 berhubungan dengan peningkatan risiko DM tipe 2 dengan adjusted OR sebesar 3,133. Analisis confounding menunjukkan bahwa usia dan jenis kelamin tidak memberikan pengaruh yang bermakna terhadap hubungan tersebut. Visualisasi LDheatmap juga mendukung adanya pola linkage disequilibrium yang rendah antara kedua SNP pada gen TCF7L2.

## Penulis

**Stella Caroline**  
Program Studi Statistika  
Universitas Sultan Ageng Tirtayasa
