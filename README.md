# Área de trabalho

Bíblioteca de scripts para instalação de sistemas após formatação do seu computador.

Feito e validado para uso com o Linux Mint, porém deve funcionar com Ubuntu e derivados.

## Como usar

Execute:

```bash
sudo mkdir -p /opt/config-desktop
wget -O /tmp/area-de-trabalho.zip https://github.com/mateusfmello/area-de-trabalho/archive/refs/heads/main.zip
sudo unzip /tmp/area-de-trabalho.zip -d /tmp
sudo mv /tmp/area-de-trabalho-main/* /tmp/area-de-trabalho-main/.* /opt/config-desktop
sudo rm -rf /tmp/area-de-trabalho-main /tmp/area-de-trabalho.zip
sudo /opt/config-desktop/instalar
```

## +

Ficará disponível via linha de comando os comandos que estão dentro do diretório `/atualizacoes`.