Funcionalidades

Páginas dos Livros (18 arquivos HTML)

Exibição da capa e sinopse do livro.

Botão “Saiba mais”: mostra ou oculta informações extras (nota, autor, data, páginas e categoria).

Botão “Áudio-sinopse”: ativa o player de áudio customizado.

Player de áudio:

Play/Pause.

Exibição do tempo atual e duração total.

Barra de progresso interativa.


Todas as páginas de livros seguem o mesmo modelo, mudando apenas o conteúdo específico de cada obra.


 Página de Contato (contato.html)

Formulário com os campos:

Nome.

E-mail.

Mensagem.


Envio via método POST (simulado).

Contato direto por:

E-mail (link mailto:).

WhatsApp (link direto para conversa).



Página “Quem somos” (quem-somos.html)

Texto institucional sobre a biblioteca.

Possibilidade de apresentar missão, visão e valores.

 Página Inicial (index.html)

Menu principal.

Listagem dos livros disponíveis.

Navegação para cada página individual de livro.



Estrutura de Pastas e Arquivos

YUME-HIRAKU/  
│  
├── 📂 audio-sinopses/  
│   ├── amor.mp3  
│   ├── amores.mp3  
│   ├── demonologistas.mp3  
│   ├── dracula.mp3  
│   ├── egito.mp3  
│   ├── enquanto.mp3  
│   ├── feras.mp3  
│   ├── ipanema.mp3  
│   ├── lichia.mp3  
│   ├── lugar.mp3  
│   ├── luz.mp3  
│   ├── metamorfose.mp3  
│   ├── milhao.mp3  
│   ├── ohayo.mp3  
│   ├── retrato.mp3  
│   ├── robo.mp3  
│   ├── sherlock.mp3  
│   └── vidas.mp3  
│  
├── 📂 capas/  
│   ├── amor.png  
│   ├── amores.png  
│   ├── cafe-lichia.png  
│   ├── demonologistas.png  
│   ├── dracula.png  
│   ├── egito.png  
│   ├── enquanto.png  
│   ├── feras.png  
│   ├── garoto-ipanema.png  
│   ├── lugar.png  
│   ├── luz.png  
│   ├── metamorfose.png  
│   ├── milhao.png  
│   ├── ohayo.png  
│   ├── retrato.png  
│   ├── robo.png  
│   ├── sherlock.png  
│   └── vidas-eternas.png  
│  
├── 📂 img/  
│   ├── background.png  
│   ├── favicon.ico  
│   ├── image 1 (1).png  
│   ├── logo.png  
│   ├── lupa.png  
│   └── seta-esquerda.png  
│  
├── 📄 amor.html  
├── 📄 amores.html  
├── 📄 contato.html  
├── 📄 demonologistas.html  
├── 📄 dracula.html  
├── 📄 egito.html  
├── 📄 enquanto.html  
├── 📄 feras.html  
├── 📄 index.html  
├── 📄 ipanema.html  
├── 📄 lichia.html  
├── 📄 lugar.html  
├── 📄 luz.html  
├── 📄 metamorfose.html  
├── 📄 milhao.html  
├── 📄 ohayo.html  
├── 📄 quem-somos.html  
├── 📄 retrato.html  
├── 📄 robo.html  
├── 📄 sherlock.html  
├── 📄 vidas.html  
│  
├── ⚙️ script.js  
└── 🎨 style.css



 Tecnologias Utilizadas

HTML5 – Estrutura das páginas.

CSS3 – Estilização e layout.

JavaScript (ES6+) – Manipulação de DOM, exibição de informações e controle do player de áudio.




 Como Executar Localmente

1. Clone este repositório ou faça o download dos arquivos:

git clone https://github.com/gustavodcarvalhoferreira/YumeHirakuBiblioteca.git


2. Certifique-se de que:

Todas as imagens estejam nas pastas img/ e capas/.

Os áudios estejam dentro de audio-sinopses/.



3. Abra o arquivo index.html em um navegador moderno.



> caso queira rodar com servidor local:

No VS Code, utilize a extensão Live Server.

Ou via terminal (Python 3):

python -m http.server

Acesse em: http://localhost:8000



 Melhorias Futuras


Sistema de busca e filtros (por autor, categoria ou nota).

Layout responsivo aprimorado para dispositivos móveis.

Sistema de avaliação interativa com estrelas.
