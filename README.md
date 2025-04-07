# Analisis Hubungan antara Karakteristik Demografi dan Pola Perilaku Belanja Konsumen di Supermarket
>`AIMAR MOHAMMAD BUTRAGUENO` - `JCDS 2804`

# **Latar Belakang**
Memahami perilaku konsumen sangat penting dalam dunia ritel saat ini, sehingga organisasi dapat menyesuaikan penawaran dan kampanye pemasaran mereka dengan lebih efektif. Dataset ini memberikan gambaran menyeluruh mengenai atribut pelanggan supermarket, kebiasaan belanja, dan partisipasi dalam kampanye promosi. Setiap titik data dalam dataset ini mewakili interaksi individu pelanggan dengan supermarket, mencakup berbagai aspek seperti data demografis, pola belanja, respons terhadap promosi, dan lainnya. Dataset ini menjadi sumber informasi yang berharga untuk menganalisis dinamika hubungan pelanggan dalam lingkungan supermarket.

# **Pernyataan Masalah**
Dengan menganalisis perilaku pelanggan di Supermarket, Strategi Pemasaran akan dirumuskan untuk membantu bisnis Supermarket menyesuaikan produknya berdasarkan pelanggan yang dituju dari berbagai jenis pelanggan. Tujuan utama dari proyek untuk merumuskan strategi pasar dengan menganalisis Perilaku Belanja Pelanggan. Proyek ini bertujuan untuk menemukan wawasan yang dapat ditindaklanjuti dengan menggali informasi dan memanfaatkan alat analisis data lanjutan, yang kemudian akan disampaikan kepada pemangku kepentingan supermarket. Misalnya, alih-alih menghabiskan uang untuk memasarkan produk baru kepada setiap pelanggan dalam basis data bisnis, supermarket dapat menentukan segmen pelanggan mana yang paling mungkin membeli produk tersebut dan kemudian memasarkan produk tersebut hanya kepada kelompok pelanggan tertentu.

# **Stakeholder**
Store Manager dan Marketing & Sales Teams

# **Data Dictionary**
**PEOPLE**
<br>

| Column | Description
| -- | --- 
| ID | Customer's unique identifier
| Year_Birth | Customer's birth year
| Education | Customer's education level
| Marital_Status | Customer's marital status
| Income | Customer's yearly household income
| Kidhome | Number of children in customer's household
| Teenhome | Number of teenagers in customer's household
| Dt_Customer | Date of customer's enrollment with the company
| Recency | Number of days since customer's last purchase
| Complain | 1 if the customer complained in the last 2 years, 0 otherwise

<br>

**PRODUCT PURCHASE BEHAVIOR**
<br>

| Column | Description
| --- | --- 
| MntWines | Amount spent on wine in last 2 years
| MntFruits | Amount spent on fruits in last 2 years
| MntMeatProducts | Amount spent on meat in last 2 years
| MntFishProducts | Amount spent on fish in last 2 years
| MntSweetProducts | Amount spent on sweets in last 2 years
| MntGoldProds | Amount spent on gold in last 2 years

<br>

**PROMOTIONAL ENGAGEMENT**
<br>

| Column | Description
| --- | --- 
| NumDealsPurchases | Number of purchases made with a discount
| AcceptedCmp1 | 1 if customer accepted the offer in the 1st campaign, 0 otherwise
| AcceptedCmp2 | 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
| AcceptedCmp3 | 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
| AcceptedCmp4 | 1 if customer accepted the offer in the 4th campaign, 0 otherwise
| AcceptedCmp5 | 1 if customer accepted the offer in the 5th campaign, 0 otherwise
| Response | 1 if customer accepted the offer in the last campaign, 0 otherwise

<br>

**PURCHASE PLACES**
<br>

| Feature | Description
| --- | --- 
| NumWebPurchases | Number of purchases made through the company’s website
| NumCatalogPurchases | Number of purchases made using a catalogue
| NumStorePurchases | Number of purchases made directly in stores
| NumWebVisitsMonth | Number of visits to company’s website in the last month

# Analisis & Visualisasi
- Merumuskan analisis dengan menganalisis korelasi untuk beberapa kolom
- Proporsi pelanggan supermarket dari berbagai demografi
- Rata-rata pengeluaran pelanggan dari berbagai demografi selama 2 tahun terakhir
- Kategori pendapatan yang memengaruhi perilaku pembelian pelanggan
- Produk terlaris

# Kesimpulan
Analisis dataset pelanggan supermarket memberikan wawasan penting mengenai perilaku pelanggan, preferensi pembelian, dan konsumsi produk. Segmentasi Pelanggan memungkinkan supermarket untuk menargetkan kampanye pemasaran dengan lebih efektif, seperti menawarkan produk premium kepada pelanggan berpendapatan tinggi. Pelanggan dengan income tinggi dan pendidikan lebih tinggi cenderung menghabiskan lebih banyak, terutama untuk produk premium. Supermarket bisa menyesuaikan harga dan produk sesuai segmen pelanggan, meningkatkan program loyalitas, dan memanfaatkan data untuk mempersonalisasi pemasaran serta mengurangi pemborosan anggaran iklan.

# Rekomendasi
- Peningkatan Pengalaman Pelanggan Berdasarkan Preferensi Produk 
- Penargetan Iklan Berdasarkan Demografi
- Optimalisasi Program Loyalitas dan Hadiah
- Pemahaman tentang Perilaku Pembelian Online vs. Offline
- Penyesuaian Harga Berdasarkan Segmen Pelanggan
- Peningkatan Keterlibatan Pelanggan Melalui Pemasaran yang Lebih Personalisasi
- Analisis Perilaku Pelanggan untuk Mengurangi Pemborosan

# Link Tableu Public
https://public.tableau.com/views/Capstone2-SupermarketCustomerAnalysis-AimarMohammadButragueno/Caps2-AimarM_Butragueno?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# Link PPT Canva
https://www.canva.com/design/DAGj6gBNSdE/VuTFguUFAwchqfFFTJ-xWg/edit?utm_content=DAGj6gBNSdE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
