---
layout: post
title: Como instalar o Slack no AviX
---
O Slack é um comunicador instantâneo para equipes, com diversos recursos adicionais através de integrações com aplicativos online para vídeo-conferência, compartilhamento de desktop, notificações de atualizações em canais de desenvolvimento, compartilhamento de arquivos, etc.

Seu uso pode trazer um grande aumento de produtividade dentro de uma empresa ou até mesmo em um pequeno grupo de trabalho.

Você pode acessar o Slack online, através do seu navegador, mas para um maior aproveitamento dos recursos disponibilizados pelo aplicativo, a instalação do cliente nativo se faz necessária.

Para instalar o aplicativo de **comunicão de equipes Slack** no **AviX**, execute os seguintes comandos no **terminal**:

(Para abrir o terminal pressione as teclas **Ctrl+Alt+T**)

`cd ~/Downloads`

`wget -c https://slack-ssb-updates.global.ssl.fastly.net/linux_releases/slack-desktop-1.2.4-amd64.deb`

`sudo dpkg -i ~/Downloads/slack-desktop-1.2.4-amd64.deb`

`sudo sed -i 's/Icon=slack/Icon=internet-chat/g' /usr/share/applications/slack.desktop`

Clique na **imagem** abaixo para uma **demonstração** da execução dos comandos.

<a href="https://asciinema.org/a/28919?autoplay=1" target="_blank"><img alt="Instalação do Slack no AviX" src="https://asciinema.org/a/28919.png" style="width: 480px;"></a>

<script type="text/javascript" src="https://asciinema.org/a/28919.js" id="asciicast-28919" async></script>
