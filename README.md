<br clear="both">

<p align="left">‏<br>‏</p>

###

<h1 align="left">Info Semvak</h1>

###

<h3 align="left">Step 1: run the script</h3>

###

<p align="left">Instalasi Script on your server<br><br></p> 

```bash
bash <(curl -Ls https://github.com/rafaasyaa/Backup-Semvak/raw/main/semvak1.sh)
``` 

###

<h3 align="left">Step 2 : Token setting</h3>

###

<p align="left">Kemudian nanti akakn dimintai token bot, Anda harus membuat bot dari https://t.me/Botfather dan memberikan token tersebut</p>

###

<h3 align="left">Step 3: Set chat id</h3>

###

<p align="left">Kemudian nanti akakn dimintai chat id, Anda harus mengambil nya dari bot https://t.me/userinfobot dan memberikan token tersebut</p>

###

<h3 align="left">Step 4 : Caption setting</h3>

###

<p align="left">The next step asks you for a caption, which you can leave blank</p>

###

<h3 align="left">Step 5 : Cronjob setting</h3>

###

<p align="left">Langkah selanjutnya menjalankan tugas cron untuk menentukan kapan script akan melakukan pengiriman file backup kepada bot telegram.<br>yang formatnya seperti ini:<br>0 1<br>Nilai pertama yaitu 0 adalah menit, dan nilai kedua yaitu 1 adalah jam<br>Angka minimum menit adalah 0 dan maksimum 60<br>Angka minimum jam adalah 0 dan maksimum 24<br>Masukkan 0 untuk keduanya setel pencadangan setiap menit sekali<br>Dalam contoh di atas, pencadangan dilakukan setiap jam sekali<br>Jika anda ingin membuat pengaturan autobackup selama 2 jam sekali maka lakukan 0 2 lalu enter.</p>

###

<h3 align="left">Step 6 : Panel selection</h3>

###

<p align="left">Pada pilihan ini anda tinggal ketik saja ( m ) yg berarti marzban lalu enter.</p>

###

<h3 align="left">Step 7 : question of removing previous crown jobs</h3>

###

<p align="left">Kemudian ia akan menanyakan apakah Anda ingin menghapus tugas cron yang telah ditentukan sebelumnya atau tidak?<br>Masukkan (y) jika Anda ingin menghapusnya, jika tidak masukkan (n)</p>

###

<h1 align="left">Possible problems</h1>

###

<p align="left">If you have entered everything correctly, the backup file should be sent to you once, otherwise there is a problem in this process and you can raise your problem from the issues</p>

###

<h1 align="left">Help us</h1>

###

<p align="left">I used the translator and if I have gramme problem please help me to improve it<br>Also, I have tested this script only on Ubuntu and developers can help us to develop this script for other operating systems.</p>

###

Special Thanks to
- [ACLover](https://github.com/AC-Lover/backup)
- [SaputraTech](https://t.me/SaputraTech)

###

<h1 align="left">Video tutorial</h1>

https://github.com/AC-Lover/backup/assets/49290111/905c545c-caa9-4ad5-80d1-82c702fb3f2e
