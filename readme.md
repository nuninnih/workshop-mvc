# MVC ASYNC

## Buatlah program asyncronous menggunakan MVC Pattern

### 1. help : Tampilkan command yang bisa dipakai oleh User saat me
```js
node app.js help
node app.js listOrder
node app.js addOrder <name> <item> <price>
node app.js findOrderById <id>
node app.js deleteOrder <id>
node app.js updateOrder <id> <item> <price>
```

### 2. listOrder : Tampilkan semua order yang ada pada data json dalam bentuk tabel
Pastikan semua data yang keluar dari model harus sudah terinstance.

### 3. addOrder : Tambahkan data yang diinputkan oleh user melalui terminal ke dalam file json
Bila sudah berhasil, maka tampilkan pesan `<name> sudah berhasil membeli <item> seharga <price>`

### 4. findOrderById : Tampilkan data dari file json dimana yang mana id-nya harus sesuai dengan input User
Output : `Order dengan id <id> : Item <item> dengan harga <price> dibeli oleh <name>`

### 5. deleteOrder : Hapus data dari json bila id-nya sama dengan yang diinput oleh User
Output : `Item <item> dengan harga <price> yang dibeli oleh <name> pada id <id> telah dihapus`

### 6. updateOrder : Update data di json dengan data yang diinput oleh user bila id-nya sesuai dengan inputan User
Output : `Order dengan id <id> telah diupdate`
