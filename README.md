tags:

elementos vazios: Não fecham tag usando /
<input>
<img>

atributos: elementos ou configurações extras
ex: o "src" e o alt da img
<img src="" alt=""> <!--Onde o alt é um texto alternativo para a imagem quando ela não aparece -->

atributos booleanos: ex -> disable
<input type="text" disabled> <!-- Não será possível escrever na caixinha de texto -->

atributos globais: são aplicados a todas classes
# class, contenteditable, data-*, hidden, id, style, tabindex, title
<div id="" class="carrinho"></div>

caracteres reservados: são caracteres que são exclusivos do html, e para evitar conflitos, é necessário usar jeitos de contornar.
# são: "", <>, &,
&lt (menor que);
&gt (maior que),
&amp, (&)
&quot, (áspas),
&apos (áspas símples)

CÓDIGO
Usamos o <code> para partes genéricas do código
e usamos o <pre> para blocos de código, já que ela respeita os espaçamentos e  quebra de linha que colocar no código

DIVISÓRIAS / DELMITADORES
Usamos o <div id="id"> para delimitar um bloco e poder alterá-lo
já o <span id="id"> é utilizado quando queremos colocar ou diferenciar palavras ou uma palavra das demais dentro de uma única linha por ex.

HYPERLINKS
Permitem navegar por meio de texto.
<a>, e permite o uso de tags globais e do 
href
    ao clicar, pode redirecionar para um e-mail, url, telefone, fragmento e  outros. 
Permite também downloads,
target 
    "_self" (padrão e  abre o link na mesma página), e "_blank" (abre uma nova página)

TABELAS
usa-se o comando <table> para iniciar as tabelas.
<Caption></caption> é usado para criar a legenda, ou descrição do que se trata a tabela
<thead></thead> é usado para fazer a parte da tabela que classifica os elementos
<tbody></tbody> é usado para a parte quantitativa ou qualitativa da tabela. onde acrescentamos VALORES.
<tr></tr> significa "table roll" que é basicamente uma linha, e aninhada a ela, usamos o <th></th> e o <td></td>
<th></th> é o CABEÇALHO
<td></td> é a DESCRIÇÃO da linha, a parte de valores
    Os atributos rowspan e colspan servem para delimitar a quantidade de LINHAS e COLUNAS (respectivamente) que os itens irão ocupar
    O atributo span pode ser usado em col, para delimitar a quantidade de colunas que irão receber aquele atributo.
    O atributo [style="background-color: cor;"] permite alterar a cor do conteúdo dentro daquela coluna
    Para fins de acessibilidade, utilizamos o atributo [scope=""] -> podendo ser col, colgroup e row
    # col = coluna
    # row = linha
    # colgroup = conjunto de colunas, usado quando criamos um <colgroup></colgroup> acima do <thead></thead>

CABEÇALHO
O <head></head> é utilizado para colocar informações que não aparecem no navegador, onde acrescentamos o <title></title>, links para css, o meta:
    meta é composto pelo atributo charset, onde serão configurados os caracteres que a página aceita, o viewport, que permite a responsividade, que permitirá que a página seja aceita em diversos dispositivos. Além disso, existe o meta author e o meta description. Em que o meta author permite você adicionar quem é o autor da página e o meta description permite acrescentar a descrição que será exibido pelo motor de busca do Google, a descrição que é encontrada abaixo do hyperlink para acessar a página.
os favicon, mecanismo que permite adicionar icones, 
