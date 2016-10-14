Arquitetura do sistema Free Code Camp
====================================

**Alunos:** Arthur Vargas, Lucas Pereira Monteiro, Thiago Lucas dos S. Sandi

**Professor:** Marco Túlio Oliveira Valente

**Monitor:** José Laerte Xavier

**Repositório Github:** https://github.com/FreeCodeCamp/FreeCodeCamp

Descrição do sistema
--------------------

Free Code Camp é um sistema de código aberto onde você pode aprender a desenvolver em várias linguagens de programação e *frameworks*, tais como: HTML 5, CSS3, JavaScript, interação com Banco de Dados, Node.js, React.js, D3.js, além disso é possível aprender a usar o Git e o GitHub.

A principal filosofia de aprendizado do Free Code Camp é o aprendizado através da prática. O usuário tem acesso à centenas de desafios, que servem de ferramenta para que ele pratique suas habilidades. O sistema de desafios é mantido e alimentado pela comunidade do Free Code Camp e está em constante atualização. O usuário também recebe especificações de projetos em forma de estórias de usuário e, como desenvolvedor, ele deve descobrir como construir a aplicação baseada nessas especificações fornecidas, usando os métodos e práticas aprendidos no sistema. Todas essas funcionalidades são oferecidas ao usuário gratuitamente.

Existem 4 certificações que podem ser obtidas no Free Code Camp: *Front End Development* (400 horas), *Data Visualization* (400 horas), *Back End Development* (400 horas), Desenvolvimento de Projetos sem fins lucrativos (800 horas), e por último uma entrevista (80 horas), totalizando ao todo 2,080 horas para receber todos os certificados disponíveis até o momento.

O Free Code Camp possui em seu sistema 2 componentes principais, o primeiro é o código base do *backend* que é um código aberto disponível no GitHub, atráves da licença BSD3, e também o *front end* que é utilizado no sistema atual de aprendizado na web que está no endereço https://freecodecamp.com/.

O objetivo do sistema é fornecer para os desenvolvedores novatos uma plataforma de desenvolvimento de fácil aprendizado. Podemos resumir o objetivo em:   “FreeCodeCamp é uma comunidade amigável de código aberto onde você aprende a desenvolver códigos de forma eficiente, e também à ajudar organizações sem fins lucrativos. Nós ajudamos nossos campistas a construir portfólios com excelência, projetos baseados em aplicações reais usadas por pessoas reais”.

