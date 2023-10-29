**Nama: Rini Ariza**

**NIM: 312210337**

**Kelas: TI.22.A3**

---

## Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file **lab5_javascript.html** seperti berikut.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World<br><br>");
        console.log("Hello World");
    </script>
</body>
</html>
```

![Screenshot (329)](https://github.com/rniarzz/Lab5web/assets/115542704/5e5bf7ca-dc68-4d78-ab8e-1eb17130fd64)

---

## Javascrip Dasar
#### Pemakaian Alert sebagai property window.

```html
<html>
    <head>
        <title>alert box</title>
    </head>
    <body>
        <script language = "Javascript">
            <!--
                window.alert("ini merupakan pesan untuk anda");
            //-->
        </script>
    </body>
</html>
```

![Screenshot (330)](https://github.com/rniarzz/Lab5web/assets/115542704/850966b7-1223-4191-b9eb-a22bc73ad80a)

---

#### Pemakaian method dalam objek

```html
<html>
    <head>
        <title>skrip Javascript</title>
    </head>
    <body>
        percobaan memakai Javascript:<br>
        <script language = "Javascript">
            <!--
                document.write("selamat mencoba javascript<br>")
                document.write("semoga sukses!");
            //-->
        </script>
    </body>
</html>
```

![Screenshot (331)](https://github.com/rniarzz/Lab5web/assets/115542704/d6fded58-efb3-4ba0-acab-8443a945b551)

---

#### Pemakaian Prompt

```html
<html>
    <head>
        <title>pemasukan data</title>
    </head>
    <body>
        <script language = "javascript">
            <!--
                var nama =prompt("siapa nama anda?","masukkan nama");
            -->
        </script>
    </body>
</html>
```

![Screenshot (335)](https://github.com/rniarzz/Lab5web/assets/115542704/aac74b43-61e7-49bc-8ac8-6fb527bd00d2)

---

#### Pembuatan fungsi dan cara pemanggilannya

```html
<html>
    <head>
        <title>contoh program javascript</title>
        <script language = "javascript">
            function pesan(){
            alert ("memanggil javascript lewat lewat body onload")
            }
        </script>
    </head>
    <body onload=pesan()>
    </body>
</html>
```

![Screenshot (352)](https://github.com/rniarzz/Lab5web/assets/115542704/e15e3f29-4298-4517-a982-9798b5d8add7)

---

## Dasar Pemrograman Di Javascript
#### Operasi dasar aritmatika

```html
<html>
  <head>
    <title>contoh program javascript</title>
    <script language="javascript">
      function test(val1, val2) {
        document.write("<br>" + "perkalian : val1*val2 " + "<br>");
        document.write(val1 * val2);
        document.write("<br>" + "pembagian : val1/val2 " + "<br>");
        document.write(val1 / val2);
        document.write("<br>" + "penjumlahan : val1+val2 " + "<br>");
        document.write(val1 + val2);
        document.write("<br>" + "pengurangan : val1-val2 " + "<br>");
        document.write(val1 - val2);
        document.write("<br>" + "modulus : val1%val2 " + "<br>");
        document.write(val1 % val2);
      }
    </script>
  </head>
  <body>
    <h3>contoh program javascript</h3>
    <input type="button" name="button1" value="aritmetic" onclick="test(9,4)" />
  </body>
</html>
```

![Screenshot (336)](https://github.com/rniarzz/Lab5web/assets/115542704/ba4f3199-db38-4bce-b73b-8c0099e55e17)

---

#### Seleksi kondisi

```html
<html>
  <head>
    <title>contoh if-else</title>
  </head>
  <body>
    <script language="javascript">
      <!--
      var nilai = prompt("nilai (0-100): ", 0);
      var hasil = "";
      if (nilai >= 60) hasil = "lulus";
      else hasil = "tidak lulus";
      document.write("hasil: " + hasil);
      //-->
    </script>
  </body>
</html>
```

![Screenshot (338)](https://github.com/rniarzz/Lab5web/assets/115542704/d96c0851-cc11-4486-b25c-3ec6d2434773)

![Screenshot (339)](https://github.com/rniarzz/Lab5web/assets/115542704/1345a0dd-f7ef-47d5-a4fd-71d938844d96)

![Screenshot (340)](https://github.com/rniarzz/Lab5web/assets/115542704/d11c3a17-0d1c-4d58-aed7-7e299fd78b71)

![Screenshot (341)](https://github.com/rniarzz/Lab5web/assets/115542704/12dd305c-83e5-4ef9-bb2d-0266339a65d7)

---

#### Penggunaan operator switch untuk seleksi kondisi

```html
<html>
    <head>
        <title>contoh program javascript</title>
        
        <script language="javascript">
            function test ()
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
                default :
                    document.write("bilangan lainnya")
            }
        }
        </script>
    </head>
    <body>
        <h3>contoh program javascript</h3>
        <input type="button" name="button1" value="switch" onclick=test()>
    </body>
