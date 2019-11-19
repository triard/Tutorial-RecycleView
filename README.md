# Tutorial RecycleView with CardView Java

## introduction

### About RecyclerView
<p>RecyclerView adalah salah satu komponen ui di Android yang sering digunakan dalam sebuah aplikasi. Karena komponen ini digunakan untuk membuat sebuah app yang didalamnya terdapat list atau daftar yang dapat discroll ke atas ke bawah atau ke kanan ke kiri.<p>
<hr>
### Komponen-Komponen RecycleView
- Data
- RecylerView
- Layout untuk satu item data
- Pengelola layout
- Adapter
- View holder

### About CardView
<p>CardView merupakan view paketan dari Material Design — diperkenalkan pada Android Versi Lolipop. Bentuk view ini biasa digunakan untuk pembungkusan data (sepaket data — beberapa view) yang ditandai dengan tampilan view nya yang memiliki drop shadow (elevation) dan corner radius. Adapun CardView ini merupakan subclass dari FrameLayout.</p>

### About Picasso
<p>Picasso (nama yang terinspirasi oleh seniman Perancis terkenal Pablo Picasso) adalah pustaka Android open-source yang sangat populer untuk memuat gambar di aplikasi Android Anda. Menurut dokumen resmi, itu menyatakan:

...Picasso memungkinkan pemuatan gambar tanpa kerumitan dalam aplikasi Anda—sering kali dalam satu baris kode!
Perhatikan bahwa Picasso menggunakan OkHttp (perpustakaan jaringan dari pengembang yang sama) di bawah tenda untuk memuat gambar melalui internet.</p>

## Mengimplementasikan RecyclerView

<b>Menambahkan Dependensi RecylerView, cardview, dan Picasso</b>
```xml
    implementation 'com.android.support:recyclerview-v7:28.0.0'
    implementation 'com.android.support:cardview-v7:28.0.0'
    implementation 'com.squareup.picasso:picasso:2.71828'
```
<b>Tambahkan RecyclerView ke activity_main</b>
<b>Buat layout untuk satu item</b>
<b>PBuat adapter dengan view holder</b>
<b>Menambhakan recyclerview di MainAcitivy</b>

<b>Hasil Output</b>

## Refrensi
1. https://code.tutsplus.com/id/tutorials/code-an-image-gallery-android-app-with-picasso--cms-30966
2. https://medium.com/easyread/tutorial-android-recyclerview-dan-cardview-9a62aaa6cc0c
3. https://google-developer-training.github.io/android-developer-fundamentals-course-concepts/idn/Unit%202/44_c_recyclerview.html
