# Sistem Lapisan Transformasi Teks

Dokumen ini menetapkan struktur dan aturan penggunaan lapisan **Kanonik**, **Alternate Varian**, **Elisi**, dan **Fonetis** dalam pengolahan teks lirik.

## 1. Prinsip Utama

**Kanonik adalah bentuk master.**

Kanonik menjadi bentuk teks resmi yang menjadi sumber seluruh turunan. Perubahan untuk kebutuhan pelafalan, pemangkasan, metrum, atau eksperimen diksi **tidak boleh mengubah Kanonik secara otomatis**.

Lapisan turunan digunakan untuk menyesuaikan teks tanpa merusak bentuk master.

---

## 2. Jenis Lapisan

### 2.1 Kanonik

Bentuk teks utama yang ditetapkan sebagai referensi resmi.

Fungsi:

* Menjadi master text.
* Menjaga bentuk bahasa dan ejaan yang dipilih sebagai bentuk resmi.
* Menjadi sumber bagi seluruh varian dan adaptasi.
* Tidak diubah hanya karena kebutuhan pelafalan atau pencetakan.

Contoh:

```text
Uninga ing sakabehing prakara
```

---

### 2.2 Alternate Varian

Bentuk alternatif dari Kanonik yang menggunakan diksi berbeda tetapi tetap mempertahankan makna inti dan fungsi dalam bait.

Alternate Varian **bukan koreksi terhadap Kanonik** dan tidak menggantikan Kanonik secara otomatis.

Contoh:

```text
Kanonik:
Uninga ing sakabehing prakara

Alternate Varian:
Widya ing saliring prakara
```

Perubahan:

```text
sakabehing → saliring
Uninga → Widya
```

merupakan **substitusi/variasi diksi**, bukan Elisi.

Alternate Varian digunakan apabila terdapat alasan seperti:

* kelancaran sastra;
* kepadatan diksi;
* kesesuaian makna;
* wirama;
* rasa bahasa;
* kemudahan pelafalan;
* atau kebutuhan artistik lainnya.

Alternate Varian dapat menjadi jalur alternatif dari Kanonik. Jika dipilih untuk digunakan, varian tersebut dapat menjalani Elisi dan Fonetis seperti jalur utama.

Alternate Varian yang hanya disediakan sebagai pilihan **tidak mengubah atau membatalkan status FINAL dari jalur utama**.

---

### 2.3 Elisi

Elisi adalah penghilangan atau pemendekan sebagian unsur teks untuk mengurangi beban pelafalan, memperbaiki wirama, atau membuat lirik lebih ringkas.

Contoh:

```text
Kanonik:
Uninga ing sakabehing prakara

Elisi:
Uninga ing kabehing prakara
```

Perubahan:

```text
sakabehing → kabehing
```

merupakan **Elisi**, karena sebagian unsur kata dihilangkan.

Elisi tidak boleh mengubah inti makna secara sembarangan.

Elisi dapat muncul sebelum Fonetis atau digabung langsung dengan Fonetis.

---

### 2.4 Fonetis

Fonetis adalah bentuk yang ditulis untuk merepresentasikan **pelafalan yang ditargetkan**, bukan bentuk Kanonik.

Fonetis digunakan untuk:

* memudahkan pembacaan;
* memandu pelafalan;
* menyesuaikan bunyi lisan;
* kebutuhan nyanyian;
* kebutuhan cetak untuk pembacaan;
* atau kebutuhan performatif lainnya.

Fonetis merupakan **gerbang menuju bentuk pelafalan akhir**.

Contoh:

```text
Kanonik:
Amba Tanpa Wekasan

Fonetis:
Ombo Tanpo Wekasan
```

Perubahan seperti:

```text
Amba → Ombo
Tanpa → Tanpo
```

merupakan perubahan fonetis dan **bukan Elisi**.

Fonetis harus menjadi bentuk pelafalan pada ujung jalur transformasi. Jika masih terdapat kebutuhan Elisi setelah suatu bentuk Fonetis, hasil akhirnya tetap harus dinyatakan dalam bentuk Fonetis.

---

