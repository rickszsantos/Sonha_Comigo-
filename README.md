💌 Sonha Comigo

Uma página-convite romântica para celular, no estilo de um player de música (Spotify), com um varal de fotos do casal e um joguinho de "Sim/Não" para o convite final.

Feita para ser enviada como um link especial — tipo um pedido pra namorar, um convite pra sair, ou uma homenagem para o casal.


✨ O que tem na página

A página é dividida em três blocos, dentro de um cartão estilo app de celular:


Player de música
Visual inspirado no Spotify: capa, nome da "faixa" (o nome do casal), barra de progresso e controles. O botão de play/pause é funcional de verdade — se você adicionar um arquivo de áudio, ele toca e pausa a música, com a barra de progresso seguindo o tempo real.
Varal de fotos ("sobre o casal")
Um carrossel de 6 fotos penduradas por clipes, com leve rotação aleatória (como fotos reais num varal). A fileira desliza sozinha, lateralmente e devagar, em loop infinito sem emendas. Ao tocar ou arrastar com o dedo, a animação pausa por alguns segundos e depois volta a deslizar.
Convite com joguinho do Sim/Não
A pergunta "Aceita sair comigo?" aparece com dois botões lado a lado. O botão Não só sai fugindo quando alguém tenta de fato clicar/tocar nele — pulando para outro lugar dentro do card, com legendas brincalhonas a cada tentativa. O botão Sim vai crescendo discretamente a cada fuga. Ao clicar em Sim, aparece a mensagem final ("Combinado! 💕 To te esperando aqui fora.") com coraçõezinhos subindo na tela.


🎨 Estilo visual


Paleta vinho/bordô profundo com acentos em rosa, remetendo ao visual de capa de álbum/app de música.
Tipografia combinando uma serifa elegante (Playfair Display, para títulos românticos) com uma sans-serif limpa (Inter, para textos e interface).
Totalmente responsiva, pensada primeiro para celular (mobile-first).


🛠️ Tecnologia

Página única em HTML + CSS + JavaScript puro — sem frameworks, sem instalação, sem dependências de build. Funciona abrindo o arquivo direto no navegador.

📁 Estrutura de arquivos

site/
├── index.html          → a página inteira (estrutura, estilo e interatividade)
├── README.md           → este arquivo
├── LEIA-ME.txt          → guia rápido de personalização (fotos, música, textos)
├── img/
│   ├── capa.jpg          → foto do player (topo), formato quadrado
│   └── varal-1.jpg ... varal-6.jpg  → as 6 fotos do carrossel, formato vertical
└── audio/
    └── musica.mp3        → a música que toca no player


As fotos e a música são detectadas automaticamente: se os arquivos existirem nas pastas com esses nomes, eles substituem os placeholders sozinhos — não precisa editar nenhum código.



🚀 Como usar


Abra LEIA-ME.txt para o passo a passo de como adicionar suas fotos, música e textos.
Para testar localmente: dê duplo clique em index.html, ele abre no navegador.
Para compartilhar com alguém ou publicar de verdade, suba a pasta site/ inteira (com img/ e audio/ dentro) em um serviço gratuito como Netlify, Vercel ou GitHub Pages, mantendo essa mesma estrutura de pastas.


📝 Personalização rápida

Dentro do index.html, os pontos mais comuns para editar são:

O que trocarOnde procurarNome/título do "player"texto Sonha ComigoSubtítulo do playertexto Você & EuTexto sobre o casalparágrafo dentro da seção "sobre o casal"Pergunta do convitetexto Aceita sair comigo?Mensagem finaltexto To te esperando aqui fora.

Detalhes completos em LEIA-ME.txt.


Feito com 💕 — qualquer ajuste de fotos, música, texto ou cor, é só pedir.
