API CONTRACT

Kelompok 3 - Course Service

1. Informasi Layanan

* Nama Layanan: Course Service
* Kelompok: 3
* Port: 8103
* Base URL: http://127.0.0.1:8103

2. Daftar Endpoint

Method	Endpoint	Fungsi
GET	/health	Memeriksa kondisi layanan
GET	/api/courses	Menampilkan daftar mata kuliah
POST	/api/courses	Menambahkan mata kuliah
DELETE	/api/courses/{id}	Menghapus mata kuliah berdasarkan ID

3. Contoh Request Menambahkan Mata Kuliah

Method: POST

Endpoint: /api/courses

Body:
{
“name”: “Pemrograman Web”,
“description”: “Mata kuliah dasar pemrograman website”
}

4. Contoh Respons Berhasil

{
“success”: true,
“message”: “Mata kuliah berhasil ditambahkan”,
“data”: {
“id”: 1,
“name”: “Pemrograman Web”,
“description”: “Mata kuliah dasar pemrograman website”
}
}

5. Teknologi yang Digunakan

* PHP
* Visual Studio Code
* XAMPP
* JSON
* Postman

6. Keterangan

Course Service merupakan layanan untuk mengelola data mata kuliah dalam sistem Mini LMS Terdistribusi.