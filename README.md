# shot-magick
Menghias hasil screenshot maupun gambar lainnya.
Katanya biar mirip hasil screenshot MacOS =)
### Light Mode
<img src="https://github.com/annzc/shot-magick/raw/main/img/light-mode.png" />

### Dark Mode
<img src="https://github.com/annzc/shot-magick/raw/main/img/dark-mode.png" />

## instalasi
```bash
pkg up -y && pkg i imagemagick -y
```
```bash
curl https://raw.githubusercontent.com/annzc/shot-magick/main/shot-magick > shot-magick
```
```bash
chmod +x shot-magick
```
```bash
./shot-magic
# atau
bash shot-magick
```

## NOTE
`shot-magick beta version 0.1`<br>
Beberapa fitur terutama `-usertag` masih tidak stabil(!)<br><br>
Cara lain untuk menggunakan fitur `-usertag` adalah dengan membuat file `.usertag` di dalam direktori yang sama.<br><br>
Contoh:<br>
```sh
echo "Shooter: @akugans $(date)" > .usertag
# output
: Shooter: @akugans Sun Jun 27 06:42:19 WIB 2021
```
dan jangan lupa sertakan argumen `-usertag` untuk menggunakan tag buatan sendiri tadi.<br><br>
Hapus file `.usertag` untuk menggunakan tag input mode.<br>
Atau edit sendiri variabel `$_DEFAULT_TAG` yang ada di dalam script.

ciao!

## automation (coming soon?)
Untuk automasi, silahkan pakai `while :` / `while true` statement di dalam direktori dimana screenshot disimpan.

<img src="https://raw.githubusercontent.com/annzc/shot-magick/main/img/automasi.png" />

## ingfo
MIT licence
