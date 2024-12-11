---
demo:
  title: 'Demo: Microsoft Copilot (copilot.microsoft.com)'
---

[Kembali ke Indeks](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot (copilot.microsoft.com)

## Copilot dan Model Bahasa Besar

### Poin Pembicaraan

Microsoft Copilot memberi Anda asisten pribadi bertenaga AI yang dapat menjawab pertanyaan dan bantuan dengan tugas umum. Saya dapat mengajukan pertanyaan padanya, dan itu akan memberi saya jawaban yang serupa dengan jawaban orang yang berpendidikan perguruan tinggi.

Saat Anda atau organisasi Anda menggunakan Copilot dengan Perlindungan Data Komersial, obrolan Anda tidak disimpan. Semua data dienkripsi, dan Microsoft tidak menyimpan perintah atau respons Anda. Mereka tidak digunakan untuk melatih model, sehingga Anda bisa yakin bahwa informasi pribadi dan organisasi Anda dirahasiakan.

Misalnya, saya dapat mengajukan pertanyaan pengetahuan umum seperti ini dan mendapatkan banyak informasi luar biasa sebagai balasan. Anda dapat menganggapnya seperti memiliki model konseptual dasar dari seluruh dunia yang dapat digunakan untuk menjawab pertanyaan.

**Contoh:**
- **Prompt:** Apa yang bisa Anda ceritakan tentang gajah?
- **Respons:** (Diskusikan respons)

Copilot menggunakan model bahasa besar (LLM) yang dilatih pada sejumlah besar informasi, termasuk pencarian dan hasil Bing. Tapi Copilot bukan hanya pemeriksa fakta. Kita dapat menggunakan Copilot sebagai mesin penalaran umum yang dapat mengambil pertanyaan Anda dan memberikan penalaran secara stokastik. Di industri, kami menyebut ini sebagai inferensi.

**Contoh:**
- **Perintah:** Saya lebih tertarik pada kekuatan gajah. Berapa banyak manusia yang dibutuhkan untuk memenangkan tarik tambang dengan gajah? CATATAN: Perlu diingat wilayah dan audiens Anda karena tidak semua orang tahu istilah "tarik tambang" sehingga Anda mungkin harus memodifikasinya dengan sesuai. 
- **Respons:** (Diskusikan respons)

Copilot dapat membuat asumsi dan menarik koneksi antara potongan pengetahuan untuk memberi saya jawaban yang lebih bernuansa untuk pertanyaan saya. Saat kami meningkatkan Copilot, kami belajar banyak tentang kelebihan dan kekurangan LLM ini dan kami membangun pengetahuan tersebut ke dalam produk saat kami membuatnya.

### Langkah Demo

> **CATATAN:** Jika Anda ingin menggunakan perintah Anda sendiri, mulailah dengan topik pengetahuan umum yang menarik bagi Anda atau pelanggan Anda.

1. Untuk meluncurkan Microsoft Copilot, buka tab browser Edge baru dan navigasi ke <a href="https://copilot.microsoft.com" target="_blank">copilot.microsoft.com</a>.

1. Masuk ke akun microsoft non-kerja.

    > **CATATAN:** Jika Anda masuk ke akun kerja, Anda akan diarahkan ke obrolan Bisnis (m365.cloud.microsoft/chat) 

1. Dalam kotak teks **Mengirim Pesan kepada Copilot**, salin dan tempel perintah dari dokumen atau jenis pustaka perintah:

    ```text
    What can you tell me about elephants?
    ```
1. Pilih tombol **Kirim**.
1. Dalam kotak teks **Mengirim Pesan kepada Copilot**, salin dan tempel perintah:

    ```text
    I’m more interested in the power of an elephant. How many humans would it take to win a tug-of-war with an elephant?
    ```
1. Pilih tombol **Kirim**.

## Pembumian

### Poin Pembicaraan

Tetapi yang membawa kekuatan ini ke tingkat berikutnya adalah kemampuan untuk mendasarkan Copilot kepada data dan pengetahuan eksternal. Terkadang ini disebut Retrieval Augmented Generation (RAG). Ini adalah proses memberikan informasi tambahan ke model bahasa yang relevan dengan tugas yang ditangani.

Kita dapat mendasarkan pertanyaan kita kepada semua jenis data dan dokumen, misalnya, laporan pekerjaan Biro Statistik Tenaga Kerja. Ini adalah dokumen besar, yang diterbitkan setiap tahun, yang penuh dengan data tentang pekerjaan dan tren pekerjaan di seluruh Amerika Serikat. Copilot bisa meluncur dan menemukan informasi itu, memahaminya, dan memberikan saya jawaban atas pertanyaan saya secara real time. Ini juga memberi saya referensi yang menunjukkan kepada saya dari mana Copilot mendapatkan informasi itu, misalnya, situs web Biro Statistik Tenaga Kerja. Ini berarti saya dapat memeriksa di mana Copilot mendapatkan informasinya dan mendapatkan lebih banyak konteks, karena ini adalah Copilot, bukan autopilot.

### Langkah Demo

1. Mulai topik baru, dengan mengklik **lihat riwayat** lalu **Mulai obrolan** baru.

1. Dalam kotak teks **Mengirim Pesan kepada Copilot**, salin dan tempel perintah:

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years?
    ```
1. Pilih tombol **Kirim**.
1. Dalam respons, di samping **Pelajari selengkapnya**, hentikan mouse di atas satu atau dua referensi.

## Keterampilan Copilot Tambahan

### Poin Pembicaraan

Ini bagus, tetapi saya benar-benar ingin melihat grafik data ini. Sayangnya, Copilot tidak bisa menggambar grafik sekarang, tapi itu tidak berarti kita terhenti. Saat membangun Copilot, kami menambahkan keterampilan yang berbeda. Keterampilan adalah cara agar Copilot dapat menggunakan daya penalarannya untuk menyelesaikan masalah.

Kemampuan lain yang saya tahu Copilot miliki adalah kemampuan untuk menulis kode. Saya akan mengingatkan Copilot bahwa ia tahu cara menulis kode dan melihat apakah saya bisa membuatnya menulis kode Python untuk grafik yang saya inginkan.

**Contoh:**
- **Perintah:** Dapatkah Anda memberi saya daftar tingkat partisipasi angkatan kerja dari Biro Statistik Tenaga Kerja selama 5 tahun terakhir? Saya juga mendengar bahwa Anda bisa menulis kode. Dapatkah Anda mengambil data dari bls.gov lalu menulis kode Python yang akan menghasilkan grafik yang saya cari?
- **Respons:** (Diskusikan respons)

Seiring waktu, kami mengharapkan proses semacam ini menjadi lebih mudah dan lebih otomatis.

### Langkah Demo

1. Mulai topik baru, dengan mengklik **lihat riwayat** lalu **Mulai obrolan** baru.

1. Dalam kotak teks **Mengirim Pesan kepada Copilot**, salin dan tempel perintah:

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years? I also heard that you could code. Can you grab the data from bls.gov and then write the Python code that would produce the graph I'm looking for?
    ```

1. Pilih tombol **Kirim**.

## Langkah-langkah Demo Opsional

### Mengenali Gambar

Pertama unduh yang berikut: [**What is this image.png**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/what_is_this_image.PNG)

1. Mulai topik baru, dengan mengklik **lihat riwayat** lalu **Mulai obrolan** baru.

1. Di bagian bawah halaman, pilih ikon Plus (**+**).

1. Telusuri ke tempat Anda mengunduh gambar, pilih **What is this picture.png**, lalu pilih **Buka**.
1. Dalam kotak teks **Mengirim Pesan Kepada Copilot...** kotak teks ketik perintah:

    ```text
    What is this picture?
    ```

1. Pilih tombol **Kirim**.

### Perlihatkan Bagaimana Copilot Dapat Membuat Gambar

1. Dalam kotak teks **Mengirim Pesan kepada Copilot**, salin dan tempel perintah:

    ```text
    Copilot, make a banner for a hamburger stand. Make it friendly and show people enjoying a hamburger.
    ```

1. Pilih tombol **Kirim**.

[Kembali ke Indeks](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)
