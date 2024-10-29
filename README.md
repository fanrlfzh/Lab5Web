# Lab5Web
#Tampilan Javascript
<!DOCTYPE html>
<html lang="en">
<head>
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
![Screenshot (263)](https://github.com/user-attachments/assets/7219b69a-64cc-4d27-b21a-a3feabdee62f)

#Pemakaian Alert sebagai property window.
<html>
<head>
<title>alert box</title>
</head>
<body>
<script languange = "javascript">
<!--
    window.alert("ini merupakan pesan untuk anda");
//-->
    //-->
</script>
</body>
</html>
![Screenshot (264)](https://github.com/user-attachments/assets/68ece8e4-acfe-4d5b-94b4-722ac7c84bab)

#Pemakaian method dalam objek
<html>
    <head>
        <title>skrip javascript</title>
    </head>
    <body>
        percobaan memakai javascript:<br>
        <script language = "javascript">
            <!--
                document.write("selamat mencoba javascript")
                document.write("semoga sukses!");
            //-->
        </script>
    </body>
</html>
![Screenshot (265)](https://github.com/user-attachments/assets/c2347581-6afb-4b7b-a7c0-56caa54a7eae)

#Pemakaian Prompt
<html>
    <head>
        <title>pemasukan data</title>
    </head>
    <body>
        <script language = "javascript">
            <!--
                var nama = prompt("siapa nama anda?","masukkan nama anda");
                document.write("hai, " + nama);
            -->
        </script>
    </body>
</html>
![Screenshot (266)](https://github.com/user-attachments/assets/be06abd0-3305-458a-bd17-f133d35732f7)

#Pembuatan fungsi dan cara pemanggilannya
</html>
<html>
    <head>
        <title>contoh program javascipt</title>
        <script language="javascript">
            function pesan(){
                alert ("memanggil javascipt lewat body onload")
            }
        </script>
    </head>
    <body onload=pesan()>
    </body>
</html>
![Screenshot (268)](https://github.com/user-attachments/assets/e88f8201-1172-48fd-8d09-106b31d2d76c)

#Operasi dasar aritmatika
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
<input type="button" name="button1" value="arithmetic"onclick=test(9,4)>
</body>
</html>
![Screenshot (269)](https://github.com/user-attachments/assets/e2a259f5-ce99-4f8d-bf2e-cac4af34bbb0)

#Seleksi kondisi (if..else)
<html>
    <head>
        <title>contoh if-else</title>
    </head>
    <body>
        <script language = "javascript">
            <!--
                var nilai = prompt("nilai (0-100): ", 0);
                var hasil = "";
                if (nilai>= 60)
                hasil = "lulus";
                else
                hasil = "tidak lulus";
                document.write("hasil: " + hasil);
            //-->
        </script>
    </body>
</html>
![Screenshot (271)](https://github.com/user-attachments/assets/33b4d286-7a2e-4b56-ad1b-c6bdd003d350)
![Screenshot (272)](https://github.com/user-attachments/assets/94596344-0e6e-4f44-abb5-fdfbfda16d0a)

#Penggunaan operator switch untuk seleksi kondisi
<html>
    <head>
        <title>contoh program javascript</title>

        <script language="javascript">
            function test()
            {
                val1=window.prompt("input nilai (1-5):")
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
                    default:
                    document.write("bilangan lainnya")
                }
            }
        </script>
    </head>
<body>
<input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
![Screenshot (275)](https://github.com/user-attachments/assets/05d1e02b-1352-45da-bdfc-c62eccb70591)
![Screenshot (276)](https://github.com/user-attachments/assets/07ff3a23-d39f-4e21-a47a-ac449e93ae64)

#Form Input
<html>
    <head>
        <script language="javascript">
            function test() {
                var val1=document.kirim.TI.value
                if (val1%2==0)
                document.kirim.T2.value="bilangan genap"
                else
                document.kirim.T2.value="bilangan ganjil"
            }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="TI" size="20">
                MERUPAKAN BIL <input type="text" name="T1" size="20">
                <p><input type="button" value="TEBAK" name="B1" onclick=test()<>/p>
        </form>
    </body>
</html>
![Screenshot (277)](https://github.com/user-attachments/assets/e6aebbe6-3387-4ee5-88b7-583f44e1aacf)

#Form Button.
<html>
    <head>
        <title>objek document</title>
    </head>
    <body>
        <script language = "javascript">
            <!--
                function ubahWarnaLB(warna) {
                    document.bgColor = warna;
                }
                function ubahWarnaLD(warna) {
                    document.fgColor = warna;
                }
            //-->
        </script>

        <h1>tes</h1>
        <form>
            <input type="button" value="Latar Belakang Hijau" onClick="ubahWarnaLB('GREEN')">
            <input type="button" value="Latar Belakang White" onClick="ubahWarnaLB('WHITE')">
            <input type="button" value="Teks Kuning" onClick="ubahWarnaLD('YELLOW')">
            <input type="button" value="Teks Biru" onClick="ubahWarnaLD('BLUE')">
        </form>
        <script language = "javascript">
            <!--
                document.write("Dimodifikasi terakhir pada " +
                document.lastModified);
            //-->
        </script>

    </body>
</html>
![Screenshot (279)](https://github.com/user-attachments/assets/a2217488-d966-45de-983e-fd5e087464ba)

#Pilihan menggunakan checkBox dengan perhitungan otomatis
<!--
    File: daftar_menu.html
//-->
<html>
    <head>
        <title>Daftar Menu</title>
        <script>
            function hitung(ele) {
                var total = document.getElementById('total').value;
                total = (total ? parseInt(total) : 0);
                var harga = 0;

                if (ele.checked) {
                    harga=  ele.value;
                    total += parseInt(harga);
                } else {
                    harga = ele.value;
                    if (total > 0)
                    total = parseInt(harga);
                }
                document.getElementById('total').value = total;
            }
        </script>
    </head>
    <body>
        <h1>Daftar Menu Makanan</h1>
        <label><input type="checkbox" value="5000" id="menu1" onClick="hitung(this);" /> Ayam Goreng Rp. 5.000</label><br />
        <label><input type="checkbox" value="500" id="menu2" onClick="hitung(this);" /> Tempe Goreng Rp. 500</label><br />
        <label><input type="checkbox" value="2.500" id="menu3" onClick="hitung(this);" /> Telur Dadar Rp. 2.500</label><hr />
        <strong>Total Bayar: Rp. <input id="total" type="text" /><strong>
    </body>
</html>
![Screenshot (280)](https://github.com/user-attachments/assets/8211d60f-9331-4694-a6e7-685956c60e78)

Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form.
<!DOCTYPE html>
<html>
<head>
    <title>Form Validation</title>
    <script>
        function validateForm() {
            let name = document.forms["myForm"]["name"].value;
            let email = document.forms["myForm"]["email"].value;
            let password = document.forms["myForm"]["password"].value;
            let message = document.getElementById("message");

            message.innerHTML = "";

            if (name === "") {
                message.innerHTML += "Nama harus diisi.<br>";
                return false;
            }

            let emailPattern = /^[^ ]+@[^ ]+\.[a-z]{2,3}$/;
            if (!email.match(emailPattern)) {
                message.innerHTML += "Masukkan email yang valid.<br>";
                return false;
            }

            if (password.length < 8) {
                message.innerHTML += "Kata sandi minimal 8 karakter.<br>";
                return false;
            }
            
            alert("Formulir berhasil dikirim!");
            return true;
        }
    </script>
</head>
<body>
    <h2>Form Validation</h2>
    <form name="myForm" onsubmit="return validateForm()">
        Nama: <input type="text" name="name"><br><br>
        Email: <input type="text" name="email"><br><br>
        Kata Sandi: <input type="password" name="password"><br><br>
        <input type="submit" value="Submit">
    </form>
    <p id="message" style="color:red;"></p>
</body>
</html>
![Screenshot (281)](https://github.com/user-attachments/assets/8940fd0a-ef3a-45fa-a7a6-15986e6d2cba)














