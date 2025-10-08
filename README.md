# RESTful API CRUD dengan PostgreSQL
**Refa Setyagama Abdillah**
**WDUIUX Celerates - Mentor Imam Fadhilah**

## Preview Screenshots

### Struktur File
![Server Running](./assets/struktur-file.png)

### Server Running
saya menjalankan ini lewat "Run Windows + R" lalu saya ketik services.msc
![Server Running](./assets/server-running.png)

### Koneksi Database
saya tes koneksi dengan membuka psql dan menjalankan perintah psql -U postgres, terdapat nama database yaitu "kampus". lalu saya tes apakah benar-benar terkoneksi.. saya jalankan perintah \c kampus (muncul keterangan You are now connected to database "kampus" as user "postgres"). artinya sudah terkoneksi
![Server Running](./assets/koneksi.png)

### Postman Testing
**GET, Menampilkan semua data mahasiswa**
get api url http://localhost:5000/api/students, ini hasil setelah saya klik "send"
![Postman POST](./assets/get-students.png)

**GET, Menampilkan mahasiswa berdasarkan ID**
get api url id http://localhost:5000/api/students/1, ini hasil setelah saya klik "send"
![Postman POST](./assets/get-student-1.png)

**POST, Menambahkan data mahasiswa baru**
post api url id http://localhost:5000/api/students, ini hasil setelah saya klik "send"
![Postman POST](./assets/post-student.png)

**PUT, Memperbarui data mahasiswa**
put api url id http://localhost:5000/api/students/4, ini hasil setelah saya klik "send"
![Postman POST](./assets/put-student-4.png)

**DELETE, Menghapus mahasiswa**
delete api url id http://localhost:5000/api/students/3, ini hasil setelah saya klik "send"
![Postman POST](./assets/delete-student-3.png)

### PostgreSQL Table
ini adalah tabel pada tampilan pgAdmin 4. tabel ini berada di PostgreSQL/Databases/kampus/Schemas/public/Tables/students
![PostgreSQL Table](./assets/table-pgadmin.png)
