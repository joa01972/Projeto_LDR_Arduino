<p align="center">
  <img src="https://img.shields.io/badge/LEVEL-01-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/QUEST-PROJETO__LDR__ARDUINO-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DIFFICULTY-EASY-blue?style=for-the-badge" />
</p>

<h1 align="center">🎮 PRESS START: Projeto LDR Arduino</h1>

<p align="center">
  <i>"Nas sombras do laboratório, apenas a luz do LDR pode acender a esperança."</i>
</p>

<p align="center">
  <!-- Imagem de Capa do Jogo / Banner do Projeto -->
  <img src="./assets/banner_game.png" alt="Capa do Jogo" width="700">
</p>

---

## 📜 MISSÃO PRINCIPAL (Lore)

Seu personagem acorda em um laboratório escuro. A única maneira de sobreviver aos perigos da noite é construindo um **Sensor Fotossensível Automático**. 

O objetivo desta missão é programar uma placa **Arduino** integrada a um sensor **LDR (Light Dependent Resistor)** para detectar a penumbra e acionar a luz de emergência (LED) em tempo real.

---

## ⚔️ INVENTÁRIO (Componentes Necessários)

Para completar esta quest, você precisará equipar os seguintes itens:

| Ícone | Item | Quantidade | Descrição / Atributo |
| :---: | :--- | :---: | :--- |
| 🎛️ | **Arduino UNO** | 1x | *O Core Central (Processador)* |
| 👁️ | **Sensor LDR (5mm)** | 1x | *Visão Noturna (+10 de Percepção)* |
| 💡 | **LED Vermelho/Verde** | 1x | *Orbe de Luz (Sinalizador)* |
| ⚡ | **Resistor 10kΩ** | 1x | *Escudo de Carga (Pulldown)* |
| ⚡ | **Resistor 220Ω** | 1x | *Limitador de Tensão (Proteção)* |
| 🔌 | **Jumpers & Protoboard** | - | *Conectores da Teia da Vida* |

---

## 🗺️ MAPA DA FASE (Esquema do Circuito)

Abaixo está o mapa tático necessário para montar seu circuito sem explodir os componentes:

<p align="center">
  <img src="./assets/circuito.png" alt="Esquema do Circuito Arduino" width="600">
  <br>
  <i>Figura 1: Mapa de conexões no circuito principal.</i>
</p>

### 📍 Mapeamento dos Pinos
* **Entrada Analógica `A0`:** Conectada ao **LDR** para leitura dos níveis de luz.
* **Saída Digital `13`:** Conectada ao **LED** com resistor limitador.

---

## 🕹️ CONTROLES E MECÂNICAS (Como Funciona)
<p align="center">
  <img src="https://img.shields.io/badge/LEVEL-01-brightgreen?style=for-the-badge&logo=gameandwatch" />
  <img src="https://img.shields.io/badge/QUEST-PROJETO__LDR__ARDUINO-orange?style=for-the-badge&logo=arduino" />
  <img src="https://img.shields.io/badge/DIFFICULTY-EASY-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LICENSE-MIT-red?style=for-the-badge" />
</p>

<h1 align="center">🎮 PRESS START: Projeto LDR Arduino</h1>

<p align="center">
  <b><i>"Nas sombras do laboratório, apenas a luz do LDR pode acender a esperança."</i></b>
</p>

<p align="center">
  <!-- Imagem de Capa do Jogo / Banner do Projeto -->
  <img src="./assets/banner_game.png" alt="Capa do Projeto LDR Arduino" width="750">
</p>

<p align="center">
  <a href="#-missão-principal-lore">Lore</a> •
  <a href="#-inventário-componentes">Inventário</a> •
  <a href="#-mapa-da-fase-circuito">Circuito</a> •
  <a href="#-tutorial-de-montagem-passo-a-passo">Montagem</a> •
  <a href="#-grimório-de-código">Código</a> •
  <a href="#-calibração-e-telemetria">Calibração</a> •
  <a href="#-solução-de-bugs-troubleshooting">Troubleshooting</a>
</p>

---

## 📜 MISSÃO PRINCIPAL (Lore)

Seu personagem acorda em um setor isolado da base. A iluminação principal falhou e criaturas da noite espreitam nas sombras. A única maneira de manter a área segura é construindo um **Sistema Fotossensível de Emergência Automático**.

