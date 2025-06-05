# 💧 Projeto: Sistema de Monitoramento de Nível de Água com Alerta Sonoro e Visual

## 📌 Problema

Enchentes e transbordamentos são um problema recorrente em áreas urbanas e rurais. A ausência de monitoramento preventivo impede ações de resposta rápida, colocando vidas e estruturas em risco. A proposta deste projeto é oferecer uma solução simples, de baixo custo e funcional para monitorar o nível da água em tempo real.

---

## 🛠️ Solução Proposta

Este projeto simula um sistema automatizado utilizando um **sensor ultrassônico HC-SR04**, conectado a um **Arduino Uno**, para medir a altura da água em um reservatório. Ao detectar um **nível crítico (distância menor que 20 cm)**, o sistema aciona:

- 🔊 Um **buzzer ativo** (alarme sonoro contínuo)
- 🚨 Um **LED vermelho** (alerta visual)

---

## 🧱 Componentes Utilizados

| Componente        | Quantidade |
|-------------------|------------|
| Arduino Uno       | 1          |
| Sensor HC-SR04    | 1          |
| Buzzer ativo      | 1          |
| LED (vermelho)    | 1          |
| Resistor 220Ω     | 1          |
| Jumpers           | Diversos   |
| Protoboard        | 1          |

---

## 🧠 Lógica de Funcionamento

- Altura máxima simulada do reservatório: `100 cm`
- Se a distância do sensor for **menor que 20 cm**, aciona LED + buzzer
- Sistema reativa automaticamente caso o nível normalize

---

## 🧪 Simulação no Wokwi
✅ Como testar:
1) Acesse o link da simulação abaixo.
2) Clique em "Start Simulation".
3) Mova o controle deslizante do sensor ultrassônico.
4) Observe o LED e o som do buzzer quando o nível crítico for atingido.

🔗 Acessar Simulação no Wokwi

---

##🎥 Demonstração em Vídeo
Assista ao projeto funcionando na prática:

🔗 Assistir no YouTube
