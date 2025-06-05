💧 Projeto: Sistema de Monitoramento de Nível de Água com Alerta Sonoro e Visual
📌 Descrição do Problema
Enchentes urbanas e transbordamento de reservatórios representam riscos à segurança pública, especialmente em áreas mal monitoradas. A falta de sistemas simples de alerta impede ações preventivas. Esse projeto busca simular uma solução prática e acessível para detectar o aumento do nível da água e emitir alertas visuais (LED) e sonoros (buzzer) quando o limite for ultrapassado.

🛠️ Visão Geral da Solução
Este projeto usa um sensor ultrassônico HC-SR04 para medir a distância entre o topo do reservatório e a superfície da água. Um Arduino Uno processa os dados e aciona:

Um LED vermelho como alerta visual.

Um buzzer ativo como alarme sonoro contínuo.

🧱 Componentes Utilizados
Componente	Quantidade
Arduino Uno	1
Sensor HC-SR04	1
Buzzer ativo	1
LED (vermelho)	1
Resistores (220Ω)	1
Jumpers	Diversos
Protoboard	1 (opcional)

📊 Lógica de Funcionamento
Altura máxima do reservatório: 100 cm

Alerta crítico: quando a distância medida for menor que 20 cm (nível da água acima de 80%)

Aciona LED e buzzer simultaneamente e de forma contínua

🔁 Diagrama ilustrativo (exemplo)
(Se quiser, posso gerar uma imagem explicativa ou layout do circuito em Fritzing ou Wokwi)

🧪 Guia para Simulação (Wokwi)
Passos:
Acesse o link da simulação abaixo.

Clique em "Start Simulation".

No sensor ultrassônico, mova o controle deslizante para simular a distância.

Veja o LED acender e o buzzer tocar quando a água "subir" (distância < 20 cm).

🎮 Link para simular no Wokwi:
🔗 Abrir simulação no Wokwi

Obs: se quiser usar o Tinkercad, o mesmo circuito pode ser montado lá, mas o Wokwi oferece controle mais intuitivo da distância do sensor.

🎥 Vídeo Demonstrativo
Assista ao vídeo abaixo para ver o projeto em ação:

🔗 Assistir no YouTube
