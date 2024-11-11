<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tipe Kepribadian</title>

        <link rel="stylesheet" href="css/app.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap" rel="stylesheet">
        <script>
        function myFunction() {
            document.getElementById("myDropdown").classList.toggle("show");
          }
                    window.onclick = function(e) {
            if (!e.target.matches('.dropbtn')) {
            var myDropdown = document.getElementById("myDropdown");
                if (myDropdown.classList.contains('show')) {
                myDropdown.classList.remove('show');
                }
            }
            }
        </script>
    </head>
<body>

<header>
    <div class="jumbotron">
    <h1>Tipe Kepribadian</h1>
    <h3>Mengenal Pembagian 4 Karakter Kepribadian </h3>
    </div>
    <nav>
        <ul>
            <li><a href="#sejarah">Sejarah</a></li>
            <div class="dropdown">
                <button class="dropbtn" onclick="myFunction()">Tipe Kepribadian
                  <i class="fa fa-caret-down"></i>
                </button>
                <div class="dropdown-content" id="myDropdown">
            <li><a href="#sanguinis">Sanguinis</a></li>
            <li><a href="#plegmatis">Plegmatis</a></li>
            <li><a href="#koleris">Koleris</a></li>
            <li><a href="#melankolis">Melankolis</a></li>
            </div>
            </div>
        </ul>
    </nav>

