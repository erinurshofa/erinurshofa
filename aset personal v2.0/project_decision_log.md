---
owner: Eri Nur Sofa
purpose: Menjadi catatan seluruh keputusan penting dalam proyek sehingga
  alasan di balik setiap solusi tidak hilang.
status: living-document
title: project_decision_log
version: 1
---

# PROJECT DECISION LOG

## Filosofi

Dokumen ini tidak mencatat **apa** yang dibuat, tetapi **mengapa**
keputusan tersebut diambil.

Setiap keputusan harus memiliki alasan yang dapat dipertanggungjawabkan.

------------------------------------------------------------------------

# Prinsip

-   Tidak semua proyek membutuhkan solusi yang sama.
-   Tidak semua fitur harus dibuat.
-   Solusi mengikuti kebutuhan, bukan tren teknologi.
-   Keputusan diambil berdasarkan manfaat, ruang lingkup, waktu, dan
    pengguna.

------------------------------------------------------------------------

# TEMPLATE

## Informasi Proyek

-   Nama Proyek:
-   Klien:
-   Tahun:
-   Peran:

## Keputusan

### Keputusan

Apa yang diputuskan?

### Alasan

Mengapa dipilih?

### Alternatif

Pilihan lain yang dipertimbangkan.

### Mengapa tidak dipilih?

### Dampak

Apa manfaat keputusan ini?

### Risiko

### Pelajaran

------------------------------------------------------------------------

# CASE 01

# E-SANKEM

## Konteks

Digitalisasi proses Santunan Kematian Dinas Sosial.

------------------------------------------------------------------------

## Decision 01

### Keputusan

Tidak langsung mulai coding.

### Alasan

Proses melibatkan banyak aktor: - Kelurahan - Kecamatan - PIC Dinsos -
Subkor - Bagian Cetak SK

Jika alur belum dipahami, revisi akan tinggi.

### Dampak

Pengembangan lebih terarah.

### Pelajaran

Discovery lebih murah daripada revisi.

------------------------------------------------------------------------

## Decision 02

### Keputusan

Melakukan discovery dengan banyak pertanyaan.

### Pertanyaan

-   Siapa yang terlibat?
-   Apa tugas masing-masing?
-   Jika ditolak?
-   Jika data salah?
-   Setelah ini siapa?
-   Apa output tahap ini?

### Alasan

Mengurangi asumsi.

### Pelajaran

Pertanyaan yang baik lebih berharga daripada langsung membuat fitur.

------------------------------------------------------------------------

## Decision 03

### Keputusan

Mencatat hasil diskusi di Notepad/buku sebelum implementasi.

### Alasan

Agar tidak kehilangan informasi saat coding.

------------------------------------------------------------------------

## Decision 04

### Keputusan

Menggunakan AI untuk membantu membuat diagram alur dan implementasi
kode.

### Alasan

AI mempercepat dokumentasi dan pengembangan.

### Catatan

AI bukan pengganti analisis kebutuhan.

Pemahaman proses tetap dilakukan oleh saya.

------------------------------------------------------------------------

## Decision 05

### Keputusan

Menambahkan Dashboard Durasi Layanan.

### Status

Inisiatif pribadi.

Bukan permintaan klien.

### Alasan

Ingin mengetahui apakah implementasi sistem benar-benar mempercepat
pelayanan.

### Dampak

Dashboard menunjukkan rata-rata durasi layanan sehingga organisasi dapat
mengevaluasi proses menggunakan data.

Contoh hasil implementasi:

-   Juni sekitar 11,18 hari (masa adaptasi pengguna).
-   Juli sekitar 3,72 hari setelah pengguna mulai terbiasa.

### Pelajaran

Jika ruang lingkup proyek memungkinkan, data evaluasi memberikan nilai
tambah yang besar.

Catatan: Tidak semua proyek membutuhkan dashboard seperti ini. Keputusan
selalu disesuaikan dengan kebutuhan proyek.

------------------------------------------------------------------------

# POLA PENGAMBILAN KEPUTUSAN

Sebelum mengambil keputusan saya biasanya bertanya:

1.  Masalah apa yang ingin diselesaikan?
2.  Siapa pengguna?
3.  Siapa yang terdampak?
4.  Apa manfaatnya?
5.  Apakah fitur ini benar-benar dibutuhkan?
6.  Apakah solusi lebih sederhana sudah cukup?
7.  Apakah keputusan ini sesuai ruang lingkup proyek?

------------------------------------------------------------------------

# KEPUTUSAN YANG HINDARI

-   Menambah fitur tanpa alasan.
-   Mengikuti tren teknologi tanpa manfaat.
-   Coding sebelum memahami proses.
-   Mengambil keputusan berdasarkan asumsi.

------------------------------------------------------------------------

# PELAJARAN BESAR

Software bukan sekadar kumpulan fitur.

Nilai sebuah sistem lahir dari keputusan-keputusan kecil yang diambil
selama proses analisis, perancangan, implementasi, dan evaluasi.

Dokumen ini akan terus bertambah seiring bertambahnya proyek.
