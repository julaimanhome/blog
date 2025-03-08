---
layout: post
title:  "Bingung buat contact form? Berikut ini cara buat contact form blogger secara gratis"
author: sal
categories: [ Tips ]
tags: [blogger ]
image: assets/images/contactformblog.png
---
Rasanya kurang lengkap jika didalam susunan blog tidak terdapat laman contact form. Beberapa pengunjung blog biasanya sering mengulik isi konten yang terdapat dalam blog yang kita buat seperti hal nya halaman contact.

Dengan adanya halaman contact us, pengunjung dapat mengirimkan pesan kepada pemilik blog. Biasanya seseorang menginginkan kepentingan lebih lanjut seperti misalnya mengajak bekerjasama terkait periklanan, menanyakan perihal karir, memberikan saran/kritik dan lain-lain.

Maka dari itu, sangat penting sekali membuat halaman contact us pada blog. Dengan halaman contact form akan memudahkan pengunjung menghubungi secara langsung serta memungkinkan pemilik blog mendapatkan peluang bisnis yang lebih besar. Melengkapi blog dengan halaman contact form juga dapat menambah profesionalitas blog dan kepercayaan pengunjung.

Jika anda pengguna blogger, anda dapat membuat halaman contact form blogger ini dengan cara yang mudah. Adapun yang pertama yaitu.

### Cara buat contact form blog dengan form bawaan blogger

Dengan menggunakan form default blogger, ini dapat dilakukan dengan menampilkanya pada halaman tersendiri. Pertama-tama., silahkan salin kode berikut ini.

```html
<div class="contact-form-container">
    <form name="contact-form">
        Nama
        <div class="col-75">
            <input class="contact-form-name" id="ContactForm1_contact-form-name" name="name" type="text" value="" />
        </div>
        Alamat Email
        <div class="col-75">
            <input class="contact-form-name" id="ContactForm1_contact-form-email" name="email" type="text" value="" />
        </div>
        Isi Pesan
        <div class="col-75">
            <textarea class="contact-form-email-message" id="ContactForm1_contact-form-email-message" name="email-message" rows="10"></textarea>
        </div>
        <div class="row" style="float: left;">
            <input class="contact-form-button contact-form-button-submit" id="ContactForm1_contact-form-submit" type="button" value="Kirim" />
        </div>
    </form>
</div>
<script src="https://www.blogger.com/static/v1/widgets/2271878333-widgets.js"></script>
```
- Salin kode diatas lalu buka dasbor blogger, pergi ke Halaman > Buat Halaman Baru.
- Silahkan ubah ke Tampilan HTML agar kode dapat diterapkan
- Buat judul halaman, misalnya 'Contact Us' lalu untuk bagian isinya silahklan Paste atau tempel kode yang telah disalin tadi.
- Lalu disebelah kanan ada pilihan 'Opsi' kemudian pilih **'Jangan Izinkan, Sembunyikan yang ada'** dengan begitu halaman contact anda tidak akan menampilkan kolom komentar.
- Klik Publikasikan

Okey, tahap pertama sudah selesai. Agar contact form dapat berfungsi, kita harus menambahkan 'Gadget Formulir Kontak' pada menu Tata Letak blogger, Caranya :

- Buka dasbor blogger.
- Klik Tata Letak.
- Tambahkan Gadget.
- Pilih Formulir Kontak lalu klik Simpan.

Agar lebih keren, kita perlu menyeting laman contact form agar posisinya tampil cukup dihalaman yang kita buat, yaitu dengan hidden formulir kontak yang telah kita tambahkan tadi, nah silahkan copy kode berikut

```css
#ContactForm1 {
    display: none !important;
}
```
- Masuk ke dasbor blogger > Tema > Edit Tema
- Silahkan cari kode ]]></b:skin> pada tema blog anda, agar lebih cepat klik ctrl+f
- Paste-kan kode tersebut tepat diatas kode ]]></b:skin>
- Klik Simpan

Silahkan tes halaman contact yang telah dibuat dengan cara mengirimkan pesan sembarangan, untuk memastikan pesan masuk atau tidak.

### Cara buat contact form dengan Formspree.io

Jika mau yang lebih simpel dan keren, anda juga bisa membuat contact form blog menggunakan formspree.io. Situs ini menyediakan layanan contact form yang free. Jika tertarik anda cukup mengunjungi situsnya di https://formspree.io/
- Kunjungi situsnya lalu klik daftar.
- Daftar menggunakan email aktif anda dan masukan password baru. 
- Klik Register.
- Masukan kode verifikasi yang masuk ke email yang telah anda daftarkan.
- Kemudian Sign-in ke akun Formspree.io yang telah dibuat.
- Klik Add New > New Form.
- Isikan Form Name, buat saja misalnya 'Contact'
- Pada bagian project ketik saja misalnya First Projek.
- Untuk bagian **Send Emails To** isikan email anda yang aktif (email sama yang telah didaftarkan di formspree).
- Jika sudah silahkan copy kode HTML yang tersedia dibawah.
- Buka dasbor blogger, Lalu buat halaman baru dengan nama misalnya contact.
- Jangan lupa untuk ubah ke Mode HTML.
- Paste-kan kode yang telah di copy tadi.
- lalu klik publikasikan.

Seperti pada langkah diatas, test dulu halaman contact yang telah dibuat tadi apakah berhasil terkirim ke email atau tidak.

### Penutup

Membuat contact form blog sangatlah penting, karena ddengan adanya contact pengunjung dapat menghubungi kita. Dengan memahami cara membuat formulir kontak diatas semoga dapat memudahkan dan bermanfaat untuk blog yang anda miliki.