</header>
<main>
    <div id="content">

        <article id="sejarah" class="card">
    <h2>Sejarah 4 Tipe Kepribadian</h2>

    <figure class="flex">
        <img src="picture/sejarah3.jpg" alt="sejarah tipe kepribadian" class="featured-image">
        <img src="picture/sejarah2.jpg" alt="sejarah tipe kepribadian" class="featured-image">
    </figure>

    <p>Asal muasal pembagian kepribadian ini adalah pengobatan Yunani-Arab, yang dulu sangat 
        populer digunakan untuk mengobati berbagai macam penyakit. Faktanya, pengobatan Yunani- 
        Arab ini masih digunakan di berbagai belahan dunia oleh praktisi-praktisi pengobatan 
        alternative. Inti dari teori 4 kepribadian adalah konsep kedokteran kuno, humorisme. Humor 
        dalam konteks ini bukanlah lawak atau banyolan. Humor ini berarti cairan tubuh yang mengalir 
        di badan seseorang. Ada 4 jenis cairan yang mengalir dalam tubuh. Setiap orang memiliki proporsi jenis cairan tubuh 
        yang berbeda dari yang lain. Cairan tubuh yang dominan pada diri seseorang menentukan tipe 
        kepribadian dan psikologis dirinya.</p>
     <p>Teori ini mengungkapkan bahwa dominasi satu jenis humor sangat menentukan penampilan dan 
        kebiasaan seseorang. Namun, sebagian besar orang memiliki kepribadian campuran. Terlebih 
        lagi sulit untuk menilai jenis kepribadian seseorang hanya dari penampilannya, apalagi bagi 
        orang awam seperti kita. Kedokteran modern menolak pembagian tipe kepribadian ini. Namun banyak teori kepribadian 
        yang baru dikembangkan dari konsep kuno ini, hanya saja menggunakan istilah yang berbeda. 
        Misalnya saja tipe kepribadian yang dikembangkan oleh Dr. Helen Fisher. Ia membagi 
        kepribadian menjadi Penjelajah (<i>Explorer</i>), Negosiator (<i>Negotiator</i>), Pengarah (<i>Director</i>), dan 
        Pembangun (<i>Builder</i>). Pembagian ini menyerupai Sanguinis, Plegmatis, Koleris, dan Melankolis 
        secara berurutan. Walau mirip, bukan berarti penelitian Dr. Fisher ini jadi sia-sia.</p>
        <p>Berikut ini kita akan membahas satu-persatu 4 tipe kepribadian ini, simak terus yuk!</p>
        </article>

        <article id="sanguinis" class="card">
    <h2>Sanguninis</h2>
            <figure class="flex">
                <img src="picture/sanguinis1.jpg" alt="sanguinis" class="featured-image">
                <img src="picture/sanguinis3.jpg" alt="sanguinis" class="featured-image">
            </figure>
        <p>Orang-orang berkepribadian sanguin cenderung tampak hidup, optimistis, emosi meluap-luap, 
            dan acuh tak acuh. Para sanguin sangat menyukai petualangan dan tahan terhadap risiko yang 
            tinggi. selain itu, mereka mudah sekali bosan dan akan aktif mencari variasi dan hiburan dalam keseharian mereka. </p>
        <p>Karena sikap inilah para sanguin cenderung mencari aktivitas yang tujuannya memberi 
            kesenangan. Banyak sanguin yang berjuang melawan kecanduan. Keinginan mereka yang besar 
            membuat para sanguine kebanyakan makan dan bermasalah dalam berat badan. 
            Orang-orang sanguin umumnya sangat kreatif dan bisa menjadi seniman yang hebat. Ditambah 
            lagi, sanguin ini penghibur yang hebat. Secara alamiah, para sanguin akan berhasil jika memilih 
            karier dalam industri <i>entertainment</i>.</p>
        <p>Kemampuan alami sanguin juga akan berfungsi maksimal jika mereka memilih pekerjaan yang 
            berhubungan dengan:
            <ul>
                <li><i>Marketing</i></li>
                <li><i>Traveling</i></li>
                <li><i>Fashion</i></li>
                <li>Memasak</li>
                <li>Olahraga</li>
            </ul>
            <p>Adapun kekuatan dan kelemahan yang dimiliki tipe kebribadian ini beberapa diantaranya adalah sebagai berikut:
                 </p>
                 <div class="flex-container">
                
                    <ul>
                        <p class="tambahan">Kekuatan</p>
                       <li>Suka bicara.</li>  
                       <li> Secara fisik memegang pendengar, emosional dan demonstratif. </li>
                       <li>Antusias dan ekspresif. </li>
                       <li>Ceria dan penuh rasa ingin tahu. </li>
                       <li> Hidup di masa sekarang. </li>
                       <li> Mudah berubah (banyak kegiatan / keinginan).</li>
                       <li>Senang dengan pujian dan ingin menjadi perhatian</li>
                       <li>Mudah berteman dan menyukai orang lain.</li> 
                       <li>Umumnya hebat di permukaan.</li>
                       <li> Berhati tulus dan kekanak-kanakan.</li>
                    </ul>
                
                 
                    <ul>
                        <p class="tambahan">kelemahan</p>
                        <li>Cenderung melihat masalah dari sisi negatif (murung dan tertekan)</li>
                        <li>Mengingat yang negatif & pendendam. </li>
                        <li>Mudah merasa bersalah dan memiliki citra diri rendah.</li>
                        <li>Lebih menekankan pada cara daripada tercapainya tujuan. </li>
                        <li>Tertekan pada situasi yg tidak sempurna dan berubah-ubah.</li>
                        <li>Melewatkan banyak waktu untuk menganalisa dan merencanakan.</li>
                        <li>Standar yang terlalu tinggi sehingga sulit disenangkan.</li>
                        <li>Tukang kritik, tetapi sensitif terhadap kritik/ yg menentang dirinya.</li>
                    </ul>
            
                </div>
        </article>

        <article id="plegmatis" class="card">
    <h2>Plegmatis</h2>
            <figure class="flex">
                <img src="picture/plegmatis1.jpg" alt="plegmatis" class="featured-image">
                <img src="picture/plegmatis2.jpg" alt="plegmatis" class="featured-image">
            </figure>
        <p>Karakter manusia yang satu ini disimbolkan dari lendir (<i>phlegm</i>) 
           dan bagian tubuh kedua, yaitu jiwa. Orang tipe plegmatis lebih fokus pada apa yang terjadi dalam dirinya.
           Umumnya orang-orang berkepribadian plegmatis ini orientasinya fokus pada manusia. Para 
           plegmatis mencari keharmonisan interpersonal dan hubungan yang erat. Para plegmatis ini 
           umumnya menjadi pasangan yang setia dan orang tua yang penyayang. Orang-orang plegmatis 
           memprioritaskan hubungannya dengan teman lama, anggota keluarga, dan tetangga.</p>
        <p> Orang-orang berkepribadian plegmatis, cenderung menghindari konflik dan selalu berusaha menjadi perantara 2 
            orang yang bertengkar untuk menjadi akrab kembali. Para plegmatis sangat senang 
            menghabiskan waktunya untuk kegiatan amal dan membantu orang lain. Karier ideal untuk tipe 
            kepribadian plegmatis sebaiknya berhubungan dengan:  </p>
        <ul>
            <li>Merawat Orang, Hewan, atau Tanaman</li>
            <li>Mengajar</li>
            <li>Psikologi atau Konseling</li>
            <li>Perkembangan Anak</li>
            <li>Pelayanan Sosial</li>
        </ul>   
       
        <p>Adapun kekuatan dan kelemahan yang dimiliki tipe kebribadian ini beberapa diantaranya adalah sebagai berikut:
        </p>

        <div class="flex-container">
            <ul>
                <p class="tambahan">Kekuatan: </p>
                <li>Mudah bergaul, santai, tenang dan teguh. </li>
                <li>Sabar, seimbang, dan pendengar yang baik.</li>
                <li>Tidak banyak bicara, tetapi cenderung bijaksana. </li>
                <li>Penengah masalah yg baik.</li>
                <li>Menyenangkan dan tidak suka menyinggung perasaan.</li>
                <li>Senang melihat dan mengawasi.</li>
                <li>Mudah diajak rukun dan damai.</li>    
            </ul>
       
        
            <ul>
                <p class="tambahan">Kelemahan: </p>
                <li>Kurang antusias, terutama terhadap perubahan/ kegiatan baru.</li>
                <li>Menghindari konflik dan tanggung jawab.</li>
                <li>Keras kepala, sulit kompromi (karena merasa benar).</li>
                <li>Terlalu pemalu dan pendiam. </li>
                <li>Menunda-nunda / menggantungkan masalah. </li>
                <li>Sulit bergerak dan kurang memotivasi diri.</li>
                <li>Lebih suka sebagai penonton daripada terlibat. </li>
            </ul>
        </div>
       
        </article>

        <article id="koleris" class="card">
    <h2>Koleris</h2>
            <figure class="flex">
                <img src="picture/koleris1.jpg" alt="koleris" class="featured-image">
                <img src="picture/koleris2.jpg" alt="koleris" class="featured-image">
            </figure>
    <p>Orang dengan kepribadian koleris murni umumnya berfokus pada tujuan. Para koleris umumnya 
        sangat cerdas, analitis, dan logis. Dalam hubungan sosial, koleris umumnya berpikir praktis dan 
        sangat blak-blakan. Itulah sebabnya para koleris terkadang sulit menjadi teman yang baik dan sulit bersosialisasi. 
        Para koleris lebih memilih sendirian dan kesepian daripada ditemani orang-orang yang 
        pikirannya dangkal. Para koleris sangat menyukai menghabiskan waktu bersama orang-orang 
        dengan minat profesional yang serupa.</p>
    <p>Para korelis merupakan pemikir yang kuat, mereka lebih suka menghabiskan waktu mereka untuk berfikir
        dan tenggelam dalam fikiran mereka sendiri, mereka juga terkadang menyukai hal yang abstrak dan memiliki intuisi yang tajam.
        Oleh karena itu, pekerjaan ideal untuk tipe kepribadian koleris ada pada bidang-bidang berikut ini: </p>
        <ul>
            <li>Manajemen</li>
            <li>Pemrograman</li>
            <li>Teknologi</li>
            <li>Bisnis</li>
            <li>Stasitik</li>
            <li>Fisikawan, Kimiawan</li>
        </ul>
   
    <p>Adapun kekuatan dan kelemahan yang dimiliki tipe kebribadian ini beberapa diantaranya adalah sebagai berikut:
    </p>
  
    <div class="flex-container">
        <ul>
            <p class="tambahan">Kekuatan: </p>

            <li>Senang memimpin, membuat keputusan, dinamis dan aktif.</li>
            <li>Sangat memerlukan perubahan dan harus mengoreksi kesalahan. </li>
            <li>Berkemauan keras dan pasti untuk mencapai sasaran/ target.</li>
            <li>Berani menghadapi tantangan dan masalah.</li>
            <li>Mencari pemecahan praktis dan bergerak cepat.</li>
            <li>Tidak begitu perlu teman.</li>
            <li>Bebas dan mandiri. </li>
            
        </ul>
   
   
        <ul>
            <p class="tambahan">Kelemahan: </p>
            <li>Tidak sabar dan cepat marah (kasar dan tidak taktis).</li>
            <li>Tidak menyukai air mata dan emosi tidak simpatik. </li>
            <li>Amat sulit mengaku salah dan meminta maaf.</li>
            <li>Memanipulasi dan menuntut orang lain, cenderung memperalat orang lain. </li>
            <li>Tidak suka yang sepele dan bertele-tele / terlalu rinci.</li>
        </ul>
    </div>
        </article>

        <article id="melankolis" class="card">
    <h2>Melankolis</h2>
                <figure class="flex">
                    <img src="picture/melankolis1.jpg" alt="melankolis" class="featured-image">
                    <img src="picture/melankolis2.jpg" alt="melankolis" class="featured-image">
                </figure>
    <p>Orang-orang berkepribadian melankolis sangat menyukai tradisi. Wanita memasak untuk 
        suaminya. Laki-laki membukakan pintu untuk wanita. Para melankolis umumnya sangat 
        mencintai keluarga dan teman dekatnya. Tidak seperti sanguin, para melankolis tidak mencari 
        kesenangan yang baru dan petualangan. Bahkan seringkali para melankolis menghindarinya.Orang dengan kepribadian melankolis umumnya enggan menikahi orang asing atau 
        meninggalkan tanah airnya. Orang melankolis sangat sosial dan ingin berkontribusi ke 
        komunitasnya. Para melankolis sangat menyukai aturan dan keakuratan. Para melankolis 
        umumnya manajer yang baik. </p>
    <p>Karier ideal untuk kepribadian melankolis adalah dalam bidang:</p>
        <ul>
            <li>Manajemen</li>
            <li>Akuntansi</li>
            <li>Administrasi</li>
            <li>Pekerjaaan Sosial</li>
        </ul>
    
    <p>Adapun kekuatan dan kelemahan yang dimiliki tipe kebribadian ini beberapa diantaranya adalah sebagai berikut:
    </p>
    <div class="flex-container">

        <ul>
            <p class="tambahan">Kekuatan: </p>
            <li>Analitis, mendalam, dan penuh pikiran.</li>
            <li>Serius dan bertujuan, serta berorientasi jadwal. </li>
            <li>Artistik, musikal dan kreatif (filsafat & puitis). </li>
            <li>Melihat masalah dan mencari solusi pemecahan kreatif (sering terlalu kreatif).</li>
            <li>Hemat</li>
            <li>Berteman dengan hati-hati.</li>
            <li>Sangat memperhatikan orang lain.</li>
            <li>Puas di belakang layar, menghindari perhatian.</li>
        </ul>
   
  
        <ul>
            <p class="tambahan">Kelemahan: </p>
            <li>Cenderung melihat masalah dari sisi negatif (murung dan tertekan).</li>
            <li>Mudah merasa bersalah dan memiliki citra diri rendah.</li>
            <li>Lebih menekankan pada cara daripada tercapainya tujuan. </li>
            <li>Melewatkan banyak waktu untuk menganalisa dan merencanakan. </li>
            <li>Tukang kritik, tetapi sensitif terhadap kritik/ yg menentang dirinya. </li>
            <li>Standar yang terlalu tinggi sehingga sulit disenangkan.</li>
        </ul>
    </div>
        </article>

    </div>
    <aside>
        <article class="profile">
            <header>
                <h2>Persentase Tipe Kepribadian</h2>
                <figure>
                    <img src="picture/aside2.png"/>
                </figure>
            </header>

            <section>
                <h3>Persentase rata-rata jumlah kepribadian di dunia:</h3>
                <table>
                    <tr>
                        <th>Sanguinis</th>
                        <td><b>33,5%</b></td>
                    </tr>
                    <tr>
                        <th>Plegmatis</th>
                        <td><b>25%</b></td>
                    </tr>
                    <tr>
                        <th>Koleris</th>
                        <td><b>26,5%</b></td>
                    </tr>
                    <tr>
                        <th>Melankolis</th>
                        <td><b>19%</b></td>
                    </tr>
                </table>

            </section>
        </article>
    </aside>
</main>
<footer>
    <p>&star; Mengenal 4 Tipe Kepribadian &star;</p>
</footer>
</body>
</html>
