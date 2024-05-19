<h1 align="center">ECG - Project</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]() <br><br>
[Português](#pt)

</div>

---

# Português <a name = "pt"></a>

## 📝 Tabela de conteúdos

- [Sobre](#about_pt)
- [Hardware](#hardware)
- [Iniciando a aplicação](#getting_started_pt)
- [Documentação](#documentacao)

## 🧐 Sobre <a name = "about_pt"></a>

projecto ECG realizado para a matéria de Objetos Inteligentes Conectados. Este projeto contempla a conexão entre o sensor AD8232 e ESP32, e o envio de dados através do protocolo MQTT para a plataforma Ubidots. Esta plataforma recebe os dados através do MQTT e armazena eles, podendo ser consultado posteriormente.

## Hardware <a name = "hardware"></a>

- ESP32-WROOM-32: é um chip, microcontrolador, de baixo custo criado pela Espressif Systems que contém Wi-fi e bluetooth integrados, se tornando hardware perfeito para prototipagem e sistemas embarcados. 
  
- sensor ECG AD8232: conhecido como sensor ECG, possibilita a medição da atividade cardíaca de determinado usuário, entretanto este dispositivo é voltado para prototipagem e experimentação e não para fins médicos. Ele geralmente é utilizado para prototipagem de projetos relacionados a saúde, e normalmente se conecta com um microcontrolador, como Arduino ou ESP32.

- Arduino IDE: É o ambiente de desenvolvimento para programar as placas Arduino. Um software gratuito que permite você escrever e gravar os códigos no microcontrolador, através da linguagem de programação C/C++. 

## 🏁 Iniciando a aplicação <a name = "getting_started_pt"></a>

Caso queira usar esse projeto como base para sua aplicação, as instruções a seguir vão te permitir ober uma cópia do projeto e rodar a aplicação localmente.

## Instalação

Para acessar o projeto, basta clonar o repositório ou realizar o download dos arquivos do projeto.<br>
Para clonar o repositório, utilize o seguinte comando no seu terminal:

- Baixe os arquivos deste repositório
- Abra o arquivo codigo.ino na ide do arduino
- Insira os valores do seu wi-fi e token ubidots

### Configuração e instalação do ESP32 na IDE do arduino

Na IDE do Arduino siga os seguintes passos:
- Arquivo > Preferências > URLs Adicionais de Gerenciadores de Placas
- Insira a URL para o pacote esp32: https://dl.espressif.com/dl/package_esp32_index.json
- Clique em OK para salvar

Para instalar o ESP32 basta ir em na IDE do arduino em Ferramentas > Placa > Gerenciador de Placas > digitar ESP32 na barra de pesquisa. Encontrar o pacote chamado "esp32 by Espressif Systems" clicar em instalar.
Para completar selecione a placa e uma porta COM associada ao ESP32

### Configuração Ubidots

Para tal deverá ser criado uma conta no ubidots. Após criar uma conta no ubidots, siga os passos a seguir:

- Na aba "Devices" crie um dispositivo chamado "esp32"
- Clique no dispositivo criado e crie uma variável chamada "sensor"

Com isso, a aplicação estará pronta para rodar. Primeiro instale os driver CH210 disponível neste repositório, a biblioteca Wifi-1.2.7 e pubsubclient-2.8.

Agora a configuração inicial está feita e pronta pra uso!

## Documentação <a name = "documentacao"></a>

- [IDE Arduino](https://www.arduino.cc/reference/pt/)
- [ESP32-WROOM-32](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html)
- [Sensor AD8232](https://www.analog.com/media/en/technical-documentation/data-sheets/ad8232.pdf)
- [Protocolo MQTT](https://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.pdf)

---
