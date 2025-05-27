# 💰 Personal Finance Dashboard – Power BI

## Deskripsi
Dashboard ini membantu pengguna mengelola dan memantau pengeluaran serta pendapatan pribadi secara interaktif.

## Tools
- Power BI
- DAX
- Dataset: `finance_data.csv`

## Fitur Dashboard
- Total Pendapatan, Pengeluaran, dan Tabungan Bersih
- Visual tren keuangan bulanan
- Analisis kategori pengeluaran terbesar
- Filter interaktif: Bulan, Jenis Transaksi, Kategori

## Sample DAX
```dax
Total Income = CALCULATE(SUM(finance_data[Amount]), finance_data[Type] = "Income")
Total Expense = CALCULATE(SUM(finance_data[Amount]), finance_data[Type] = "Expense")
Net Savings = [Total Income] - [Total Expense]
```

## Screenshot
(Insert preview image)

## Author
- Nama: Erico Vincentcius
- LinkedIn: https://www.linkedin.com/in/ericovincentcius/
