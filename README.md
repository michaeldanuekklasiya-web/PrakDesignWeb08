# PrakDesignWeb08

## Alur logika pengisian formulir : 
Pada HTML Formulir: 
•	HTML menyediakan formulir dengan elemen-elemen input seperti teks, email, password, dan tanggal lahir.
•	Setiap input memiliki atribut id yang unik, memungkinkan JavaScript untuk merujuk pada data javascript

## Memiliki JavaScript Event Listener:
•	JavaScript menambahkan event listener pada formulir untuk menanggapi pengajuan formulir.
•	Ketika formulir diajukan, fungsi event listener dijalankan.

## Memiliki Validasi Input:
•	Dalam fungsi event listener, nilai-nilai input dari formulir diambil.
•	Dilakukan serangkaian validasi, seperti memastikan bahwa semua input yang diperlukan diisi dengan benar.

## Ajax Request ke Server:
•	jika semua validasi berhasil, fungsi sendDataToServer() dipanggil.
•	Fungsi ini mengambil nilai-nilai input dan mengirimkannya ke server menggunakan teknik Ajax.
