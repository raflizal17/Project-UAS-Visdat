<h1 align="center">
  Pembangunan Dashboard Informasi Menggunakan <i>Library Flexdashboard R</i> (Studi Kasus: Profil Kemiskinan di Indonesia Tahun 2021)
</h1>

<h2>Ringkasan Penelitian</h2>
<h3>1. Latar Belakang </h3>
  <p align="justify"> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Penelitian ini didasarkan pada tujuan SDG's pertama yaitu pengentasan kemiskinan (<i>Zero Poverty</i>) yang diharapkan tercapai pada tahun 2030. Masalah kemiskinan merupakan salah satu persoalan mendasar yang bersifat kompleks dan multidimensional sehingga sering dijadikan pusat perhatian bagi pemerintah setiap negara termasuk Pemerintah Indonesia. Pemerintah Indonesia sendiri memiliki tujuan nasional yang diatur dalam UUD 1945 yaitu mewujudkan masyarakat adil dan makmur. Pemerintah dalam mewujudkan tujuan tersebut harus merencanakan dan merealisasikan program-program pembangunan nasional dalam rangka pengentasan kemiskinan di masyarakat Indonesia secara tepat dan akurat. Salah satu aspek penting untuk mendukung keakuratan dan ketepatan kebijakan dalam melaksanakan pembangunan sebagai strategi penanggulangan kemiskinan yakni tersedianya akses data dan informasi mengenai potret kemiskinan secara aktual. Oleh sebab itu, ketersediaan sarana penyajian informasi dan kemudahan dalam mengakses data perlu diperhatikan agar dapat membantu pemerintah dalam menetapkan kebijakan yang terarah dan berkelanjutan. Sarana penyajian informasi yang umum digunakan pada lingkup organisasi/pemerintah adalah dalam bentuk rupa <i>dashboard</i>. Saat ini, teknologi <i>dashboard</i> sudah sangat pesat dan beragam jenisnya. Dengan memperhatikan perkembangan teknologi yang semakin cepat serta pentingnya kebutuhan informasi mengenai kondisi kemiskinan di tengah masyarakat, maka pemanfaatan <i>dashboard</i> sebagai media penyajian data dan informasi ini perlu digalakkan dalam menunjang kegiatan pelaporan atau diseminasi hasil dari suatu penelitian, survei maupun kajian ilmu lain. Oleh karena itu, penelitian ini akan menghasilkan <i>output</i> suatu <i>dashboard</i> informasi yang menyajikan profil kemiskinan di Indonesia tahun 2021 dengan tampilan yang menarik, lengkap dan akurat, serta memberikan kemudahan kepada pengguna dalam memahami data yang disajikan dengan pemilihan visualisasi data yang tepat. Dengan demikian, hasil yang diperoleh diharapkan dapat memfasilitasi para <i>stakeholder</i> sebagai pengguna data dalam memahami informasi terkait potret kemiskinan yang terjadi di Indonesia tahun 2021 sebagai acuan dalam merancang dan menerapkan kebijakan pembangunan nasional dengan tepat dan berdaya guna kepada masyarakat. 
   </p>
  
<h3>2. Tujuan Penelitian</h3>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Penelitian ini memiliki dua tujuan yaitu: (1) membuat visualisasi dari hasil publikasi data yang dirilis oleh BPS terkait profil kemiskinan di Indonesia tahun 2021 dengan memanfaatkan berbagai library visualisasi data di R; (2) membangun <i>dashboard</i> informasi sebagai wadah penyajian data dan informasi mengenai profil kemiskinan di Indonesia tahun 2021 dengan menggunakan <i>Library Flexdashboard R</i> yang berbasis web responsif; dan (3) melakukan evaluasi terhadap dashboard informasi yang telah dibuat dengan menggunakan pengukuran <i>System User Scalabilty</i>(SUS)
  </p>
  
