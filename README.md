# belajarGitHub

## Halo semua warga ITEC! Jika kalian membuka ini dalam VSCode, gunakan shortcut `CTRL + Shift + V` untuk mempermudah membacanya.
### Pastikan kalian sudah mendownload [`Git`](https://git-scm.com/downloads) untuk menjalankannya dan gunakan terminal dari bash (nama lain dari terminal git)

Jadi kita akan gunakan repo ini sebagai tes buat nyoba fitur [fork repo](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) dari github. Kalian bisa membaca tutorialnya dari acnhor tersebut jika ingin membacanya secara manual dan lebih rinci.

### Setelah fork repo dibuat

Pastikan fork repomu telah dibuat dahulu, jika sudah maka kita buka dahulu fork reponya. Kita akan lakukan `git clone` alias menyalin repo tersebut ke komputer kita. URL untuk git clone bisa ditemukan di tombol hijau yang bertuliskan `Code` di atas fork kamu.

Setelah cloning selesai dilakukan, buatlah folder baru sesuai nama atau nickname kalian di dalam folder `belajarGitHub`. Pastikan kita mengakses folder `belajarGitHub` terlebih dahulu baik secara menyeluruh atau terminalnya saja. Hal tersebut penting karena kita akan menggunakannya untuk menjalankan perintah-perintah git. Dalam folder kalian masing masing, bisa diisi dengan `html` biasa saja untuk mencoba, kalian boleh styling juga sebebas kalian.

Jika sudah puas dengan website atau hal yang di tambahkan, lakukan commit lalu push ke repo fork kamu:

```bash
git commit -am "commit pertama dari [nama kamu] "
git push -u origin main
```

Setelah berhasil di push ke repo fork kamu, kalian bisa melihat perubahan kamu di repo fork kamu. Lalu kalian pergi ke bagian pull request dan buatlah `New pull request` dan pastikan informasi yang ditulis deskriptif yaa!

### Setelah selesai maka selamat kamu telah berhasil membuat pull request ke repo asli!