# Lab5Web
### Disini saya akan menjelaskan sedikit tentang Praktikum 5
# A. Javascript dasar
### Seperti biasa langkah awal adalah buka Aplikasi text editor yang biasa kalian pakai, disini saya menggunakan text Editor VsCode.

### 1. Mengenal Java Script
jika sudah dibuka, langsung buat folder bernama lab5_javascript. setelah itu buat file dengan nama "Mengenal Javascript".

lalu ketik code seperti berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mengenal JavaScript</title>
</head>
<body>
  <h1>Pengenalan JavaScript</h1>
  <h3>Contoh document.write dan console.log</h3>
  <script>
    document.write("Hello World")
    console.log("Hello world")
  </script>
</body>
</html>
```
![1 Mengenal javascript](https://user-images.githubusercontent.com/101393632/162875072-4b109b77-1ca3-40bf-ab6f-d63b965d6f2e.png)

Maka hasilnya akan seperti berikut :

![1 hasil](https://user-images.githubusercontent.com/101393632/162875157-4b5010f5-b8b2-4b52-81c0-a64c03aacac7.jpg)
Klik tombol f12 pada komputer anda, agar bisa melihat console.log.

### 2. Alert Box
Selanjutnya kita akan menampilkan Alert box dengan Javascript. Masukan Kode seperti di bawah ini :
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Alert Box</title>
  </head>
  <body>
    <script lang="javascript">
      
      window.alert("ini merupakan pesan untuk anda");
      
    </script>
  </body>
</html>
```
![2 alertbox](https://user-images.githubusercontent.com/101393632/162875789-06dbeb65-fdfd-4b85-b31e-0589d8cd455a.png)

Maka Hasilnya akan seperti ini :

![2 hasil](https://user-images.githubusercontent.com/101393632/162877559-3fdc9bfe-0a48-41b2-9fa0-4c159be8a444.jpg)

### 3. Method dalam objek
Disini kita akan mencoba memakasi javascript sebagai objek. Masukkan kode berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Script JavaScript</title>
</head>
<body>
  Percobaan memakai javascript: <br>
  <script lang="javascript">
    
    document.write("Selamat Mencoba javascript<br>");
    document.write("Semoga Sukses !");
    
  </script>
</body>
</html>
```
![3 method objek](https://user-images.githubusercontent.com/101393632/162878294-3c00eb88-df67-40bc-a3ad-00446aaaa324.png)

Lalu buka di web browser, dan lihat hasilnya. 

![3 hasil](https://user-images.githubusercontent.com/101393632/162878363-4d0d0535-c9d7-4358-b420-852b6636d7ac.jpg)

### 4. Prompt
Prompt digunakan untuk memasukkan data, bentuknya sama seperti alert box.
masukkan kode berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pemasukan Data</title>
</head>
<body>
  <script lang="javascript">
    var nama=prompt("siapa nama Anda?","Masukkan nama anda");
    document.write("hai, "+ nama );
  </script>
</body>
</html>
```
![4 prompt](https://user-images.githubusercontent.com/101393632/162878484-74f39871-340c-4e45-8aab-b8dfbc464663.png)

Maka hasilnya akan seperti di bawah ini :

![4 hasil](https://user-images.githubusercontent.com/101393632/162878523-ebd44fd3-f656-49bd-8e3a-dda1a84690de.jpg)

jika kita ketik sebuah nama, maka akan muncul kalimat 'hai, (nama)'

### 5. On load
sama seperti alert box, masukkan kode berikut :
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Contoh program javascript</title>
    <script lang="javascript">
      function pesan() {
        alert ("memanggil javascript lewat body onload")
      }
    </script>
  </head>
  <body onload="pesan()">
  </body>
</html>
```
![5 onload](https://user-images.githubusercontent.com/101393632/162878699-ebabf471-7db6-40a9-80e7-a75fe86e6d6b.png)

Maka Hasil akan muncul seperti ini : 

![5 hasil](https://user-images.githubusercontent.com/101393632/162878761-716d2b0f-e922-4443-becf-b9fb81152c13.jpg)

### 6. Operasi Aritmatika
Kali ini kita akan membuat sebuah program aritmatika menggunakan JavaScript. Perhatikan dan ketiklah kode berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contoh Program Javascript</title>
  <script lang="javascript">
    function test (val1,val2)
    {
      document.write("<br>"+"perkalian : val1*val2"+"<br>")
      document.write(val1*val2)
      document.write("<br>"+"pembagian : val1/val2"+"<br>")
      document.write(val1/val2)
      document.write("<br>"+"penjumlahan : val1+val2"+"<br>")
      document.write(val1+val2)
      document.write("<br>"+"pengurangan : val1-val2"+"<br>")
      document.write(val1-val2)
      document.write("<br>"+"modulus : val1%val2"+"<br>")
      document.write(val1%val2)

    }
  </script>
</head>
<body>
  <input type="button" name="button1" value="arithmethic" onclick="test(9,4)">
</body>
</html>
```
![6 operasi aritmatika](https://user-images.githubusercontent.com/101393632/162879094-921a4468-593a-4708-a43b-f595ccf112c6.png)

Jika sudah, langsung buka di browser dan lihat hasilnya. 

Tampilan awal, kita langsung di perlihatkan tombol dengan nama 'arithmethic',

![6 hasil 1](https://user-images.githubusercontent.com/101393632/162879237-374fcc60-2e89-4364-918f-2401a56e8273.jpg)

Jika kita klik tombol tersebut, maka akan muncul aritmatikanya
![6 hasil 2](https://user-images.githubusercontent.com/101393632/162879350-888d91d9-b323-4b81-9569-7858dc42edb5.jpg)

### 7. If - Else
sekarang kita akan membuat program if else, if else berguna sesuai dengan kondisi yang kita atur. pada Praktikum ini, Program yang dibuat adalah nilai rendah dan tinggi. jika kita masukan nilai diatas 60, maka program akan menampilkan hasil 'lulus', Sebaliknya jika kita masukan nilai di bawah 60 maka program akan menampilkan hasil 'tidak lulus'.
berikut kodenya :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contoh if-else</title>
</head>
<body>
  <script lang="javascript">
    var nilai = prompt("nilai (0-100): ", 0);
    var hasil = "";
    if (nilai >= 60) 
    hasil = "Lulus";
    else
    hasil = "Tidak Lulus";
    document.write("hasil: " + hasil);
  </script>
</body>
</html> 
```
Kita lihat Hasilnya di web browser :

![7 hasil](https://user-images.githubusercontent.com/101393632/162880010-ec8937bc-d76d-4adf-8bf7-7098883d64fb.jpg)

### 8. Operator Switch
Operator Switch akan menampilkan hasil dengan program yang kita perintah, Ketik kode berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>COntoh program javascript</title>

  <script lang="javascript">
    function test ()
    {
      val1=window.prompt("input nilai (1-5):")
      switch (val1)

      {
        case "1":
          document.write("bilangan satu")
          break
        case "2":
          document.write("bilangan dua")
          break
        case "3":
          document.write("bilangan tiga")
          break
        case "4":
          document.write("bilangan empat")
          break
        case "5":
          document.write("bilangan lima")
          break
        default :
          document.write("bilangan lainnya")
      }
    }
  </script>
</head>
<body>
  <input type="button" name="button1" value="switch" onclick="test()">
</body>
</html>
```
![8 operator switch](https://user-images.githubusercontent.com/101393632/162880269-ed5e69fb-cee2-4fc0-9711-4ef8aad61a60.png)

Maka Hasilnya akan menunjukan bilangan yang kita pilih, yaitu angka 0-5. jika yang kita masukan adalah bilangan yang lebih dari 5, maka akan menampikan hasil 'bilangan lainnya'

![8 hasil](https://user-images.githubusercontent.com/101393632/162880360-690c537e-5de7-43e3-b2b4-36da06d3d515.jpg)

### 9. Form Input
Ketik Kode seperti berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>form input</title>

  <script lang="javascript">
    function test (){
      var val1=document.kirim.T1.value
      if (val1%2==0)
        document.kirim.T2.value="bilangan genap"
      else 
        document.kirim.T2.value="bilangan ganjil"
    }
  </script>
</head>
<body>
  <form method="post" name="kirim">
    <p>BIL <input type="text" name="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
    <p><input type="button" value="tebak" name="B1" onclick="test()"></p>
  </form>
</body>
</html>
```
![9 Form input](https://user-images.githubusercontent.com/101393632/162881412-6717311f-6acf-4d70-8a6d-64fa566b53c7.png)

Maka hasilnya akan menampilkan seperti ini :

![9 hasil](https://user-images.githubusercontent.com/101393632/162881450-20590108-d9c7-42c4-8984-5c645d241deb.jpg)

### 10. Form Button
Pada Praktikum ini, akan di tunjukkan bagaimana cara merubah warna background dan warna font hanya dengan mengklik tombol. 

ketik kode berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>objek document</title>
</head>
<body>
  <script lang="javascript">
    function ubahWarnaLB(warna) {
      document.bgColor = warna;
    }
    function ubahWarnaLD(warna) {
      document.fgColor = warna;
    }
  </script>

  <h1>Test</h1>
  <form>
    <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('green')">
    <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('white')">
    <input type="button" value="teks kuning" onclick="ubahWarnaLD('yellow')">
    <input type="button" value="teks biru" onclick="ubahWarnaLD('blue')">
  </form>
  <script lang="javascript">
    document.write("dimodifikasi terakhir pada " + document.lastModified);
  </script>
</body>
</html>
```
![10 form button](https://user-images.githubusercontent.com/101393632/162881702-bc65c91f-615b-4806-a499-6e8896f0d981.png)

Lihat hasilnya di browser :

![10 hasil](https://user-images.githubusercontent.com/101393632/162883304-2c49feb7-9e8e-44b1-9c60-71e0db9bb0ae.jpg)

### 11. HTML DOM
Kali ini kita akan memuat program yang menghasilkan jumlah, masukan kode berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Daftar menu</title>
  <script>
    function hitung(ele) {
      var total = document.getElementById('total').value;
          total = (total ? parseInt(total) : 0);
      var harga = 0;

      if (ele.checked) {
        harga = ele.value;
        total += parseInt(harga);
      } 
      else {
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
  <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />Ayam Goreng Rp. 5000</label><br>
  <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />Tempe Goreng Rp. 500</label><br>
  <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />Telur Dadar Rp. 2.500</label><br>
  <strong>Total Bayar: Rp. <input id="total" type="text"/></strong>
</body>
</html>
```
![11 Html Dom](https://user-images.githubusercontent.com/101393632/162883568-9cc5f5e0-ea18-4cb9-a93c-ef0819f0766c.png)

dan hasilnya akan seperti berikut :

![11 hasil](https://user-images.githubusercontent.com/101393632/162883603-a854ae66-d66b-48aa-8b85-7ed561167b9f.jpg)

=====================================================================
## B. TUGAS
Diperintahkan untuk membuat script untuk melakukan validasi pada sebuah form.
saya membuat form tersebut dengan kode seperti berikut :

![12 Tugas](https://user-images.githubusercontent.com/101393632/162884609-bbb642b2-8ea2-40c2-831d-e6c63c4c8c7c.png)

Disini agar tampilan form menarik, saya tambahkan juga CSS. Seperti berikut :

![12 Tugas CSS](https://user-images.githubusercontent.com/101393632/162884706-16bb0350-fa02-4116-878c-12ae86147c7d.png)

Dan Hasil dari 2 Kode tersebut sebagai berikut :

![12 hasil 1](https://user-images.githubusercontent.com/101393632/162884961-64cba980-0c95-4e5b-9b51-35cf43b87fb2.jpg)

Karena Form yang dibikin adalah Form Validasi, jika ada kekurangan pada pengisinan data maka tampilannya akan seperti ini :

![12 hasil 2](https://user-images.githubusercontent.com/101393632/162885091-fc49809d-e937-4399-bd8f-31691f05c60e.jpg)

==============S E L E S A I================
