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
![input](https://user-images.githubusercontent.com/28387331/54903356-49ee4800-4f0e-11e9-8491-accbc0ed2add.PNG)

### Output
![output](https://user-images.githubusercontent.com/28387331/54903397-5e324500-4f0e-11e9-96bc-876805b08863.PNG)

