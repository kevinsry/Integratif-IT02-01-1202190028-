# Integratif-IT02-01-1202190028

**Kevin Surya Diansyah**
**1202190028**

# TAHAP 1 - Laravel #
---


```markdown
1.Buka Cmd
```

```markdown
2.Lalu Ketikan \xampp\htdocs
```
![1](https://user-images.githubusercontent.com/89094789/173069065-3e192585-6897-488c-9129-c1b44d7a8a7a.PNG)

```markdown
3.Langkah Berikutnya 
```

**Ketikan (composer create-project --prefer-dist laravel/laravel nama_projectmu)**

![2](https://user-images.githubusercontent.com/89094789/173069422-c3b0d7d6-24e2-4fe7-b99a-27b98a66b60c.PNG)

```markdown
4.cek Installan Di Browser 
```

![3](https://user-images.githubusercontent.com/89094789/173069623-08cc8d0a-8bef-4d2b-bb7d-bad5a151c355.PNG)

```markdown
4.Selanjutnya Ketikan "CD kevinnnn
```

![4](https://user-images.githubusercontent.com/89094789/173069922-35415cbf-9345-4430-b45f-447641937d74.PNG)


```markdown
5.Salin link yang telah disediakan oleh Laravel. "http://127.0.0.1:8000/"
```


![5](https://user-images.githubusercontent.com/89094789/173070358-069956f1-31d4-43c8-9b04-54624c847bad.PNG)


# TAHAP 2 - RSS #
---

• Mengubah DB_DATABASE di .env sesuai dengan nama database yang dibuat di phpmyadmin

• Buatlah 2 table rrs dan news dengan fitur migrations menggunakan syntax

![Screenshot (6)](https://user-images.githubusercontent.com/89094789/175805194-7864424c-c5a4-4ea5-a692-b81dc8e92557.png)


```
php artisan make:migration create_rss_table
php artisan make:migration create_news_table
```

• Tambahkan kolom name dan url pada table rss

![Screenshot (13)](https://user-images.githubusercontent.com/89094789/175805269-1f95c522-d46f-4d1e-a3e4-5a34b60a4cce.png)

![Screenshot (10)](https://user-images.githubusercontent.com/89094789/175805295-9b23e308-1916-4483-8a1c-5fd767c61527.png)

• Untuk menjalankan migrasi yang dibuat jalankan perintah diterminal , lalu cek database
php artisan migrate

![Screenshot (12)](https://user-images.githubusercontent.com/89094789/175805324-12f8a64f-122c-48e6-b5c3-96acb39034e1.png)

• Edit file Rss.php, RssSeeder.php serta DatabaseSeeder.php 

![Screenshot (16)](https://user-images.githubusercontent.com/89094789/175805399-cc28f2fd-a614-41f2-bf78-2c8ec0a581d7.png)

![Screenshot (14)](https://user-images.githubusercontent.com/89094789/175805430-59ada4f6-c31e-45fd-805d-314cf2b87aed.png)

![Screenshot (15)](https://user-images.githubusercontent.com/89094789/175805446-c63e8369-3147-47fb-90ee-0b8fe1addbb8.png)


•  Kemudian cek koneksi , dengan syntax
![Screenshot (19)](https://user-images.githubusercontent.com/89094789/175805477-32c2ff4d-9117-470e-bc09-c62b55081bed.png)

![Screenshot (20)](https://user-images.githubusercontent.com/89094789/175805514-3a51c357-d482-408b-83d0-82f8534e568c.png)

![Screenshot (21)](https://user-images.githubusercontent.com/89094789/175805522-fee221f1-b0d0-489d-92b2-7dfcae6aa3bf.png)

![Screenshot (28)](https://user-images.githubusercontent.com/89094789/175805550-6e3c7640-5fd6-4a3f-8aea-f90ea3d2ff96.png)

• Cek dilokal host 
http://127.0.0.1:8000/aggregrate/1

![Screenshot (35)](https://user-images.githubusercontent.com/89094789/175805645-77ead77f-df91-48c4-aa47-e3461e3d78e0.png)

http://127.0.0.1:8000/aggregrate/4

![Screenshot (32)](https://user-images.githubusercontent.com/89094789/175805663-d4a1da86-825a-4b57-8779-723c74da862c.png)


http://127.0.0.1:8000/aggregrate/6

![Screenshot (33)](https://user-images.githubusercontent.com/89094789/175805665-888e9cf4-067a-422a-9a08-9df768d20319.png)

![Screenshot (34)](https://user-images.githubusercontent.com/89094789/175805702-bb31190c-28d4-4447-a2a7-177c6274165f.png)







