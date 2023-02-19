# final-project Pre Processing
## Handling Missing Value
Missing values dilakukan dengan cara imputation /  menggisi nilai dengan median dan modus. Hal ini karena data missing value sebesar 32,966% dari data yang dimiliki sehingga menghapus data missing value kurang tepat untuk dilakukan. 

Kolom yang diisi menggunakan median :  
Tenure ,Order Amount Hike From last Year, CouponUsed, OrderCount, day since last order

Kolom yang diisi menggunakan modus :
Hour spend on App
## Handle duplicated data
Berdasarkan kolom CustomerID dapat diketahui bahwa jumlah nilai uniknya sebanyak jumlah data yang dimiliki. Sehingga dapat disimpulkan bahwa satu baris mewakili satu customer.
Maka pada dataset yang dimiliki dapat disimpulkan bahwa tidak ada duplikat data.
## Handle outliers
Handle outlier dilakukan dengan menggunakan z-score karena metode tidak membuang terlalu banyak data yang dimiliki dibandingkan dengan metode IQR. Jumlah total data yang dimiliki yaitu 5630.
## Feature Encoding
1. menggunakan label encoding pada kolom Churn dan complain
2. menggunakan one heat encoding pada kolom'CityTier', 'PreferredLoginDevice', 'PreferredPaymentMode', 'Gender', 'PreferedOrderCat', 'MaritalStatus', 'SatisfactionScore’,
## Handle Class Imbalance
Metode yang digunakan yaitu oversampling
## Feature Engineering
1. Shipping cost
2. Usia Pelanggan
3. Lama Waktu pengiriman
4. Total Spend
