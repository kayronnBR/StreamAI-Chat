StreamAI Chat Companion 🎙️💬
Dê vida ao seu chat e nunca mais faça uma live "falando sozinho"!

Começar a fazer lives é um desafio. O chat parado pode ser intimidador e é comum sentir que estamos falando com as paredes. O StreamAI Chat Companion foi criado exatamente para resolver isso: é uma ferramenta simples que ouve o que você fala durante a transmissão e gera reações imediatas de "espectadores" no seu chat, ajudando a manter o ritmo, treinar sua oratória e deixar a tela da sua live com mais movimento.

🚀 Por que usar este projeto?
Combate a solidão da live: Preenche os silêncios com reações naturais e gírias da internet.

Ideal para iniciantes: Ajuda a se acostumar a falar enquanto joga ou conversa, mesmo quando não há espectadores reais ainda.

Visual Personalizado: Interface inspirada nos grandes chats de plataformas de streaming (Twitch/YouTube).

Fácil integração: Projetado para ser capturado facilmente pelo OBS Studio.

⚙️ Como configurar
Para utilizar o projeto, você precisará de uma API Key do Google Gemini (gratuita).

Obtenha sua Chave: Acesse o Google AI Studio e crie uma API Key.

Execute o projeto:

Se você estiver usando o VS Code, a maneira mais fácil é instalar a extensão "Live Server".

Abra o arquivo index.html e clique em "Go Live" no canto inferior direito do VS Code. Isso abrirá seu navegador no endereço [http://127.0.0.1:5500](http://127.0.0.1:5500).

Nota: Não abra o arquivo diretamente via file:///, pois o navegador bloqueará o acesso à API por motivos de segurança.

Configuração Inicial: Ao abrir o link pela primeira vez, uma janela solicitará sua chave de API. Cole-a lá e clique em "Salvar e Iniciar". Ela ficará salva no cache do seu navegador.

📺 Como colocar na sua Live (OBS Studio)
No OBS, adicione uma nova fonte do tipo "Navegador" (Browser).

Cole o link do seu "Live Server" (ex: [http://127.0.0.1:5500](http://127.0.0.1:5500)).

Defina a largura e altura desejadas (ex: 350x600).

Para deixar o fundo transparente (opcional):

Nas propriedades da fonte de Navegador, você pode aplicar um filtro de "Chroma Key" (Chave de cor) selecionando a cor de fundo do seu chat.

Posicione no local desejado da sua tela e comece a falar!

🛠️ Tecnologias Utilizadas
HTML5 / CSS3 / JavaScript: Para a interface e lógica do chat.

Web Speech API: Para transformar sua voz em texto em tempo real.

Google Gemini API: Para processar o contexto e gerar as reações dos espectadores.

LocalStorage: Para salvar sua chave de API com segurança no seu navegador.

📝 Licença
Este projeto é de código aberto. Sinta-se à vontade para modificar e adaptar para suas necessidades!
