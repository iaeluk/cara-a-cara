🎲 Cara a Cara Retro
<div align="center">

O jogo de adivinhação estilo "Heads Up!" definitivo para o seu navegador. Visual Retrô • +3000 Cartas • Mobile First

Ver Demo · Reportar Bug · Solicitar Feature

</div>

📖 Sobre o Projeto
Cara a Cara Retro é um web app interativo desenvolvido em React, projetado para animar festas e reuniões de amigos. Inspirado no clássico "Heads Up!", o jogador coloca o celular na testa e tenta adivinhar a palavra exibida com base nas dicas dos amigos antes que o tempo acabe.

O diferencial deste projeto é a Engenharia de Frontend aplicada para contornar limitações de navegadores móveis, garantindo uma experiência nativa (App-like) sem precisar instalar nada.

✨ Funcionalidades Principais
🎨 Design Retrô & Responsivo: Interface vibrante inspirada nos anos 90, com tipografia nostálgica e paleta de cores pastel.
📚 Database Massivo: Mais de 3.000 cartas organizadas em categorias inteligentes (Comida, Geek, Famosos, História, etc.).
🧠 Algoritmo Smart Shuffle: Sistema de embaralhamento que garante zero repetições até que todas as cartas de uma categoria tenham sido jogadas.
📱 Mobile UX Avançada:
Rotation Lock: Lógica CSS/JS que força a orientação correta durante o jogo e permite o uso do teclado na vertical nos menus.
Wake Lock API: Impede que a tela do celular desligue durante a partida.
Touch Areas: Zonas de toque gigantes para facilitar a interação "às cegas" (celular na testa).
🔊 Feedback Imersivo: Efeitos sonoros gerados via Web Audio API (sem arquivos pesados de mp3) e feedback visual (flashes de tela).
⏱️ Modos de Jogo: Tempos predefinidos (1, 3, 5 min) ou totalmente personalizado.
🕹️ Como Jogar
Escolha o Tempo: Selecione a duração da rodada ou digite um tempo personalizado.
Escolha a Categoria: Selecione entre "Variados" ou temas específicos como "Geek", "Famosos", "Comida", etc.
Posicione: Ao clicar em iniciar, coloque o celular na testa com a tela virada para seus amigos.
Adivinhe: Seus amigos darão dicas sem dizer a palavra exata.
✅ Acertou? Toque no lado Direito da tela (ou incline, se implementado).
❌ Passou/Errou? Toque no lado Esquerdo.
Placar: Ao final, veja quantos pontos você fez e some ao seu placar global!
🛠️ Tecnologias Utilizadas
React: Biblioteca principal para construção da UI.
Tailwind CSS: Estilização utilitária para design rápido e responsivo.
Lucide React: Ícones leves e modernos.
Hooks Customizados: useRef e useCallback para gerenciamento de performance e lógica do baralho.
🚀 Instalação e Execução Local
Siga os passos abaixo para rodar o projeto na sua máquina:

Clone o repositório:
git clone [https://github.com/seu-usuario/cara-a-cara-retro.git](https://github.com/seu-usuario/cara-a-cara-retro.git)
Instale as dependências:
cd cara-a-cara-retro
npm install
# ou
yarn install
Rode o servidor de desenvolvimento:
npm run dev
# ou
yarn dev
Abra http://localhost:5173 no seu navegador.
📂 Estrutura do Banco de Dados
O jogo utiliza uma estrutura JSON otimizada para carregar milhares de palavras sem impactar a performance:

const RAW_DATA = {
  "Comida": ["Coxinha", "Feijoada", ...],
  "Geek": ["Harry Potter", "Darth Vader", ...],
  // ...
};
🤝 Contribuição
Contribuições são o que fazem a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será muito apreciada.

Faça um Fork do projeto
Crie uma Branch para sua Feature (git checkout -b feature/MinhaFeature)
Adicione suas mudanças (git commit -m 'Adicionando uma nova feature incrível')
Faça o Push (git push origin feature/MinhaFeature)
Abra um Pull Request
📝 Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.

<div align="center"> <p>Feito com 💖 para animar suas festas!</p> </div>
