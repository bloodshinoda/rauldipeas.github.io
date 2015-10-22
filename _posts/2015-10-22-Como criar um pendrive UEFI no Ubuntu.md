---
published: false
---


## Como criar um pendrive UEFI no Ubuntu

Eu havia tentado de várias formas executar esse procedimento, mas sem sucesso, usei programas como UNetBootIn, DD, GNOME Disks, o Criador de discos do Ubuntu, entre outros...

Após juntar algumas informações de tutoriais que achei espalhados pela web, consegui criar o pendrive UEFI.

O processo foi tão complicado de entender inicialmente, que resolvi fazer um vídeo explicando em detalhes.

Esse método serve pra gravar qualquer tipo de imagem, seja do Linux, Windows ou OS X.

Comandos utilizados no vídeo:

sudo apt-get install -y gparted p7zip

sudo mount /dev/sdX /mnt

sudo 7z x ubuntu-15.04-desktop-amd64.iso -o/mnt

sudo parted /dev/sdX set 1 boot on

https://www.youtube.com/embed/djW5N4MYxjs
