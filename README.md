# Sensor LDR com ESP32

## Descrição
Sistema simples de monitoramento de luminosidade usando **ESP32** e **sensor LDR**.  
O microcontrolador lê a intensidade da luz ambiente e liga ou desliga um LED automaticamente com base em um valor limite definido no código.

---

## Objetivo
- Ler dados analógicos do LDR via ADC  
- Exibir valores no Monitor Serial  
- Acionar um LED conforme a luminosidade  

---

## Componentes
- ESP32  
- Sensor LDR  
- LED  
- Resistor (LED)  
- Resistor (divisor de tensão)  
- Protoboard e jumpers  

---

## Funcionamento
- O LDR é ligado em **divisor de tensão**.
- O ESP32 realiza a leitura analógica (0 a 4095).
- Um **limiar** define se o ambiente está claro ou escuro.
- Se estiver escuro → LED liga.  
- Se estiver claro → LED desliga.
- A leitura é exibida no Monitor Serial (115200 baud).

---

## ▶️ Execução
1. Abrir o código na Arduino IDE  
2. Selecionar placa **ESP32 Dev Module**  
3. Fazer upload  
4. Abrir Monitor Serial  

---

Projeto desenvolvido para fins acadêmicos.

---
## Autores
- Rebeca gomes
- Luana Bomfim