O objetivo desta *quest* é integrar um microcontrolador **Arduino UNO** a um sensor de luz **LDR (Light Dependent Resistor)**. O sistema monitora a luminosidade do ambiente em tempo real e aciona um **Farol de Emergência (LED)** assim que o nível de luz cai abaixo do limite de segurança.

---

## ⚔️ INVENTÁRIO (Componentes Necessários)

Equipe os seguintes itens em seu inventário antes de iniciar a montagem:

| Ícone | Item / Componente | Qtd. | Especificação / Função | Atributo |
| :---: | :--- | :---: | :--- | :--- |
| 🎛️ | **Arduino UNO R3** | 1x | Microcontrolador ATmega328P | *Core da Operação* |
| 👁️ | **Sensor LDR 5mm** | 1x | Sensor Fotossensível (10k-100kΩ) | *Percepção +15* |
| 💡 | **LED Difuso (Vermelho/Verde)** | 1x | Atuador Visual (5V) | *Emissão de Luz* |
| ⚡ | **Resistor 10kΩ (Castanho-Preto-Laranja)** | 1x | Divisor de Tensão (Pulldown) | *Estabilidade de Sinal* |
| ⚡ | **Resistor 220Ω (Vermelho-Vermelho-Castanho)** | 1x | Limitador de Corrente do LED | *Proteção contra Queima* |
| 🔌 | **Protoboard (Breadboard 400 furos)** | 1x | Base de Conexões Sem Solda | *Mesa de Crafting* |
| 🧵 | **Jumpers Macho-Macho** | 6x | Condutores Elétricos Flexíveis | *Linhas de Sinal e Poder* |
| 💻 | **Cabo USB A-B** | 1x | Conexão de Comunicação e Energia | *Link de Dados* |

---

## 🗺️ MAPA DA FASE (Circuito Eletrônico)

Consulte o mapa tático abaixo para posicionar os pinos corretamente sem curtar a placa:

<p align="center">
  <img src="./assets/circuito.png" alt="Esquema Eletrônico do Circuito" width="650">
  <br>
  <i>Figura 1: Esquema elétrico gerado via Tinkercad / Fritzing.</i>
</p>

### 📍 Tabela de Pinos (Pinout Tático)

| Origem (Componente) | Pino do Componente | Destino (Arduino) | Tipo de Sinal |
| :--- | :--- | :--- | :--- |
| **LDR** | Perna 1 | **5V** (Barramento Positivo) | Alimentação (+5V) |
| **LDR** | Perna 2 | **A0** e **Resistor 10kΩ** | Sinal Analógico (Entrada) |
| **Resistor 10kΩ** | Perna 2 | **GND** (Barramento Negativo) | Terra (0V) |
| **LED** | Anodo (`+` Perna longa) | **Resistor 220Ω** -> **Pino Digital 13** | Sinal Digital (Saída) |
| **LED** | Catodo (`-` Perna curta) | **GND** (Barramento Negativo) | Terra (0V) |

---

## 🧰 TUTORIAL DE MONTAGEM (Passo a Passo)

Siga este guia em etapas para concluir a construção da engenhoca:

1. **Alimentação da Protoboard:**
   * Conecte o pino **5V** do Arduino na linha vermelha `(+)` da protoboard.
   * Conecte o pino **GND** do Arduino na linha azul/preta `(-)` da protoboard.

2. **Montagem do Sensor LDR:**
   * Insira o **LDR** na protoboard.
   * Ligue uma perna do LDR à linha de **5V**.
   * Ligue a outra perna do LDR ao pino analógico **A0** do Arduino.
   * Conecte o resistor de **10kΩ** na mesma perna ligada ao **A0** e leve a outra extremidade do resistor ao **GND**.

3. **Montagem do Indicador LED:**
   * Insira o **LED** na protoboard.
   * Ligue o **Catodo (perna curta)** ao barramento de **GND**.
   * Conecte o resistor de **220Ω** no **Anodo (perna longa)** e ligue a outra ponta do resistor ao **Pino Digital 13** do Arduino.

---

## 📸Imagens do Circuito

![Texto alternativo para acessibilidade](https://github.com/joa01972/Projeto_LDR_Arduino/blob/main/Captura%20de%20tela%202026-09-07%20194902.png?raw=true)
