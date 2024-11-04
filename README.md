# Lab5Web
<h1>Membuat Dokumen HTML dengan nama file</h1>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Mengenal JavaScript</title>
    </head>
    <body>
        <h1>Pengenalan JavaScript</h1>
        <h3>Contoh dokument.write dan console.log</h3>
        <script>
            document.write("Hello Word");
            console.log("Hello Word");
        </script>    
    </body>
    </html>

![image](https://github.com/user-attachments/assets/b09563ec-b6e8-46b9-954f-bde49b976873)


Kode JavaScript ini menggunakan `document.write` untuk menampilkan "Hello World" langsung di halaman web, sementara `console.log` mencetak teks tersebut di konsol browser. `document.write` berguna untuk menampilkan konten di halaman, sedangkan `console.log` bermanfaat untuk debugging tanpa memengaruhi tampilan halaman.
<br> <hr>

<h2>2. Pemakaian Alert sebagai property window.</h2>

    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>alert box</title>
     </head>
     <body>
         <script language = "Javascript">
             window.alert("ini merupakan pesan untuk anda");
         </script>
     </body>
     </html>

![image](https://github.com/user-attachments/assets/f5404db1-507a-478c-8309-b5cd61c39362)


Kode JavaScript ini memakai `window.alert` untuk menampilkan kotak pesan (alert box) yang berisi teks "ini merupakan pesan untuk anda" begitu halaman dimuat. Pengguna harus menutup kotak pesan ini agar dapat melanjutkan interaksi dengan halaman.
<br> <hr>

3. <h2>Pemakaian method dalam objek</h2>

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Skrip JavaScript</title>
        </head>
        <body>
            percobaan memakai JavaScript:<br>
            <script language = "javascript">
                document.write("Selamat mencoba Javascript<br>");
                document.write("Semoga sukses!");
            </script>
            
        </body>
        </html>

![image](https://github.com/user-attachments/assets/75f7dd27-64c1-4aaa-b880-d2cae56f2b98)

Kode JavaScript ini menampilkan teks "selamat mencoba javascript" diikuti dengan pindah baris (`<br>`), lalu menampilkan "semoga sukses!" di halaman web. `document.write` digunakan untuk langsung menuliskan teks ke halaman saat kode dijalankan.
<br> <hr>

<h2>Pemakaian Prompt</h2>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Pemasukan data</title>
    </head>
    <script language = "javascript">
        var nama = prompt("Siapa nama anda?","Masukkan nama anda");
        document.write("hai, "+ nama);
    </script>
    <body>
        
    </body>
    </html>

![image](https://github.com/user-attachments/assets/56103af1-bcbb-4f03-bd2f-603f46035e52)


Setelah perintah tadi lalu muncul seperti gambar diatas, lalu ketik "nama Ahmad Puat Kamal" lalu akan muncul seperti gambar dibawah ini
<br>

![image](https://github.com/user-attachments/assets/76f2a5cd-28fb-495c-9e3b-815813fc43f7)

nah "Ahmad Puat Kamal" akan muncul seperti yang diatas 
<hr> <br>

<h2>5. Pembuatan fungsi dan cara pemanggilannya</h2>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Contoh program javascript </title>
        <script language = "javascript">
            function pesan(){
                alert("Memanggil javascript lewat body onload")
            }
        </script>
    </head>
    <body onload=pesan()>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/f27d4176-cf69-4f22-a489-83ede0d396e4)


Kode ini memunculkan kotak pesan (alert box) dengan teks "memanggil javascript lewat body onload" ketika halaman selesai dimuat. Atribut `onload="pesan()"` di dalam tag `<body>` secara otomatis memanggil fungsi `pesan()` saat halaman selesai dimuat, sehingga pesan ditampilkan sebagai pop-up.
<hr> <br>

<h2>6. Dasar Pemrograman Di Javascript</h2>
<h3>Operasi Dasar Aritmatika</h3>

    <html>
    <head>
        <title>contoh program javascript</title>
        <script language="javascript">
            function test (val1, val2)
            {
                document.write("<br>"+"perkalian : val1*val2"+"<br>")
                document.write(val1*val2)
                document.write("<br>"+"pembagian : val1/val2 "+"<br>")
                document.write(val1/val2)
                document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
                document.write(val1+val2)
                document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
                document.write(val1-val2)
                document.write("<br>"+"mmodulus : val1%val2 "+"<br>")
                ocument.write(val1%val2)
            }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/5dcd7833-0e58-4eff-a7be-e215875fd3f0)
![image](https://github.com/user-attachments/assets/990af973-4a1f-496a-ab35-1b0a0fc4d368)

Kode ini mendefinisikan fungsi `test(val1, val2)` yang menjalankan operasi aritmatika (perkalian, pembagian, penjumlahan, pengurangan, dan modulus) pada dua angka yang diberikan. Ketika tombol "arithmetic" diklik, fungsi dipanggil dengan nilai 9 dan 4. Hasil dari setiap operasi ditampilkan di halaman melalui `document.write`, menghasilkan output berikut:

Perkalian: 36  
Pembagian: 2.25  
Penjumlahan: 13  
Pengurangan: 5  
Modulus: 1
<hr> <br>

<h2>7. Seleksi kondisi (if..else)</h2>

    <html>
    <head>
        <title>contoh if-else</title>
        <script language="javascript">
            var nilai = prompt("nilai (0-100): ", 0);
            var hasil = " ";
            if (nilai >= 60)
            hasil = "lulus";
            else
            hasil = "tidak lulus";
            document.write("hasil: " + hasil);
        </script>
    </head>
    <body>
    </html>

![image](https://github.com/user-attachments/assets/d5fa97ff-995d-4894-8564-da79180a5d0a)

setelah mengikuti perintah tersebut akan muncul gambar seperti ini, lalu saya akan mengisi dengan angka 75

![image](https://github.com/user-attachments/assets/fcbc55d5-45bc-4d27-b70e-1b4db8571473)

dan hasilnya lulus.
<br> <hr>

<h2>8. Penggunaan operator switch untuk seleksi kondisi</h2>
    
    <html>
    <head>
        <title>contoh if-else</title>
        <script language="javascript">
                function test() {
                    let val = window.prompt("Input nilai (1-5):")
                    switch (val) {
                        case "1":
                            document.write("Bilangan satu")
                            break
                        case "2":
                            document.write("Bilangan dua")
                            break
                        case "3":
                            document.write("Bilangan tiga")
                            break
                        case "4":
                            document.write("Bilangan empat")
                            break
                        case "5":
                            document.write("Bilangan lima")
                            break
                        default:
                            document.write("Bilangan lainnya")
               }
        }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="switch" onclick=test()>
    </body>
    </html>
    
![image](https://github.com/user-attachments/assets/37394524-27b9-47d6-9c3e-dbb352e1a2cd)

Ketika angka 4 dimasukkan sebagai output dari perintah tersebut, hasil yang ditampilkan adalah 

![image](https://github.com/user-attachments/assets/76500ec5-7319-40ab-bb2f-00cedf6292a5)

"bilangan 4"
<br> <hr>

<h2>9. Form Input</h2>

    <html>
    <head>
        <title>Contoh if-else</title>
        <script language="javascript">
        function test() {
            var val1 = document.kirim.T1.value; // Ganti 'ver' dengan 'var'
            if (val1 % 2 == 0)
                document.kirim.T2.value = "bilangan genap";
            else
                document.kirim.T2.value = "bilangan ganjil";
        }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="T1" size="20"> <!-- Ganti T2 dengan T1 -->
            MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
            <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p> <!-- Tambahkan tanda kutip -->
        </form>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/db45cd0a-4807-45a7-b358-bd583c1ce484)

Kode ini memeriksa apakah nilai yang dimasukkan pada kotak input pertama (T1) merupakan bilangan genap atau ganjil. Saat tombol "TEBAK" ditekan, hasilnya akan ditampilkan di kotak input kedua (T2) dengan keterangan "bilangan genap" atau "bilangan ganjil".
<br> <hr>

<h2>10. from button</h2>

    <html>
    <head>
        <title>objek document</title>
    </head>
    <body>
        <script language="javascript">
            function ubahWarnaLB(warna) {
                document.bgColor = warna;
            }
            function ubahWarnaLD(warna) {
                document.fgColor = warna;
            }
            </script>
            <h1>tes</h1>
            <form>
                <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
                <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
                <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
                <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
            </form>
            <script language = "javascript">
                document.write("Dimodifikasi terakhir pada " +
                document.lastModified);
            </script>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/6f9643f5-388b-43bc-91db-0ae92656222c)
![image](https://github.com/user-attachments/assets/b6aabbed-4344-4b31-b030-45b308157b77)
![image](https://github.com/user-attachments/assets/4299e66f-b70c-4ed8-84f1-17003606329c)
![image](https://github.com/user-attachments/assets/4d6c0493-f5fc-422e-a273-46691f9fb2ff)
![image](https://github.com/user-attachments/assets/33978714-6db4-4a96-a9b9-fa23a71f5da8)

Kode ini menyediakan tombol untuk mengganti warna latar belakang dan warna teks pada halaman. Fungsi `ubahWarnaLB` digunakan untuk mengubah warna latar belakang (bgColor), sedangkan fungsi `ubahWarnaLD` digunakan untuk mengubah warna teks (fgColor). Tombol yang tersedia memungkinkan pengguna untuk memilih warna latar belakang hijau atau putih serta warna teks kuning atau biru. Di bagian bawah halaman, `document.write` menampilkan informasi tentang terakhir kali halaman dimodifikasi menggunakan `document.lastModified`.
<br> <hr>

<h2>11. HTML DOM</h2>

    <!--
    File: daftar_menu.html
    -->
    <html>
    <head>
        <title>Daftar Menu</title>
        <script>
            function hitung(ele) {
                var total = document.getElementById('total').value;
                total = (total ? parseInt(total) : 0);
                var harga = 0;
    
                if (ele.checked) {
                    harga = ele.value;
                    total += parseInt(harga);
                } else {
                    harga = ele.value;
                    if (total > 0)
                        total -= parseInt(harga);
                }
    
                document.getElementById('total').value = total;
            }
        </script>
    </head>
    <body>
        <h1>Daftar Menu Makanan</h1>
        <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"> Ayam Goreng Rp. 5.000</label><br />
        <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"> Tempe Goreng Rp. 500</label><br />
        <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"> Telur Dadar Rp. 2.500</label><hr />
        <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/e49f976b-f3a5-455a-9dce-44e8a83653dd)

Kode ini menampilkan daftar menu makanan dengan checkbox untuk memilih item dan menghitung total harga. Fungsi `hitung` akan menambah atau mengurangi harga dari item yang dipilih atau dibatalkan, kemudian memperbarui nilai total di kotak input total. Setiap checkbox memiliki nilai harga sesuai dengan itemnya, dan saat dipilih, total harga akan diperbarui secara langsung di halaman.
<br> <hr>

<h1>Pertanyaan dan Tugas</h1>
<h2>1. Buat script untuk melakukan validasi pada isian form.</h2>
    
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Validasi Form</title>
        <script>
            function validateForm() {
                // Mengambil nilai dari input
                var name = document.forms["myForm"]["name"].value;
                var email = document.forms["myForm"]["email"].value;
                var phone = document.forms["myForm"]["phone"].value;

            // Validasi Nama
            if (name === "") {
                alert("Nama harus diisi.");
                return false;
            }

            // Validasi Email
            var emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/; // Regex untuk validasi email
            if (email === "") {
                alert("Email harus diisi.");
                return false;
            } else if (!emailPattern.test(email)) {
                alert("Email tidak valid.");
                return false;
            }

            // Validasi Nomor Telepon
            var phonePattern = /^[0-9]+$/; // Regex untuk validasi nomor telepon
            if (phone === "") {
                alert("Nomor telepon harus diisi.");
                return false;
            } else if (!phonePattern.test(phone)) {
                alert("Nomor telepon hanya boleh berupa angka.");
                return false;
            }

            // Jika semua validasi berhasil
            alert("Form berhasil dikirim!");
            return true; // Mengizinkan form untuk disubmit
        }
    </script>
    </head>
    <body>
        <h1>Formulir Pendaftaran Lomba Informatika 2024 </h1>
        <form name="myForm" onsubmit="return validateForm()">
            <label for="name">Nama:</label><br>
            <input type="text" name="name"><br><br>
            
        <label for="email">Email:</label><br>
        <input type="text" name="email"><br><br>
        
        <label for="phone">Nomor Telepon:</label><br>
        <input type="text" name="phone"><br><br>
        
        <input type="submit" value="Kirim">
    </form>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/6a05a47d-00f6-4dab-857f-ab8c0a9d628f)
![image](https://github.com/user-attachments/assets/0f960be3-4741-4610-8ed0-2ee6bec82b9e)

Fungsi validateForm(): Fungsi ini dijalankan saat form disubmit. Ia mengambil nilai dari input dan melakukan validasi.
Validasi Nama: Memastikan bahwa kolom nama tidak kosong.
Validasi Email: Memastikan kolom email tidak kosong dan memenuhi pola email yang benar menggunakan regular expression (regex).
Validasi Nomor Telepon: Memastikan kolom nomor telepon tidak kosong dan hanya berisi angka.
Menggunakan alert: Jika ada kesalahan dalam input, pengguna akan diberi tahu melalui pesan alert.
Mengizinkan atau Mencegah Pengiriman Form: Jika semua validasi berhasil, form akan disubmit; jika tidak, pengiriman akan dibatalkan.
