# Portfólio — Joabe Junior

Portfólio pessoal desenvolvido para apresentar minha trajetória, meus serviços, habilidades e projetos como estudante de Análise e Desenvolvimento de Sistemas.

## Sobre o projeto

O site é uma página única e responsiva. Ele reúne uma apresentação pessoal, tecnologias com as quais trabalho, projetos em destaque e formas de contato.

## Recursos

- Layout adaptável para celular, tablet e computador.
- Alternância entre tema escuro e claro, com preferência salva no navegador.
- Menu de navegação para dispositivos móveis.
- Animações de entrada ao rolar a página e efeito de texto digitado.
- Links para projetos, redes sociais e currículo em PDF.
- Formulário de contato integrado ao [FormSubmit](https://formsubmit.co/).

## Tecnologias

- HTML5
- CSS3
- JavaScript
- Google Fonts (Outfit e JetBrains Mono)
- Font Awesome

## Estrutura de arquivos

```text
.
├── index.html                 # Conteúdo e estrutura da página
├── assets/
│   ├── curriculo/
│   │   ├── joabe-goncalves-dos-santos-junior.pdf   # Currículo atual disponibilizado no site
│   │   └── anteriores/
│   │       ├── curriculo-anterior.docx             # Versão anterior arquivada
│   │       └── curriculo-anterior.pdf              # Versão anterior arquivada
│   └── images/                                     # Foto e imagens dos projetos
├── css/
│   └── style.css                                   # Estilos, temas e layout responsivo
├── js/
│   └── script.js                                   # Interações e animações
├── .gitignore
└── README.md
```

## Como visualizar

Não é necessário instalar dependências nem compilar o projeto.

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto.
3. Abra `index.html` no navegador.

Para facilitar a visualização durante alterações, também é possível abrir a pasta no Visual Studio Code e usar uma extensão de servidor local, como o Live Server.

## Personalização

- Atualize textos, navegação, projetos e links em `index.html`.
- Altere cores, tipografia e comportamento visual em `css/style.css`.
- Ajuste o tema, menu e animações em `js/script.js`.
- Substitua arquivos em `assets/images/` ou `assets/curriculo/` e atualize os caminhos correspondentes no HTML. O botão de currículo baixa o arquivo PDF atual em `assets/curriculo/`.
- O formulário usa o endereço configurado no atributo `action` do `<form>` em `index.html`; altere-o para atualizar o destino das mensagens.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie os arquivos e pastas desta pasta do projeto para a raiz do repositório.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/(root)` e salve.

O arquivo `index.html` está na raiz para servir como página inicial do GitHub Pages.

## Projetos em destaque

- [Plataforma de Adoção — ONG Anjos do Poço](https://github.com/Joabejunior444/Site-Pra-Ong)
- [TaskGO — Marketplace](https://github.com/Joabejunior444/Projeto-Inter-Atualizado) · [Demonstração](https://taskgo-pi.vercel.app)
- [7 Palavras](https://github.com/Joabejunior444/Jogo7Palavras) · [Demonstração](https://jogo7palavras.vercel.app)

O TaskGO possui código de back-end no repositório, mas a demonstração online está sem um servidor hospedado para executar os recursos que dependem dele.

## Contato

- [GitHub](https://github.com/Joabejunior444)
- [LinkedIn](https://www.linkedin.com/in/joabe-junior-dev/)
- [Instagram](https://www.instagram.com/joabejunior77/)
