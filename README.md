# Tugas-minggu-awal 
 # Resummary One week
1. **Unix Command Line**
- Shell: yang dimana bertujuan untuk berkomunikasi atau memerintah system. Pengertian lainnya Shell yang menerima perintah kita lalu meneruskan perintah kita untuk dieksekusi oleh system.
- Untuk pengguna windows maka kita bisa membuka yang namanya powershell.
- Command Line Interface: jenis shell yang berbentuk teks.
- Navigation: yaitu perintah ketika kita ingin pindah pindah ke suatu folder.
1.  ls: menampilkan daftar file
2.  ls - la: menampilkan daftar file yang di sembunyikan/hidden.
3. cd : pindah directory/folder
4. cd .. : pindah ke directory sebelumnya
5. clear: bersihkan tampilan terminal
6. ni nama_file.extensi: perintah untuk membuat file melalui windows
7. Touch nama_file.extensi:perintah untuk membuat file melalui Linux & Unix (MacOs).
8. cp :menduplikat file.
9.pindah ke directory master: cd nama_master_directory contoh **cd D**:
10.  mkdir: membuat folder

2. **Git & Github**
- Git merupakan sebuah software atau tools yang digunakan untuk melakukan manajemen versi pada sebuah project
- Git & GitHub adalah tools code collaboration yang wajib bagi software developer untuk saling berkolaborasi dalam mengembangkan suatu aplikasi
- **Perintah**
-  git init . Perintah yang dapat kita gunakan untuk mengistal git di folder / directory kerja kita.
git config yaitu Perintah yang dapat kita gunakan untuk melakukan konfigurasi git dengan memberikan nama email yang akan kita gunakan baik pada local project maupun global project.
- git config --list : melihat configurasi git kita.
- git commit :Menyimpan perubahan secara permanen dari staging area pada repository
- git status: mengecek status dari git kita ,biasanya itu tentang file yang belum di add atau di commit, jika sudah aman maka messege yang keluar "hufhing to commite, working to tree clean"
- git add <nama_file> : menambahkan 1 file ke satgging area dan masih perlu commit.
- git add : menambahkan seluruh file yang belum di add ke stagging area dan masih perlu commit.
- git commit -m " pesan terserah yg ingin kita tulis" dan meng ACC mengcommit tentang penambahan checkpoint.
- git log : melihat history/kumpulan checkpoint (commit) yg telah kita buat.
- git revert <nomor_commit> : kembali ke checkpoint tanpa menghapus commitan sesudahnya.
- git branch: melihat kumpulan branch.
- git branch <nama_branch yg diinginkan> :membuat branch baru.
- git checkout <nama_branch> :  pindah ke branch yang kita inginkan.
- git checkout -b <nama_branch> :membuat branch baru dan langsung pindah ke branch yang baru kita buat.
- git checkout -d <nama_branch> :menghapus branch
- git merge <nama_target branch yg ingin kita tarik> :menggabungkan kedua buah branch.
- git remote -v : untuk melihat berhasil atau tidak antara Git & Github.
-Ctrl+Shift+Insert : paste dari hasil copy.
 
3. **HTML**
- HTML adalah sebuah bahasa yang kita gunakan untuk :Membuat kerangka suatu website, selain itu HTML digunakan untuk menampilkan konten pada browser. Contoh konten yang dapat ditampilkan seperti Text, Image, Video, Link, dan masih banyak lainnya.
- HTML bukanlah sebuah bahasa pemrograman, artinya HTML tidak bisa dinamis mengolah data.
- Ada 2 tools utama yang harus dipersiapkan untuk membuat HTML
1. Browser
2. Code Editor
- **Tag Komentar**
<!-- Area Content -->

**Heading**
```<h1></h1> - <h6></h6>```

**Paragraph** ```<p></p>```

**Hyperlink** : dimana kita gunakan ketika kita ingin memanggil CSS ke dalam HTML
```<a href=""></a>```

**Atribut / Properties HTML**
- id
- class
- name

**Table tag**

```<table border="1">```

    <thead>
        <tr>
            <td>No</td>
            <td>Nama</td>
            <td>Jenis Kelamin</td>
            <td>Golongan Darah</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Linda Rahayu</td>
            <td>perempuan</td>
            <td>O</td>
        </tr>
    </tbody>
```</table>```

**Form Tag**
 
