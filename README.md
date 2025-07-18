# Capstone-Project-Sentiment-Analysis-Netizen-Indonesia-terhadap-5-E-Course-E-Learning

**Title project**
Capstone Project Sentiment Analysis Netizen Indonesia terhadap 5 E-Course E-Learning

**Project overview**
● Tujuan Proyek
Proyek ini bertujuan untuk mengetahui persepsi masyarakat terhadap 5 jenis e-course/e-learning (Basic Online Course Learning (BOCL), Premium Online Learning (POL), Private Online Course Learning (POCL), Onsite Course Learning (OCL), dan Private Course Onsite Learning (PCOL)), dengan cara mengurutkan mereka berdasarkan sentimen atau rating tertinggi, serta mengelompokkan review ke dalam kategori sentimen bagus, netral, dan buruk untuk mendukung pemahaman yang lebih mendalam bagi penyedia e-learning.

● Latar Belakang & Permasalahan
Meningkatnya pemanfaatan e-learning di Indonesia menciptakan kebutuhan untuk memahami pengalaman pengguna secara mendalam agar kualitas layanan e-course dapat ditingkatkan. Analisis sentimen secara sistematis terhadap ulasan pengguna akan membantu penyelenggara platform dalam membuat keputusan berbasis data yang relevan dan tepat sasaran.

● Pendekatan
- Pengumpulan dan pengolahan data ulasan pengguna (review) dari berbagai platform e-learning.
- Pengurutan e-course berdasarkan skor sentimen dan rating serta klasifikasi sentimen review menggunakan model AI berbasis Large Language Model (LLM) IBM Granite 3.3.

**Raw dataset link**
[https://www.kaggle.com/datasets/defaultujijk/dataset-netizen-indonesian-sentiment-review1
](url)

**Insight & findings**
Berdasarkan analisis sentimen terhadap lima jenis e-course/e-learning, Onsite Course Learning (OCL) menduduki peringkat tertinggi dengan rata-rata sentimen 1.41 dari 438 ulasan, mengindikasikan kepuasan pengguna yang cukup kuat. Diikuti oleh Private Online Course Learning (POCL) dan Private Course Onsite Learning (PCOL) yang juga mendapatkan rating sentimen di atas rata-rata. Sebaliknya, Premium Online Learning (POL) berada pada posisi terendah dengan rata-rata sentimen 1.00 dari 439 ulasan, menunjukkan adanya ruang perbaikan yang cukup signifikan.

Analisis mendalam menunjukkan bahwa sentimen buruk umumnya berkaitan dengan kualitas materi yang kurang mendalam atau usang, performa instruktur yang kurang mengena, serta platform yang mengalami masalah teknis dan sulit digunakan. Sebaliknya, sentimen bagus didominasi oleh materi yang relevan dan up-to-date, instruktur yang komunikatif dan adaptif, serta platform yang ramah pengguna dan stabil. Sentimen netral menunjukkan kondisi standar dengan beberapa modul unggulan dan performa instruktur serta platform yang memadai tanpa kelebihan signifikan.

**AI support explanation**
Dalam proyek ini, AI digunakan secara efektif dengan memanfaatkan model Large Language Model (LLM) IBM Granite versi 3.3 untuk berbagai tugas analisis dan klasifikasi ulasan pengguna e-learning dalam Bahasa Indonesia. Model ini diaplikasikan untuk:
- **Klasifikasi Sentimen:** Model mengklasifikasikan ulasan menjadi tiga kategori sentimen utama, yaitu Buruk, Netral, dan Bagus, berdasarkan isi teks ulasan. Hal ini memungkinkan segmentasi data secara sistematis untuk memahami persepsi pengguna terhadap produk e-learning.
- **Pembuatan Rangkuman (Summarization):** Dengan memproses kumpulan ulasan yang besar, AI secara otomatis menghasilkan ringkasan insight singkat dan padat yang merefleksikan poin-poin utama terkait kualitas materi, performa instruktur, dan kemudahan penggunaan platform. Ini mempercepat pemahaman hasil analisis tanpa perlu membaca seluruh review secara manual.
- **Analisis Sentimen Kontekstual dan Kategori:** AI membedakan dan mengelompokkan feedback berdasarkan kategori konten yang spesifik, seperti Content Quality, Instructor Performance, dan Platform Usability, sehingga hasil analisis menjadi lebih terstruktur dan informatif.

Model IBM Granite 3.3 dilengkapi dengan kemampuan reasoning canggih yang meningkatkan akurasi klasifikasi dan pemahaman konteks, serta konfigurasi parameter seperti top_k, top_p, dan repetition_penalty dioptimalkan agar menghasilkan output yang relevan, ringkas, dan stabil.
Penggunaan model AI ini secara signifikan meningkatkan efisiensi proses analisis data ulasan besar dan membantu penyelenggara e-learning membuat keputusan strategis berbasis data, yang jauh lebih cepat dan akurat dibandingkan metode manual tradisional. Oleh karena itu, integrasi dengan AI memungkinkan update analisis secara berkala dengan konsistensi tinggi, memberikan insight terkini terkait persepsi pengguna di pasar e-learning Indonesia.
