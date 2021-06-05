*previous repository: https://github.com/reinabil/MOODO-WEB-BISMILLAH -> broken :(
# Moodo Web
> Pelengkap Moodo-App "Jurnal for your daily mood"
    
## Laporan Akhir Projek
- KOM 331 | Rekayasa Perangkat Lunak | P1
- Kelompok 4

## Dibimbing oleh :
- Qory Khairunnisa
- Indah Puspita

## Tim Pengembang Moodo
<table>
    <thead>
        <tr>
            <th></th>
            <th>Nama</th>
            <th>Nim</th>
            <th>Role</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Hana Tasnim</td>
            <td>G64190018</td>
            <td>Front-end Developer</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Nabil Raihan Alfarizi</td>
            <td>G64190034</td>
            <td>Back-end Developer</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Renny Atikasari</td>
            <td>G64190040</td>
            <td>UI/UX Researcher</td>
        </tr>
                <tr>
            <td>4</td>
            <td>Dwayne Cameron S</td>
            <td>G64190085</td>
            <td>Quality Assurance</td>
        </tr>
    </tbody>
</table>

## Selayang Pandang

<img src="https://i.imgur.com/93M2Wzl.png" width="316" height="87.91" />

Moodo Web "Jurnal for your daily mood" adalah website yang berisikan fitur jurnal. Memungkinkan user untuk menulis jurnal harian sesuai mood dan terhubung dengan doa yang berkaitan sesuai mood yang dirasakan user. 
## Latar Belakang
Selain mengembangkan aplikasi yang berisikan doa/zikir harian, tim moodo juga mengembangkan moodo website yang memuat fitur jurnal harian.
Berdasarkan riset dari tim moodo, selain dengan berdoa, journaling juga merupakan salah satu kegiatan yang dapat membuat mood menjadi lebih baik. Harapan kami selaku tim pengembang, semoga dengan adanya website moodo, user mampu lebih mengekpresikan diri melalui jurnal. 

## Tujuan
- Memberikan ruang tulis kepada user untuk membuat jurnal harian
- Memberikan rekomendasi doa sesuai dengan jurnal yang ditulis user berdasarkan mood 

## Ruang Lingkup
### Minimum requirement
<table>
    <thead>
    </thead>
    <tbody>
        <tr>
            <td>Browser</td>
            <td colspan=3 style="text-align:center">Chrome, Edge, Firefox, or Safari</td>
        </tr>
        <tr>
            <td>Processor</td>
            <td colspan=3 style="text-align:center">32-bit or 64-bit processor</td>
        </tr>
        <tr>
            <td>Memory</td>
            <td colspan=3 style="text-align:center">1 GB or above</td>
        </tr>
        <tr>
            <td>Screen Resolution</td>
            <td colspan=3 style="text-align:center">480x800 or above</td>
        </tr>
        <tr>
            <td>Internet Access</td>
            <td colspan=3 style="text-align:center">Required</td>
        </tr>
    </tbody>
</table>

### Spesifikasi Teknis Pengembangan
<table>
    <thead>
    </thead>
    <tbody>
        <tr>
            <td>Software</td>
            <td colspan=3 style="text-align:center">VS Code, XAMPP</td>
        </tr>
        <tr>
            <td>Hardware</td>
            <td colspan=3 style="text-align:center">Intel i5-6200U @2.30 GHz ; 8 GB DDR4 RAM : NVIDIA GeForce 930M</td>
        </tr>
        <tr>
            <td>Tech Stack</td>
            <td colspan=3 style="text-align:center">Laravel, MySQL, and Apache server</td>
        </tr>
    </tbody>
</table>

## User Analysis
Target dari website moodo adalah semua kalangan yang ingin menuliskan jurnal harian. Ada banyak platform jurnal yang sudah umum digunakan, namun dalam website moodo, tim moodo mengembangkan sebuah fitur menulis jurnal yang berkaitan dengan mood  sehingga user mampu melihat record mood yang dirasakan selama menuliskan jurnal harian. Tidak lupa juga fitur pada moodo-web memungkinkan agar user dapat melihat doa yang terkait dengan jurnal yang ditulis. Doa dilengkapi dengan arab, latin, arti dan tentang doa. 

### User story
- Sebagai seorang insan, saya ingin menulis jurnal harian  untuk mendokumentasikan peristiwa/perasaan saya ke dalam tulisan
- Sebagai seorang muslim, saya ingin apa yang saya tulis tetap sesuai dengan syariat silam
- Sebagai seorang remaja, saya ingin jurnal yang saya tulis bisa disesuaikan dengan mood yang saya rasakan sehingga saya bisa melihat record jurnal harian yang pernah saya tulis sebelumnya

## Hasil dan Pembahasan