## 3. Urutan Lapisan

Urutan dasar sistem adalah:

```text
Kanonik
    ↓
[Alternate Varian]
    ↓
[Elisi]
    ↓
Fonetis
```

Tanda `[ ]` menunjukkan bahwa lapisan tersebut bersifat opsional.

Namun, **Elisi dan Fonetis dapat digabung dalam satu bentuk akhir** apabila pemangkasan dan penyesuaian pelafalan dilakukan bersamaan.

Contoh:

```text
Kanonik
    ↓
Fonetis
    ↓
Fonetis | Elisi
    ↓
FINAL
```

Dalam kasus tersebut, bentuk **Fonetis | Elisi** adalah bentuk Fonetis terakhir dan menjadi FINAL.

Dengan demikian:

> **Fonetis merupakan gerbang terakhir dari jalur transformasi, tetapi kemunculan Fonetis pertama belum otomatis berarti FINAL jika masih terdapat transformasi pelafalan yang diperlukan.**

---

## 4. Jalur Tanpa Varian

Jika tidak ada Alternate Varian:

```text
Kanonik
    ↓
[Elisi]
    ↓
Fonetis
    ↓
FINAL
```

Jika tidak membutuhkan Elisi:

```text
Kanonik
    ↓
Fonetis
    ↓
FINAL
```

Jika Elisi masih diterapkan setelah bentuk Fonetis:

```text
Kanonik
    ↓
Fonetis
    ↓
Fonetis | Elisi
    ↓
FINAL
```

Bentuk terakhir pada jalur tersebut adalah bentuk yang digunakan untuk pelafalan.

---

## 5. Jalur Dengan Alternate Varian

Jika terdapat Alternate Varian yang dipilih sebagai jalur yang digunakan:

```text
Kanonik
    ↓
Alternate Varian
    ↓
[Elisi]
    ↓
Fonetis
    ↓
FINAL
```

Contoh:

```text
Kanonik:
Uninga ing sakabehing prakara

Alternate Varian:
Widya ing saliring prakara

Fonetis | Varian:
Widyo ing saliring prakoro
```

Karena tidak ada pemangkasan yang diperlukan, Elisi dapat dilewati.

Jika masih diperlukan pemangkasan:

```text
Kanonik:
Uninga ing sakabehing prakara

Alternate Varian:
Widya ing saliring prakara

Fonetis | Elisi | Varian:
Widyo ing saliring prakoro
```

Bentuk Fonetis terakhir pada jalur tersebut menjadi FINAL.

Alternate Varian lain yang hanya disediakan sebagai pilihan tetap berada di luar jalur FINAL.

---

## 6. Elisi dan Fonetis Dapat Digabung

Elisi tidak wajib memiliki versi tersendiri jika pemangkasan dan penyesuaian pelafalan dilakukan dalam satu tahap.

Contoh:

```text
Kanonik:
Uninga ing sakabehing prakara

Fonetis | Elisi:
Uning[o] ing kabehing prakoro
```

Dalam kasus seperti ini, perubahan:

```text
sakabehing → kabehing
```

merupakan Elisi, sedangkan:

```text
Uninga → Uningo
prakara → prakoro
```

merupakan Fonetis.

Keduanya dapat ditulis langsung dalam satu bentuk akhir.

Jika setelah Fonetis masih dilakukan Elisi, maka hasil tersebut harus tetap menjadi bentuk Fonetis:

```text
Fonetis
    ↓
Fonetis | Elisi
    ↓
FINAL
```

---

## 7. Fonetis Sebagai Gerbang Akhir

Fonetis adalah **lapisan terakhir dalam representasi pelafalan**, tetapi tidak selalu berarti bahwa kemunculan Fonetis pertama langsung menjadi FINAL.

Jika setelah Fonetis masih terdapat transformasi yang diperlukan untuk mencapai bentuk pelafalan akhir, transformasi tersebut dapat menghasilkan bentuk Fonetis baru.

Contoh:

```text
Kanonik
    ↓
Fonetis
    ↓
Fonetis | Elisi
    ↓
FINAL
```

Dengan demikian, yang menentukan FINAL adalah:

