# Linux Shell

#### 1. Cari dan jelaskan 3 command shell selain yang ada di ebook!
- **"df"**, fungsinya untuk menampilkan jumlah ukuran disc yang tersedia.
 Contoh : ![df](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Linux-Shell-/assets/98991080/d3043780-ed50-4f90-80e5-f7567a5e682e)
- **"ps"**, fungsinya untuk menampilkan informasi tentang proses yang berjalan. <br/>
Contoh :<br/>![ps](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Linux-Shell-/assets/98991080/f082f260-513c-4b3f-a6b3-b759ceb11dbd) 
- **"pwd"**, Print Working Directory fungsinya untuk menampilkan direktori kerja saat ini sebagai output. <br/>
 Contoh : <br/>![pwd](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Linux-Shell-/assets/98991080/6fb78ad3-48d4-411d-8713-46812150c5f8)
 
 #### 2. Perbedaan antara BASH dan Shell.
 
 - Visual antara BASH dan Shell Contoh : <br/>
 BASH : <br/>![Bash](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/4496ec33-040a-465b-bb35-9fd3e498b906) <br/> penulisan rommel@random berwarna hijau. <br/> Shell : <br/> ![Shell](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/fd04fa10-0768-42d7-8e49-2044caafdabc) <br/> Shell hanya menampilkan ($) dollar.
 - System yang ada di shell belum tentu ada di BASH, sebaliknya System yang ada di BASH, sudah pasti ada di Shell. karena version BASH yang baru. berbeda dengan halnya Shell, version lama.

#### 3. Instalasi Apache2 dan dapat diakses melalui IP Address server.

1. Sebelum menginstall Apache2 pastikan update package terlebih dahulu dengan command ``$ sudo apt update`` : <br/> ![Install apache2 1](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/eda61b70-588b-4b6d-abe5-47e0b4f881e6) 
2. lalu install apache2 packagenya, ``$ sudo apt install apache2``: <br/> ![Install apache2 2](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/8a16dcef-6914-4400-9b1e-732daaa4e477)
3. Setelah sudah terpasang apache2, web server seharusnya sudah aktif dan berjalan. Periksa dengan system init systemd untuk memastikan layanan berjalan  dengan command ``$ sudo systemctl status apache2``: <br/> ![Install apache2 3](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/a55a56e2-d6b9-4f13-9bea-7e03cb09efa3)
4. Lakukan membuka IP Address yang kalian punya melalui browser yang tersedia. Dan Installan Apache2 berhasil, Selamat!: <br/>![Install apache2 4](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/e92dd70e-2236-46a3-940c-e221b5c2db84) 













