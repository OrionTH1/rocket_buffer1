<div align="center">
  <h1>Rocket buffer 🚀</h1>

  <h4>A lessons playlist by <a href="https://discord.gg/Bzx3tzJw">Discover</a> with the intention of share <strong>knowledge</strong> and <strong>learnings</strong> with the <strong>community</strong>!<h4>
  
  <p><a href="https://github.com/OrionTH1/rocket_buffer1/blob/main/README.md">Português-Brasileiro</a>  · <a href="https://github.com/OrionTH1/rocket_buffer1/blob/main/docs/english-readme">English</a> </p>
  
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
> Um caminho a percorrer é importante, sem ele o desenvolvedor ficará perdido, sem saber o que fazer, implementar e remover



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
  >       - [ ] Navegação por TAB
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
  >     **3.** Verifique se as senhas dos campos(Senha, comfirmarSenha) são iguais.
  >     
  >     **4.** Crie uma conta com as informações capturadas dos campos(Usuário, Senha).
  >     
  >     **5.** Envie para o banco de dados todas as informações capturadas no processo (Serial, Usuário, Senha)
  >     
  >     **6.** Pegue o serial do player e busque no banco de dados suas informações(Usuário e Senha), em seguida logue o player com as informações retornadas

</details>

<br/>

<h2 id="folder-structure">Estruturas de pastas</h1>

> Estruturas de pastas são formas de estruturar seu projeto, se bem usadas pode trazer os seguintes benefícios:
> - Uma organização e legibilidade grande para o projeto;
> - Torna mais fácil o trabalho em grupo;
> - Torna o projeto mais profissional;
> - [...].
> 
> Entre outros benefícios. Estruturar bem seu projeto é umas das características que torna você um profissional melhor.

<details>
<summary><strong>Exemplo de estrutura de pasta</strong></summary>

  <br/>

  - <h3>Public</h3>

    > <img src="https://user-images.githubusercontent.com/95851792/218883668-1bfde26d-4cc2-4d70-88d5-c5de1d306543.png"></img>
    > <p>Tudo aquilo público, como os assets(imagens, ícones e etc) do projeto e entres outras coisas.</p>
  
  <br/>
  
  - <h3>Source</h3>

    > <img src="https://user-images.githubusercontent.com/95851792/218883369-1567812c-5ab3-40d3-aedd-b706127366c7.png"></img>
    >
    > <p>É a fonte do nosso código, aonde está o funcionamento principal do código.</p>
    
    <br/>
    
    - <h3>Core</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218883772-f7eaef7f-8bfd-4766-aa5d-3990942097eb.png"></img>
      >
      > <p>Aqui está o código principal, aonde tudo se junta para ocorrer o funcionamento do código.</p>
      
      <br/>
      
    - <h3>Events</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218883949-deb01a69-6c66-42d7-bc15-1aaacc835bc4.png"></img>
      >
      > <p>Aqui ficam os listens, que quando disparados, chamam outra parte ou função do código.</p>
      
      <br/>
      
    - <h3>Utils</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218884097-eddafd98-879c-4e03-8b89-dc05a84179a8.png"></img>
      >
      > <p>Aqui ficam algumas utilidades, que podem ser exportadas posteriormente para outra parte do código.</p>
      
   <br/>
      
  - <h3>Arquivos gerais</h3>

    > <img src="https://user-images.githubusercontent.com/95851792/218884258-69c53540-f03f-4187-8153-1f6c45c6f6db.png"></img>
    >
    > <p>Arquivos gerais são todos aqueles que não tem um tópico definido ou os que são recomendados está no escopo inicial da pasta como o meta.xml, .git e entre outros.</p>
  
  <br/>

  <details>
  <summary><h3>Ideia final</h3></summary>
  
  <br/>

  <img src="https://user-images.githubusercontent.com/95851792/218884547-56b4d081-c596-446b-b5f9-b46facee806f.png"></img>
      
  </details>
  

 

</details>
