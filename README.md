# Coway-study-case
Python Task Test

Catatan:

1.) ada 2 tabel baru yang ditambahkan pada data, yaitu kolom Outstanding group dan Collection Rate.

2.) Kolom Outstanding group terdiri atas grup A, B, C, dan D. Dimana, grup A berisikan Outstanding Amount < 500000, grup B berisikan 500000 <= Outstanding amount <= 5000000,
grup C berisikan 5000001 <= Outstanding amount <= 10000000, grup D berisikan amount Outstanding > 10000000.

3.) Collection Rate akan bernilai 100 jika jumlah payment >= jumlah invoice. Jika jumlah payment < jumlah invoice, maka akan menggunakan rumus: (jumlah payment / jumlah invoice) x 100.

4.) terdapat 2 dataset hasil akhir, yaitu cleaned data1 dan cleaned data2. cleaned data1 berisikan dataset tanpa '[NULL]' dalam kolom Total Payment (rows yang mengandung [NULL] didrop). 
cleaned data2 berisikan dataset dengan '[NULL]' dalam kolom Total Payment (nilai '[NULL]' dianggap sebagai 0 dikarenakan null = uang tidak masuk payment = nilainya 0).

5.) terdapat 2 jenis file ipynb, data cleaning.ipynb menghasilkan dataset cleaned data1 dan data cleaning2.ipynb menghasilkan dataset cleaned data2.


Link for aggregated data: https://drive.google.com/drive/folders/135qEQNInfY-iZSbD6OSAwkuTP4Me7-D6?usp=sharing