- ERD
    atau Entity Relationship Diagram adalah suatu bentuk diagram yang menjelaskan hubungan antar objek-objek data yang mempunyai hubungan antar relasi. Berikut adalah ilustrasi ERD pada perangkat lunak Moodo.

    <img src="https://trello-attachments.s3.amazonaws.com/60bb200eb6e68d6497665302/1188x892/252a7a5d4fd8c587a55352e1d21f3afe/Inkedchrome_qIh8AijRSt_LI.jpg" width="500" height="350" />

- Class Diagram
    berfungsi untuk menggambarkan struktur sebuah sistem pemrograman. Class diagram banyak memperhatikan hubungan antarkelas dan penjelasan detail tiap kelas dalam pemodelan desain (dalam logical view) dari suatu sistem. Berikut adalah ilustrasi Class Diagram pada perangkat lunak Moodo.

    <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb205755445348b444362c/dce1087ae693dcf706ddfc66870383fe/chrome_AJnnkPzU92.png" width="500" height="250" />

- Arsitektur Diagram
    Diagram arsitektur adalah bahasa gambar yang digunakan dalam bidang arsitektur untuk menerangkan konsep, prinsip, anasir, dan komponen, termasuk cara kerja maupun petunjuk penggunaannya. Berikut adalah ilustrasi arsitektur diagram pada perangkat lunak Moodo.
    
     <img src="https://i.imgur.com/lTV9FT1.png"/>
### Fungsi Utama 
1. Register & Log in
       
    Pada fitur Register & Log in, user dapat melakukan registrasi akun kemudian log in untuk dapat menulis jurnal pada moodo-web
    
    <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/c3cad91ec221ef5e4004a8920ca18ada/1._register.png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/1e35e9b8ea1559941f4e2316aa3e02b8/2._login.png" width="630" height="330" />

2. Home Page
        
    Pada home page, user dapat melihat ada dua fitur yang disediakan. Yaitu fitur jurnal dan doa. Fitur jurnal bisa digunakan user untuk melihat jurnal yang telah dibuat ataupun menuliskan jurnal, sedangkan fitur doa bisa diguakan user untuk melihat doa-doa yang dilengkapi dengan detail doa, seperti: arab, latin, arti dan tentang doa.
    
    <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/c52a3e5945124d5b5054d0c504d91e65/3._home.png" width="630" height="330" /> 

3. Catatan Harianmu
        
    Pada fitur catatan harianmu, user dapat menambahkan jurnal dengan menuliskan catatan harian pada fitur ini. Fitur catatan harianmu juga dilengkapi dengan view detail jurnal, sehingga user dapat melihat kembali jurnal yang pernah ditulis. Fitur ini juga memungkinka user untuk dapat memilih doa yang terkait dengan jurnal yang dibuat. 
    
    <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/18eb7e62aff76b15e483c38ebf74945d/6._tambah_jurnal.png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/c2ed08936c9510706c3808eb3833de50/4._detail_jurnal_(1).png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/66dcb204824d4e748eb0895852472ffc/4._detail_jurnal_(2).png" width="630" height="330" /> 

4. Setting profil
        
    Fitur setting profile difungsikan untuk user dapat mengatur profile secara up to date. Pada fitur ini, user dapat menautkan informasi profil (username, email user), update password, browser sessions, dan user juga bisa menghapus akunnya secara mandiri. 
    
    <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/d884c466f966f6e7cabff6757686640d/8._edit_profil_(1).png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/8ea2620bef569883b984d9952988aa01/8._edit_profil_(2).png" width="630" height="330" /> 

5. Detail Doa

    Fitur detail doa memuat doa-doa terkait mood, dilengkapi dengan tulisan arab, latin, arti, dan tentang doa. 

    <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/1978ac0160f5d0c4a9e547f97d652019/9._page_doa.png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/6b475ea2d4dd79aa5630edd9a5090cde/10._detail_doa.png" width="630" height="330" /> 


### Fungsi CRUD
CRUD adalah singkatan dari create, read, update, and delete yang merupakan fungsi-fungsi utama yang diimplementasikan dalam aplikasi database.

<table>
    <thead>
        <tr>
            <th></th>
            <th>CRUD</th>
            <th>Fungsi</th>
            <th>Fitur</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Create</td>
            <td>Menambahkan jurnal</td>
            <td>Catatan harianmu</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Read</td>
            <td>Membaca jurnal & Membaca doa</td>
            <td>Catatan harianmu & Detail doa</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Update</td>
            <td>Update jurnal & Update Profile</td>
            <td>Catatan harianmu & Profile</td>
        </tr>
                <tr>
            <td>4</td>
            <td>Delete</td>
            <td>Menghapus jurnal & Menghapus akun</td>
            <td>Catatan harianmu & Profile</td>
        </tr>
    </tbody>
