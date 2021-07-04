# tugas-10-SBD-19.B1

tugas basis data backup restore :

1. masuk db :

![image](https://user-images.githubusercontent.com/82306673/124390801-5e3d6400-dd17-11eb-8929-15136bd36a03.png)

2. backup restore dgn perintah sql :

![image](https://user-images.githubusercontent.com/82306673/124390850-a6f51d00-dd17-11eb-850d-b78a4a39d901.png)

hasil backup,an tsb :

![image](https://user-images.githubusercontent.com/82306673/124390882-d0ae4400-dd17-11eb-9a45-3e740b262c66.png)

3. backup dgn mysqldump :

![image](https://user-images.githubusercontent.com/82306673/124391078-04d63480-dd19-11eb-8d32-07ffc6bbcbae.png)

4. script cron job :

<p> 59 23 * * 7 mysqldump -uroot -p kapi_311910766 > kapi_backup_db_backup.sql </p>
