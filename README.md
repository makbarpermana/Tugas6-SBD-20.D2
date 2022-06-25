# Tugas6-SBD-20.D2
## Nama        : Muhammad Akbar Permana
## Kelas       : TI.D2.20
## Mata kuliah : Database System 

# 1. Masuk ke database nama_nim!
![database 6 1](https://user-images.githubusercontent.com/72698864/175764965-a1555b91-d969-4b94-bac9-38b5b6e237e5.PNG)
# 2. Lakukan proses backup & recovery dengan sql dari tugas database sebelumnya
## Proses backup database!
![database 6 2](https://user-images.githubusercontent.com/72698864/175765018-5a3706e6-695e-44a2-a4d1-26918a3757a6.PNG)
###### Jika proses backup berhasil maka akan muncul file pada directori C:\xampp\mysql\data\(akbar_312010216) nama database
![database 6 3](https://user-images.githubusercontent.com/72698864/175765265-e7fb2bbc-3835-46a8-b189-96f2656a3d4a.PNG)
### Proses pemulihan
###### data yang telah di backup dapat dikembalikan kapan saja dan sintaks yang digunakan di mysql adalah load data infile 'nama_backup_file' INTO table nama_table;
![database 6 4](https://user-images.githubusercontent.com/72698864/175765274-a0172f5a-cac5-4677-9d23-4e7e6bec1d6c.PNG)
# 3. Lakukan proses backup & recovery dengan sqldump dari database tugas sebelumnya!
![database 6 5](https://user-images.githubusercontent.com/72698864/175765314-9ddc7dd3-d51c-49f2-969c-d589bf5e4ebe.PNG)
# 4. Tuliskan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam!
###### 00**7 mysqldump -u root -p akbar_312010216>akbar_312010216_backup.sql
