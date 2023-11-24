# GlobalSolution-IOT

# Monitor Vacina já

# Pré-requisitos:

Antes de começar, certifique-se de ter instalado o node.js

# Instruções para Replicar e Testar a Solução:

1. Protótipo no Wokwi:
Acesse o protótipo no Wokwi [https://wokwi.com/projects/382189026097883137].
Inicialize o protótipo.
Clique sobre o sensor DHT22 para simular a alteração de temperatura e umidade.

2. Configuração do Node-RED:
Abra o Node-RED no seu computador utilizando o comando node-red no terminal.
Copie e cole o endereço IP no navegador para acessar o ambiente Node-RED.

3. Importação do Fluxo:
No Node-RED, clique menu superior direito da tela.
Selecione "Import" e depois "Select a file to import".
Importe o arquivo com o fluxo que está na documentação, com o nome de "flows".

4. Simulação do Circuito e Deploy no Node-RED:
Inicialize a simulação do circuito no Wokwi.
No Node-RED, clique em "Deploy" para enviar as informações do sensor DHT22 com ESP32 para o Node-RED.
Visualize os dados enviados no debug do Node-RED.

5. Visualização da Dashboard
No Node-RED, clique no menu superior direito em "Dashboard".
Visualize o painel com as condições de armazenamento das vacinas.


