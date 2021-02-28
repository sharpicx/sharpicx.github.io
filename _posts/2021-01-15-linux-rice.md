---
layout: post
title:  "Linux Rice"
date:   2021-01-15 21:03:36 +0530
categories: unixporn bspwm linux-rice
---

akhir-akhir ini saya belom bisa nulis write-up CTF. karena waktu yang sibuk ditambah note-note ringkasan solusi writeup simpanan saya banyak yang hilang sejak ganti *Linux Distro* ke [Archlinux](https://archlinux.org). kenapa bisa hilang? karena waktu install ini OS terlalu buru-buru dengan rasa kesal yang menjadi-jadi, ribet nginstallnya.

## Apa itu **Linux Rice**
menurut saya, **Linux Rice** memiliki arti secara istilah berasal dari *Linux* atau *GNU/Linux* yaitu sebuah sistem operasi yang *open-source* alias bisa *bisa dimodifikasi dan bisa dikembangkan siapa saja*. sedangkan *Rice* sendiri memiliki arti *Nasi* atau *Beras*, maksud Rice disini sebenarnya bukan *Nasi* ataupun *Beras*. Tetapi, *RICE stands for Race Inspired Cosmetic Enhancement*. merujuk pada mobil sport buatan Asia yang memiliki banyak modifikasi dan sedikit atau tanpa modifikasi internal. 

## Komunitas Linux Ricing
[r/unixporn](https://reddit.com/r/unixporn), sebuah komunitas untuk pecinta *Unix Customization* yang membahas tentang cara bagaimana mengkustomisasi / mengkonfigurasi sebuah sistem operasi linux. 

## Properti Yang Dibutuhkan. 
* ### Operating System
ini adalah komponen yang paling penting bagi sejuta umat, yaitu, sistem operasi. tanpa sistem operasi semua tidak berjalan semesti yang diinginkan. sedangkan sistem operasi sendiri
adalah sebuah system software yang dimana untuk mengatur hardware dari komputer. dan juga sistem operasi yang digunakan adalah *Linux*, contohnya, [Arch Linux](https://archlinux.org), [Debian](https://debian.org), [Void Linux](https://voidlinux.org), [Gentoo](https://gentoo.org).

* ### Window Manager
adalah sebuah sistem software yang dimana untuk mengatur tampilan dan tata letak dari *window* dalam sistem *Graphical User Interface* / *GUI*. **Window Manager** sendiri dibuat atau didesain untuk membantu menyediakan sebuah *desktop environment*. misalnya seperti, *i3-gaps*, *bspwm*, *dwm*, *awesome*, *openbox*, *fluxbox*, dll. 

* ### Panel / Bar
sebuah program yang digunakan untuk menampilkan status, keadaan dan informasi tentang *Network*, *Persentase Baterai*, *Memory*, *Volume Suara*, *Kecepatan Internet*, *Kalender*, dll. contohnya, [polybar](https://github.com/polybar/polybar), [lemonbar](https://github.com/LemonBoy/bar).

* ### App Launcher
sebuah program yang digunakan untuk menjalankan suatu program selain menggunakan Terminal Emulator. contohnya, [rofi](https://github.com/davatorium/rofi).

* ### Display Manager
adalah program yang digunakan untuk masuk ke layar GUI untuk desktop sistem operasi linux. Setelah masuk ke Graphical User Interface, kendali sepenuhnya diberikan kepada WM. DM menyediakan fitur seperti memilih sesi DE/WM yang akan digunakan dan fitur reboot, halt, suspend. contohnya, [LightDM](https://github.com/canonical/lightdm), [LXDM](http://www.linuxfromscratch.org/blfs/view/8.4/x/lxdm.html).

* ### Window Compositor
suatu program yang berfungsi untuk mengatur transparansi, animasi, bayangan, dll. pada window manager. contohnya [compton](https://github.com/chjj/compton) atau [picom](https://github.com/yshui/picom), dll.

* ### Screen Locker
sebuah program yang digunakan sebagai tampilan lockscreen pada window manager. contohnya, [betterlockscreen](https://github.com/pavanjadhaw/betterlockscreen), [i3lock](https://i3wm.org/i3lock/), dll.

* ### Terminal Emulator
adalah program yang digunakan alias berfungsi sebagai sarana interaksi dengan *Unix-Shell* seperti menjalankan program, mengirim perintah, mengatur sistem, dll. contohnya, [termite](https://github.com/thestinger/termite), [simple-terminal](https://st.suckless.org/), [kitty](https://sw.kovidgoyal.net/kitty/), dan sebagainya.

* ### Notification-Daemon
dan yang terakhir adalah sebuah program yang digunakan atau berfungsi sebagai penampil *pop-up*
notifikasi. contoh, [dunst](https://dunst-project.org/), dan masih banyak lagi.

## Pendapat Saya Tentang WM / DE
kenapa saya lebih memilih **WM (Window Manager)** timbang **DE (Desktop Environment)**? 
* pertama, menggunakan *DE* sama saja dengan menggunakan **Windows** tidak ada sensasi yang menarik perhatian, malah yang ada tambah bosan dan tidak terlihat keren.
* kedua, *DE* itu lebih Instan dan tidak bisa dimodifkasi untuk lebih ringan atau sesuai selera.
* ketiga, *DE* itu entah kenapa dapat mengembalikkan ingatan saya kepada sistem operasi milik Microsoft.

dan juga tentang *WM* yang saya sukai yaitu berbasis *tiling window* seperti, *i3, bspwm, dwm*, dll. kenapa? karena keseruan yang didapat itu masuk. dan juga menurut saya menggunakan WM itu mempunyai banyak manfaat diantaranya,
* Menambah wawasan alias ingin mendalami pengetahuan tentang sistem operasi linux.
* Kebebasan untuk memilih komponen/properti yang dibutuhkan.
* Bisa memamerkan hasil jerih payah sendiri dengan menggunakan **Archlinux + WM**.
* Menambah bahasa pemrograman *(scripting)* seperti, **Shell**, **Python**, **Rust**.
* Lebih ringan ketimbang DE yang instan.
* User-friendly alias nyaman digunakan.

## Contoh Linux Rice Milik Saya
walaupun ukuran resolusi kecil *1366x768* dengan spec laptop seadanya, tp saya sudah bersyukur tidak memakai lagi sistem operasi milik microsoft yang penuh bacotan di laptop saya ini. semoga dengan adanya blog ini, di masa depan ketika sudah memiliki setup-setup yang saya butuh sekaligus inginkan bisa tercapai secepatnya.

![gif](https://s4.gifyu.com/images/ezgif-6-caef54386e61.gif)<br/>
*(screenshot: 28/02/2021)*

* OS: [Arch Linux](https://archlinux.org)
* Panel/Bar: [Polybar](https://github.com/polybar/polybar)
* App Launcher: [Rofi](https://github.com/davatorium/rofi) / [Dmenu](http://tools.suckless.org/dmenu/)
* WM: [Bspwm](https://github.com/baskerville/bspwm)
* Display Manager: [LightDM](https://github.com/canonical/lightdm)
* Screen Locker: [betterlockscreen](https://github.com/pavanjadhaw/betterlockscreen)
* Terminal: [termite](https://github.com/thestinger/termite/)
* Window Compositor: [picom](https://github.com/yshui/picom)
* Notification-Daemon: [dunst](https://dunst-project.org/)

## Referensi
* <https://www.urbandictionary.com/define.php?term=Rice%20car>
* <https://en.wikipedia.org/wiki/Operating_system>
* <https://reddit.com/r/unixporn>