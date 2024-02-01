# ***CAPSTONE PROJECT MODULE 3 - SAUDI ARABIA USED CARS***

OLEH: JUSTIFY ESTER PASARIBU (JCDS 0406 006)

<br>

***Source of Dataset:***

- Dataset Saudia Arabia Used Cars: [disini](https://drive.google.com/drive/folders/123QthHe9ECfB1qUFCfDinHibrNhsnZKQ)

<br>

***References about Saudi Arabia Used Cars:***

- [Saudi Arabia Used Car Market Size & Share Analysis - Growth Trends & Forecasts (2024 - 2029)](https://www.mordorintelligence.com/industry-reports/saudi-arabia-used-car-market)

- [Saudi Arabia Used Car Market Report by Vehicle Type (Hatchback, Sedan, MUV and SUV), Sales Channel (Online, Offline), Vendor Type (Organized, Unorganized), and Region 2024-2032](https://www.imarcgroup.com/saudi-arabia-used-car-market)

- [Saudi Arabia Used Car Industry Outlook to 2025 - Digital Enablement, Technological Advancements and Growing Demand from Smaller Cities to Drive Used Car Sales in Saudi Arabia: Ken Research](https://finance.yahoo.com/news/saudi-arabia-used-car-industry-104200074.html)

- [Saudi Arabia Used Car Market Report 2022-2028: Increased Reliability and Quality in Used Cars Presents Opportunities for Growth - ResearchAndMarkets.com](https://www.epicos.com/article/734216/saudi-arabia-used-car-market-report-2022-2028-increased-reliability-and-quality-used)

- [Saudi Arabia Used Car Market Report 2022: Sector Lead by Key Players Kayishha Yallamotor, SaudiSale, Abdul Latif Jameel Motors, Abi Sayara, Olx Saudi Arabia, Carmudi.com & Copart](https://finance.yahoo.com/news/saudi-arabia-used-car-market-120800042.html)

- [Market Opportunities for Used Cars in Saudi Arabia, 2020](https://www.glasgowinsights.com/blog/market-opportunities-for-used-cars-in-saudi-arabia-2020/)

- [Saudi Arabia Used Car Market Trends](https://www.mordorintelligence.com/industry-reports/saudi-arabia-used-car-market/market-trends)

- [Saudi Arabia 2023. YTD Sales Are Up 20.8% From Prior Year](https://www.focus2move.com/saudi-arabia-auto-market/)

- [Sales of New Cars In Saudi Arabia – Data, Trends, Charts & Analysis](https://www.goodcarbadcar.net/saudi-arabia-car-sales-data/)

- [SAUDI ARABIA AUTOMOTIVE MARKET](https://www.trade.gov/market-intelligence/saudi-arabia-automotive-market))

- [Saudi Arabia Used Car Market Trends, Share, Demand and Analysis 2023- Future Outlook, CAGR Growth, Business Opportunity and Forecast Report 2032: SPER Market Research](https://easytoend.com/saudi-arabia-used-car-market-opportunity-research-report-2023/)

- [Saudi Arabia Used Cars Market Growth, Business Opportunities, Share Value, Key Insights and Size estimation by 2031](https://www.iscaninfo.com/article/11800921/Saudi-Arabia-Used-Cars-Market-Growth--Business-Opportunities--Share-Value--Key-Insights-and-Size-estimation-by-2031-%7C-Taiwan-News-%7C-2023-08-22-06-36-58)

- [Saudi Arabia Adopts Measures to Control Used Cars Market, Reduce Prices](https://english.aawsat.com/business/4358941-saudi-arabia-adopts-measures-control-used-cars-market-reduce-prices)

- [SPER Market Research on Saudi Arabia Used Car Market](https://www.sperresearch.com/report-store/saudi-arabia-used-car-market.aspx?sample=1)

<br>

***Project Overview:***

Dalam pengerjaan *capstone project module 3* ini tahapan sesuai dengan contoh capstone project yang diberikan oleh pihak Purwadhika: [Contoh *Capstone Project Module 3*](https://colab.research.google.com/drive/1nLY8-wFKMsfvJDxFJpGjvFzz4glDh2OV#scrollTo=4AfFAHobk-A1)

1. *Business Problem Understanding*
2. *Data Understanding*
3. *Data Preprocessing*
4. *Modeling*
5. *Conclusion*
6. *Recommendation*

***CONTEXT***

Arab Saudi, sebagai salah satu negara terkaya di Timur Tengah, memiliki potensi pasar mobil bekas yang signifikan. Dengan peningkatan pendapatan yang tersedia, jumlah pengemudi wanita yang meningkat (sebelumnya dilarang), dan berkembangnya pasar online untuk jual beli mobil bekas, penjualan mobil bekas di negara tersebut diperkirakan akan tumbuh secara substansial. Dari tahun 2019 hingga 2025, nilai (Gross Transaction Value) penjualan mobil bekas diproyeksikan meningkat hingga 4,5%, sementara volume penjualan meningkat hingga 2%. Pandemi COVID-19 telah menyebabkan peningkatan stok mobil bekas dan pengurangan pendapatan masyarakat, khususnya dengan kenaikan pajak pertambahan nilai dari 5% menjadi 15% pada tahun 2020, mendorong calon pembeli untuk lebih tertarik pada mobil bekas. Platform online seperti Syarah.com menjadi semakin penting dalam konteks ini, menyediakan platform bagi penjual dan pembeli mobil bekas. Seperti yang dilaporkan oleh [Saudi Arabia Used Car Market Size & Share Analysis - Growth Trends & Forecasts (2024 - 2029)](https://www.mordorintelligence.com/industry-reports/saudi-arabia-used-car-market), pasar mobil bekas di Arab Saudi mencapai nilai USD 4,91 miliar pada tahun 2021 dan diproyeksikan akan meningkat menjadi USD 8,69 miliar pada tahun 2027, dengan tingkat pertumbuhan tahunan gabungan (CAGR) sebesar 7,36%.

***PROBLEM STATEMENT***

Tantangan utama adalah menentukan harga mobil bekas dengan akurat. Harga yang terlalu tinggi dapat menghambat penjualan, sementara harga yang terlalu rendah dapat mengurangi keuntungan. Faktor-faktor seperti merk, model, tahun, jarak tempuh, ukuran mesin, dan lain-lain, mempengaruhi harga mobil bekas, namun tidak semua penjual memiliki pengetahuan yang cukup tentang fluktuasi harga ini.

***GOALS***

Tujuan utama adalah mengembangkan model yang dapat memprediksi harga mobil bekas berdasarkan spesifikasi mobil. Model ini akan menjadi referensi bagi penjual dan pembeli mobil bekas, membantu mereka membuat keputusan transaksi dengan lebih cepat. Model ini juga bermanfaat bagi platform online seperti Syarah.com untuk meningkatkan jumlah transaksi dan pertumbuhan bisnis mobil bekas.

***ANALYTIC APPROACH***

Membangun model regresi yang menganalisis spesifikasi mobil yang mempengaruhi harga. Model ini akan dibangun berdasarkan data historis dan fitur yang relevan.

***METRIC EVALUATION***

**Metrik Evaluasi untuk Regresi:**
- `Root Mean Squared Error (RMSE):` Mengukur rata-rata kesalahan kuadrat.
R-Squared: Menunjukkan seberapa baik data cocok dengan model regresi.
- `Mean Absolute Error (MAE):` Mengukur rata-rata kesalahan absolut.
- `Mean Absolute Percentage Error (MAPE):` Mengukur rata-rata persentase kesalahan.
- `Mean Squared Log Error (MSLE):` Fokus pada perbedaan logaritmik antara nilai prediksi dan aktual.
- `Root Mean Squared Logarithmic Error (RMSLE):` Cocok untuk data dengan outlier.
- `R-squared (R2):` Menunjukkan seberapa besar variasi nilai yang dapat dijelaskan oleh model.

Semua metrik ini akan digunakan untuk membandingkan dan memilih model terbaik yang sesuai dengan karakteristik data yang ada. Pendekatan ini akan memastikan model yang dikembangkan akurat dan dapat diandalkan dalam memprediksi harga mobil bekas di pasar Arab Saudi.