<h3>3. Metode Penelitian</h3>
  <h4> A. Studi Literatur </h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tahap awal penelitian ini adalah melakukan studi literatur dari penelitian lain yang berkenaan dengan pembangunan <i>dashboard</i> visualisasi data dan informasi menggunakan <i>Library Flexdashboard R</i>. Studi literatur penelitian ini diperoleh melalui jurnal dan artikel ilmiah yang membahas tentang teknik visualisasi data dan pembuatan <i>dashboard</i> informasi.
  </p>
  <h4> B. Pengumpulan Data </h4>
  <p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data yang akan digunakan merupakan indikator kemiskinan yang dirilis oleh BPS yang terdiri atas 5 variabel meliputi:
  <ol>
    <li>Variabel Jumlah Penduduk Miskin</li>
    <li>Variabel Persentase Penduduk Miskin</li>
    <li>Variabel Garis Kemiskinan</li>
    <li>Variabel Indeks Kedalaman Kemiskinan</li>
    <li>Variabel Indeks Keparahan Kemiskinan</li>
    <li>Variabel Indeks Gini (<i>Gini Ratio</i>)</li>
  </ol> 
Kelima variabel data yang dikumpulkan dari tahun 2011 hingga 2021, baik dalam lingkup nasional maupun lingkup provinsi. 
  </p>
  <h4> C. Pengolahan Data </h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pada proses pengolahan data dilakukan beberapa tahapan sebelum data divisualisasikan. Tahapan pengolahan data ini penting karena data-data yang telah dihimpun perlu disesuaikan dan diseleksi berdasarkan referensi waktu dan wilayah cakupan penelitian. Tahapan pengolahan data ini meliputi pembersihan data (<i>data cleaning</i>), identifikasi variabel, penyatuan data (<i>data integration</i>), perencanaan jenis visualisasi, dan konversi data (<i>data convertion</i>). Seluruh tahapan dalam pengolahan data dilakukan pada <i>Microsoft Office Excel</i> dan <i>R</i>.    
  </p>
  <h4> D. Visualisasi Data </h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pada tahapan ini, data yang sudah diolah akan dilakukan visualisasi sesuai dengan rencana jenis visualisasi yang telah ditetapkan sebelumnya. Alat atau tools dalam pembuatan visualisasi data ini menggunakan beberapa library visualisasi data di dalam koleksi modul R. Library tersebut antara lain <i>highcharter, DT, plotly, ggplot2, mapview,</i> dan lain-lain. Adapun dalam pemilihan warna dan tema grafik menggunakan library viridis untuk memberikan efek gradien warna pada chart visualisasi data tertentu yang memberikan penekanan atau maksud tertentu. Berikut ini rencana jenis visualisasi yang akan dibuat:
  <ul>
    <li>Visualisasi Teks Sederhana (<i>Simple Text</i>)</li>
    <li>Visualisasi <i>Bar Chart</i></li>
    <li>Visualisasi <i>Pie Chart</i>
    <li>Visualisasi <i>Line Chart</i></li>
    <li>Visualisasi Tabular (<i>Data Table</i>)</li>
    <li>Visualisasi Peta Tematik Interactive (<i>Interactive Choropleth Map</i>)</li>
  </ul>
  </p>
  
  <h4> E. <i>Design Dashboard</i></h4>
  <p><i>Design Dashboard</i> dibuat menggunakan aplikasi <i>Figma</i>. Berikut ini tampilan <i>design dashboard</i> tiap halaman</p>
  <ol>
  <li><h5><i>Design Dashboard</i> Halaman Utama (Lingkup Nasional)</h5></li>
  <img src="Images/Design_Dashboard_1.png"> </img>
  
  <li><h5><i>Design Dashboard</i> Halaman Kedua (Lingkup Provinsi)</h5></li>
  <img src="Images/Design_Dashboard_2.png"> </img>
  
  <li><h5><i>Design Dashboard</i> Halaman Pencarian</h5></li>
  <img src="Images/Design_Dashboard_3.png"> </img>
  
  <li><h5><i>Design Dashboard</i> Halaman Informasi</h5></li>
  <img src="Images/Design_Dashboard_4.png"> </img>
  </ol>

  <h4> F. Perancangan <i>Dashboard</i></h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dashboard yang efektif didesain dengan penuh cermat dan mempertimbangkan peran dari pengguna dalam pengambilan keputusan. Haryanti (2008) menjabarkan mengenai metodologi pembangunan dasbor terdiri atas 7 tahap, meliputi identifikasi kebutuhan, perencanaan, perancangan prototype, review prototype, implementasi, deployment, dan maintenance
</p>
  
  
  <h4> G. Evaluasi Sistem</h4>
  <h4> H. Penyusunan Laporan</h4>
    
    
    
    


