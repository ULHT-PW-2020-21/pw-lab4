**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**
 
# Programação Web - Laboratório 4: Integração de elementos semânticos HTML5 no meu website e estilização com seletores e propriedades CSS 

## Objetivo
* O objetivo deste laboratório é experimentar o maior numero de elementos HTML5 assim como seletores e propriedades noa conteúdos do laboratório 3.

## Pré-requisitos
* Deverá ter feito o [lab3](https://github.com/ULHT-PW-2020-21/pw-lab3).
* 🔴 Veja o video sobre [propriedades CSS](https://educast.fccn.pt/vod/clips/2ea2z4vajw/html5.html?locale=en) e consulte os respetivos [slides](https://secure.grupolusofona.pt/ulht/moodle/pluginfile.php/800079/course/section/398731/pw-02.6-propriedades-css.pdf). É material extra À aula teórica desta semana que precisam de saber para realizar este laboratório 🔴.


## Recomendações
* Leia o enunciado todo com atenção antes de o começar a resolver para entender o que fará.
* Execute com atenção cada passo, certificando-se que implementa todos os detalhes. Contém todos os detalhes para a criação do website. 
* Se tiver alguma dúvida, consulte os slides sobre [HTML5 e seus elementos semanticos](https://secure.grupolusofona.pt/ulht/moodle/pluginfile.php/800079/course/section/398731/pw-02.4-html5-e-elementos-semanticos.pdf) e [CSS e seus seletores](https://secure.grupolusofona.pt/ulht/moodle/pluginfile.php/800079/course/section/398731/pw-02.5-css-e-seus-seletores.pdf) para ver como integrar os vários aspectos técnicos que são pedidos. Tem também disponivel o [video da aula](https://educast.fccn.pt/vod/clips/2qr2g6hysf/html5.html?locale=en) com capítulos sobre cada tópico. Estes contêm todos os conhecimentos que precisa para realizar este laboratório.
* Este laboratório deverá ser concluido antes da sua aula prática da semana de 15 de março. Este será avaliado nessa aula. 
 

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
    4. um novo elemento `footer` com o seu nome, numero, universidade, e ano, tudo numa linha.
2. Nas tabelas, utilize os elementos `caption`, `thead`, `tbody`, `tfoot`.
3. Nas imagens recorra a elemento `figure` e `figcaption`, tendo neste ultimo um elemento `details` para mostrar/esconder mais detalhes sobre a imagem.

Se visualizar no seu navegador as páginas HTML, verá que estes elementos nada mudaram em termos visuais. No entanto, estes permitirão aplicar estilos. Neste primeiro laboratório aplicaráa esta estrutura estilizações simples. No entanto, no lab5 esta estrutura permitirá criar layouts dinâmicos, configurados pelo CSS.

# 3. Página HTML5 & CSS

1. Crie uma nova página HTML `html5-css.html` que tenha o mesmo cabeçalho das restantes.
2. Insira um elemento `h3` com o título HTML5 e CSS.
3. Crie uma subsecção intitulada HTML 5 onde deverá incluir:
    1. uma frase introdutória sobre o HTML5
    2. um tabela com :
       * na primeira coluna todos os elementos HTML5 apresentados na aula, um por linha. 
       * na segunda coluna, para cada elemento HTML5 deverá indicar se o usou ou não nalguma página, recorrendo a um icon adequado (use os icones Google)
       * na terceira coluna deverá incluir uma breve descrição a explicar onde utilizou. 
4. Crie uma subsecção intitulada CSS onde deverá incluir:
    1. uma frase introdutória sobre CSS 
    2. uma tabela com todos os tipos de seletores CSS, um por linha. Na segunda coluna deverá indicar se o usou ou não nalguma página, recorrendo a um icon adequado (use os icones Google), e na terceira coluna deverá incluir um breve comentário a explicar como este funciona e onde o utilizou. 
    3. uma tabela com todos os combinadores de seletores apresentados na aula, um por linha. Na segunda coluna deverá indicar se o usou ou não nalguma página, recorrendo a um icon adequado (use os icones Google), e na terceira coluna deverá incluir um breve comentário a explicar como este funciona e onde o utilizou.

# 4. Estilização com CSS

Para a definição dos estilos será usado um único ficheiro estilos.css, que guardará todos os estilos usados nas páginas. Em cada ficheiro HTML deverá existir um link para este ficheiro, de modo a permitir usar os estilos.

1. crie o ficheiro estilos.css 
2. deverá utilizar todos os tipos seletores apresentados na aula em pelo menos 3 sitios diferentes. 
3. Deverá utilizar pelo menos três composições de selectores (descendentes, filhos `>`, adjacentes `~`, imediatamente adjacentes `+`, agrupados `,`). 
4. Para o texto do menu, deverá utilizar os selectores de pseudo-classe `link`, `visited`, `hover`, `active` para configurar os links utilizando apenas as cores da palete, assim como os selectores `before` e `after` no menu quando passar com o rato por cima. Inclua, antes de cada palavra do menu, um icon adequado, usando ícones Google, Awesome Font ou Bootstrap. 
5. Escolha e use uma Google font para o seu website.
6. Configure a cor de background do seu website, assim como de alguns elementos HTML5 usando seletores adequados. 
7. Em particular nas tabelas e no poema os selectores de pseudo-classe assim como os pseudo-elementos, explorando cores de fonte e fundos diferentes. Por exemplo, introduza variedades de cor nas linhas pares e impares das tabelas.
9. Deverá recorrer aos 6 seletores de atributo `=`, `~=`, `|=`, `^=`, `$=` e `*=` para configurar as cores e larguras das molduras em redor das imagens da página interesses.
10. No texto descritivo, use os pseudo-elementos first-letter, first-line para estilizá-lo.
11. nos seus formulários, remova o uso de quebras de linha `br` para colocar inputs em linhas diferentes. Em vez disso, transforme os elementos `input` em blocos através da propriedade `display`. 
12. No formulário de comentário, atualize a informação relativa ao elemento escondido, que deverá indicar que o comentário é referente ao lab 4.
13. estilize as molduras (border) das imagens e iframes usando seletores, sem recorrer a classes.

# 7. Multimedia

1. Na secção de multimédia insira mais algumas imagens, aplicando a técnica de sobreposição de imagens e texto umas por cima das outras, recorrendo a posições absolutas e relativas. 
2. Brinque também com a propriedade sticky e fixed, em imagens a colocar no background.


# 8. Referências

Quanto maior for o número de referências no seu website para outros websites, maior a relevância que o website ganhará assim como a visibilidade nos motores de busca. Coloque uma referência no final de um parágrafo de texto que tenha extraído de uma fonte online, assim como na legenda de uma fotografia. Pode usar a notação `[1]` colocando um hiperlink para a página de onde foi extraída informação. 

# 9. Submissão

1. Verifique que todos os links do seu website funcionam devidamente.
2. Carregue a sua pasta no seu repositório Github através dos seguintes passos:
    1.  abra o processador de comandos e posicione-se dentro da pasta do seu repositório (`pw-labs-nomeapelido-numero`).
    2.  escreva as seguintes instruções:
        * `git add *`
        * `git commit –m "submissão laboratório 3"`
        * `git push`
3. Sincronize o GitHub com o Heroku tal como fez no [lab1](https://github.com/ULHT-PW-2020-21/pw-lab1). Deverá ir ao Heroku e, em Deploy, fazer deploy branch, de forma a colocar disponível na cloud os novos conteúdos criados. 
4. Verifique que o seu website online funciona corretamente, mostra todas as imagens e os hiperlinks funcionam devidamente.
5. No seguinte [ficheiro](https://drive.google.com/file/d/1kphRYAo78NSxWznBXHqNbPksELqlyloI/view) garanta que esteja:
    * link da sua aplicação Heroku
    * link do seu repositório privado no GitHub
    * adicione os docentes de PW como membros do seu repositório, que têm como usernames no GitHub: luciostuder, logdarkmatter, rfgsantos.

Esperamos que tenha gostado de aplicar os conhecimentos de HTML5 e CSS!