> **Bentuk Fonetis terakhir pada jalur transformasi yang dipilih.**

Jika tidak ada transformasi lanjutan:

```text
Kanonik
    ↓
Fonetis
    ↓
FINAL
```

Jika terdapat Elisi setelah Fonetis:

```text
Kanonik
    ↓
Fonetis
    ↓
Fonetis | Elisi
    ↓
FINAL
```

---

## 8. Prinsip Identitas Setiap Lapisan

| Lapisan              | Pertanyaan utama                              |
| -------------------- | --------------------------------------------- |
| **Kanonik**          | Apa bentuk teks resminya?                     |
| **Alternate Varian** | Apakah ada pilihan diksi alternatif yang sah? |
| **Elisi**            | Apa yang dapat dipangkas tanpa merusak makna? |
| **Fonetis**          | Bagaimana bentuk tersebut dilafalkan?         |

Dengan prinsip ini, setiap perubahan memiliki tempat yang jelas dan tidak tercampur.

---

## 9. Aturan Perlindungan Kanonik

Kanonik tidak boleh diubah hanya karena:

* sulit dilafalkan;
* terlalu panjang untuk dinyanyikan;
* membutuhkan pemangkasan;
* terdapat alternatif diksi yang lebih indah;
* terdapat perubahan vokal dalam pelafalan;
* atau terdapat kebutuhan versi cetak.

Solusinya adalah membuat lapisan turunan.

Dengan demikian:

```text
KANONIK = MASTER
```

sedangkan:

```text
ALTERNATE VARIAN = PILIHAN DIKSI
ELISI = PEMANGKASAN
FONETIS = REPRESENTASI PELAFALAN
```

Kanonik tetap menjadi bagian dari jalur FINAL ketika suatu bentuk Fonetis terakhir telah ditetapkan.

---

## 10. Prinsip Final

Sistem transformasi mengikuti prinsip:

```text
Kanonik
    ↓
[Alternate Varian]
    ↓
[Elisi]
    ↓
Fonetis
    ↓
FINAL
```

Tanda `[ ]` menunjukkan bahwa lapisan tersebut bersifat opsional.

Namun, jika Fonetis pertama masih memerlukan penyesuaian melalui Elisi, bentuk Fonetis tersebut dapat menghasilkan bentuk Fonetis akhir:

```text
Kanonik
    ↓
Fonetis
    ↓
Fonetis | Elisi
    ↓
FINAL
```

### Aturan inti

1. **Kanonik selalu menjadi master.**
2. **Alternate Varian tidak mengubah Kanonik.**
3. **Elisi hanya memangkas atau menghilangkan unsur.**
4. **Substitusi kata bukan Elisi; gunakan Alternate Varian.**
5. **Fonetis merepresentasikan pelafalan, bukan bentuk bahasa resmi.**
6. **Fonetis merupakan gerbang terakhir menuju pelafalan akhir.**
7. **Kemunculan Fonetis pertama belum otomatis berarti FINAL jika masih diperlukan transformasi pelafalan.**
8. **Bentuk Fonetis terakhir pada jalur yang dipilih menjadi FINAL.**
9. **Kanonik, beserta transformasi yang membentuk Fonetis terakhir tersebut, merupakan bagian dari paket FINAL.**
10. **Elisi dapat berdiri sendiri sebelum Fonetis atau langsung digabung dengan Fonetis.**
11. **Alternate Varian yang hanya disediakan sebagai pilihan tidak membatalkan status FINAL dari jalur utama.**
12. **Tidak semua lapisan harus dibuat jika tidak diperlukan.**
13. **Versi cetak/performa menggunakan bentuk Fonetis terakhir yang telah ditetapkan.**
14. **Versi publik/arsip utama tetap merujuk pada Kanonik.**

Dengan sistem ini, perubahan bahasa, pilihan diksi, pemangkasan, dan kebutuhan pelafalan dapat berkembang tanpa mengganggu integritas teks Kanonik.

**Fonetis terakhir menjadi gerbang akhir menuju pelafalan dan menjadi penanda bahwa jalur utama telah FINAL.**
