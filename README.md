# Tugas 3 - PBKK A
```
Nama : Muhammad Ryanda Nugraha M
NRP : 05111640000180
```
## Petunjuk Penggunaan

### Data yang harus diinput
-Nama: Nama Mahasiswa
-NRP : NRP Mahasiswa
-Score: IPK Mahasiswa

### Alur Program

- Melalui route '/home' controller akan return 'homes.jsp'
- Pada homes.jsp terdapat link request '/form' ke controller
- Controller kemudian membalas dengan mengembalikan halaman 'form.jsp' yang sekaligus melakukan inisialisasi kelas model
- Data yang diinputkan berupa:
  - nama : String
  - nrp : String
  - score : Double

- Jika data sesuai maka form mengirim hasil input ke route '/form_input_output' kemudian diproses oleh controller untuk kemudian memasukkan data input ke model yang telah ada
- Setelah itu controller akan mengembalikan 'inputoutput.jsp'
- Di dalam inputoutput.jsp data pada model dipanggil dengan sintaks '${_nama_atribut_}'


Buatlah sebuat UDP Picture server yg secara periodik akan mengirimkan gambar-gambar ke client
Sisi server, mengirimkan gambar-gambar ke client yg Connect di port 9000
Sisi client, akan mengambil gambar tersebut dan menyimpannya sesuai dengan nama filenya

### Form Entry
![Input](input.png)

### Output
![Output](output.png)

