# FullStack Learning Path (WIP)

Um guia objetivo e prático para te guiar no aprendizado fullstack passando por backend, frontend e devops.

Indicado para você que está começando, ou para um frontend que quer conhecer backend e vice-versa ou mesmo para você que quer reafirmar conceitos e aprimorar conhecimentos.

Esse guia adota duas premissas:

1. Te **ensinar 20% de tudo para resolver 80% dos problemas**, pois o estudo e aprimoramento é constante, _ao infinito e além_. Você vai aprender aquele tanto suficiente para conseguir criar e ser produtivo.

2. **Não existe bala de prata**. As tecnologias desse guia foram selecionadas de acordo com critérios que atendem o contexto e a realidade da LNA Systems. Isso significa que essas tecnologias não são melhores que outras ou as únicas que deveriam ser estudadas durante a sua carreira.

E pra cada assunto novo, você irá descobrir links e referências para áreas relacionadas. Calma, não mergulhe de cabeça em tudo porque irá se perder, vá anotando e fazendo um mapa mental pra te ajudar a ligar os pontos do cenário macro, porém se atente em seguir o guia que te dá o caminho do essencial primeiro.
 
## Senta que lá vem história...

Antes de sujar a mão com código, você precisa saber como a história foi moldada aos trancos e barrancos (para o bem ou para o mau) para entender como e porque as coisas funcionam atualmente. Prepara a pipoca.

