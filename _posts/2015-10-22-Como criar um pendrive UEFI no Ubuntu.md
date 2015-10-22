---
layout: post
title: Como criar um pendrive UEFI no Ubutu
---

Eu havia tentado de várias formas executar esse procedimento, mas sem sucesso, usei programas como UNetBootIn, DD, GNOME Disks, o Criador de discos do Ubuntu, entre outros...

Após juntar algumas informações de tutoriais que achei espalhados pela web, consegui criar o pendrive UEFI.

O processo foi tão complicado de entender inicialmente, que resolvi fazer um vídeo explicando em detalhes.

Esse método serve pra gravar qualquer tipo de imagem, seja do Linux, Windows ou OS X.

Comandos utilizados no vídeo:

sudo apt-get install -y gparted p7zip

sudo mount /dev/sdX /mnt

sudo 7z x ubuntu-15.04-desktop-amd64.iso -o/mnt

sudo parted /dev/sdX set 1 boot on


<a href="http://www.youtube.com/watch?feature=player_embedded&v=djW5N4MYxjs" target="_blank">
<img src="http://img.youtube.com/vi/djW5N4MYxjs/0.jpg" width="100%" height="480"/></a>

<object width="560" height="315">
<param name="movie" value="https://www.youtube.com/v/djW5N4MYxjs&amp;hl=pt_BR&amp;fs=1&amp;hd=1"></param>
<param name="allowFullScreen" value="true"></param>
<param name="allowscriptaccess" value="always"></param>
<embed src="https://www.youtube.com/v/djW5N4MYxjs&amp;hl=pt_BR&amp;fs=1&amp;hd=1" allowscriptaccess="always" allowfullscreen="true" width="560" height="315"></embed>
</object>
