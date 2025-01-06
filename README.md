# Robô Sumô

Repositório contendo o código e as instruções para a criação de um robô sumô utilizando Arduino.

---

## Descrição

Este projeto foi desenvolvido com o objetivo de construir um robô sumô para competições. O robô é capaz de:
- Identificar oponentes usando sensores ultrassônicos.
- Detectar bordas da arena utilizando sensores de linha.
- Executar estratégias básicas de ataque e defesa por meio de movimentos programados.

O código controla motores e sensores, permitindo ao robô competir em arenas de sumô de maneira eficiente.

---

## Estrutura do Repositório

1. **Código Principal:**
   - Contém o programa em Arduino (.ino) que controla os sensores e motores do robô.

2. **Configuração de Hardware:**
   - Guia para conexão dos componentes eletrônicos, incluindo motores, sensores e fonte de alimentação.

3. **Bibliotecas Necessárias:**
   - Listagem das bibliotecas utilizadas no projeto, com links para instalação.

---

## Funcionalidades

- **Detecção de Oponentes:**  
  Utiliza sensores ultrassônicos para localizar outros robôs na arena.

- **Identificação de Bordas:**  
  Emprega sensores de linha para evitar que o robô saia da arena.

- **Movimentos Programados:**  
  Executa ações de ataque ou evasão dependendo da situação.

---

## Requisitos

### Hardware:
- Arduino Uno (ou compatível).  
- Motor Shield (compatível com a biblioteca AFMotor).  
- 4 motores DC.  
- 1 sensor ultrassônico (HC-SR04).  
- 2 sensores de linha (IR ou similares).  
- Fonte de energia para motores e Arduino.  
- Chassi do robô.  

### Software:
- Arduino IDE.  

### Bibliotecas:
- **AFMotor:** Controla os motores por meio do Motor Shield.  
- **Ultrasonic:** Gerencia o sensor ultrassônico.  

Para instalar as bibliotecas necessárias, utilize o **Gerenciador de Bibliotecas** da Arduino IDE.

---

## Como Usar

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/Robo-Sumo.git


