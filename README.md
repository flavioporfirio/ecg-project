<h1 align="center">ECG - Project</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]() <br><br>
[Português](#pt)

</div>

---

# Português <a name = "pt"></a>

## 📝 Tabela de conteúdos

- [Sobre](#about_pt)
- [Iniciando a aplicação](#getting_started_pt)
- [Estrutura do projeto](#project_structure_pt)
- [Deploy](#deployment_pt)
- [Usando](#usage_pt)
- [Tecnologias](#built_using_pt)

## 🧐 Sobre <a name = "about_pt"></a>

projecto ECG realizado para a matéria de Objetos Inteligentes Conectados. Este projeto contempla a conexão entre o sensor AD8232 e ESP32, e o envio de dados através do protocolo MQTT para a plataforma Ubidots.

## Componentes utilizados

- ESP32-WROOM-32
- sensor ECG AD8232
- protoboard
- Jumpers
- Cabo USB

## 🏁 Iniciando a aplicação <a name = "getting_started_pt"></a>

Caso queira usar esse projeto como base para sua aplicação, as instruções a seguir vão te permitir ober uma cópia do projeto e rodar a aplicação localmente.

### Instalação

Para acessar o projeto, basta clonar o repositório ou realizar o download dos arquivos do projeto.<br>
Para clonar o repositório, utilize o seguinte comando no seu terminal:

- Baixe os arquivos deste repositório
- Abra o arquivo codigo.ino na ide do arduino
- Insira os valores do seu wi-fi e token ubidots

### Configuração Ubidots

Para tal deverá ser criado uma conta no ubidots. Após criar uma conta no ubidots, siga os passos a seguir:

- Na aba "Devices" crie um dispositivo chamado "esp32"
- Clique no dispositivo criado e crie uma variável chamada "sensor"

Com isso, a aplicação estará pronta para rodar. Primeiro instale os driver CH210 disponível neste repositório, a biblioteca Wifi-1.2.7 e pubsubclient-2.8.

Agora a configuração inicial está feita e pronta pra uso!

---
