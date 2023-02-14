<div align="center">
  <h1>Rocket buffer 🚀</h1>

  <h4>Um conjunto de aulas disponibilizada pela <a href="https://discord.gg/Bzx3tzJw">Discover</a> com o intuito de compartilhar <strong>conhecimento</strong> e <strong>aprendizado</strong> com a <strong>comunidade</strong>!<h4>
  
  <p><a href="">Português-Brasileiro<a/>  · <a href="">English</a> </p>
  
</div>
<br/>


<h2>Tópicos da aula</h2>

<ul>
  <li><a href="#first-step-dev">Primeira etapa do desenvolvimento</a></li>
  <li><a href="#folder-structure">Estruturas de pastas</a></li>
</ul>

<br/>
<br/>

<h2 id="first-step-dev">Primeira etapa do desenvolvimento</h1>

> A primeira etapa do desenvolvimento é o pensamento, a criação do algoritmo, é preciso pensar em:
> <ul>
  >  <li>O que será o projeto;</li>
  >  <li>O que será usado no projeto;</li>
  >  <li>Quais features o projeto terá;</li>
  >  <li>Como será o funcionamento do projeto.</li>
> </ul>
>
> Um caminho a pecorrer é importante, sem ele o desenvolvedor ficará perdido, sem saber o que fazer, implementar e remover



<details>
<summary><strong>Exemplo de projeto</strong></summary>
  
  <br/>
  
  > <h4>Sistema de cadastro / login automático por serial</h4>
  >
  > 1. Um sistema de cadastro e um login automático por serial.
  > <br/>
  >
  > 2. O que será usado no projeto:
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
  > 3. Features:
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
  > 4. Funcionamento:
  > 
  > 
  >     **1.** Quando o player entrar pegue o seu serial e verifique se ele está existente no banco de dados: (Se sim pule para a etapa 6, se não continue).
  >     
  >     **2.** Mostre a tela de cadastro e capture todas a informações digitadas nos campos(Usuário, Senha, comfirmarSenha.
  >     
  >     **3.** Verique se as senhas dos campos(senha, confirmarSenha) são iguais.
  >     
  >     **4.** Crie uma conta com todas as informações capturadas dos campo.
  >     
  >     **5.** Envie para o banco de Dados todas as informações capturadas no processo (Serial, Usuário, Senha)
  >     
  >     **6.** Pegue o serial do player e busque no banco de dados suas informações(Usuário e Senha), em seguida logue o player com as informações retornadas

</details>

<br/>

<h2 id="folder-structure">Estruturas de pastas</h1>

> Estruturas de pastas são formas de estruturar seu projeto, se bem usada pode trazer os seguintes benefícios
> - Uma organização e legibilidade grande para o projeto;
> - Torna mais fácil o trabalho em grupo;
> - Torna o projeto mais profissional;
> - [...].
> 
> Entre outros benefícios. Estruturar bem seu projeto é o que difencia você de um profissional e um amador

<details>
<summary><strong>Exemplo de estrutura de pasta</strong></summary>

  <br/>

  - <h3>Public</h3>
  
    > <img src="https://user-images.githubusercontent.com/95851792/218877350-a0b77dae-ee4d-4d92-b9ec-b1c90475f38d.png"></img>
    > <p>Tudo aquilo público, como os assets do projeto(imagens, ícones e etc) e entres outros.</p>
  
  <br/>
  
  - <h3>Source</h3>
  
    > <img src="https://user-images.githubusercontent.com/95851792/218877350-a0b77dae-ee4d-4d92-b9ec-b1c90475f38d.png"></img>
    >
    > <p>Tudo aquilo público, como os assets do projeto(imagens, ícones e etc) e entres outros.</p>
    
    <br/>
    
    - <h3>Core</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218877350-a0b77dae-ee4d-4d92-b9ec-b1c90475f38d.png"></img>
      >
      > <p>Tudo aquilo público, como os assets do projeto(imagens, ícones e etc) e entres outros.</p>
      
      <br/>
      
    - <h3>Events</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218877350-a0b77dae-ee4d-4d92-b9ec-b1c90475f38d.png"></img>
      >
      > <p>Tudo aquilo público, como os assets do projeto(imagens, ícones e etc) e entres outros.</p>
      
      <br/>
      
    - <h3>Utils</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218877350-a0b77dae-ee4d-4d92-b9ec-b1c90475f38d.png"></img>
      >
      > <p>Tudo aquilo público, como os assets do projeto(imagens, ícones e etc) e entres outros.</p>
      
   <br/>
      
  - <h3>Arquivos gerais</h3>

    > <img src="https://user-images.githubusercontent.com/95851792/218877350-a0b77dae-ee4d-4d92-b9ec-b1c90475f38d.png"></img>
    >
    > <p>Tudo aquilo público, como os assets do projeto(imagens, ícones e etc) e entres outros.</p>
  
  <br/>

  <details>
  <summary><h3>Ideia final</h3></summary>
  
  <br/>
  
  <img src="https://user-images.githubusercontent.com/95851792/218861870-19adb83d-cbf7-496f-aa7d-eb0100f92119.png"></img>
      
  </details>
  

 

</details>
