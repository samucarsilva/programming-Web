## 1. Linguagem HTML

O *HyperText Markup Language* — Linguagem de Marcação de HiperTexto —, mais conhecido como `HTML`, consiste a linguagem fundamental da web que define o significado e a estrutura de documentos web.

*"O hipertexto consiste num texto que engloba links para outros textos — sendo um dos aspectos fundamentais da web — assim sendo, o hipertexto conecta diferentes documentos web uns aos outros, seja dentro de um site ou entre sites diferentes"*

### 1.1 Tags

Uma **tag** consiste num marcador que delimita onde um elemento inicia e termina: a maioria dos elementos possuem uma tag de abertura — indicando onde eles iniciam — e uma tag de fechamento — indicando onde eles terminam:

- Abertura: compostas por um conjunto de sinais de desigualdade e pelo nome da tag posicionada entre eles — `<tag>`

- Fechamento: compostas por um conjunto de sinais de desigualdade, barra e pelo nome da tag posicionadas entre os sinais delimitadores — `</tag>`

Existem dois tipos fundamentais de tags: as que necessitam de fechamento e as que se fecham sozinhas — estas recebem o nome de **elementos vazios**.

#### 1.1.1 Elementos

Um **elemento** corresponde a todo objeto que pode ser identificado dentro de um documento, composto geralmente por um par de tags e conteúdo — podendo conter um item de dados, um bloco de texto, uma imagem ou nada. cada elemento pertence a uma determinada categoria, organizando o conteúdo para ser exibido em um navegador web.

#### 1.1.2 Atributos

Os elementos podem ter **atributos** — eles controlam seu funcionamento. Um atributo fornece dados adicionais sobre um elemento, alterando seu comportamento ou fornecendo metadados: os atributos devem ser inseridos dentro da tag de abertura e possuem um **nome** e um **valor** — separados por um caractere de igualdade.

*"Nem todos os atributos possuem valor ou precisam ser separados por um sinal de igualdade: alguns atributos podem apenas ser inseridos nas tags de abertura para que o comportamento do elemento seja alterado"*

Os atributos se encontram classificados em dois grupos fundamentais: os **atributos globais** — comuns a todos os elementos — e os **atributos específicos** — aplicados apenas a tags exclusivas.

### 1.2 Estrutura

Todo **documento web** compartilha uma estrutura base fundamental composta por um conjunto de tags essenciais que informam aos navegadores como interpretar e renderizar o documento da forma correta. A estrutura de um documento web segue o seguinte modelo:

```html
<!DOCTYPE html>
<html lang="en-US">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>
            Page Title
        </title>
    </head>
    <body>
        Page Code
    </body>
</html>
```

- `<!DOCTYPE>`: diretiva que informa aos navegadores a forma como o documento deve ser renderizado; deve ser a primeira coisa a ser inserida em um documento web — na primeira linha do documento. O termo **html** faz parte da diretiva e deve ser incluso — ele informa ao navegador que deve ser utilizada a release mais recente da linguagem

A diretiva mencionada anteriormente — `<!DOCTYPE>` — evita que os navegadores entrem no chamado *Quirks Mode* quando renderizarem um documento web, evitando que eles emulem o comportamento de navegadores antigos.

- `<html>`: elemento raiz do documento que engloba todos os outros elementos; o atributo **lang** especifica o idioma principal do documento, ajudando motores de busca e leitores de tela de formas distintas

- `<head>`: elemento que engloba metadados sobre o documento, incluindo seu título e links para scripts e folhas de estilos — os navegadores e motores de busca leem esses metadados e os utilizam para diferentes finalidades

- `<meta>`: elemento que fornece dados adicionais sobre o documento aos navegadores, mecanismos de busca e outros clientes; este elemento suporta variados atributos

Os atributos **charset**, **name** e **content** utilizados anteriormente nesse elemento servem, respectivamente, para definir a forma como os navegadores devem decodificar caracteres a fim de garantir que eles sejam exibidos corretamente, para definir o nome do metadado, e para fornecer o valor associado ao atributo **name** — logo, **name** trabalha em conjunto com **content**.

O valor **viewport** fornecido ao atributo **name** instrui os navegadores sobre como dimensionar o documento para o dispositivo do visitante: o valor fornecido ao atributo **content** instrui os navegadores a fazerem a largura do documento acompanhar a largura do dispositivo e define o nível inicial de zoom.

- `<title>`: elemento que define o título do documento, exibido na aba dos navegadores e nos resultados de pesquisa dos mecanismos de busca

- `<body>`: elemento que define o corpo do documento — engloba tudo aquilo que os visitantes veem e com que interagem, como textos, links e imagens

### 1.3 Comentários

Um **comentário** consiste num trecho de texto inserido no **código-fonte** de um programa — ignorados pelos navegadores — que serve exclusivamente para humanos, auxiliando os desenvolvedores a documentar e organizar a estrutura do projeto.

Um comentário se inicia com `<!--` e termina com `-->` e funciona tanto para uma linha quanto para mais de uma linha ou blocos: tudo que estiver inserido dentro de um comentário é ignorado pelo navegador, incluindo elementos.
