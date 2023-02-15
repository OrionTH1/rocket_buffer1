<div align="center">
  <h1>Rocket buffer 🚀</h1>

  <h4>A lessons playlist by <a href="https://discord.gg/Bzx3tzJw">Discover</a> with the intention of share <strong>knowledge</strong> and <strong>learnings</strong> with the <strong>community</strong>!<h4>
  
  <p><a href="https://github.com/OrionTH1/rocket_buffer1/blob/main/README.md">Português-Brasileiro</a>  · <a href="https://github.com/OrionTH1/rocket_buffer1/edit/main/docs/english-readme.md">English</a> </p>
  
</div>
    
<br/>

<h2>Lessons Topics</h2>

<ul>
  <li><a href="#first-step-dev">First step of development</a></li>
  <li><a href="#folder-structure">Folder Structures</a></li>
</ul>

<br/>
<br/>

<h2 id="first-step-dev">First step of development</h1>

> The first step of development is thinking, the creation of the algorithm, you need to think about:
> <ul>
  >  <li>What the project will be;</li>
  >  <li>What will be used in the project;</li>
  >  <li>What features will the project have;</li>
  >  <li>How the project will work.</li>
> </ul>
>
> A way to go is important, without it the developer will be lost, not knowing what to do, implement and remove.



<details>
<summary><strong>Project example</strong></summary>
  
  <br/>
  
  > <h4>Sign up system / automatic login by serial</h4>
  >
  > 1. A sign up system and a automatic login by serial.
  > <br/>
  >
  > 2. What will be used in the project:
  >
  >     - [ ] A UI of a sign up form containing inputs of (User, Password, confirmPassword)
  >
  >     - [ ] Database Containing: (Serial, User, Password)
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
  >     - [ ] Sign up with username and password
  >     
  >     - [ ] Automatic login according to serial
  >     
  >     - Others:
  >       - [ ] TAB navigation
  >       
  >       - [ ] Button that allows you to hide/show the typed password
  > 
  > <br/>
  > 
  > 4. How will work.:
  > 
  > 
  >     **1.** When the player enters, take your serial and check if it exists in the database: (If yes, skip to step 6, else continue).
  >     
  >     **2.** Show the registration screen and capture all the information typed in the inputs(User, Password, confirmPassword.
  >     
  >     **3.** Verify if the passwords in the inputs(Password, confirmPassword) are equals.
  >     
  >     **4.** Create an account with the informations captured from the inputs(User, Password).
  >     
  >     **5.** Send to the database all the information captured in the process (Serial, User, Password)
  >     
  >     **6.** Take the player's serial and search in the database your informations (Username and Password), then login the player with the information returned

</details>

<br/>

<h2 id="folder-structure">Folder Structures</h1>

> Folder structures are ways of structuring your project, if used correctly can bring the following benefits:
> - A great organization and readability for the project;
> - Makes group work be most easy;
> - Makes project more professional;
> - [...].
> 
> And other benefits. Structuring your project well is one of the characteristics that make you a better professional..

<details>
<summary><strong>Folder Structures Example</strong></summary>

  <br/>

  - <h3>Public</h3>

    > <img src="https://user-images.githubusercontent.com/95851792/218883668-1bfde26d-4cc2-4d70-88d5-c5de1d306543.png"></img>
    > <p>Everything that is public, such as the project's assets(images, icons, etc...) and other things.</p>
  
  <br/>
  
  - <h3>Source</h3>

    > <img src="https://user-images.githubusercontent.com/95851792/218883369-1567812c-5ab3-40d3-aedd-b706127366c7.png"></img>
    >
    > <p>It is the source of our code, where the main functioning of the code is.</p>
    
    <br/>
    
    - <h3>Core</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218883772-f7eaef7f-8bfd-4766-aa5d-3990942097eb.png"></img>
      >
      > <p>Here is the main code, where everything comes together to make the code work.</p>
      
      <br/>
      
    - <h3>Events</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218883949-deb01a69-6c66-42d7-bc15-1aaacc835bc4.png"></img>
      >
      > <p>Here are the listens, which when triggered, call another part or function of the code.</p>
      
      <br/>
      
    - <h3>Utils</h3>

      > <img src="https://user-images.githubusercontent.com/95851792/218884097-eddafd98-879c-4e03-8b89-dc05a84179a8.png"></img>
      >
      > <p>Here are some utilities, which can be exported later to another part of the code.</p>
      
   <br/>
      
  - <h3>General files</h3>

    > <img src="https://user-images.githubusercontent.com/95851792/218884258-69c53540-f03f-4187-8153-1f6c45c6f6db.png"></img>
    >
    > <p>General files are all those that do not have a defined topic or those that are recommended are in the initial scope of the folder, such as meta.xml, .git and etc.</p>
  
  <br/>

  <details>
  <summary><h3>Final Folder Structure</h3></summary>
  
  <br/>

  <img src="https://user-images.githubusercontent.com/95851792/218884547-56b4d081-c596-446b-b5f9-b46facee806f.png"></img>
      
  </details>
  

 

</details>
