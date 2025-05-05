<h2>Instalasi Codeigniter 4</h2>
Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual
dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual.

![image](https://github.com/user-attachments/assets/d0b1cf76-d564-4a19-ac7a-ac9aa98e962a)
  
<h2>Menjalankan CLI (Command Line Interface)</h2>
Codeigniter 4 menyediakan CLI untuk mempermudah proses development. Untuk mengakses
CLI buka terminal/command prompt.

![image](https://github.com/user-attachments/assets/4aa07ff5-7aa6-4350-b711-5157544c2cfd)

Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah: <br>
![image](https://github.com/user-attachments/assets/2b9b58ed-3cd2-42dd-9664-5d56c8e67c75)

Untuk memudahkan mengetahui jenis errornya,
maka perlu diaktifkan mode debugging dengan mengubah nilai konfigurasi pada environment
variable CI_ENVIRINMENT menjadi development.
![image](https://github.com/user-attachments/assets/f4e3184c-6aa7-4cdc-885e-237ebf39e8be)

Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable
CI_ENVIRINMENT menjadi development.
![image](https://github.com/user-attachments/assets/8f0eb008-dd23-4d6c-9d09-667cf7b6dab2)

<h2>Routing dan Controller</h2>
Router terletak pada file app/config/Routes.php

![image](https://github.com/user-attachments/assets/9aeb3920-ea69-4e15-b0b2-628d45c0f7cb)
<h2>Membuat Route Baru.</h2>
Untuk mengetahui route yang ditambahkan sudah benar, buka CLI dan jalankan perintah
berikut.

![image](https://github.com/user-attachments/assets/4dc72ae6-307c-46f0-ad30-247359ef0810)

<h2>Membuat Controller</h2>
Selanjutnya adalah membuat Controller Page. Buat file baru dengan nama page.php pada
direktori Controller kemudian isi kodenya seperti berikut.

![image](https://github.com/user-attachments/assets/975b4a8d-8a21-476c-8f15-44d054ff2a04)
