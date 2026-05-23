## 1. Elementos HTML

Um documento web tem em sua estrutura um conjunto variado de outros elementos que permitem com que os visitantes visualizem e interajam com o site de diferentes maneiras.

A linguagem tem em sua estrutura mais de cem elementos oficiais documentados — incluindo a capacidade de criar elementos personalizados —, assim sendo, existem diversas maneiras de se marcar o conteúdo de um documento. 

Os elementos podem ser classificados de diferentes formas — sendo comumente agrupados por finalidade:

### 1.1 Agrupamento

- `<div>`: define um contêiner em bloco sem significado — comumente utilizado para agrupar elementos para fins de estilos

- `<span>`: define um contêiner em linha sem significado — pode ser utilizado para agrupar elementos para fins de estilos

### 1.2 Textuais

Os elementos textuais consistem em tags utilizadas especificamente para estruturar, organizar e dar significado semântico aos textos de um documento web.

#### 1.2.1 Headings

Os elementos headings — `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` — representam cada um dos seis níveis de títulos de uma section, sendo `<h1>` o mais alto — ou mais importante — e `<h6>` o mais baixo — ou menos importante.

#### 1.2.2 Parágrafo

- `<p>`: representa um parágrafo — consistindo tipicamente num conjunto de frases que formam um bloco de texto com um ou mais enunciados que abordam um determinado assunto — que podem ser utilizados para qualquer agrupamento estrutural de conteúdo relacionado

### 1.3 Listas

- `<ol>`: representa uma lista ordenada de itens — normalmente renderizada como uma lista numerada — de modo que alterar a ordem alteraria o significado do documento

- `<ul>`: representa uma lista de itens onde a ordem se faz irrelevante — normalmente renderizada como uma lista de marcadores — de modo que alterar a ordem dos itens preservaria o significado do documento

- `<li>`: representa um item de uma lista — logo, cada item de uma lista é representado por este elemento; deve estar contido num elemento pai: `<ol>` ou `<ul>`

### 1.4 Hiperlinks

- `<a>`: representa um hiperlink — âncora de referência — caso o atributo `href` esteja presente na tag; o conteúdo de cada link deve indicar seu destino

O atributo **href** define o destino de um hiperlink, indicando o caminho para onde os navegadores devem ir ao clicar no elemento: o valor atribuído ao atributo pode variar dependendo do que se busca.

Normalmente, utiliza-se o símbolo de *hashtag* — `#` — como valor para impedir que o documento seja recarregado ou redirecionado, atuando como um *placeholder*. Ademais, alguns dos atributos suportados pelo elemento devem ser omitidos caso o atributo href esteja ausente.

### 1.5 Multimídia

- `<img>`: incorpora uma imagem no documento — fornecida pelo atributo `src`, o qual aponta para a origem onde a imagem se encontra salva; o atributo `alt` descreve a imagem em forma de texto

O atributo **src** deve estar presente no elemento e deve conter o caminho da imagem que se busca incorporar no documento — ele deve fazer referência a um determinado recurso de imagem.

O atributo **alt** deve estar presente no elemento para acessibilidade, contendo um texto alternativo para imagem — leitores de tela realizam a leitura do valor do atributo para seus utilizadores, para que saibam o significado da imagem.

*"Caso a origem da imagem esteja quebrada por qualquer motivo — link quebrado ou problemas de rede — o navegador exibirá o texto alternativo no local da imagem: os navegadores geralmente utilizam um ícone de moldura para imagens quebradas"*

### 1.6 Tabelas

- `<table>`: representa dados tabulares — apresentados em uma tabela bidimensional composta por linhas e colunas de células; os elementos dentro da tabela geram grades retangulares — as células devem cobrir completamente a grade formada

- `<tr>`: representa uma linha de células de uma tabela — as quais podem ser estabelecidas combinando os elementos `<td>` e `<th>`; resumidamente, define uma linha horizontal na tabela

- `<thead>`: representa o agrupamento de um conjunto de linhas de tabela — `<tr>` — que consiste nas legendas das colunas da tabela

- `<th>`: representa uma célula como cabeçalho de um grupo de células; a natureza do grupo é definida pelos atributos `scope` e `headers`

- `<tbody>`: representa o agrupamento de um conjunto de linhas de tabela — `<tr>` — que consiste no corpo dos dados da tabela; resumidamente, agrupa os dados da tabela

- `<td>`: representa uma célula de dados de uma tabela

- `<tfoot>`: representa o agrupamento de um conjunto de linhas de tabela — `<tr>` — consiste nos resumos das colunas da tabela