Vocabulário Específico
----------------------

 - *Browser*: software que permite acessar a internet e interagir com páginas web.
 - *Commit*: salvar um código que foi alterado em um Controlador de Versão, como o GitHub por exemplo.
 - ECMAScript: linguagem de programação padronizada pela Ecma International e que foi a base para o JavaScript. 
 - ECMAScript 5 / ES5: é a quinta edição do ECMAScript e que foi padronizada em 2009. Esse padrão foi quase que completamente implementado por todos os *browsers*.
 - ECMAScript 6 / ES6: é a sexta edição do ECMAScript e que foi padronizada em 2015. Ainda está parcialmente implementada pelos browsers, como pode ser verificada na figura de representação de compatibilidade abaixo, onde a porcentagem indica a quantidade de características do ES6 que já estão disponíveis.
   ![tabela de compatibilidade es6](https://raw.githubusercontent.com/lucasmonteiro001/engenharia-de-software-2-freeCodeCamp/master/img/tabela_compatibilidade.png)
   			Fonte: http://kangax.github.io/compat-table/es6/ 
   			
 - *End-to-end*: é um princípio de design da área de redes de computadores que diz respeito a comunicação entre processos fim a fim; 
 - *Feature*: característica de um software, por exemplo, performance. 
 - *Framework*:  é uma abstração que une códigos comuns entre vários projetos de software provendo uma funcionalidade genérica. Um *framework* pode atingir uma funcionalidade específica, por configuração, durante a programação de uma aplicação; 
 - *Full-stack*: um *framework full-stack* seria aquele que é, de certa forma, mais complexo e que serve o desenvolvedor com funcionalidades.  
 - Função *callback*: pedaço de código, ou função (x), que é passado para outra função (y) e que somente é executado quando a função (y) chamá-lo explicitamente. 
 - *Issue*: No contexto de uma ferramenta de controle de versão como o GitHub, as issues são uma forma de manter registro de tarefas, melhoramentos e *bugs* de um projeto. As *issues* são compartilhadas e discutidas pelos membros de um projeto de forma que se ache uma solução para elas.
 - *Milestone*: normalmente utilizado em Gerenciamento de Projetos para especificar pontos chave/específicos durante o desenvolvimento de um software, tais como início do projeto, entrega de versão 1.0 e fim do projeto. 
 - *Mobile-first:* abordagem para o design responsivo. Primeiro, projete para pequenas telas, depois adicione conteúdo e características para telas maiores. 
 - *Open Source*: código aberto. 
 - Programação orientada a eventos: em geral um loop principal espera por eventos e executa um função *callback* quando um evento ocorre. 
 - *Pull request*: Mudanças que foram subidas para um repositório e que necessitam de aprovação para serem integradas ao código principal.
 -  *Push*: Enviar *commits* para o repositório onde o código está localizado. 
 - SDK: *Software Development Kit*. Normalmente os SDKs são disponibilizados por empresas ou projetos de código aberto para que programadores externos tenham uma melhor integração com o software proposto.
 - *Transpiler*: é um tipo de compilador que obtém como entrada um programa escrito em uma linguagem X e gera o código equivalente na linguagem Y. No contexto desse trabalho, o transpiler obtém um código em ES6 e converte para ES5.

Equipe de desenvolvimento
-------------------------

Free Code Camp é um sistema bastante popular no GitHub (182.575 estrelas e 6.930 *forks* no dia 13/10/2016), e por ter uma popularidade tão alta, contou com a contribuição de dezenas de desenvolvedores de vários lugares do mundo. 

Entre novembro de 2013 até os dias atuais foram feitos inúmeros *commits*, para uma melhor visualização veja a imagem abaixo onde temos o gráfico do número de commits ao longo do tempo.

![contribuicoes ao longo do tempo](https://raw.githubusercontent.com/lucasmonteiro001/engenharia-de-software-2-freeCodeCamp/master/img/commits.png)
   			Fonte: http://kangax.github.io/compat-table/es6/ 

O principal contribuidor do projeto e também professor do Free Code Camp é o usuário QuincyLarson (1648 *commits*), seguido por BerkeleyTrue (1253 *commits*), Sahat (1143 *commits*) e a partir de Sahat o número de commits cai para 500 e continua a decrescer.

Evolução do sistema
-------------------

O projeto do Free Code Camp no GitHub foi iniciado em novembro de 2013. A evolução e adição de novas *features* neste projeto geralmente são motivadas pelo sistema de *issues* e *pull requests*. Uma vez que problemas ou propostas são apontadas por usuários e/ou desenvolvedores, uma *issue* é gerada, e assim, os contribuidores do sistema tentam resolvê-la. A seguir, mostraremos algumas *milestones* importantes do sistema em ordem cronológica:

 - 07/2015 - *Nonprofit Projects*: nesse *update*, toda a infraestrutura dos projetos para ajudar organizações sem fins lucrativos foi migrada do Google Forms para a base de dados principal do sistema. E com isso foram adicionadas funcionalidades para que os usuários e os *stakeholders* pudessem interagir, criar e se incluir em projetos dentro da própria aplicação;
 - 01/2016 - *Challenges*: Novos desafios foram adicionados, levando em conta o uso das tecnologias React + SASS. Além disso, novos desafios podem ser criados e designados para os usuários tendo como base *issues* do GitHub;
 - 01/2016 - *New Curriculum*: adiciona novos currículos JS e jQuery e a funcionalidade *on-the-go curriculum*;
 - 01/2016 - *Framework Migration* - migração de *framework* de Express.js para Loopback.js;
 - 01/2016 - *Camperbot*: Lançamento do *Camperbot*, um *chatbot* que auxilia usuários nos chats Gitter do Free Code Camp através de comandos interativos;
 - 01/2016 - *Follow Mode*: adicionadas várias funcionalidades para o usuário, como: seguir outros usuários, visualizar perfis de usuários, trancar informações do perfil e torná-las privadas, etc;
 - 09/2016 - *Hotkeys*: implementa a funcionalidade de *hotkeys* (atalhos de teclado) para os usuários, de forma que  estes possam navegar pelo site e editar seus códigos usando apenas o teclado. Os usuários podem definir suas próprias *hotkeys*;
 
 Muitas funcionalidades importantes estão em aberto e sendo implementadas no momento, tais como:
 - *Night Mode*: Uma versão alternativa do CSS do sistema para ambientes com pouca iluminação.
 - *Simplify Authentication*: Um jeito de simplificar a autenticação dos usuários para não gerar problemas futuros com gerenciamento de contas. A idéia é que os usuários possam se autenticar apenas através de contas Google ou GitHub, sem uso de senha.
 - *Real-time pair programming:* Usuários podem programar com parceiros de programação em tempo real e navegar pelos desafios do site juntos. Além de poderem se comunicar com áudio via VOIP.
 - *Teacher mode*: Um modo para professores feito para que estes consigam gerenciar e acompanhar o progresso usuários dentro de um grupo de trabalho, além de terem acesso a gráficos informativos sobre o desempenho dos seus alunos.
 - *Offline mode with syncing:* Criação de um modo *offline* para que os usuários possam programar e resolver os desafios mesmo quando não estiverem com acesso a internet. Para isso, o conteúdo das aulas pode ser baixado e completado *offline* para que depois o usuário submeta e sincronize seu progresso *online*.

Para ilustrar a evolução do sistema, temos abaixo o gráfico de frequência de submissão de código desde 18/10/2016.

![frequencia submissao](https://raw.githubusercontent.com/lucasmonteiro001/engenharia-de-software-2-freeCodeCamp/master/img/frequencia_submissao.png)
   			Fonte: https://github.com/FreeCodeCamp/FreeCodeCamp


Principais linguagens
---------------------

**JavaScript**

O projeto é desenvolvido principalmente em ECMAScript 6 (ou apenas ES6), que é a nova versão da linguagem JavaScript. Como a essa nova versão do JavaScript ainda não é compatível com os *browsers*, é usada uma ferramenta chamada Babel (explicado na seção de ferramentas), que serve de *transpiler* para compilar o código em ES6 e convertê-lo para ES5 (que é compatível com os *browsers* atuais).

Exemplo:

    ES6
    	[1,2,3,4,5].filter(val => val % 2 === 0);

    ES5
    	[1,2,3,4,5].filter(function(val) {
    		if(val % 2 === 0){
    			return true;
    		}
    		else {
    			return false;
    		}
    	});


**HTML**

Linguagem de marcação para criar páginas Web. Essa linguagem descreve como uma página Web deve ser estruturada utilizando-se *tags*.

**Jade/Pug**

Linguagem de template que gera código HTML. Sua principal característica é que ela permite o uso de uma sintaxe mais simples e poderosa que escrever em HTML puro. Esse tipo de linguagem também é conhecida como HTML *preprocessor*. Depois do código escrito, roda-se um script que converte o código para HTML.

Exemplo:

    Jade
    	h1 Ola, meu nome é
    	p.pull-left SemNome

    HTML
    	<h1> Olá, meu nome é </h1>
    	<p class="pull-left"> Sem nome </p>

**CSS**

CSS (*Cascading Style Sheets*) é uma linguagem para Web que define como os elementos devem ser mostrados. Exemplo: um elemento deve ter 14px de tamanho, estar alinhado à esquerda, ter uma borda sólida, sua cor de linha deve ser verde e a cor de fundo amarela.

**Sass**

Sass (*Syntactically Awesome Style Sheets*) é um CSS *preprocessor*. Utilizando-se Sass, é possível escrever em uma linguagem de programação mais amigável e mais poderosa que CSS puro. Exemplo: criar variáveis em Sass e utilizá-las depois, o que não é possível em CSS. Outro exemplo seria o de aninhar elementos, como mostrado abaixo.

Exemplo:

    Sass
    	div.red {
    		color: red;
    		p {
    			color: blue;
    		}
    	}

    CSS
	    div.red {
	    		color: red;
	    	}
	    div.red p {
	    		color: blue;
	    	}

**Less**

Less é um CSS *preprocessor* e possui a mesma função do Sass.

Ambiente de execução
--------------------

**Node.js**

É um ambiente de execução de JavaScript construído sobre o motor JavaScript V8 do Chrome. Node.js usa um modelo de I/O não blocante e é baseado em eventos (fluxo do programa é determinado por eventos, tais como mensagens e cliques de mouse pelo usuário).

**NPM**
O gerenciador de pacotes utilizado pelo Node.js é o npm (Node Package Manager), o qual é o maior gerenciador de pacotes de código aberto da atualidade.

Principais frameworks
---------------------

**Loopback**

Loopback é um *framework* de código aberto que consiste em bibliotecas de módulos do Node.js e que funciona de maneira *full-stack*, ajudando o desenvolvedor na construção de APIs *mobile*, web e de outros dispositivos. Esse framework entra como uma camada acima dos serviços e dos dados da aplicação, e provê diversas funcionalidades que habilitam o desenvolvedor a, por exemplo:

 - Criar REST APIs dinâmicas e com design *end-to-end*;
 - Acessar e se conectar a dados de diversas fontes, como: Oracle, MySQL, PostgreSQL, MS SQL Server, MongoDB, SOAP e outras REST APIs;
 - Monitorar e implantar os Apps de forma gráfica através da ferramenta Strongloop Arc;
 - Executar as aplicações localmente ou na nuvem;
 - Criar aplicações cliente de forma fácil usando diferentes SDKs;

A figura a seguir ilustra como é a estrutura de uma aplicação em Loopback. Esse *framework* tem papéis em diferentes partes da aplicação através do seu extenso conjunto de módulos:

![loopback](https://raw.githubusercontent.com/lucasmonteiro001/engenharia-de-software-2-freeCodeCamp/master/img/loopback.png)
   			Fonte: https://loopback.io/ 

**Bootstrap**

É um *framework* HTML, CSS e JavaScript para desenvolvimento de projetos responsivos e mobile-first.

Principais ferramentas
----------------------

O sistema usa uma grande variedade de ferramentas para gerar a sua versão que será executada em produção. Várias dessas ferramentas ajudam o programador a otimizar seu tempo, seja por meio facilidade de escrever em determinada DSL ao invés da linguagem a ser interpretada pelos *browsers*, ou mesmo para executar testes automatizados sem a necessidade de executar um script manualmente.

Dentre as ferramentas utilizadas, podemos destacar:

 - Gulp: segundo a própria descrição da ferramenta, sua função é automatizar e melhorar o fluxo de trabalho. Seguindo a convenção "código ao invés de configuração", torna seu uso mais simples para desenvolvedores. Na próxima subseção, será mostrado o *workflow* simplificado de *build* do sistema para que o leitor entenda como é feita a geração do código final.
 - Babel: biblioteca (*transpiler*) que converte código de ES6 para ES5.
 - Eslint: biblioteca que realiza a análise estática de código para procurar por padrões problemáticos ou por pedaços de código que não seguem um padrão determinado em um guia de estilo.
 - Travis: ferramenta de integração contínua que facilita a verificação de código que foi *committed* e *pushed* para o GitHub. Após o código ter sido *pushed*, o GitHub notifica o Travis e ele executa os testes definidos pelo sistema para verificar se o novo código não quebra nenhuma função já existente no sistema.
 - Var.ci: ferramenta para automatizar o gerenciamento de *issues* e *pull requests*.
 - Bower: gerenciador de versões para *frameworks*, bibliotecas e arquivos estáticos.
 - Snyk: ferramenta para detecção, prevenção e correção de vulnerabilidades conhecidas para aplicativos desenvolvidos em Node.js.
 - pm2Start: ferramenta para gerenciamento de aplicativos Node.js que estão executando em produção. Essa ferramenta provê vários serviços, tais como gerenciamento de memória e monitoração de métricas pré-definidas.
 - Webpack: biblioteca que funciona como um empacotador de módulos. Ao se executar o webpack, ele pega todos os módulos com dependências e gera arquivos estáticos contendo esses módulos.
 

Ambiente de desenvolvimento
---------------------------

O ambiente de desenvolvimento gira o torno do Gulp (*task runner*). Para otimizar a produção de código, inicia-se uma *task* do Gulp (*watcher*) que fica observando os arquivos. Por exemplo, se um arquivo .jade mudar, Gulp percebe essa mudança e executa uma tarefa que pega esse código e compila para HTML. Temos uma figura simplificada de como o gulp trabalha:

![build-flow gulp](https://raw.githubusercontent.com/lucasmonteiro001/engenharia-de-software-2-freeCodeCamp/master/img/build-flow.png)
   			Fonte: arquivo pessoal

Gulp, após realizar tarefas pré-configuradas, como as mostradas acima, gera uma pasta (nesse caso é *dist/*), a qual é o sistema final. Assim, o *browser* consegue ler os arquivos gerados, pois todos foram gerados como HTML, CSS ou JavaScript ES5.

As *tasks* mostradas na figura acima são explicadas na seção de principais ferramentas. Além das ferramentas mostradas no fluxo, para aumentar a segurança do sistema, Snyk é executado para procurar por vulnerabilidades do sistema.

Para garantir que o código criado não quebrou funcionalidades já existentes, quando o código é *pushed* para o GitHub, uma notificação é feita para o sistema Travis que executa os testes automatizados para verificar que todos os testes já escritos continuam sendo executados com sucesso.

Por fim, para monitorar a aplicação final, é usado a ferramenta pm2start que traz várias métricas sobre o sistema em execução, o que ajuda a monitorá-lo e garantir que tudo está ocorrendo sem problemas.

Arquitetura
-------------------------------------------------------
Após análise do sistema no GitHub, foi possível concluir que o sistema é dividido em 4 módulos: Client, Server, Public e Common. Onde cada um possui suas respectivas responsabilidades na execução e funcionamento do sistema.

**Client**

Neste módulo temos o código que deve ser executado somente no lado do cliente. Aqui são executadas as funções do cliente de acordo com o que foi requisitado. Temos 5 repositórios neste módulo: *commonFramework*, *less*, *rechallenge*, *sagas*, *utils*.

No repositório *commomFramework* temos o *framework* que executa e analisa os desafios feitos pelo cliente, desafios relacionados ao desenvolvimento do curso, temos funções para verificar qual o tipo de desafio, testar se o desafio foi feito corretamente, etc.

No repositório *less*, temos os arquivos .less da parte do cliente, estes arquivos possuem uma linguagem baseada em CSS. No repositório temos vários arquivos que definem o layout da página, por exemplo o arquivo map.less que define como será as cores de fontE, tamanho de margem, layout relacionado ao filtro, entre outras configurações de layout relacionadas ao mapa do sistema. Portanto podemos definir este módulo como as configurações de layout do cliente.

No repositório *rechallenge* é feito configurações para execução de determinado desafio, que pode ser selecionado pelo cliente na página do sistema.

O repositório *saga* serve para iniciar e lidar com os possíveis eventos do sistema. Por exemplo o arquivo execute-challenge-saga.js inicializa um evento relacionado à algum determinado desafio. Temos o arquivo err-saga.js também que adiciona o evento de erro caso ocorra, este evento de erro é descrito no seguinte código do arquivo:

    export default function errorSaga(action$) {
      return action$
        .filter(({ error }) => !!error)
        .map(({ error }) => error)
        .doOnNext(error => console.error(error))
        .map(() => ({
          type: 'app.makeToast',
          payload: {
            type: 'error',
            title: 'Oops, something went wrong',
            message: 'Something went wrong, please try again later'
          }
        }));
    }

O repositório *utils* contém utilitários comuns na execução do cliente, *utils* é usado em várias partes do código do cliente. Em *utils* temos por exemplo o arquivo flash-to-toast.test.js que faz testes de entradas de dados, como também temos arquivos que identificam qual o caminho das rotas de acesso do sistema na parte do cliente.

**Server**

Eeste módulo se relaciona com toda a parte que diz respeito ao servidor e tudo que é executado nele. Neste módulo o servidor é iniciado de acordo com as configurações pré-definidas e as variáveis de ambiente são setadas, os bancos de dados usados são definidos e são também definidos os middlewares a serem usados. Existem 7 diretórios neste módulo, que são: *boot*, *manifests*, *middlewares*, *resources*, *services*, *utils*, *views*, os quais serão explicados a seguir.

 - *boot*: aqui são definidas as rotinas de inicialização do sistema.
 - *manifests*: esse diretório contém arquivos json gerados em tempo de execução de acordo com cada cliente.
 - *middlewares*: são definidas as formas que o servidor vai lidar com os diferentes requisições do sistema, no sentido de servir como um *parser* para as diferentes linguagens pré-compiladas ou de domínio específico, de forma que elas sejam compiladas e convertidas para linguagens que o servidor entenda.
 - *resources*: este diretório contém alguns recursos do servidor, no caso, ele possui apenas o arquivo testimonials.json, que contém uma lista de testemunhos dados por usuários da aplicação, juntamente com informações básicas deste usuário e um *link* para a foto de perfil dele. Essa lista serve para abastecer a sessão de testemunhos da aplicação.
 - *services*: contém instanciações de alguns serviços da aplicação.
 - *utils*: contém utilitários, ou seja, funções úteis que facilitam o desenvolvimento e são usadas em outras partes do módulo. Um exemplo é o arquivo auth.js, que contém funções para lidar com a autenticação de um usuário ou setar o perfil de um usuário de acordo com seu perfil em outra plataforma, como o GitHub.
 - *views*: possui arquivos, em sua maioria, escritos em .Jade, e possui o papel de definir e configurar a parte de visualização no lado do servidor.

**Public**

Neste módulo é feito as configurações iniciais, e configurações básicas do sistema. Temos vários repositórios que definem vários fatores do sistema. Por exemplo o repositório css que define as configurações padrões de layout. Temos também o repositório fonts que contém arquivos de extensão .ttf que define as fontes usadas no sistema. Além disso temos vários outros repositórios que definem as configurações públicas do sistema(aquela que é visível sem necessitar nenhum tipo de login). Além do mais, esse repositório fornece os arquivos estáticos utilizados pela aplicação no lado do cliente.

**Common**

 O módulo *common* diz respeito a partes do sistema que são executados tanto no servidor quanto no cliente e é composto por 3 repositórios: *app*, *models*, *utils*, os quais são explicados a seguir: 
 
*App*: a aplicação usa React para definir a parte de visualização referente a interface de usuário, e é nesse módulo e que encontramos arquivos com extensão jsx, que definem algumas configurações para esta tecnologia. No repositório de *app* temos 5 outros repositórios que o compõe, sendo eles: *components*, *redux*, *routes*, *toasts* e *utils*.

 - *Components*: no repositório *components* é onde definimos questões relacionadas à navegação da barra do sistema, como também configurações relacionadas ao rodapé da página. Além de definir estes componentes temos também a definição do mapa do site, que é uma espécie de menu lateral que abre ao lado.
 - *Redux*: Nessa pasta temos alguns arquivos referentes a tecnologia Redux, que é um "recipiente de estados" que emite atualizações de estados do sistema em resposta a certas ações. Nesse sistema em específico, o Redux é usado em conjunto com a tecnologia React, e ambas funcionam muito bem em conjunto visto que o React abstrai a interface de usuário de forma que podemos descrevê-la como uma função de estado, o que é algo muito conveniente para a integração com o Redux.
 - *Routes*: No repositório *routes* é onde é feita a configuração das rotas do sistema, temos as configurações do repositório *settings* e *challenges* (o repositório *Admin* ainda não possui nenhum tipo de implementação). Além disso temos também os arquivos de extensão .jsx, que são scripts escritos na linguagem ExtendScript (uma extensão da linguagem JavaScript). Estes arquivos .jsx tem como propriedade a definição das modais do sistema, bem como seu preenchimento (títulos, strings, ou qualquer outro tipo de informação visual).
 - *Toasts*: no repositório *toasts* definimos algumas pequenas notificações bem simples que podem ser exibidas no sistema. Essas notificações são exibidas em pequenas janelas para o usuário com informações relevantes sobre seu progresso, entre outras notificações importantes.
 - *Utils*: contém utilitários, ou seja, funções úteis que facilitam o desenvolvimento e são usadas em outras partes do módulo.

*Models*: no repositório models é onde temos o modelo dos dados baseado na linguagem .json (javaScript Object Notation). Json é uma notação de objetos que tem como objetivo a troca de informações/dados entre sistemas. Neste repositório temos arquivos no formato .js e .json que definem o modelo de dados em várias funcionalidades do sistema. Para demonstração temos o arquivo User-Identity.json que define os dados referente à identidade do usuário, isso é feito na pequena parte do código abaixo:

    {
      "name": "userIdentity",
      "plural": "userIdentities",
      "base": "UserIdentity",
      "properties": {},
      "validations": [],
      "relations": {
        "user": {
          "type": "belongsTo",
          "model": "user",
          "foreignKey": "userId"
        }
      },
      "acls": [
        {
          "accessType": "*",
          "principalType": "ROLE",
          "principalId": "$everyone",
          "permission": "DENY"
        }
      ],
      "methods": {}
    }

*Utils*: contém utilitários, ou seja, funções úteis que facilitam o desenvolvimento e são usadas em outras partes do módulo. Um exemplo é o arquivo get-first-challenge.js, que faz algumas verificações e retorna o primeiro desafio que o usuário em questão terá de resolver ao logar no sistema.


Referências
-----------
- http://gulpjs.com/
- http://www.w3schools.com/html/html_intro.asp
- https://github.com/pugjs/pug
- http://learnjade.com/
- http://www.w3schools.com/css/css_intro.asp
- http://sass-lang.com/
- http://lesscss.org/
- https://github.com/strongloop/loopback
- https://loopback.io/
- http://www.i-programmer.info/news/150-training-a-education/9698-freecodecamp-not-just-a-bootcamp.html
- https://nodejs.org/en/
- https://en.wikipedia.org/wiki/Event-driven_programming
- https://www.npmjs.com/
- http://getbootstrap.com/
- http://moboom.com/blog-post/what-is-mobile-first-design-and-why-should-i-care/e14c121f-f539-aa88-23a1-5217e7b71283
- https://en.wikipedia.org/wiki/Source-to-source_compiler
- https://pt.wikipedia.org/wiki/ECMAScript
- https://en.wikipedia.org/wiki/Software_feature
- https://en.wikipedia.org/wiki/Milestone_(project_management)
- https://babeljs.io/
- http://eslint.org/
- https://travis-ci.org/
- https://var.ci/
- https://bower.io/
- https://snyk.io/
- http://pm2.keymetrics.io/
- https://webpack.github.io/
