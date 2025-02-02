# Projeto 05: **Controle de LEDs e Botões com Interrupções no RP2040**
**EMBARCATECH - UNIDADE 04**

## Desenvolvedora
**Desenvolvido pela aluna Graziele Coelho de Alencar**

## **Descrição do Projeto**
Este projeto implementa um sistema de controle de LEDs e botões utilizando interrupções no microcontrolador RP2040, presente na placa BitDogLab. O objetivo é demonstrar a manipulação de botões com debounce via software e a exibição de números em uma matriz 5x5 de LEDs WS2812 com interrupções.

## **Funcionalidades**
- *Interrupções nos botões:* Responde aos botões A (GPIO 5) e B (GPIO 6) de forma eficiente.

- *Debounce via software:* Evita leituras falsas devido ao bouncing dos botões.

- *Exibição dinâmica de números:* Usa matriz de LEDs 5x5 WS2812 (GPIO 7) para exibir números de 0 a 9.

- *LED RGB Vermelho piscando a 5 Hz:* Utiliza GPIO 13 com temporizador repetitivo.

- *Lógica circular:* Incrementa e decrementa valores entre 0 e 9.

## **Hardware Utilizado**
- Placa BitDogLab

- Microcontrolador RP2040

- Matriz de LEDs WS2812 (5x5)

- Botões A e B

- LED RGB (canal vermelho)

## **Principais Componentes do Código**

- *Configuração do Sistema:* Inicializa GPIOs, define pinos e ativa pull-ups.

- *Interrupções:* Configuração para detecção dos botões.

- *Manipulação dos Botões:* Lógica para incrementar e decrementar números.

- *Exibição na Matriz 5x5:* Atualização dinâmica dos LEDs.

- *Rotina do LED Vermelho:* Pisca a 5 Hz utilizando temporizador.

- *Loop Principal:* Monitora eventos e atualiza a matriz.

## **Como Executar o Projeto**
**1. Configurar o ambiente**

- Instalar o SDK do RP2040.

- Configurar o compilador ARM GCC.

- Usar Visual Studio Code com suporte ao Raspberry Pi Pico.

**2. Compilar e carregar o código**
- Copiar o arquivo .uf2 gerado para a unidade do Raspberry Pi Pico.

## **Conclusão do Projeto**
- Foi utilizado interrupções e debounce via software para garantir um sistema estável.

- Foi implementado a exibição numérica dinâmica na matriz WS2812.

- O LED vermelho pisca a 5 Hz usando temporizador.