</table>

#### Detail CRUD perangkat lunak moodo :
1. Create
        
    Fungsi CRUD yang pertama adalah create. Fungsi ini memungkinkan user membuat record baru dalam database.

    Pada perangkat lunak moodo-web, fitur catatan harianmu termasuk ke dalam fungsi create dikarenakan user dapat menuliskan jurnal pada page catatan harianmu. 

2. Read
        
    Fungsi read hampir mirip dengan fungsi search. Fungsi ini memungkinkan user untuk mencari dan mengambil data tertentu dalam tabel dan membaca nilainya.
    
    Pada perangkat lunak moodo-web, fitur catatan harianmu dan daftar doa termasuk ke dalam fungsi read dikarenakan user bisa membaca kembali jurnal harian yang telah ditulis pada fitur catatan harianmu. User juga bisa membaca doa-doa yang tersedia pada pada page daftar doa.

3. Update
        
    Fungsi update digunakan untuk memodifikasi record yang telah tersimpan di database.

    Pada perangkat lunak moodo-web, fitur catatan harianmu dan profile termasuk ke dalam fungsi update dikarenakan user dapat melakukan editing terhadap jurnal yang sudah ditulis sebelumnya. User juga dapat meng-update profile secara mendiri.

4. Delete

    Ketika ada record atau data yang tidak lagi dibutuhkan dalam database, fungsi CRUD yang digunakan adalah fungsi delete. Fungsi ini dapat digunakan untuk menghapus data tersebut.

    Pada perangkat lunak moodo-web, fitur catatan harianmu dan profile termasuk ke dalam fungsi delete dikarenakan user dapat menghapus jurnal yang telah ditulis. User juga dapat menghapus akun moodo-web apabila sudah tidak diperlukan.

## Hasil Implementasi
Dilampirkan screenshot hasil pengembangan perangkat lunak moodo-web

<img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/c3cad91ec221ef5e4004a8920ca18ada/1._register.png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/1e35e9b8ea1559941f4e2316aa3e02b8/2._login.png" width="630" height="330" />   <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/c52a3e5945124d5b5054d0c504d91e65/3._home.png" width="630" height="330" />  <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/18eb7e62aff76b15e483c38ebf74945d/6._tambah_jurnal.png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/c2ed08936c9510706c3808eb3833de50/4._detail_jurnal_(1).png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/66dcb204824d4e748eb0895852472ffc/4._detail_jurnal_(2).png" width="630" height="330" /> 
 <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/d884c466f966f6e7cabff6757686640d/8._edit_profil_(1).png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/8ea2620bef569883b984d9952988aa01/8._edit_profil_(2).png" width="630" height="330" /> 
<img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/1978ac0160f5d0c4a9e547f97d652019/9._page_doa.png" width="630" height="330" /> <img src="https://trello-attachments.s3.amazonaws.com/6020b019834f9a761fda2244/60bb21ddfae3452ace097cb1/6b475ea2d4dd79aa5630edd9a5090cde/10._detail_doa.png" width="630" height="330" /> 

## Testing (Test Case)
<table>
    <thead>
        <tr>
            <th></th>
            <th>Test Case Name</th>
            <th>Action</th>
            <th>Expected Result</th>
            <th>Positive Test</th>
            <th>Negative Test</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Login: Sign up
</td>
            <td>Memasukkan email dan password dengan 9 karakter</td>
            <td>Akun berhasil dibuat dan dialihkan ke halaman index jurnal</td>
            <td>Akun berhasil dibuat. User dialihkan ke halaman index jurnal</td>
            <td style="text-align:center">-</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Login: Sign up
</td>
            <td>Memasukkan email dan password dengan 256 karakter</td>
            <td>Akun gagal dibuat</td>
            <td style="text-align:center">-</td>
            <td>Akun gagal dibuat. User diminta memasukkan password dengan batasan 255 karakter</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Login: Sign in
</td>
            <td>Memasukkan email dan password yang sudah terdaftar</td>
            <td>Akun berhasil login dan dialihkan ke halaman index jurnal</td>
            <td>Akun berhasil login. User dialihkan ke halaman index jurnal</td>
            <td style="text-align:center">-</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Login: Sign in
</td>
            <td>Memasukkan email/password yang salah atau belum terdaftar</td>
            <td>Akun gagal login</td>
            <td style="text-align:center">-</td>
            <td>Akun gagal login. User diminta memasukkan email/password yang benar atau terdaftar dan cocok</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Check that user can go to page create journal
