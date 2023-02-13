
# #rocket buffer_1 🚀

Rocket Buffer é um conjunto de aulas disponibilizada pela [Discover](https://discord.gg/Bzx3tzJw) com o intuito de compartilhar **conhecimento** e **aprendizado** com a **comunidade**!


<h2>Tópicos da aula</h2>

<ul>
  <li><a href="#first-step-dev">Primeira etapa do desenvolvimento</a></li>
  <li><a href="#folder-structure">Estruturas de pastas</a></li>
  <li><a href="#solid">SOLID</a></li>
</ul>

<br/>
<br/>

<h2 id="first-step-dev">Primeira etapa do desenvolvimento</h1>

> A primeira etapa do desenvolvimento é o pensamento, a criação do algoritmo, é preciso pensar em:
> <ul>
>  <li>O que será o projeto - <a href="#first-step">1</a></li>
>  <li>O que será usado no projeto - <a href="#second-step">2</a></li>
>  <li>Quais features o projeto terá - <a href="#third-step">3</a></li>
>  <li>Como será o funcionamento do projeto - <a href="#fourth-step">4</a></li>
> </ul>
>
> Um caminho a pecorrer é importante, sem ele o desenvolvedor ficará perdido, sem saber o que fazer, implementar e remover

<details open>
<summary><h3>Projeto de exemplo</h3></summary>
  
  > <h4>Sistema de cadastro / login automático por serial</h4>
  >
  > 1. <span id="first-step">Um sistema de cadastro e um login automático por serial. </span>
  > <br/>
  >
  > 2. <span id="second-step">O que será usado no projeto: </span>
  >
  >     - [ ] Uma UI de um painel de cadastro contendo campos de (Usuário, Senha, confirmarSenha)
  >
  >     - [ ] Banco de Dados Contendo: (Serial, Usuário, Senha)</a>
  >
  >     - <a href="https://wiki.multitheftauto.com/wiki/OnPlayerJoin"><em>onPlayerJoin</em></a>
  >     
  >     - <a href="https://wiki.multitheftauto.com/wiki/AddAccount"><em>addAccount</em></a>
  >     
  >     - <a href="https://wiki.multitheftauto.com/wiki/LogIn"><em>logIn</em></a>
  >     
  > <br/>
  > 
  > 3. <span id="third-step">Features: </span>
  > 
  >     - [ ] Cadastro com usuário e senha
  >     
  >     - [ ] Login automático de acordo com o serial 
  >     
  >     - Outros:
  >       - [ ] Naveção por TAB
  >       
  >       - [ ] Botão que permita esconder/mostrar a senha digitada
  > 
  > <br/>
  > 
  > 4. <span id="fourth-step">Funcionamento: </span>
  > 
  >     1- Quando o player entrar pegue o seu serial e verifique se ele está existente no banco de dados: (Se sim pule para a etapa 6, se não continue).
  >     
  >     2- Mostre a tela de cadastro e capture todas a informações digitadas nos campos(Usuário, Senha, comfirmarSenha.
  >     
  >     3- Verique se as senhas dos campos(senha, confirmarSenha) são iguais.
  >     
  >     4- Crie uma conta com todas as informações capturadas dos campo.
  >     
  >     5- Envie para o banco de Dados todas as informações capturadas no processo (Serial, Usuário, Senha)
  >     
  >     6- Pegue o serial do player e busque no banco de dados suas informações(Usuário e Senha), em seguida logue o player com as informações retornadas

</details>




<h2 id="folder-structure">Estruturas de pastas</h1>

<h2 id="solid">SOLID</h1>
