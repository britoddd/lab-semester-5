# Sesi 2
## Classification
untuk predict kategori dari data

## Regression
untuk predict suatu nilai dari data
### Linear Regression -> fokus di sesi ini
untuk output yang masuk ke dalam linear line (garis lurus)
$$ \hat{y} = wx + b $$
$x$ = input  
$\hat{y}$ = prediction  
$m$ = weight  
$b$ = bias

## Loss Function
Mengukur seberapa salah prediksi yang dilakukan model. Untuk linear regression bisa pake Mean Squared Error. Akan lebih highlight error yang lebih besar (karena dikuadratkan)
$$ MSE = \frac{1}{n} \Sigma^{n}_{i=0} (y-\hat{y})^2 $$

## Gradient Descent
untuk mencari titik yang punya loss terkecil pake derivative

### Learning Rate
menentukan seberapa cepat gradient descent kerja
- Terlalu rendah: training terlalu lama karena terlalu pelan
- Terlalu cepat: training juga lama karena terlalu lompat-lompat dan ngga bakal converge