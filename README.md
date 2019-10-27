CARA MEMBUAT REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB SERTA CARA MEMBUAT FILE README.md

Yang kalian butuhkan:

1. Akun github
2. software atau program git

DAftar Akun Github

1. buat akun github dengan cara membuka laman https://github.com
2. masukan username, Email dan password yang akan kalian gunakan pada akun github kalian.

![Screenshot (12)](https://user-images.githubusercontent.com/57041175/67627910-b1e38300-f88f-11e9-9983-d9dc21fdc5a1.png)

3. lalu buka email yang anda masukan tadi dan lakukan verifikasi.

![Screenshot (51)](https://user-images.githubusercontent.com/57041175/67628264-c24a2c80-f894-11e9-99b5-88e9a5416030.png)

4.setelah melakukan verifikasi, kalian akan dialihkan ke laman github untuk selanjutnya membuat repository baru, lalu masukan nama repository kalian dan klik "create repository".

![Screenshot (38)](https://user-images.githubusercontent.com/57041175/67628301-7946a800-f895-11e9-98f4-14d895f30647.png)

5. seperti inilah tampilan repository yang baru.

![Screenshot (39)](https://user-images.githubusercontent.com/57041175/67628325-e6f2d400-f895-11e9-8840-6bd5c389a46c.png)

DOWNLOAD SOFTWARE GIT

1. Untuk mendownload software git kita harus masuk ke laman https://git-scm.com

![Screenshot (15)](https://user-images.githubusercontent.com/57041175/67628352-81ebae00-f896-11e9-9e3d-66267a7b9152.png)

2.pilih download dan sesuaikan dengan operating system dan spesifikasi laptop atau komputer kalian.

![Screenshot (16)](https://user-images.githubusercontent.com/57041175/67628358-a47dc700-f896-11e9-94d0-44c596faaf74.png)

3. lakukan instalasi git pada laptop atau komputer kalian.

![Screenshot (17)](https://user-images.githubusercontent.com/57041175/67628367-dc850a00-f896-11e9-9674-999805398495.png)

4. pastikan software atau program git sudah terinstall 100%.

![Screenshot (30)](https://user-images.githubusercontent.com/57041175/67628384-3e457400-f897-11e9-8574-6cd106bd7dd4.png)

5. pastikan program git sudah dapat digunakan diperangkat kalian dengan cara membuka command prompt lalu ketik "git --version" jika muncul berarti git sudah dapat digunakan.

![Screenshot (31)](https://user-images.githubusercontent.com/57041175/67628421-84023c80-f897-11e9-9c53-aedaf284eca7.png)


MEMBUAT REPOSITIRY LOKAL DAN MEMBUAT FILE README.md

1. buatlah "folder" baru di directory kalian lalu "klik kanan" pada folder tersebut dan pilih "Git Basg Here"

![Screenshot (41)](https://user-images.githubusercontent.com/57041175/67628437-de030200-f897-11e9-9507-1efe43338850.png)

2. lalu konfigurasi dengan menggunakan perintah "git config --global user.name"nama_user" dan "git config --global user.email"email_user"

![Screenshot (42)](https://user-images.githubusercontent.com/57041175/67628454-2c180580-f898-11e9-981b-1e266dda39b4.png)

3. buatlah directory baru dengan menggunakan perintah "mkdir latihan1" dan pindah ke directory tersebut dengan menggunakan perintah "cd latihan1"

![Screenshot (43)](https://user-images.githubusercontent.com/57041175/67628462-62558500-f898-11e9-802d-64f367554780.png)

4. buatlah file kosong berformat git dengan cara menjalankan perintah "git init"

![Screenshot (44)](https://user-images.githubusercontent.com/57041175/67628474-99c43180-f898-11e9-88bd-0a360257145b.png)

5. buat file README.md dengan menggunakan perintah echo "#latihanpython1">>README.md"

![Screenshot (45)](https://user-images.githubusercontent.com/57041175/67628484-ddb73680-f898-11e9-9f34-9886e259e889.png)

6. untuk membuat file, gunakan perintah ls-l

![Screenshot (46)](https://user-images.githubusercontent.com/57041175/67628501-1e16b480-f899-11e9-9742-d0fe0964f4ba.png)

7. masukan file README.md ke repository lokal dengan menggunakan perintah "git add README.md"

![Screenshot (47)](https://user-images.githubusercontent.com/57041175/67628540-b44ada80-f899-11e9-818d-e1c9f329d0db.png)

8. simpan perubahan ke dalam database repositiry dengan menggunakan perintah "git commit -m"

![Screenshot (48)](https://user-images.githubusercontent.com/57041175/67628560-f70cb280-f899-11e9-8f20-f8d1f03d641b.png)

9. masuk ke laman github dan buka URL yang sudah dibuat di repositiry github, gunakan perintah "git remote add origin [URL]", ccontoh: git remote add origin https://github.com/adindaputrimelani/LATIHAN-PYTHON.git

![Screenshot (50)](https://user-images.githubusercontent.com/57041175/67628583-64204800-f89a-11e9-844c-a6f886dabb43.png)

10. kirim perubahan local repository ke github dengan menggunakan perintah "git push -u origin master"

![Screenshot (50)](https://user-images.githubusercontent.com/57041175/67628596-c416ee80-f89a-11e9-9128-8abb7c302709.png)

11. cek kembali repository dilaman github.
^. 