História das linguagens: [Parte 1](https://www.youtube.com/watch?v=p9-WuJbVHHc) _(11m)_ e [Parte 2](https://www.youtube.com/watch?v=XcTTajFENHI) _(13m)_

Uma característica fundamental de programadores experientes é escrever menos código, evitando desperdício e maximizando a entrega de valor. Lembre-se: _código é um meio para se criar uma solução para um problema do mundo real, e não a atividade fim_. Apesar desse pensamento não ser tão trivial, é importante começar a se habituar com o conceito [YAGNI](https://martinfowler.com/bliki/Yagni.html).

## Trilhas

Programação tem muitas vertentes, e no mundo do desenvolvimento web podem ser separadas em dois principais grupos: backend e frontend. De forma simplista o backend é aquilo não se vê, é o código que implementa regras de negócio e fica no servidor, e o frontend é a parte visual que roda no navegador. E um terceiro caminho é o de DevOps que é o operacional de infraestrutura trabalhando em conjunto com o desenvolvimento.

Vamos estudar tudo isso um pouco mais a fundo:

Primeiro, assista o vídeo [Conhecimentos Básicos para Iniciantes em Programação](https://www.youtube.com/watch?v=sx4hAHhO9CY) _(21m)_ que irá dar uma visão prática de como é começar em Programação

Depois entenda a [A História do Front-End](https://www.youtube.com/watch?v=VKmPGmFY7H4) _(48m)_

E finalmente vamos estudar as entranhas dos sistemas com o vídeo Entendendo Back-End para Iniciantes em Programação [Parte 1](https://www.youtube.com/watch?v=Qjk-cSW-jk4) _(47m)_, [Parte 2](https://www.youtube.com/watch?v=N6vgZr1k03g) _(55m)_, [Parte 3](https://youtu.be/cx1ULv4wYxM) _(42m)_ e [Parte 4](https://www.youtube.com/watch?v=gYJSWs-gp1g) _(1h01m)_.

E por último mas não menos importante, temos a área de Devops que é integrado com desenvolvimento mas tem suas próprias características e portanto todo seu conteúdo será tratado no tópico específico de Devops. Pode pular pra lá se o seu foco é Devops.
 
## Fundação

Um profissional não resolve nada sem conhecer suas ferramentas e sem saber se comunicar. É o básico do básico. Então vamos investir um tempo para fortalecer a base estudando os itens abaixo:

### Inglês

Não, esse guia não tem um curso de inglês embutido. Mas é extremamente importante saber se comunicar em inglês: ler, escrever, ouvir e falar. Esse guia deixa apenas o vídeo [Como eu aprendi Inglês? E entendendo "padrões"](https://www.youtube.com/watch?v=OkboNGQ9LU0) _(25m)_ como tarefa para que seja um start no seu estudo de inglês, que deve ocorrer em paralelo com o estudo de programação.

### Lógica de Programação

Adquirir raciocínio lógico e conhecer as estruturas bases da programação é essencial antes de aprender uma linguaguem ou plataforma específica.

[Livro Lógica de Programação](https://www.casadocodigo.com.br/products/livro-programacao)

### Git

De nada adianta escrever código se não puder compartilhar com outras pessoas ou se não puder obter o código de outros. Programação sem Git é como viver numa ilha deserta.

[Aprenda Git](http://aprenda.vidageek.net/aprenda/git) - um guia prático que combina teoria e exercícios. Complete todos.

[git - the simple guide](http://rogerdudler.github.io/git-guide/index.html) - esse simples guia do Git vai te ajudar a reforçar o que foi aprendido no GitHub Guides e também serve como consulta no dia-a-dia. E sim, o git é uma ferramenta muito usada.

### Sistema/Terminal

TODO

## Backend

### Elixir

Como você já aprendeu, existem centenas de linguagens com variados propósitos e não existe a linguagem perfeita. E este guia adota a linguagem [Elixir](https://elixir-lang.org) pelos seguintes motivos:

 - [The Free Lunch Is Over](http://www.gotw.ca/publications/concurrency-ddj.htm) (_não precisa ler este artigo inteiro mas fique a vontade se quiser_). O ponto crucial é: "The major processor manufacturers and architectures, from Intel and AMD to Sparc and PowerPC, have run out of room with most of their traditional approaches to boosting CPU performance. Instead of driving clock speeds and straight-line instruction throughput ever higher, they are instead turning en masse to hyperthreading and multicore architectures.". Portanto, uma linguagem que possui suporte nativo a concorrência tem mais chances de sobreviver no longo prazo.
 - Por possuir recursos como imutabilidade, pattern matching, documentação como first-class citizen, processos, tolerância a falhas, streams e um bom tooling nativo. (Você vai aprender tudo isso)
 - Comunidade forte que resulta em boas libs, fóruns, livros, cursos e eventos.

Para se aventuar no aprendizado de Elixir, complete o curso [Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers) que oferece textos, vídeos e exercícios para afirmar o que é aprendido. Você irá construir um jogo, divirta-se.

O curso é completo e suficiente porém há 3 livros que podem ser usados em paralelo para tirar dúvidas ou mostrar uma abordagem diferente do mesmo assunto:

[Programming Elixir](https://pragprog.com/book/elixir16/programming-elixir-1-6)

[Elixir in Action](https://www.manning.com/books/elixir-in-action-second-edition)

[The Litter Elixir & OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook)

Não é obrigatório ler os 3 livros, use como complemento do curso.

## Frontend

TODO: html css javascript vuejs/angular/react

## DevOps

Primeiro vamos entender a história o alinhar o entendimento. Assista o vídeo [Entendendo "Devops" para Iniciantes em Programação (Parte 1)](https://www.youtube.com/watch?v=bwO8EZf0gLI) _(47m)_ e depois assista [Entendendo "Devops" para Iniciantes em Programação (Parte 2)](https://www.youtube.com/watch?v=mcwnQVAn0pw) _(41m)_

## Fluxo de Trabalho

Partindo pra prática no mundo real, o primeiro passo é entender o fluxo de trabalho. E este fluxo é gerenciado com Kanban:

[Kanban em 5 minutos](https://vimeo.com/145281435) _(5m)_

## Tasks para acompanhar o progresso
 - [ ] Assistir o vídeo **História das linguagens parte 1**
 - [ ] Assistir o vídeo **História das linguagens parte 2**
 - [ ] Ler o artigo **YAGNI**
 - [ ] Assistir o vídeo **Conhecimentos Básicos para Iniciantes em Programação**
 - [ ] Assistir o vídeo **A História do Front-End**
 - [ ] Assistir o vídeo **Entendendo Back-End para Iniciantes em Programação parte 1**
 - [ ] Assistir o vídeo **Entendendo Back-End para Iniciantes em Programação parte 2**
 - [ ] Assistir o vídeo **Entendendo Back-End para Iniciantes em Programação parte 3**
 - [ ] Assistir o vídeo **Entendendo Back-End para Iniciantes em Programação parte 4**
 - [ ] Assistir o vídeo **Como eu aprendi Inglês ?**
 - [ ] Ler o livro **Lógica de Programação**
 - [ ] Completar o mini-curso **Aprenda Git**
 - [ ] Ler o guia **git - the simple guide**
 - [ ] Completar o curso **Elixir for Programmers**
 - [ ] Assistir o vídeo **Entendendo DevOps para Iniciantes em Programação parte 1**
 - [ ] Assistir o vídeo **Entendendo DevOps para Iniciantes em Programação parte 2**
 - [ ] Assistir o vídeo **Kanban em 5 minutos**

## Referências
 
 - [Canal do Fabio Akita](https://www.youtube.com/channel/UCib793mnUOhWymCh2VJKplQ)
 - [Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap)
