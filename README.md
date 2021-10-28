<div align="center">
<img src="https://telegra.ph/file/9b873234a9cc47a5916ae.jpg" alt="NinoBot" width="500" />

# Simple-bot

> Simple-bot adalah script ori dari Nino dan Ikyy yang saya ubah sedemikian rupa.
>
>

<h3 align="center">Made with ❤️ by</h3>
<p align="center">
  <a href="https://github.com/Nino-chan02"><img src="https://avatars.githubusercontent.com/u/81684610?s=400&u=25765902db0b709938966cf4127ac11af5eafb5d&v=4" height="128" width="128" /></a>
</p>

<p align="center">
  <a href="https://github.com/Nino-chan02"><img title="Author" src="https://img.shields.io/badge/Author-Marz-purple.svg?style=for-the-badge&logo=github" /></a>
</p>
<p align="center">
<a href="https://github.com/Nino-chan02/followers"><img title="Followers" src="https://img.shields.io/github/followers/Nino-chan02?color=blue&style=flat-square"></a>
<a href="https://github.com/Nino-chan02/megumikato2/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/Nino-chan02/NinoWangy?color=red&style=flat-square"></a>
<a href="https://github.com/Nino-chan02/megumikato2/network/members"><img title="Forks" src="https://img.shields.io/github/forks/Nino-chan02/NinoWangy?color=red&style=flat-square"></a>
<a href="https://github.com/Nino-chan02/megumikato2/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/Nino-chan02/NinoWangy?label=Watchers&color=blue&style=flat-square"></a>
</p>

<p align="center">
  <a href="https://github.com/Nino-chan02/NinoWangy#requirements">Requirements</a> •
  <a href="https://github.com/Nino-chan02/NinoWangy#instalasi">Installation</a> •
  <a href="https://github.com/Nino-chan02/NinoWangy#features">Features</a> •
  <a href="https://github.com/Nino-chan02/NinoWangy#thanks-to">Thanks to</a>
</p>
</div>


---



# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases) (for sticker command)
* [Libwebp](https://developers.google.com/speed/webp/download) (for sticker wm)
* Any text editor

# Instalasi
## For Windows
```bash
git clone https://github.com/Nando35/Simple-bot
cd Simple-bot
npm install
node main
```
## For Termux
```bash
termux-setup-storage
pkg update && pkg upgrade
pkg install nodejs git ffmpeg libwebp 
git clone https://github.com/Nando35/Simple-bot
cd Simple-bot
npm install
node main
```

## Installing the FFmpeg for Windows
* Unduh salah satu versi FFmpeg yang tersedia dengan mengklik [di sini](https://github.com/BtbN/FFmpeg-Builds/releases).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `ffmpeg`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
> ffmpeg -version
```


## Installing the libwebp for Windows
* Unduh salah satu versi libwebp yang tersedia dengan mengklik [di sini](https://developers.google.com/speed/webp/download).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `libwebp`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
setx /m PATH "C:\libwebp\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal libwebp, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
webpmux -version
```

# Features
- Cek [disini](https://github.com/Nando35/Simple-bot/blob/main/message/help.js)

# TERIMA KASIH KEPADA
* [`Baileys`](https://github.com/adiwajshing/Baileys)
* [`Arip`](https://github.com/Akkun3704)
* [`MhankBarBar`](https://github.com/MhankBarBar)
* [`Aqulzz`](https://github.com/zennn08)
* [`Hexa`](https://github.com/Hexagonz)
* [`Slavyan`](https://github.com/SlavyanDesu)
* [`Galang`](https://github.com/Zobin33)
* [`Franky`](https://github.com/Frankysolo)
* [`Nando`](https://github.com/Nando35)
