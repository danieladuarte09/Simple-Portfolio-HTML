# Practica-HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/reset.css">
    <link rel="stylesheet" href="/main.css" >
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Daniela Duarte</title>
</head>
<body>

    <header>
        <!--Hay que poner un logo, optimizado-->
    <nav>
        <!--<div class="nav-hamburg">-->

        <a href="#" class=" enlace">
           <img src="/tv.png" class="logo" alt="logo icon">
        </a>

        

        

        <ul class="responsive">
            <li>
                <a href="#" class="menu" >Blog </a>
            </li>
            <li>
                <a href="#contact" class="menu" >Contact </a>
            </li>
            <li>
                <a href="#" class="menu" >Projects</a>
            </li>
            <li>
                <a href="#" class="menu" >Python </a>
            </li>
        </ul>

        <input type="checkbox" id="check">
        <label for="check" class="checkbtn">
            <i style="font-size:24px" class="fa">&#xf0c9;</i>
        </label>
          
        
    </nav>
    </header>

    <main>
    <div class="title" >
    <h1>Web development</h1>
    <h2>Web desing. UX/UI</h2>
    <h2>Front-End</h2>
    </div>
    
    

    <div class="picture">
        <img class="picture01" src="/images/web-desing.jpg" alt="presentation image" height="200" >

    </div>
    <!--Description-->

    <article class="about">
        <h3>Web development <br > and web desing Junior </h3>
        <p>
            I desing and redesing webs according to customer needs.
            I also program the website to add interactivity with the user. 
        </p>

        <p>
            Constantly learning about the new trends and tecnologies to the future 
            and interested in the application of that technologies in the work environment, 
            and the impact that they generate day by day.
        </p>
             

    </article>


    <section class="skills">
        <!-- skills de progrmación, barras de progreso animadas con css-->
        <h3 class="h3-skills">Technical Knowledge and Skills</h3>
        <div class="skills-0">
            <li class=" skills-1">HTML</li>
                <div class="percentage" id="html"> 70%</div>
            <li class=" skills-1">CSS</li>
                <div class="percentage" id="css"> 70%</div>
            <li class=" skills-1">JAVASCRIPT</li>
                <div class="percentage" id="js"> 60%</div>
            <li class=" skills-1">PYTHON</li>
                <div class="percentage" id="python"> 80%</div>
            <li class=" skills-1">UI/UX DESING </li>
                <div class="percentage" id="ux"> 85%</div>
            
        </div>

    </section>

    <div class="container2">

    <section id="contact" class="contact">
        <h3> Contact</h3>
            
        <form class="form" action="#" method="post" novalidate>
            <div class="form">
              <label for="name">Name</label>
              <input required id="name" name="name" type="text" placeholder="Add your name">
            </div>
            <div class="form">
                <label for="last_name">Last name</label>
                <input required id="last_name" name="last_name" type="text" placeholder="Add your last name">
              </div>
            <div class="form">
              <label for="mail">Email</label>
              <input required id="mail" name="email" type="email" placeholder="email@contacto.com">
            </div>
            
            <div class="form">
              <label for="phone">Phone</label>
              <input type="tel" id="phone" name="phone" pattern="[0-9]+" placeholder="+12345678">
            </div>
    
            <div class="form">
                <label for="last_name">GitHub username</label>
                <input required id="last_name" name="last_name" type="text" placeholder="@username" pattern="^@[^\s]+">
              </div>
            <div>
    
              <legend>How did you meet me?</legend>
              
              <div class="for">
              <label for="kc">Keepcoding kick-off</label>
              <input required id="kc" type="radio" name="option" value="kc">
              </div>
              
              <div class="for">
              <label for="Linkedin">Linkedin</label>
              <input required id="Linkedin" type="radio" name="option" value="Linkedin">
              </div>
    
              <div class="for">
              <label for="GitHub">GitHub</label>
              <input  required id="GitHub" type="radio" name="option" value="GitHub">
              </div>
    
              <div class="for">
                <label for="other">Other</label>
                <input  required id="other" type="radio" name="option" value="other">
                <input required id="other" name="other" type="text" placeholder="Tell me more">
              </div>

              <div class="text">
                <label for="more">How can I help you?</label>
                <textarea required id="more" maxlength="180"></textarea>
              </div>
    
            <div class="button">
            <input class="btn" type="submit" value="Enviar">
            </div>
          </form>
        </div>

    </section>

    </main>
    <footer>
        <a class="icon" href="https://www.linkedin.com/in/daniela-duarte-587874163/" target="_blank">
            <img src="/images/linkedin.png" class="linkedin" alt="logo de linkedin">

        </a>
        <a class="icon" href="https://github.com/danieladuarte09" target="_blank">

            <img src="/images/github.png" class="gith" alt="logo github">

        </a>

           

        <a class="icon" href="https://www.instagram.com/niela09/" target="_blank">
            
            <img src="/images/instagram.png" class="instagram" alt="logo instagram"> </a>
    </footer>
</body>
</html>
    
</body>
</html>