</html>
```

![Screenshot (343)](https://github.com/rniarzz/Lab5web/assets/115542704/681ff98a-82dd-4cf5-b8ac-34ecf9881358)

![Screenshot (344)](https://github.com/rniarzz/Lab5web/assets/115542704/41f24a8c-479b-4198-9ea7-2d76ccff83af)

![Screenshot (345)](https://github.com/rniarzz/Lab5web/assets/115542704/fb48aad7-218e-43ef-88a6-b2e81425df03)

![Screenshot (346)](https://github.com/rniarzz/Lab5web/assets/115542704/e2730378-c0cd-42c2-bbe5-2f62463fdfe8)

---

## Pembuatan Form
#### Form Input

```html
<html>
    <head>
        <script language="javascript">
            function test () {
                var val1=document.kirim.T1.value
                if (val1%2==0)
                    document.kirim.T2.value="bilangan genap"
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
```

![Screenshot (347)](https://github.com/rniarzz/Lab5web/assets/115542704/411df721-dc1f-4f83-9ddc-ae2aa21cd5c7)

![Screenshot (348)](https://github.com/rniarzz/Lab5web/assets/115542704/47527992-0b9a-4083-bf93-10554f1a1c8a)

---

#### Form Button.

```html
<html>
  <head>
    <title>objek document</title>
  </head>
  <body>
    <script language="javascript">
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
      <input
        type="button"
        value="Latar Belakang Hijau"
        onclick="ubahWarnaLB('GREEN')"
      />
      <input
        type="button"
        value="Latar Belakang Putih"
        onclick="ubahWarnaLB('WHITE')"
      />
      <input
        type="button"
        value="Teks Kuning"
        onclick="ubahWarnaLD('YELLOW')"
      />
      <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')" />
    </form>
    <script language="javascript">
      <!--
      document.write("Dimodifikasi terakhir pada " + document.lastModified);
      //-->
    </script>
  </body>
</html>
```

![Screenshot (349)](https://github.com/rniarzz/Lab5web/assets/115542704/4c6beb55-d4a7-4bdb-b74b-3864dec06d2a)

---

## HTML DOM
#### Pilihan menggunakan checkBox dengan perhitungan otomatis

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Daftar Menu</title>
    <script>
      function hitung(ele) {
        var total = document.getElementById("total").value;
        total = total ? parseInt(total) : 0;
        var harga = 0;

        if (ele.checked) {
          harga = ele.value;
          total += parseInt(harga);
        } else {
          harga = ele.value;
          if (total > 0) total -= parseInt(harga);
        }
        document.getElementById("total").value = total;
      }
    </script>
  </head>
  <body>
    <h1>Daftar Menu Makanan</h1>
    <label
      ><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />
      Ayam Goreng Rp. 5000</label
    ><br />
    <label
      ><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />
      Tempe Goreng Rp. 500</label
    ><br />
    <label
      ><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />
      Telur Dadar Rp. 2.500</label
    ><br />
    <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
  </body>
</html>
```

![Screenshot (350)](https://github.com/rniarzz/Lab5web/assets/115542704/095c0ab9-503b-48bf-91d5-d3d9a8aa5eee)

---

## Pertanyaan dan Tugas
#### 1. Buat script untuk melakukan validasi pada isian form.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Validasi Form</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
  </head>
  <body>
    <h2>Formulir Validasi</h2>
    <form id="myForm" onsubmit="return validateForm()">
      <label for="nama">Nama:</label>
      <input type="text" id="nama" name="nama" /><br />

      <label for="email">Email:</label>
      <input type="text" id="email" name="email" /><br />

      <label for="umur">Umur:</label>
      <input type="text" id="umur" name="umur" /><br />

      <input type="submit" value="Submit" />
    </form>

    <p id="error-message"></p>

    <script>
      function validateForm() {
        var nama = document.forms["myForm"]["nama"].value;
        var email = document.forms["myForm"]["email"].value;
        var umur = document.forms["myForm"]["umur"].value;

        var errorMessage = "";

        if (nama === "") {
          errorMessage += "Nama harus diisi.\n";
        }

        if (email === "") {
          errorMessage += "Email harus diisi.\n";
        } else {
          var emailPattern = /^\w+@[a-zA-Z_]+\.[a-zA-Z]{2,3}$/;
          if (!email.match(emailPattern)) {
            errorMessage += "Email tidak valid.\n";
          }
        }

        if (umur === "") {
          errorMessage += "Umur harus diisi.\n";
        } else {
          var umurValue = parseInt(umur);
          if (isNaN(umurValue) || umurValue < 1 || umurValue > 100) {
            errorMessage += "Umur harus berupa angka antara 1 dan 100.\n";
          }
        }

        if (errorMessage !== "") {
          document.getElementById("error-message").textContent = errorMessage;
          return false;
        }

        return true;
      }
    </script>
  </body>
</html>
```

```css
/* CSS untuk styling formulir */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

h2 {
    text-align: center;
}

form {
    max-width: 400px;
    margin: 0 auto;
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

label {
    display: block;
    margin-bottom: 10px;
}

input[type="text"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

input[type="submit"] {
    background-color: #007BFF;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

input[type="submit"]:hover {
    background-color: #0056b3;
}

#error-message {
    color: red;
    font-weight: bold;
    margin-top: 10px;
}
```

![Screenshot (351)](https://github.com/rniarzz/Lab5web/assets/115542704/606237e0-91cd-4747-85dc-fa5d0fbc137e)


<h1 <p align="center"><b>======== Sekian Terima Kasih ==========</b></p></h1>
