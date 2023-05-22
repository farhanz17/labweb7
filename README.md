# konfigurasi untuk penggunaan codeigniter 4

## Profil
| #               | My Data           |
| --------------- | ----------------- |
| **Nama**        | Muhammad Farhan   |
| **NIM**         | 312110128         |
| **Kelas**       | TI.21.A.1         |
| **Mata Kuliah** | Pemrograman Web 2 |
---

1. download codeigniter4 yang bisa didownload pada codeigniter.com

2. buat folder **lab11_ci** pada htdocs lalu masukkan file codeigniter yang sudah di ekstrak

3. rename folder codeigniter yang awalnya **codeigniter4-framework-v4....** menjadi **ci4**

4. pada folder ci4 cari file bernama **env** kemudian rename menjadi **.env**

5. buka file .env kemudian ubah **CI_ENVIRONMENT = production** menjadi **CI_ENVIRONMENT = development** kemudian save

# konfigurasi xampp untuk mengakses codeigniter 4

---

1. buka xampp lalu pilih config pada apache kemudian pilih php.ini

![labweb7-1](https://github.com/farhanz17/labweb7/assets/92637117/ffd3103e-590b-4ffd-9660-10e2b450d338)

2. cari **;extension=intl** kemudian hapus tanda titik koma

![labweb7-2](https://github.com/farhanz17/labweb7/assets/92637117/e73dd711-9d1c-4075-ae5b-7cccd734a410)

3. nyalakan apache dan buka shell pada xampp kemudian masuk ke directory ci4 yang terdapat didalam folder lab11_ci dalam htdocs xampp. Setelah itu coba tes dengan mengetik **php spark**

![labweb7-3](https://github.com/farhanz17/labweb7/assets/92637117/f8f611dd-1217-4f5c-90c3-56505ed2eb4e)

apabila muncul output seperti dibawah ini, maka lanjutkan dengan mengetik **php spark serve** untuk mengakses codeigniter kita

![labweb7-4](https://github.com/farhanz17/labweb7/assets/92637117/8d6cabfd-b70e-4e18-a8a6-04dbeb545c3d)

4. setelah itu akan muncul code seperti ini yang bisa kita gunakan untuk mengakses codeigniter kita

![labweb7-5](https://github.com/farhanz17/labweb7/assets/92637117/04ee554b-4c83-407b-af9b-1f5c440dc0f4)

# output

![lanweb7-6](https://github.com/farhanz17/labweb7/assets/92637117/e1910aba-46fe-4f22-9fcc-784236075ce0)
