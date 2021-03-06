**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**
 
# Programação Web - Laboratório 4: Integração de elementos semânticos HTML5 no meu website e estilização com seletores e propriedades CSS 

## Objetivo
* Neste laboratório formatará o website criado no Laboratório 3
* Irá estruturar o conteúdo com etiquetas semânticas de HTML5
* irá formatár o website usando CSS, explorando os seus seletores e propriedades.
* Este laboratório deverá ser concluido antes da sua aula prática da semana de 8 de março. Este será avaliado nessa aula. 

## Recomendações
* Leia o enunciado todo com atenção antes de o começar a resolver para entender o que fará.
* Execute com atenção cada passo, certificando-se que implementa todos os detalhes. Contém todos os detalhes para a criação do website. 
* Se tiver alguma dúvida, recorra ao [Moodle](https://secure.grupolusofona.pt/ulht/moodle/course/view.php?id=38119), onde no Programa existem links para os slides de cada tópico, assim cmoo vídeos, contendo todos os conhecimentos que precisa para realizar este laboratório.

## Pré-requisitos
* Deverá ter feito o [lab3](https://github.com/ULHT-PW-2020-21/pw-lab3).

# 1. Estruturação do repositório de laboratórios
1. Clone  (descarregue uma cópia) o seu repositório no seu computador local da seguinte forma:
    1. abra um processador de comandos (Tecla Windows e escreva `cmd`, ou `Powershell`, ou `git bash`)
    2. escolha a pasta onde quer colocar o repositório (navegando com o comando `cd nome-de-pasta` para entrar numa determinada pasta)
    3. escreva o comando `git clone https://github/seuusername/pw-labs-nomeapelido-numero` (hiperlink do seu repositório, com o seu username do GitHub e nome do repositório).

2. Crie a pasta `lab4`. 

3. Atualize o `index.html` da sua aplicação, incluindo na lista o nome deste laboratório com um link para lab4/index.html.

3. Copie os conteúdos do `lab3` para a pasta `lab4`, que servirão de base para este laboratório.

5. Neste laboratório irá criar mais umas página. Atualize o menu de todas as páginas HTML existentes com um novo link: html5-css.html.


# 2. Nova estrutura das páginas

1. Todas as suas páginas HTML deverão ser reestruturadas com elementos semânticos HTML5. No `body` deverá ter:
    1. dentro de um elemento `header` deverá incluir o cabeçalho, com o titulo do site e fotografia 
    2. o menu de navegação deverá estar dentro do elemento `nav`
    3. o conteúdo dentro de um elemento `main`. Dentro do `main`, use elementos `section` para dividir o conteúdo em secções (cada elemento `section` deverá ter um elemento `hx` e parágrafos `p`).
    5. um novo elemento `footer` com o seu nome, numero, universidade, e ano, tudo numa linha.

Se visualizar no seu navegador as páginas HTML, verá que estes elementos nada mudaram em termos visuais. No entanto, estes permitirão aplicar estilos. Neste primeiro laboratório aplicaráa esta estrutura estilizações simples. No entanto, no lab5 esta estrutura permitirá criar layouts dinâmicos, configurados pelo CSS.

# 3. Página HTML5 & CSS

1. Crie uma nova página HTML `html5-css.html` que tenha o mesmo cabeçalho das restantes.
2. Insira um elemento `h3` com a palavra Tecnologias Usadas.
3. Crie uma subsecção intitulada HTML 5 onde deverá incluir:
    1. uma frase introdutória sobre o HTML5
    2. um tabela com todos os elementos HTML5 apresentados na aula, um por linha. Na segunda coluna deverá indicar se o usou ou não nalguma página, recorrendo a um icon adequado (use os icones Google), e na terceira coluna deverá incluir um breve comentário a explicar onde utilizou. Utilize os marcadores associados ao elemento `table` (`caption`, `thead`, `tbody`, `tfoot`).
4. Crie uma subsecção intitulada CSS onde deverá incluir:
    1. uma frase introdutória sobre CSS 
    2. um tabela com todos os seletores CSS apresentados na aula, um por linha. Na segunda coluna deverá indicar se o usou ou não nalguma página, recorrendo a um icon adequado (use os icones Google), e na terceira coluna deverá incluir um breve comentário a explicar como este funciona e onde o utilizou.  Utilize os marcadores associados ao elemento `table` (`caption`, `thead`, `tbody`, `tfoot`).
    3. um tabela com todos os combinadores de seletores apresentados na aula, um por linha. Na segunda coluna deverá indicar se o usou ou não nalguma página, recorrendo a um icon adequado (use os icones Google), e na terceira coluna deverá incluir um breve comentário a explicar como este funciona e onde o utilizou.  Utilize os marcadores associados ao elemento `table` (`caption`, `thead`, `tbody`, `tfoot`).

# 4. Estilização com CSS

1. crie o ficheiro estilos.css onde deverá utilizar todos os tipos seletores apresentados na aula pelo menos em 3 sitios diferentes. 
2. Deverá utilizar pelo menos três composições de selectores (descendentes, filhos `>`, adjacentes `~`, imediatamente adjacentes `+`, agrupados `,`). 
3. Para o menu, deverá utilizar os selectores de pseudo-classe `link`, `visited`, `hover`, `active` para configurar os links utilizando apenas as cores da palete, assim como os selectores `before` e `after` no menu quando passar com o rato por cima. 
4. 

poema
tabelas

os selectores de pseudo-classe first-child, last-child, nth-child(), nth-last-child(), only-child, nth-of-type, first-of-type, last-of-type, oly-of-type, assim como os pseudo-elementos first-letter, first-line, explorando cores de fonte e fundos diferentes.
c)	Na tabela dos seletores usados, configurada a partir do ficheiro estilos.css, introduza variedades de cor nas linhas pares e impares (não use div nem class).
d)	Deverá recorrer aos 6 seletores de atributo =, ~=, |=, ^=, $= e *= para configurar as cores e larguras das molduras em redor das imagens da página interesses.
e)	Na página de introdução e interesses, deverá utilizar os pseudo-elementos first-letter, first-line.





