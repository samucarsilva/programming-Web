## 1. Acessibilidade Web

A **acessibilidade** consiste na qualidade de um recurso que permite seu uso por qualquer pessoa, independentemente de suas capacidades, visando garantir que todas tenham autonomia para executar atividades cotidianas — no contexto web, a acessibilidade se refere ao cumprimento dos pilares da acessibilidade no desenvolvimento de sistemas disponíveis na internet:

*"Tradicionamente, esse conceito é pensado como algo voltado a pessoas com deficiência, entretanto, a prática de tornar sites acessíveis também beneficia outros grupos — como aqueles que utilizam dispositivos móveis, por exemplo"*

Assim sendo, a acessibilidade web significa que sites, ferramentas e tecnologias devem ser projetados e desenvolvidos de modo que todas as pessoas possam perceber, entender, navegar e interagir com a web, visando garantir que esses sistemas sejam utilizados pela maior quantidade possível de pessoas.

> O poder da web está em sua universalidade. O acesso por todas as pessoas, independentemente da deficiência, é um aspecto essencial — Tim Berners-Lee

Para que a acessibilidade seja implementada num site, ele deve seguir as normas definidas pelo `WCAG` — *Web Content Accessibility Guidelines* — um extenso e detalhado documento que inclui diretrizes precisas e independentes de tecnologia para conformidade com a acessibilidade. As normas definidas nesse documento podem ser resumidas em quatro categorias principais:

- **Perceptibilidade**: estabelece que os dados e componentes da interface devem ser apresentados de modo que os utilizadores sejam capazes de perceber o conteúdo de alguma forma, utilizando um ou mais sentidos

- **Operabilidade**: estabelece que os utilizadores devem ser capazes de controlar os componentes da interface de alguma forma

- **Compreensibilidade**: estabelece que os dados e o funcionamento da interface devem ser compreendidos pelos utilizadores

- **Robustez**: estabelece que o conteúdo seja suficientemente robusto para ser interpretado de forma segura por uma ampla variedade de navegadores — incluindo tecnologias assistivas — tanto atuais quanto futuras

### 1.1 Semântica

De maneira universal, a **semântica** se refere ao estudo do significado e sentido atribuído aos diferentes recursos de uma linguagem — como símbolos, termos e palavras, por exemplo. Em sistemas computacionais, a semântica garante que um determinado processo estruturalmente correto produza o comportamento esperado ao ser executado.

No `HTML`, a semântica se refere ao uso de elementos que descrevem claramente o significado do conteúdo — sem necessariamente comunicar a forma como ele deve parecer visualmente, mas sim o que ele representa —, assim sendo, cada elemento semântico foi criado para uma determinada finalidade.

A semântica existe desde a primeira release da linguagem, entretanto, ela era simples e limitada: ao longo do tempo, a falta de recursos para expressar o significado do conteúdo se tornou um problema: o uso excessivo dos elementos `<div>` e `<span>` para absolutamente tudo e muitas outras funcionalidades visuais que misturavam a forma como o conteúdo era apresentado e estruturado tornou a web problemática.

A release mais recente da linguagem — `5` — foi desenvolvida para resolver o problema do uso excessivo desses elementos genéricos: ela introduziu um conjunto de elementos de seccionamento semântico e redefiniu semanticamente outros elementos que já existiam.
