<div align="center">
 
 # DESAFIO WEB 3.0 STACKX

</div>

 Trago-lhe aqui três Projetos que faz parte do Módulo Web 3.0 do curso para `Desenvolvedor Full Stack da Editech StackX`. O conceito destas aplicações, serão três Single Page Aplication, aplicadas em <i>`React`,`Angular`,`Vue.js`</i>. Cada uma foi estruturada dentro de suas particularidades e seus conceitos utilizados conforme 
a demanda dos Frameworks, Bibliotecas e Linguagens manuseadas.A intenção da construção destes Projetos será uma lista com as tecnologias a qual tem experiência, onde será feito um array no HTML e a inserção de um map para listar. Ao clicar no botão de linguagem o texto de apresentação ”Olá meu nome....” mudará para a linguagem selecionada. O botão de linguagem deve ser um componente onde passará 3 propriedades: Título, ícone e o click dele. Estarei apresentando aqui o segundo Projeto feito em Angular. 

***
   
  # Entendendo sobre o conceito Angular
  
 O AngularJS é um framework de código aberto usado para construir aplicativos para web baseados em uma única página dinâmica. Os desenvolvedores também usam essa ferramenta para criar menus animados para páginas de internet baseadas em HTML. O framework é um conceito de Misko Hevery e Adam Abrons, engenheiros da Google. A empresa lançou a primeira versão do AngularJS em 2012 e tem mantido o serviço ativo desde então com atualizações e melhorias. 
 
  #  Desafio 02 Angular
 
  Esta aplicação foi construida em `Angular 5`, utilizando a plataforma `Vitets` que é um bundler, onde consegue usar compiladores e frameworks direto da caixa, além da criação de hot module e replacement dentro do Projeto. Foi utilizado também o arquivo ``SASS(SCSS)`` que é um programa escrito em `Ruby`, que reune folhas de estilo para um navegador, além de adicionar funcionalidades essenciais para o css como: variáveis, aninhamento, dentre outros. 
  
   <br>
  
  ### <div align="center"> [Clique aqui para acessar o Projeto](https://projeto-02-web-3-o-angular.vercel.app/)
   
   ***
   
   <img src="angular.png" align="center" height="500em" width="100%" href="https://projeto-02-web-3-o-angular.vercel.app/"> 
   
   ***
 
 #  Passo a Passo da contrução do Projeto
        
   ###  Executar o comando CLI
 
 - ```npm install -g angular/cli``` ,irá gerar o CLI( Command Line Interface) dentro do Angular, uma linha de comando cujo o objetivo principal será facilitar o gerenciamento do projeto nesse framework, além de executar o Angular dentro da máquina global.
 
 #
 
###  Começar um Projeto Angular
   
- ```ng new```, ao criar esse comando, será inicializada uma nova pasta contendo uma estrutura de diretório com os arquivos necessários para uexecução do projeto.
 
 #
 
###  Abrir o Projeto no Terminal
   
- ```code .```, Aplicar este comando no PowerShell para ter acesso ao Projeto no VsCode.

 #
 
###  Efetuar o Projeto no servidor
   
- ```ng serve```,  é um comando `ajudante` que permite executar o projeto Angular no ambiente de desenvolvimento, criando um servidor web local para servir os arquivos do programa. Executando este comando, clique no endereço http://localhost:4200/ a aplicação carregará automaticamente os arquivos de origem no navegador.
 
 #
 
###  Criando o component
   
- ```ng g c```, gera todos or arquivos components em HTML, SCSS, TS, SPEC e Module.ts. Dentro do component usa-se um decorator chamado `@component` um seletar para fazer a declaração da view.
 
 #
 
###  Criando o Module
   
- ```ng g m```, constrói mais de um component declara quais componentes serão usados e gerenciados, quais services serão injetados, além de modularizar a aplicação em si.
 
 #
 
###  Criando o service
   
- ```ng g s`` ,auxilia e separa do component algumas informações importantes como também o modo como iremos obter lógica de negócio e requisição ao servidor.
 
 #
 
###  Instalando o Material Angular
   
- ```ng add @angular/material``` ,é a implementação oficial para o Angular do `material design` uma especificação de interfaces interativas do Google. O Material design cobre desde pequenos elementos como: ícones, cores;  até elementos maiores como : cards, imagens dentre outros.
 
 #
 
###  Implementando o Build
   
- ```ng build```, Execute ng build para compilar o projeto. Os artefatos de construção serão armazenados no diretório dist/ para ser aberto em um navegador.
 
 #
 
 ###  Executando o test no Projeto
   
- ```ng test```, executa os testes de unidade via Karma dentro da instância do navegador.
 
 #
 
 ###  Executando test e2e 
   
- ```ng test```, permite abrir a palicação no browser e interatuam com ela para garantir que as funcionalidades executam corretamente.
 
 #
 
 ###  Conceito de Routing
   
- É uma maneira simples de navegar nas páginas do app. Permite que os usuários criem um aplicativo de página única com múltiplas visualizações e de navegação entre elas. Os usuários podem alternar entre essas visualizações sem perder o estado e as propriedades do aplicativo.  
 
 
 
 

 
 
   

 
 








