SmartHome Assistant ⚡

SmartHome Assistant é um sistema de automação residencial completo e fácil de usar, desenvolvido com JavaScript, Node.js, React, e integração com Google Assistant. Controle dispositivos inteligentes, automatize rotinas e transforme sua casa em um verdadeiro lar do futuro — tudo a partir de uma interface web intuitiva.

🌟 Destaques
Controle Remoto de Dispositivos: Controle lâmpadas, termostatos, câmeras e mais de qualquer lugar.
Automação Personalizada: Crie cenários de automação que otimizam suas rotinas diárias.
Comandos de Voz com Google Assistant: Integração total para controlar dispositivos com sua voz.
Interface Web Intuitiva: Simples, moderna e fácil de usar.
Segurança & Privacidade: Armazene seus dados de forma segura com criptografia.
📚 Introdução
Imagine poder controlar todos os dispositivos da sua casa com um simples toque ou até mesmo com a sua voz. Com o SmartHome Assistant, isso se torna realidade. Ele centraliza a gestão de seus dispositivos inteligentes em uma única plataforma, eliminando a necessidade de diversos aplicativos e facilitando o controle completo da sua casa.

Quer criar uma rotina que apaga as luzes ao dormir ou ajustar a temperatura automaticamente quando estiver voltando para casa? Agora, você pode fazer isso de forma fácil e eficiente.

🚀 Tecnologias Utilizadas
Este projeto foi construído com as seguintes tecnologias:

Node.js – Back-end e controle de dispositivos.
React – Front-end com uma interface dinâmica e responsiva.
MongoDB – Armazenamento dos dispositivos e rotinas dos usuários.
Socket.io – Comunicação em tempo real entre o servidor e os dispositivos.
Google Assistant API – Para comandos de voz automáticos e controle via assistente de voz.
Docker – Para facilitar o deployment e a execução do projeto em qualquer ambiente.
🛠️ Como Instalar
Siga os passos abaixo para configurar o SmartHome Assistant em sua máquina local:

Clone este repositório:

bash
Copiar código
git clone https://github.com/lucasniceas/SmartHomeAssistant.git
Navegue até o diretório do projeto:

bash
Copiar código
cd SmartHomeAssistant
Instale as dependências:

bash
Copiar código
npm install
Configure as variáveis de ambiente:

MONGO_URI: A URL de conexão com o MongoDB.
GOOGLE_API_KEY: Sua chave de API do Google Assistant.
Inicie o servidor:

bash
Copiar código
npm start
Abra o navegador e acesse http://localhost:3000.

📖 Como Usar
Acessar Dashboard: No dashboard, você verá todos os dispositivos conectados.
Adicionar Dispositivos: Vá até as configurações e adicione novos dispositivos (compatíveis com a API do Google Home ou outros padrões suportados).
Criar Rotinas de Automação: Crie rotinas automáticas para acionar dispositivos com base em horários ou eventos específicos.
Comandos de Voz: Acesse a aba de integração com o Google Assistant e configure comandos de voz como “OK Google, apague as luzes da sala”.
💡 Características Especiais
Automação via Reconhecimento de Voz: Integração com Google Assistant para comandos de voz práticos e eficientes.
Notificações em Tempo Real: Receba alertas sobre o status dos dispositivos diretamente no dashboard.
Cenários Personalizados: Crie "Cenários" para automatizar várias ações com um único comando (ex: "Hora de Dormir" desliga todas as luzes e tranca as portas).
Como ele resolve problemas?
O SmartHome Assistant resolve o problema de gerenciar vários dispositivos inteligentes dispersos por diferentes aplicativos e interfaces. Ele unifica o controle de dispositivos, tornando mais fácil automatizar tarefas e oferecer uma experiência integrada para qualquer usuário que deseja aumentar o conforto e eficiência de seu lar.

🤝 Como Contribuir
Contribuições são sempre bem-vindas! Para colaborar, siga os passos abaixo:

Faça um fork deste repositório.
Crie uma branch para sua feature ou correção:
bash
Copiar código
git checkout -b feature/nova-feature
Commit suas alterações:
bash
Copiar código
git commit -m 'Adicionei uma nova feature'
Envie para a branch principal:
bash
Copiar código
git push origin feature/nova-feature
Abra um Pull Request.
📄 Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.

❓ FAQ
1. O que preciso para integrar o Google Assistant?
Você precisará de uma conta no Google e configurar uma chave de API usando o Google Cloud Console.

2. Posso controlar dispositivos que não sejam compatíveis com o Google Home?
Sim, o projeto pode ser expandido para suportar dispositivos compatíveis com outras APIs, como Zigbee ou Z-Wave, bastando implementar os adaptadores corretos.

3. É possível usar em dispositivos móveis?
Sim, a interface web é responsiva e pode ser acessada em qualquer dispositivo com um navegador, como smartphones e tablets.

