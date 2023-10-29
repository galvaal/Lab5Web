## lab5web

## Praktikum
Buat dokumen html lab5_javascript.html
    <html>
    
    <head>
        <title>Mengenal Javascript</title>
    </head>
    
    <body>
        <h1>Pengenalan Javascript</h1>
        <h3>Contoh document.write dan console.log</h3>
        <script>
            document.write('Hello World !');
            console.log('Hello World !');
        </script>
    </body>
    
    </html>/

![a1](https://github.com/galvaal/Lab5Web/assets/115516730/daff4bf3-4656-4fe2-87a2-c6ae588e5a27)

#### Method
    <html>
    
    <head>
        <title>skrip Javascript</title>
    </head>
    
    <body>
        percobaan memakai Javascript:<br>
        <script lang="Javascript">
            document.write("selamat mencoba javascript<br>");
            document.write("Semoga sukses !");
        </script>
    </body>
    
    </html>

![a3](https://github.com/galvaal/Lab5Web/assets/115516730/7c5af955-487a-406d-9d20-a2282bce1f4e)

#### Prompt
    <html>
        <head>
            <title>Pemasukan Data</title>
        </head>
        <body>
            <script lang="javascript">
                let nama = prompt("Siapa nama anda ?", "Masukan nama anda");
                document.write('hai, ' + nama);
            </script>
        </body>
    </html>

![a4](https://github.com/galvaal/Lab5Web/assets/115516730/cff20203-2ce7-402e-9937-561d21633194)

#### Fungsi 
    <html>
    
    <head>
        <title>contoh program javascript</title>
        <script lang="javascript">
            function message() {
                alert("Memanggil javascript lewat body onload")
            }
        </script>
    </head>
    
    <body onload="message()"></body>
    
    </html>

![a5](https://github.com/galvaal/Lab5Web/assets/115516730/784245a1-2c54-44f2-b6bd-1ffa13097e65)

#### Operasi Aritmatika
    <html>
        <head>
            <title>contoh program javascript</title>
            <script language="javascript">
                function test (a, b){
                    document.write(`<br> perkalian : ${a} * ${b} <br>`);
                    document.write(a*b);
                    document.write(`<br> pembagian : ${a}/${b} <br>`);
                    document.write(a/b);
                    document.write(`<br> penjumlahan : ${a} + ${b} <br>`);
                    document.write(a+b);
                    document.write(`<br> pengurangan : ${a} - ${b} <br>`);
                    document.write(a-b);
                    document.write(`<br> modulus : ${a} % ${b} <br>`)
                    document.write(a%b)
                }
            </script>
        </head>
        <body>
            <input type="button" value="arithmetic" onclick="test(4, 2)">
        </body>
    </html>

![a6](https://github.com/galvaal/Lab5Web/assets/115516730/90268c15-5261-4556-8d9f-d30cd189b9fa)

#### If Else 
    <html>
    
    <head>
        <title>contoh if-else</title>
    </head>
    
    <body>
        <script lang="javascript">
            let nilai = prompt("nilai (0-100): ", 0);
            let hasil = "";
            if (nilai >= 60) {
                hasil = "lulus";
            } else {
                hasil = "tidak lulus";
            }
            document.write(`hasil: ${hasil}`);
        </script>
    </body>
    
    </html>

#### If Else 
    <html>
    
    <head>
        <title>contoh if-else</title>
    </head>
    
    <body>
        <script lang="javascript">
            let nilai = prompt("nilai (0-100): ", 0);
            let hasil = "";
            if (nilai >= 60) {
                hasil = "lulus";
            } else {
                hasil = "tidak lulus";
            }
            document.write(`hasil: ${hasil}`);
        </script>
    </body>
    
    </html>

![a7](https://github.com/galvaal/Lab5Web/assets/115516730/d5d24ae0-c5d5-43f9-a58b-b7a820a1ea2d)

![a8](https://github.com/galvaal/Lab5Web/assets/115516730/2d1bc52c-d94c-4e30-8a7b-ea621dc5fa39)

#### Switch
    <html>
    
    <head>
        <title>contoh program javascript</title>
        <script lang="javascript">
            function test() {
                let num = window.prompt("Input 1-5")
                switch (num) {
                    case "1":
                        document.write("bilangan satu");
                        break;
                    case "2":
                        document.write("bilangan dua");
                        break;
                    case "3":
                        document.write("bilangan tiga");
                        break;
                    case "4":
                        document.write("bilangan empat");
                        break;
                    case "5":
                        document.write("bilangan lima");
                        break;
                    default:
                        document.write(`bilangan ${num} tidak termasuk`)
                        break;
                }
            }
        </script>
    </head>
    <body>
        <input type="button" value="switch" onclick="test()">
    </body>
    
    </html>

![a9](https://github.com/galvaal/Lab5Web/assets/115516730/10045e49-2c5b-4ca1-84b7-c48086b6b300)

#### Form Input
    <html>
    
    <head>
        <title>Form Input</title>
        <script lang="javascript">
            function test() {
                let val = document.kirim.T1.value
                if (val % 2 === 0) {
                    document.kirim.T2.value = "bilangan genap"
                } else {
                    document.kirim.T2.value = "bilangan ganjil"
                }
            }
        </script>
    </head>
    
    <body>
        <form method="post" name="kirim">
            <p>
                BIL <input type="text" name="T1" size="20" /> MERUPAKAN BIL
                <input type="text" name="T2" size="20" />
            </p>
            <p><input type="button" value="TEBAK" name="B1" onclick="test()" /></p>
        </form>
    </body>
    
    </html>

![b1](https://github.com/galvaal/Lab5Web/assets/115516730/fad726f2-8975-465c-984a-f1e73a611d02)

### Menu
Pilihan checkbox yang akan menghasilkan perhitungan otomatis

    <html>
    
    <head>
        <title>Daftar Menu</title>
        <script>
            function hitung(ele) {
                let total = document.getElementById("total").value;
                total = total ? parseInt(total) : 0;
                let harga = 0;
    
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
        <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />
            Ayam Goreng Rp 5.0000</label><br />
        <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />
            Tempe Goreng Rp 500</label><br />
        <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />
            Telur Dadar Rp 2.500</label>
        <hr />
        <strong>Total Bayar: Rp <input type="text" id="total" /></strong>
    </body>
    
    </html>

![b2](https://github.com/galvaal/Lab5Web/assets/115516730/eedf25c6-4127-4d4c-ad19-0d5bf03075ee)