```<form>```


    <input type="text"/>
    <input type="number"/>
    <input type="password"/>
    <input type="file"/>
    <input type="email"/>

    <select>


        <option value="">Pilih Kota</option>
        <option value="bandung">Bandung</option>
        <option value="sumbawa">Sumbawa</option>
        <option value="jakarta">Jakarta</option>
    </select>
    
    <textarea></textarea>

    <button type="submit">Klik Saya</button>
```</form>```

4. **CSS**
- CSS adalah bahasa komputer yang digunakan untuk menambahkan design ke suatu halaman website di internet.
- Fungsi CSS adalah sebagai 'baju' atau 'dekorator' dari sebuah website.
- Bagaimana CSS Bekerja di Web Browser?
Web browser seperti Chrome, Firefox, Edge, Safari, atau Opera akan membaca dokumen HTML. Dokumen HTML yang berisi tag-tag HTML akan memberitahu browser bagaimana cara menampilkan sebuah konten.
- Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya.
- **Terdapat 3 cara untuk menggunakan CSS**
1. Inline Styles: ketika kita akan menambahkan CSS ke atribut element HTML / menggunakan attribute style untuk menyisipkan kode CSS langsung di dalam HTML element. The ```<style></style>``` Tag

2. Internal CSS, yaitu menggunakan element ```<style>``` untuk menyisipkan kode CSS. Element ```<style>``` tersebut diletakkan di dalam element .

3. External CSS, yaitu sebuah file CSS terpisah yang disambungkan dengan file HTML dengan menggunakan element ```<link>```.

-.CSS Files: ketika kita membutuhkan banyak code pada CSS maka kita perlu memisahkan code CSS di file sendiri contoh (index.css) terpisah dari file HTML. kemudian access file .css in HTML.
- **mendesain element HTML di CSS**
-CSS Tag-Name:
jika menggunakan Tag Name , dia akan merubah secara keseluruhan /Global jadi semua h1 berubah jadi warna merah.

**FLEXBOX**
-Flexbox yaitu suatu cara untuk mengatur layout.
- Ada dua istilah penting saat belajar flexbox:
1. container adalah element yang membungkus dan mengatur tampilan dari element di dalamnya,
2. item adalah element dalam container yang diatur tampilannya.

 **salah satu dari property flexbox**: -justify-content dengan space-between.

 <head>
	<style>
		#flex-container {
			display: flex;
			flex-direction:row;
		}
		.flex-item {
			flex-basis: 100%;
			height: 100px;
			margin: 4px;
			background: #ec5453;
			font-size: 60px;
			color: white;
			text-align: center;
		}
	</style>
</head>

<body>
	<div id="flex-container">
		<div class="flex-item">1</div>
		<div class="flex-item">2</div>
		<div class="flex-item">3</div>
    <!-- jika ingin menambah flexbox lagi maka tinggal di tambah angka selanjutnya-->
    <div class="flex-item">4</div>
    <div class="flex-item">5</div>
	
  </div>
</body>

5. **Algorithma & Pseudocode**
- apa yang dimaksud dengan Algorithma? nah algorithma yaitu deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah
-kenapa harus belajar algorithma? karena Memudahkan kita dalam proses menyelesaikan permasalahan melalui bahasa pemrograman dan membuat program yang kita buat menjadi lebih efisien.
-Tujuan membuat algoritma adalah sebagai sarana dalam mengasah kemampuan dalam menganalisa.
- Apa itu Pseudocode : Pseudocode adalah menuliskan algoritma dengan umumnya bahasa inggris sebelum kita implementasikan ke bahasa pemograman tertentu.

**contoh pseudocode**

BEGIN 
SET name = "Linda"
DISPLAY = " Linda Rahayu Ningsih"
END
*/maka yang di tampilan dari pseudocode yaitu "Linda Rahayu Ningsih"/*

**terdapat beberapa Algorithma**

1. Procedural 
adalah cara berpikir secara runtun. Artinya serangkaian perintah yang berurutan
2. Conditional 
yaitu digunakan saat dibutuhkan percabangan kasus. Komputer akan melakukan suatu tindakan jika suatu kondisi terpenuhi. 
- ex: Jika hari ini tidak kerja, maka saya tetap di rumah, jika tidak maka saya pergi ke kantor.
Jika tidak terpenuhi, maka tidak akan dijalankan.
3. Looping
- ketika kita membutuhkan perulangan dalam kasus tertentu, kita bisa menggunakan Looping.
4. Recursive
- Recursive adalah pola pikir dalam algoritma yang memanggil method/function didalam sebuah function.

**TERIMAKASIH**