# 3. Página Comentários

1. Crie uma nova página HTML `comentarios.html` que tenha o mesmo cabeçalho das restantes.
2. Insira um elemento h3 com a palavra Comentários.
3. Esta página servirá para recolher opiniões sobre o seu website assim como ideias de coisas a melhorar.
4. Crie um formulário para recolher opiniões sobre o seu website, avaliando 10 critérios. Listam-se em baixo alguns padrões intelectuais do pensamento crítico: 
    * clareza (compreensível, em que o significado pode ser identificado sem que haja confusão ou ambiguidade.)
    * rigor (livre de erros)
    * precisão (exato, segundo o nível necessário do pormenor)
    * profundidade (contém complexidades e múltiplas inter-relações)
    * amplitude (que abrange diferentes aspectos, pontos de vista, pespectivas)
    * lógica (em que as partes fazem sentido num todo, sem contradições: faz sentido no conjunto, provém de evidências)
    * significância (focado no importante, não trivial)
    * originalidade (criativo e original)
    Para tal, utilize elementos `input` com atributos `range`, `checkbox` e `radio`. Deverá igualmente ter um elemento `textarea` que permita submeter sugestões de melhoria.
6. Inclua um elemento escondido que identifica que se trata da opinião relativa ao website do laboratório 3. De facto, os laboratórios seguintes trarão várias melhorias ao seu website que resultarãm em comentários ainda melhores. 
7. Quando desenvolver o *back-end*, será capaz de processar estes dados introduzidos por
utilizadores e será capaz de fazer uma análise do seu website assim como uma visão crítica deste. 

# 4. Desenhos SVG

1. Altere a wordcloud que criou por forma a que seja um SVG embutido no HTML com a wordcloud:
   * inclua a wordcloud que criou no Laboratório 2 (com o elemento `image`). 
   * Sobreponha na imagem da wordcloud elementos transparentes sobre agumas palavras, com hiperlinks para páginas do seu website (abra a imagem no Paint para extrair as coordenadas dos vértices dos poçígonos sobre cada palavra). 
   * Deverá usar uma área default que cubra todo a imagem (restantes palavras para as quais não inseriu links específicos), e que remete para a introdução do seu website. Garanta que esta se encontra "por baixo" dos restantes elementos.

2. Crie um menu usando um SVG embutido no HTML ao estilo de uma wordcloud:
   * aplique efeitos a cada uma das palavras rodadas ou encurvadas, diferentes tamanhos, formas, cores, etc.
   * cada palavra deverá conter um elemento `animate` que deverá especificar como muda no tempo um determinado atributo. Explore o atributo `begin` também.
   * cada palavra deverá ter um hiperlink para a respetiva página.
   * coloque esta imagem no final de cada página do seu website.

