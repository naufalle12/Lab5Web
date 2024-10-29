# Lab5Web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script type="text/JavaScript" src="index.js"></script>
    <script type class="text/JavaScript">
        alert("Javascript pada tag head.");
    </script>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write</h3>
    <script>
        document.write("Hello World");
    </script>
</body>
</html>
# index.js
document.write("Hello World.")
![Screenshot (243)](https://github.com/user-attachments/assets/257df4b3-87c7-4862-8302-95e066127c89)
![Screenshot (244)](https://github.com/user-attachments/assets/6602dacc-06a5-49ff-9c27-8a7d96b4ead7)
![Screenshot (245)](https://github.com/user-attachments/assets/4d1fae4c-4f43-4274-89e7-91a7ab4b4944)
![Screenshot (246)](https://github.com/user-attachments/assets/0439a898-7ff7-4143-8d47-896b879dbdf9)

## praktikum 5
code 1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>

js dasar
pemakaian alert sebagai property window
<!DOCTYPE html>
<html>
<head>
    <title>alert box</title>
</head>
<body>
    <script language = "javascript">
        window.alert("ini merupakan pesan untuk anda");
    </script>
</body>
</html>

pemakaian method dalanm objek
<!DOCTYPE html>
<html>
    <head>
        <title>skrip javascript</title>
    </head>
    <body>
        percobaan memakai javascript:<br>
        <script language = "javascript">
            document.write("selamat mencoba javascript<br>");
            document.write("semoga sukses!");
        </script>
    </body>
</html>

pemakaian prompt
<!DOCTYPE html>
<html>
    <head>
        <title>pemasukan data</title>
    </head>
    <body>
        <script language = "javascript">
            var nama = prompt("siapa nama anda?", "masukkan nama anda");
            document.write("hai, " + nama);
        </script>
    </body>
</html>

pembuatan fungsi dan cara pemanggilan
<!DOCTYPE html>
<html>
<head>
    <title>contoh program Javascript</title>
    <script language="javascript">
        function pesan () {
            alert ("memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload=pesan()>
</body>
</html>

operasi dasar aritmatika
<html>
    <head>
        <title>contoh program javascript</title>
        <script language="javascript">
        function test (val1,val2)
        {
            document.write("<br>"+"perkalian : val1*val2 "+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"pembagian : val1/val2 "+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
            document.write(val1-val2)
            document.write("<br>"+"modulus : val1%val2 "+"<br>")
            document.write(val1%val2)
        }
        </script>
    </head>
    <body>
        <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
    </body>
</html>

seleksi kondisi if.else
<html>
    <head>
        <title>contoh if-else</title>
    </head>
    <body>
        <script language = "javascript">
            var nilai = prompt("nilai (0-100): ", 0);
            var hasil = "";
            if (nilai >= 60)
            hasil = "lulus";
            else
            hasil = "tidak lulus";
        document.write("hasil: " + hasil);
        </script>
    </body>
</html>

operasi switchutk seleksi kondisi
<html>
    <head>
        <title>contoh program javascript</title>
        <script language="javascript">
            function test ()
            {
                val1=window.prompt("input nilai (1-5): ")
                switch (val1)
                {
                    case "1" :
                        document.write("bilangan satu")
                        break
                    case "2" :
                        document.write("bilangan dua")
                        break
                    case "3" :
                        document.write("bilangan tiga")
                        break
                    case "4" :
                        document.write("bilangan empat")
                        break
                    case "5" :
                        document.write("bilangan lima")
                        break
                    default :
                        document.write("bilangan lainnya")
                }
            }
        </script>
    </head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>

pembuatan form input
<html>
    <head>
        <script language="javascript">
        function test () {
            var val1=document.kirim.T1.value
            if (val1%2==0)
                document.kirim.T2.value=" bilangan genap"
            else
                document.kirim.T2.value="bilangan ganjil"
        }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="T1" size="20">
            MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
            <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
        </form>
    </body>
</html>

form button
<html>
    <head>
        <title>objek document</title>
    </head>
    <body>
        <script language = "javascript">
            function ubahWarnaLB(warna) {
                document.bgColor = warna;
            }
            function ubahWarnaLD(warna) {
                document.fgColor = warna;
            }
        </script>
        <h1>test</h1>
        <form>
            <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
            <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
            <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
            <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
        </form>
        <script language = "javascript">
            document.write("Dimodifikasi terakhir pada" +
            document.lastModified);
        </script>
    </body>
</html>

html dom
<!--file : daftar menu.html-->
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
        <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" /> Ayam Goreng Rp. 5.000</label><br />
        <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" /> Tempe Goreng Rp. 500</label><br />
        <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" /> Telor Dadar Rp. 2.500</label><hr />
        <strong>Total Bayar: Rp. <input id="total" type="text"/></strong>
    </body>
</html>


script pertanyaan dan tugas validasi form
<!DOCTYPE html>
<html lang="id">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Validasi Form Bilangan Ganjil atau Genap</title>
        <style>
            .error { color: red; }
        </style>
        <script language="javascript">
            function cekBilangan() {
                // Ambil nilai dari input T1
                var val1 = document.forms["kirim"]["T1"].value;
                var hasil = document.forms["kirim"]["T2"];
                var errorMessage = document.getElementById("errorMessage");

                // Bersihkan pesan kesalahan
                errorMessage.textContent = "";
                
                // Pastikan input tidak kosong
                if (val1 === "") {
                    errorMessage.textContent = "Harap masukkan bilangan.";
                    hasil.value = ""; // Kosongkan hasil
                    return false;
                }

                // Pastikan input adalah angka
                if (isNaN(val1)) {
                    errorMessage.textContent = "Input harus berupa angka.";
                    hasil.value = ""; // Kosongkan hasil
                    return false;
                }

                // Pastikan angka adalah bilangan bulat
                if (!Number.isInteger(parseFloat(val1))) {
                    errorMessage.textContent = "Harap masukkan bilangan bulat.";
                    hasil.value = ""; // Kosongkan hasil
                    return false;
                }

                // Tentukan apakah bilangan genap atau ganjil
                if (val1 % 2 == 0) {
                    hasil.value = "Bilangan Genap";
                } else {
                    hasil.value = "Bilangan Ganjil";
                }
                return true;
            }
        </script>
    </head>
    <body>
        <h1>Cek Bilangan Ganjil atau Genap</h1>
        <form name="kirim" onsubmit="return cekBilangan()">
            <p>
                Masukkan Bilangan: <input type="text" name="T1" size="20">
            </p>
            <p>
                Hasil: <input type="text" name="T2" size="20" readonly>
            </p>
            <p class="error" id="errorMessage"></p>
            <p>
                <input type="button" value="Cek Bilangan" onclick="cekBilangan()">
            </p>
        </form>
    </body>
</html>
