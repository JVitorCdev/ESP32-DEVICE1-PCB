Projeto de Placa com ESP32 e Sensor SPI

## - Descrição

Este projeto consiste no desenvolvimento de uma placa eletrônica utilizando a plataforma **Eagle**, que integra uma placa de desenvolvimento **ESP32 DevKit V1** com um dispositivo externo denominado **DEVICE1**, que foi criado manualmente através das ferramentas de criação de componentes no **Eagle**.

O dispositivo simula um sensor que se comunica com o ESP32 através do protocolo **SPI**, baseado no funcionamento de sensores reais como o BMP280.

## - Conexões

As conexões entre o ESP32 e o DEVICE1 foram feitas utilizando a interface SPI, com os seguintes pinos:

| ESP32            | DEVICE1 | Função         |
|------------------|---------|----------------|
| 3V3 (VCC)        | VCC     | Alimentação    |
| GND              | GND     | Terra          |
| D23 (MOSI)       | SDI     | Dados para o dispositivo |
| D19 (MISO)       | SDO     | Dados do dispositivo     |
| D18 (SCK)        | SCK     | Clock          |
| D5  (CS)         | CS      | Chip Select    |

## - Arquivos do Projeto

O repositório contém:
- Arquivos do Eagle (.sch, .brd, .lbr)
- Esquemático do projeto
- Layout da placa PCB
- Biblioteca personalizada do componente **DEVICE1**

## - Licença

Este projeto é de uso acadêmico, livre para estudo e modificação.
