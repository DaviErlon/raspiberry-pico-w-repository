# Raspberry Pi Pico W - Repositório Central

Bem-vindo ao repositório **raspberry-pico-w-repository**! Este espaço foi estruturado para consolidar os códigos desenvolvidos com o microcontrolador Raspberry Pi Pico W, ou junto da placa de desenvolvimento BitDogLab ou com simulações no [wokwi](https://wokwi.com).

O objetivo principal é manter um histórico organizado, abrangendo desde manipulação de GPIOs até o uso avançado de periféricos e protocolos.

## 📋 Lista dos repositórios

Abaixo estão os módulos desenvolvidos durante o estudo no EmbarcaTech. Cada link direciona para um repositório isolado contendo o código-fonte em C, e os detalhes de implementação daquela atividade específica.

* 🔗 [**tarefa-ledbuzzer**](https://github.com/DaviErlon/tarefa-ledbuzzer)
    * **Descrição:** Controle e acionamento de atuadores básicos. Implementação de lógicas de saída digital para controle de estado de LEDs e geração de tons em buzzers.

* 🔗 [**tarefa-teclado**](https://github.com/DaviErlon/tarefa-teclado)
    * **Descrição:** Leitura de teclado matricial. Aplicação de técnicas de varredura de linhas e colunas (relacionadas à lógica de circuitos digitais) e tratamento de *debounce* via software.

* 🔗 [**tarefa-leds**](https://github.com/DaviErlon/tarefa-leds)
    * **Descrição:** Controle dedicado de LEDs, explorando padrões de acionamento, pisca-pisca e manipulação de matrizes de LEDs endereçáveis (WS2812b).

* 🔗 [**tarefa-interrupcao**](https://github.com/DaviErlon/tarefa-interrupcao)
    * **Descrição:** Tratamento de eventos assíncronos. Uso de Interrupções de Hardware (IRQs) em pinos GPIO para detectar mudanças de estado (como o clique de um botão) sem bloquear o laço principal de execução.

* 🔗 [**tarefa-interfaces**](https://github.com/DaviErlon/tarefa-interfaces)
    * **Descrição:** Comunicação com periféricos externos. Exploração de protocolos de comunicação serial (como I2C, SPI ou UART) para integração de displays, sensores ou comunicação com outros dispositivos.

* 🔗 [**tarefa-pwm**](https://github.com/DaviErlon/tarefa-pwm)
    * **Descrição:** Modulação por Largura de Pulso (PWM). Geração de sinais para controle proporcional, permitindo o ajuste suave de brilho de LEDs ou o controle de posição/velocidade de motores.

* 🔗 [**tarefa-timer**](https://github.com/DaviErlon/tarefa-timer)
    * **Descrição:** Uso de temporizadores de hardware e alarmes para a execução precisa, periódica e não-bloqueante de rotinas do sistema.

---

## 🚀 Como utilizar

1. **Acesse as Tarefas:** Clique em qualquer um dos links acima para ser redirecionado ao repositório específico da tarefa.
2. **Documentação Local:** Cada repositório contém instruções próprias, finalidades e dependências necessárias.
3. **Gravação no Pico:** O processo envolve compilar o código utilizando o SDK do Pico (gerando um arquivo `.uf2`), podendo ser feito o uso do CMAKE, e arrastar este arquivo para a unidade de armazenamento do Raspberry Pi Pico W em modo `BOOTSEL`.

## 🛠️ Tecnologias e Ferramentas
* **Placa:** Raspberry Pi Pico W (RP2040)
* **Linguagem Principal:** C (via Pico SDK)
* **Build System:** CMake
