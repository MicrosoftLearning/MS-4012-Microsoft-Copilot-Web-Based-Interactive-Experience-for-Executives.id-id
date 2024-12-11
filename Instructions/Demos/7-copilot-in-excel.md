---
demo:
  title: 'Demo: Copilot di Excel'
---

[Kembali ke Indeks](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft 365 Copilot di Excel

## Persiapan Demo

Unduh dokumen contoh Excel [**EV_Charger_Sales_Analysis_v1.xlsx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/raw/refs/heads/master/Resourcefiles/EV_Charger_Sales_Analysis_v1.xlsx). Anda akan menggunakan berkas ini untuk menjalankan langkah-langkah demo yang diuraikan dalam panduan ini.


## Poin Pembicaraan

Microsoft 365 Copilot di Excel mengubah siapa pun menjadi analis data, sehingga memungkinkan Anda untuk dengan cepat memahami tren utama, metrik kinerja, dan faktor-faktor yang mendorong hasil bisnis atau proyek Anda.

Apakah Anda mengolah data penjualan, laporan keuangan, umpan balik pelanggan, atau metrik operasional, Copilot membantu Anda menyusun dan menganalisis informasi Anda, dengan memberikan wawasan dari kumpulan data kompleks yang berasal dari berbagai sumber.

Dengan Copilot, Anda dapat dengan mudah memperoleh wawasan yang bermakna untuk mendukung pembuatan keputusan yang lebih baik, terlepas dari jenis data atau kompleksitas analisisnya.

## Langkah Demo

> **CATATAN:** Pastikan untuk membuka berkas Excel **EV_Charger_Sales_Analysis_v1.xlsx** sebelum melanjutkan.

1. **Buka tab "Penjualan berdasarkan Produk"**  di berkas Excel.

1. Gunakan Copilot untuk Menghitung Pendapatan Bulanan:  

   Mari kita mulai dengan mencari tahu kategori bisnis Anda yang menghasilkan pendapatan terbesar. Lembar ini berisi data penjualan tiga tahun, dengan ribuan baris yang menunjukkan penjualan berdasarkan produk per bulan. Meskipun ini tugas rutin, volume data ini bisa menjadi sangat berat. Anda dapat meminta Copilot untuk menghitung pendapatan bulanan dengan cepat berdasarkan produk.

   Gunakan perintah berikut ini:

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```
    - Copilot tahu cara melakukannya dan data mana yang akan dilihat di seluruh tab. 
    - Copilot membuat rencana untuk menjalankan perhitungan tersebut, melaksanakan rencana itu sambil menunjukkan proses kerjanya, dan meminta Anda untuk mengajukan pertanyaan atau menyusun solusi yang telah dicapai.
    - Klik  **+Tambahkan kolom**, lalu kembali ke tab **Penjualan berdasarkan Produk**.
   

1. Gunakan Copilot untuk menganalisis pendapatan dengan memasukkan perintah berikut di panel Copilot:

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot akan menjalankan perhitungan dan membuat diagram batang yang dapat Anda tambahkan ke buku kerja Anda.
    - Klik **+Tambahkan ke lembar baru**, lalu kembali ke tab **Penjualan berdasarkan Produk** .

1. Sekarang, gunakan Copilot untuk menyoroti produk dengan penjualan rendah dengan memasukkan perintah ini:

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot akan menerapkan pemformatan bersyarat, sehingga membantu Anda mengidentifikasi produk yang tidak memenuhi standar Anda.

1. **Buka tab "Ulasan"** untuk menganalisis umpan balik pelanggan.

1. Minta Copilot untuk meringkas masalah utama dengan memasukkan perintah berikut:

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot akan menganalisis umpan balik dan menampilkan tiga kekhawatiran teratas pelanggan. Sepertinya kecepatan pengisian menjadi masalah yang baru muncul.

1. Selanjutnya, sorot ulasan yang menyebutkan kecepatan pengisian daya dengan memasukkan perintah ini:

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot akan menyoroti semua ulasan yang relevan dalam dataset.

### Wrap-up

Dengan bantuan Copilot, Anda dapat menganalisis kumpulan data yang kompleks dan memperoleh wawasan tentang kinerja produk dan umpan balik pelanggan. Wawasan ini dapat digunakan untuk menginformasikan ulasan bisnis Anda berikutnya.
