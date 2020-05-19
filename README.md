
# PokeLovers


## Índice

* [1. Definição de produto](#1-definicao-de-produto)
* [2. Definição de persona ](#2-definicao-de-persona )
* [3. Protótipo de baixa fidelidade](#3-prototipo-de-baixa-fidelidade)
* [4. Teste de usabilidade](#4-teste-de-usabilidade)
* [5. Histórias de usuário](#5-historias-de-usuarios)



## 1. Definição do produto  
Nosso site permite com que jogadores novos e antigos, possam consultar as características de cada pokemon, como tipos, fraquezas e outros detalhes importantes antes de começar um jogo.  Dessa forma, podem usar a aplicação como um guia de bolso, sempre que precisarem de detalhes  sobre os pokes.  

## 2. Definição das personas   
  ### Ele: João Pereira 
  Idade: 32 anos;
  Profissão: Engenheiro;
  Classe Social: Média
  Estilo: Amante da cultura pop;
  Hobbies: Jogos e bicicletas;
  Detalhes:  É jogador mais avançado, consulta o site para tirar eventuais dúvidas sobre cada pokemon. 

  ### Ela: Luíza Santos 
  Idade: 17 anos;
  Profissão: Estudante;
  Classe Social: Média baixa
  Estilo: Rock e Pop;
  Hobbies: Jogos e ouvir música;
  Detalhes:  Ela está começando a jogar e precisa saber alguns detalhes sobre cada pokémon
  
## 3. Protótipo de baixa fidelidade 
Realizamos um protótipo de baixa fidelidade, pra entender como nossa interface deveria funcionar.
Realizamos um form que nos ajudou a definir o tema do nosso projeto e as necessidades do usuário. 
Foi constato que nosso usuário precisa conseguir obter algumas informações como: Tipo de pokémon, Habilidades, 
comida, ordenar por tamanho. 

[Protótipo de baixa fidelidade](https://marvelapp.com/8de5ahf/screen/69280075) 

Nos testes de usabilidade detectamos os seguintes problemas:


## 4. Testes de usabilidade: 
Nos testes de usabilidade detectamos os seguintes problemas:
* A necessidade de um botão para voltar à visualização de todos os Pokémons na tela.   
* A necessidade de um botão para voltar ao topo depois que a barra de rolagem fosse acionada.
* A indicação para a mudança da fonte para a letra usada no menu.
* A sinalização para que a caixa que acopla o pokémon ficasse de acordo com o tamanho de cada um.

Como os problemas foram resolvidos:
* Incluímos os botões: "Ver Todos", "Topo". Alteramos o tipo e tamanho da fonte usada no menu. 
E almentamos a caixa de fundo de cada pokémon. 


## 5. Histórias de usuário  

 1- Como usuário eu posso acessar a página inicial de boas vindas;
 - Definição de pronto: Página HTML + Texto de boas vindas + botão "Go".

 2- Como usuário eu posso ver todos os 151 pokémons apresentados na tela;
 - Definição de pronto: Página HTML + Cards com a imagem e o nome dos Pokemóns são apresentados assim que a página é carregada
  obedecendo a função do JS.

 3- Como usuário eu posso voltar para tela Inicial, assim como ser redirecionado à página de jogos quando acabar minha pesquisa no PokeLovers.
 - Definição de pronto: Botões "Tela Inicial" e "Ir pra jogo" com links para as páginas recíprocas, via função no JS.

 4- Como usuário eu posso pesquisar o pokémon por nome, ou parte do nome;
 - Definição de pronto: Input de pesquisa, que reconheça letras digitadas no campo e acionem a função de busca. 

 5- Como usuário eu posso filtrar meu pokemon por tipo e fraqueza;
 - Definição de pronto: Selectors com as opções de tipo e fraqueza que acionem a função de filtro. 

 6- CP... ter um card (modal) onde eu consiga ter informações detalhadas do pokémon selecionado.
 - Definição de pronto: Função que ao clicar no pokémon abre o modal com mais informações.

 7- CP... Ordenar os pokemons por "Nome A-Z", "Nome Z-A", "Tamanho - p/ + ", "Tamanho + p/ - " e "Maior Chance de Captura" 
 - Definição de pronto: Função ordenar usando Swith que capture o select escolhido.

 8- CP... voltar ao topo depois que a barra de rolagem for acionada e voltar à visualização de todos os Pokémons na tela.
 - Definição de pronto: Botões "Topo" e "Ver Todos" com funções JS com os devidos comandos.

 9- CP... visualizar a aplicação em telas de celular, tablet e computador 
 - Definição de pronto: Responsividade via Media Query no CSS.

 10- CP... posso visualizar a porcentagem de pokémons pertencente à cada tipo selecionado.
 - Definição de pronto: Exibe a informação no HTML via função JS.
