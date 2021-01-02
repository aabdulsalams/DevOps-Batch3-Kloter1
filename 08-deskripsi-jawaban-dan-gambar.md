# JAWABAN NO 8
Disini saya menggunakan docker agar memudahkan ketika ingin menambahkan app baru dan tanpa menginstall app yang tidak dibutuhkan dalam proses membuat webserver. Adapun langkah-langkahnya sebagai berikut:

1. Menyiapkan file docker-compose.yml

![DevOps Flow](/folder-images-jawaban/09.png)

2. Menyiapkan Dockerfile untuk nginx

![DevOps Flow](/folder-images-jawaban/10.png)

3. Menyiapkan index.html untuk page yang akan ditampilkan

![DevOps Flow](/folder-images-jawaban/11.png)

4. Menambahkan dns secara static pada /etc/hosts

![DevOps Flow](/folder-images-jawaban/12.png)

5. “Docker-compose up” untuk menjalankan web server

![DevOps Flow](/folder-images-jawaban/13.png)

6. Menguji coba dengan menggunakan links(web browser cli), dengan perintah 	"links dumbways-abdulsalam.xyz:2727"

![DevOps Flow](/folder-images-jawaban/14.png)