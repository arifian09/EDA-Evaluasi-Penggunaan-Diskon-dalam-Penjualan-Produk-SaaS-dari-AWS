# EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS

Project ini merupakan tugas akhir dari modul program Job Connector Data Science di Purwadhika Digital Technology School yang telah mempelajari tentang SQL, data manipulation, data visualization, dan statistics. project ini bertujuan untuk mengimplementasikan materi yang telah dipelajari tersebut kedalam sebuah project.

Yang ditekankan dalam project ini adalah ketajaman analisis dari penyelesaian problem melalui pertanyaan-pertanyaan bisnis yang dibuat. Kita juga bisa membuat pembatasan masalah yang bisa diambil supaya pembahasannya tidak terlalu luas dan fokus. adapun untuk coding yang digunakan bebas, asalkan bisa memberikan informasi baik secara grafik ataupun tabel.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/b85d7d6d-4365-4ef4-b049-58909ac575e3)

Dataset didapatkan dari https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales . Dataset ini berisi data transaksi dari perusahaan SaaS fiktif yang menjual perangkat lunak penjualan dan pemasaran ke perusahaan lain (B2B). Dalam dataset ini, setiap baris mewakili satu transaksi/pesanan (9.994 transaksi).
Topik yang diambil adalah evaluasi penggunaan diskon yang dilakukan tim sales AWS supaya bisa menjaga margin perusahaan sehat. hasilnya akan berupa rekomendasi berdasarkan variabel waktu, customer, industry, segment.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/ab869966-b352-47e9-8232-c20bf0eb8029)

Kenapa ini dilakukan adalah karena ada kebutuhan dari tim Sales & marketing yang ingin mengevaluasi penggunaan diskonnya beberapa tahun kebelakang untuk bisa melakukan efisiensi mengingat budget yang ditentukan perusahaan untuk mengeluarkan diskon terbatas.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/d135887e-3168-47bb-a5de-40fa79c1438d)

Kita bisa lihat hampir setengah dari transaksi yaitu 51,99% deal dengan discount dan peringkat diskon yang sering digunakan adalah 20%,70% lalu 80%. cukup besar ketergantungan transaksi kepada penggunaan diskon, tapi apakah ini sudah yang paling optimal? yang menarik lagi adalah peringkat 2 dan 3 diduduki oleh diskon 70% dan 80%. tentu ini jadi perhatian bagaimana keadaan margin kita jika berjualan dengan diskon sebesar itu.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/d73a3218-2d4c-403f-9bbe-851e91332d68)

kabar baiknya, transaksi terbanyak masih dipegang oleh transaksi tanpa diskon. tetapi cukup besar prosentase transaksi dengan diskon 70% & 80%.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/14806490-e905-4a84-9b39-8f341102a5a2)

untuk menanggapi  itu, kita menemukan beberapa alasan diantaranya adalah persaingan memperebutkan market share dengan kompetitor AWS dan tentunya dalam rangka menyambut market size didunia cloud computing yang sedang berkembang, stimulus diskon menjadi salah satu pilihan untuk bersaing. Tetapi apakah penerapannya sudah tepat?
berikut merupakan pertanyaan yang bisa kita ajukan untuk menjawab pertanyaan diatas

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/6e774ec3-e29d-4fda-9805-c54180c3a36f)

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/c78c431b-b77f-441a-8e1d-9f912449c8ab)

Setelah dilakukan EDA, kita bisa mengetahui berapa banyak pengguna diskon dan non diskon. dari sini kita akan fokus ke transaksi yang menggunakan diskon saja.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/b95419f1-3173-488d-a3c3-6536bf35927e)

untuk waktu terbaik setelah EDA, kita menemukan seperti slide diatas.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/688aa314-3bd5-4157-bbe6-169d710edf14)

untuk customer, kita mesti mengevaluasi penggunaan diskon ke customer morgan stanley dan allstate karena kita cukup banyak spending diskon ke mereka tetapi tidak berbanding lurus dengan sales yang dihasilkan

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/c152e85e-982f-4d4d-a1fa-2018916259cc)

Untuk product kita bisa mengakui bahwa marketing suite gold merupakan produk yang oke karena tidak begitu mengeluarkan spending diskon besar tetapi menghasilkan sales yang bagus. Sebaliknya, yang perlu dievaluasi adalah SaaS Conector Pack, karena secara spending diskon besar tetapi tidak menghasilkan sales yang oke.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/bd2333e2-0380-4cc0-a36b-dcddc268b936)

Untuk industry dan segment mempunyai hubungan korespondensi antara budget yang dikeluarkan terhadap sales yang dihasilkan sehingga tidak ada temuan yang bisa kita ambil.

![image](https://github.com/arifian09/EDA-Evaluasi-Penggunaan-Diskon-dalam-Penjualan-Produk-SaaS-dari-AWS/assets/151009269/8fa5da92-cc6e-4979-994b-e936ba09227b)
Kesimpulan yang bisa kita ambil, untuk waktu terbaik dikeluarkannya diskon ada diawal awal tahun yaitu bulan januari dan februari diakhir bulan yaitu tanggal 29-31. lalu ada beberapa customer yang harusnya dievaluasi untuk mendapatkan diskon seperti morgan stanley dan allstate. untuk product marketing suite gold bisa menjadi product andalan yang mungkin bisa dibundling untuk menaikan sales product lain dan product yang perlu dievaluasi adalah SaaS Conector Pack ini bisa dibuat bundling atau diberikan treatment tertentu untuk bisa menaikan sales tanpa harus menambah spanding diskonnya.
