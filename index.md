---
title: Instruksi yang Tersedia Online
permalink: index.html
layout: home
---

# MS-4012: Pengalaman interaktif Microsoft Copilot untuk Eksekutif 

## Daftar Isi Direktori

Demo untuk kursus ini didasarkan pada demo dari kit akselerator [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

Penting bagi Anda untuk membiasakan diri dengan demo sebelum memberikan pelatihan ini. Untuk beberapa lab, Anda akan menggunakan dokumen sampel dan rapat dan email Teams yang telah dibuat sebelumnya.

- Unduh semua contoh dokumen [di sini](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles).
- Siapkan rapat Teams dan utas email dengan mengikuti instruksi [di sini](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Biasakan diri Anda dengan pengalaman Interaktif yang ditemukan [di sini](https://aka.ms/CopilotWebEE).



## Deskripsi Kursus

Jelajahi potensi transformatif Microsoft Copilot dan dampaknya terhadap efisiensi organisasi. Dirancang untuk eksekutif dan pemimpin bisnis tanpa lisensi Copilot, pengalaman ini mendalami seni membuat perintah yang efektif, menawarkan pengalaman interaktif, dan menunjukkan bagaimana Microsoft 365 Copilot dapat berintegrasi dengan mulus ke dalam alur kerja bisnis harian untuk meningkatkan produktivitas dan inovasi.

Tujuan utama untuk penyampaian ini adalah untuk:

- Mengajarkan cara membuat perintah yang efektif
- Mendemonstrasikan Microsoft Copilot (cakupan web) dan memandu peserta melalui pengalaman interaktif
- Mendemonstrasikan Microsoft 365 Copilot di aplikasi office (hingga 3 demo)
- Mengundang peserta untuk mengunduh dan mencoba Microsoft Copilot untuk Seluler

## Waktu Kursus (Perkiraan) 

| # | Topik                                 | Detail                                                                                          | Total Waktu      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Membuat prompt efektif di Microsoft 365 Copilot | - Slide seni perintah <br> - Slide membangun prompt <br> - Slide lab copilot | 10 menit    |
| 2 | Microsoft Copilot di web          | - Demo Microsoft Copilot (mode web) <br> - Pengalaman Interaktif  <br> - Slide Membagikan Pengalaman Anda | 30 menit
                |
| 3
           | Cara kerja Microsoft 365 Copilot     | - Slide Microsoft Graph <br> - Demo Copilot di Word, Microsoft Copilot (mode kerja), Copilot di Outlook, dan Copilot di Teams <br> - Slide Testimonial <br> - Slide Microsoft Copilot di Seluler | 20 menit      |
|   |                                       |                                                                                                  | **Total waktu 60 menit** |


Tautan ke masing-masing demo tercantum di bawah ini.

## Demo

{% assign demos = site.pages | where_exp:"page", "page.url berisi '/Instructions/Demos'" %}
| Demo |
| --- |
{% untuk aktivitas di Demo %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