3. Inspirado nalgum aspecto da cidade que escolheu, faça um desenho criativo embutido no HTML utilizando a maior diversidade de formas que consiga e utilizando os elementos animate, animateMotion e animateTransform. Coloque-o na secção Multimedia, especificando numa legenda os aspectos que o inspiraram para tal.

4. Inspirado nalgum aspecto da cidade que escolheu, utilize um editor SVG (por exemplo (Boxy-svg)[https://boxy-svg.com/app]) para criar um ficheiro SVG, explorando as ferramentas disponíveis. Coloque-o na secção Multimedia, especificando numa legenda os aspectos que o inspiraram para tal.

5. Na página `local.html` insira um SVG com o mapa SVG da localidade escolhida:
    * procure um mapa SVG da sua cidade (aqui)[https://commons.wikimedia.org/wiki/Category:SVG_maps_of_freguesias_in_Portugal] ou na Wikimedia Commons (se a cidade não for em Portugal).
    * insira no mapa pontos de interesse, objetos com hiperlinks que abram imagens sobre essa zona. 
    * Veja o [slide](https://secure.grupolusofona.pt/ulht/moodle/pluginfile.php/800079/course/section/398731/pw-02.1-html.pdf?time=1614518293580) 50 da aula sobre [html](https://secure.grupolusofona.pt/ulht/moodle/pluginfile.php/800079/course/section/398731/pw-02.1-html.pdf?time=1614518293580) que explia como fazer isso.
    * deverá criar um objeto iframe por baixo do mapa com um nome (`name`)
    * espicifique como target de cada hiperlink do mapa o nome da iframe, de forma a que a imagem abra dentro da iframe.

# 5. Multimedia

Na página de multimedia altere também a forma como abrem as fotografias grandes.
1. Veja o [slide](https://secure.grupolusofona.pt/ulht/moodle/pluginfile.php/800079/course/section/398731/pw-02.1-html.pdf?time=1614518293580) 50 da aula sobre [html](https://secure.grupolusofona.pt/ulht/moodle/pluginfile.php/800079/course/section/398731/pw-02.1-html.pdf?time=1614518293580).
2. insira um elemento iframe com a dimensão das fotografias (largura  800 pixels). Atribua um nome à iframe.
3. no target do hiperlink de cada imagem pequena especifique o nome da iframe.
4. quando clicar numa imagem pequena, a foto grande abrirá dentro da iframe. 

# 6. Referências

Quanto maior for o número de referências no seu website para outros websites, maior a relevância que o website ganhará assim como a visibilidade nos motores de busca. Coloque uma referência no final de um parágrafo de texto que tenha extraído de uma fonte online, assim como na legenda de uma fotografia. Pode usar a notação `[1]` colocando um hiperlink para a página de onde foi extraída informação. 

# 7. Submissão

1. Verifique que todos os links do seu website funcionam devidamente.
2. Carregue a sua pasta no seu repositório Github através dos seguintes passos:
    1.  abra o processador de comandos e posicione-se dentro da pasta do seu repositório (`pw-labs-nomeapelido-numero`).
    2.  escreva as seguintes instruções:
        * `git add *`
        * `git commit –m "submissão laboratório 3"`
        * `git push`
3. Sincronize o GitHub com o Heroku tal como fez no [lab1](https://github.com/ULHT-PW-2020-21/pw-lab1). Deverá ir ao Heroku e, em Deploy, fazer deploy branch, de forma a colocar disponível na cloud os novos conteúdos criados. 
4. Verifique que o seu website online fucnioa corretamente, mostra todas as imagens e os hiperlinks funcionam devidamente.
5. No seguinte [ficheiro](https://drive.google.com/file/d/1kphRYAo78NSxWznBXHqNbPksELqlyloI/view) garanta que esteja:
    * link da sua aplicação Heroku
    * link do seu repositório privado no GitHub
    * adicione os docentes de PW como membros do seu repositório, que têm como usernames no GitHub: luciostuder, logdarkmatter, rfgsantos.

Esperamos que tenha gostado de aplicar os conhecimentos de HTML e de ter feito um website &#127760;!
