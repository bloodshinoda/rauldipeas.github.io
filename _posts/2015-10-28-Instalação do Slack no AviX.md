---
published: false
---

Para instalar o aplicativo de **comunicão de equipes Slack** no **AviX**, execute os seguintes comandos no **terminal**:
(Para abrir o terminal pressione as teclas **Ctrl+Alt+T**)

`cd ~/Downloads`

`wget -c https://slack-ssb-updates.global.ssl.fastly.net/linux_releases/slack-desktop-1.2.4-amd64.deb`

`sudo dpkg -i ~/Downloads/slack-desktop-1.2.4-amd64.deb`

`sudo sed -i 's/Icon=slack/Icon=internet-chat/g' /usr/share/applications/slack.desktop`

<a href="https://asciinema.org/a/28919?autoplay=1" target="_blank"><img alt="Instalação do Slack no AviX" src="https://asciinema.org/a/28919.png" style="width: 480px;"></a>