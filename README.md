# Impressora Braille com Raspberry Pi Pico (RP2040)

Projeto desenvolvido com o objetivo de criar uma **impressora Braille acessível e de baixo custo**, utilizando o microcontrolador **RP2040 (Raspberry Pi Pico)**, com funcionalidades de conectividade Wi-Fi, exibição em matriz de LEDs e interação por joystick. 
Projeto Final do curso Capacitação Em Sistemas Embarcados pelo IFCE

## Motivação

O alto custo das impressoras Braille comerciais dificulta o acesso à comunicação escrita para pessoas com deficiência visual. Este projeto busca oferecer uma alternativa viável, simples e eficiente com o uso de tecnologias embarcadas.

## Tecnologias Utilizadas

- **RP2040 (Raspberry Pi Pico)**
- Linguagem **C** com **Pico SDK**
- Simulação via Wokwi.
- Comunicação **Wi-Fi** e **Serial**
- Display **OLED**
- **Joystick**, **botão**, **buzzer** e **matriz de LEDs**
- Simulação de servo motor para "perfuração" do Braille

## Funcionalidades

- Conexão com Wi-Fi e exibição via HTTP
- Escolha de letras com joystick
- Exibição da letra em:
  - Texto comum (OLED)
  - Formato Braille (matriz de LEDs)
- Ativação de buzzer com botão
- Envio e recebimento de dados por **interface serial** e **Wi-Fi**

## Resultados Obtidos

- Interface de seleção funcional com feedback visual e sonoro
- Exibição da letra Braille correspondente
- Comunicação entre dispositivos funcionando corretamente

## Fluxograma

<ins>*Veja o fluxograma completo no PDF ou no vídeo explicativo.*</ins>

## Esquemático

A montagem completa do circuito pode ser visualizada e testada no Wokwi:

 [Simulação e esquemático no Wokwi](https://wokwi.com/projects/422462944257278977)

## Código

Você pode acessar todos os arquivos e testar por conta própria:

 [Download do código e arquivos .rar no Google Drive](https://drive.google.com/file/d/13mjcy-aNqzdeHb31dFhLXVwtdshu6TsW/view?usp=sharing)

Para análise rápida:

[main.c + Esquemático no Wokwi](https://wokwi.com/projects/422462944257278977)

## Demonstração em Vídeo

Confira o vídeo explicativo mostrando o projeto em funcionamento:

[YouTube - Ryan Macedo Gomes](https://www.youtube.com/watch?v=XEcrpR2UbN8&ab_channel=RyanMacedoGomes)

## Referência

Projeto inspirado em exemplos da BitDogLab:

[BitDogLab/C no GitHub](https://github.com/BitDogLab/BitDogLab-C/tree/main)

---

**Desenvolvido por:** Ryan Macedo Gomes  
**Curso:** Ciência da Computação - IFCE  