</td>
            <td>Mengklik tombol 'tambah jurnal' pada halaman index jurnal</td>
            <td>User akan dialihkan ke halaman create jurnal</td>
            <td style="text-align:center">-</td>
            <td>User berhasil dialihkan ke halaman create jurnal</td>
        </tr>
         <tr>
            <td>6</td>
            <td>Check that user can add new journal

</td>
            <td>Mengisi semua kolom yang perlu diisi pada halaman create jurnal termasuk doa terkait</td>
            <td>User akan berhasil membuat jurnal baru</td>
            <td>User berhasil membuat jurnal baru</td>
           <td style="text-align:center">-</td>
        </tr>
         <tr>
            <td>7</td>
            <td>Check that user can add new journal

</td>
            <td>Mengisi semua kolom yang perlu diisi pada halaman create jurnal kecuali doa terkait</td>
            <td>User akan gagal membuat jurnal baru</td>
            <td style="text-align:center">-</td>
            <td>User gagal membuat jurnal. User diminta memasukkan doa terkait</td>
        </tr>
          <tr>
            <td>8</td>
            <td>Check that user can go to page edit journal

</td>
            <td>Menekan tombol 'edit' pada kartu jurnal yang sudah dibuat</td>
            <td>User akan dialihkan ke halaman edit jurnal</td>
            <td>User berhasil dialihkan ke halaman edit jurnal</td>
            <td style="text-align:center">-</td>
        </tr>
         <tr>
            <td>9</td>
            <td>Check that user can edit journal


</td>
            <td>Mengisi semua kolom yang perlu diisi pada halaman edit jurnal termasuk doa terkait</td>
            <td>User akan berhasil memperbaharui jurnal</td>
            <td>User berhasil memperbaharui jurnal</td>
            <td style="text-align:center">-</td>
        </tr>
          <tr>
            <td>10</td>
            <td>Check that user can edit journal


</td>
            <td>Mengisi semua kolom yang perlu diisi pada halaman edit jurnal kecuali doa terkait</td>
            <td>User akan gagal memperbaharui jurnal</td>
            <td style="text-align:center">-</td>
            <td>User gagal memperbaharui jurnal. User diminta memasukkan doa terkait</td>
        </tr>
         <tr>
            <td>11</td>
            <td>Check that user can see the journal


</td>
            <td>Menekan tombol 'detail' pada kartu jurnal yang sudah dibuat</td>
            <td>User akan dialihkan ke halaman detail jurnal</td>
            <td>User berhasil dialihkan ke halaman detail jurnal.</td>
            <td style="text-align:center">-</td>
        </tr>
        <tr>
            <td>12</td>
            <td>Check that user can delete journal


</td>
            <td>Menekan tombol 'delete' pada kartu jurnal yang sudah dibuat</td>
            <td>Kartu jurnal yang dipilih akan terhapus dari sistem dan database</td>
            <td>User berhasil menghapus jurnal dari sistem dan database</td>
            <td style="text-align:center">-</td>
        </tr>
        <tr>
            <td>13</td>
            <td>Check that user can go to page daftar doa


</td>
            <td>Menekan tombol 'daftar doa' pada navbar</td>
            <td>User akan dialihkan ke halaman daftar doa</td>
            <td>User berhasil dialihkan ke halaman daftar doa</td>
            <td style="text-align:center">-</td>
        </tr>
        <tr>
            <td>14</td>
            <td>Check that user can see detail doa


</td>
            <td>Menekan tombol 'detail' di samping judul doa pada halaman daftar doa</td>
            <td>User akan dialihkan ke halaman detail doa yang dipilih</td>
            <td>User berhasil dialihkan ke halaman detail doa yang dipilih</td>
            <td style="text-align:center">-</td>
        </tr>
        <tr>
            <td>15</td>
            <td>Check that user can go to page profil


</td>
            <td>Menekan tombol 'profil' pada navbar</td>
            <td>User akan dialihkan ke halaman profil</td>
            <td>User berhasil dialihkan ke halaman profil</td>
            <td style="text-align:center">-</td>
        </tr>
        <tr>
            <td>16</td>
            <td>Logout


</td>
            <td>Menekan tombol 'logout' pada navbar</td>
            <td>User akan dialihkan ke halaman login</td>
            <td>User berhasil dialihkan ke halaman login</td>
            <td style="text-align:center">-</td>
        </tr>
    </tbody>
</table>

## Projek Documentation 
- [Klik di sini untuk melihat dokumentasi github](http://ipb.link/moodo-github)
- [Klik di sini untuk melihat dokumentasi trello](http://ipb.link/moodo-trello)
- [Klik di sini untuk melihat dokumentasi Google-site](http://ipb.link/moodo-site)
- [Klik di sini untuk melihat dokumentasi Drive](http://ipb.link/moodo-drive)

## Saran untuk pengembangan selanjutnya




