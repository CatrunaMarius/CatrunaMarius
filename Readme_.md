<svg fill="none"  width="80vw" height="4000" xmlns="http://www.w3.org/2000/svg">

<foreignObject width="100%" height="100%">
  <div xmlns="http://www.w3.org/1999/xhtml">
<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: inherit;
}
h2 {
    margin-left: 1rem;
    font-size: 3rem;
    font-weight:1rem;
}
.container {
    display: grid;
    grid-template-rows:  repeat(3, min-content);
    grid-template-columns: [sidebar-start] 7rem [sidebar-end center-start]   repeat(6, [col-start] minmax(min-content, 14rem) [col-end]) [center-end] minmax(6rem, 1fr) [full-end];
  }
  .intro {
    grid-column:center-start/ center-end;
    margin: 2rem 0 2rem 0;
  }
  .intro-box{
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(20rem, 1fr));
      gap: 5rem;
  }
  .language {
      display: grid;
      grid-column:center-start/ center-end;
      grid-template-columns: repeat(auto-fit, minmax(2rem, 4rem));
      align-items: center;
      justify-items: center;
      justify-content: center;
      align-content: center;
      padding: 2rem;
  }
  .images {
    height: 3rem;
    width: 3rem;
}
  .pro{
        grid-column: sidebar-start/full-end;
  }
    .project {
        display: grid;
        grid-column: center-start/ center-end;
        grid-template-columns: repeat(auto-fit, minmax(20rem, 1fr));
        gap: 7rem;
        margin-top: 2rem;
    }
    .box{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        row-gap: 0.5rem;
    }
    .gif {
        width: 100%;
        height: 100%;
        grid-column: 1 /-1;
        grid-row: 1 /2;
    }
    .code {
        grid-column: 1 /-1;
        place-self: center;
    }
    .title {
        font-size: 1.5rem;
        font-weight: bold;
        border-radius: 0.3rem;
        padding: 0.5rem;
        border: none;
        background: linear-gradient(to right bottom, #FF3366,  #BA265D);
        color: #FFFFFF
    }
    .title:hover{
        background: linear-gradient(to left bottom, #FF3366,  #BA265D);
        margin-right: 0.3rem;
        transform:translateY(-0.3rem);
        box-shadow: 0 .5rem 2rem rgba(0, 0, 0, .2);
    }
    .github {
        font-size: 1.5rem;
        font-weight: bold;
        border-radius: 0.3rem;
        padding: 0.5rem;
        border: none;
        background: linear-gradient(to left bottom, #FF3366,  #BA265D);
        color: #FFFFFF
    }
    .github:hover {
        background: linear-gradient(to right bottom, #FF3366,  #BA265D);
        margin-left: 0.3rem;
        transform:translateY(-0.3rem);
        box-shadow: 0 .5rem 2rem rgba(0, 0, 0, .2);
    }
    .badge {
        border-radius: 5px;
    }
    .btn,.btn:link , .btn:visited {
        margin: 5rem 0 5rem;
        padding: 0.3rem;
        grid-column: col-start 3 / col-start 5;
        font-size: 2.5rem;
        border-radius: 3rem;
        text-transform: uppercase;
        background: linear-gradient(to right bottom, #FF3366,  #BA265D);
        color: #fff;
        border: none;
        transition: all .2s;
        position: relative;
    }
    .btn:hover {
        transform:translateY(-1rem);
        box-shadow: 0 .5rem 2rem rgba(0, 0, 0, .2);
        background: linear-gradient(to left bottom, #FF3366,  #BA265D);
        border-radius:  3rem;
    }
    .btn:hover::after {
        transform: scaleX(1.4) scaleY(1.6);
        opacity: 0;
    }
    .btn:active, .btn:focus {
        outline: none;
        transform:translateY(-1px);
        box-shadow: 0 .5rem 1rem rgba(0, 0, 0, .2)
    }
    .btn--green {
        background: linear-gradient(to right bottom, #FF3366,  #BA265D);
        color: #fff;
    }
        .btn--green::after {
          background: linear-gradient(to right bottom, #FF3366,  #BA265D);
        }
    .btn::after {
        content: "";
        display: inline-block;
        height: 100%;
        width: 100%;
        border-radius: 10rem;
        position: absolute;
        top: 0;
        left: 0;
        z-index: -1;
        transition: all .4s;
    }
      #wrapper {
        overflow: hidden;
        transition: height 200ms;
        height: 0;
      }
      .open[style] {
          height:fit-content !important;
      }
      .contact {
        display: grid;
        grid-column: center-start / center-end;
        grid-template-columns: repeat(auto-fit, minmax(2rem, 4rem));
        align-items: center;
        justify-items: center;
        justify-content: center;
        align-content: center;
      }
</style>  

<div class="container">
<h2 class="pro">Hi there <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30" />, </h2>
<div class="intro">
  <div class ="intro-box">
    <div class="intro-text">
      <h3>I’m Marius from Romania and I like to codin and I also like web design. I'm an tehnologi enthusiasm . I really enjoy learning languages and framworks like React and Tensorflow. Also enjoy wireframing, ui, ux and design in general.</h3>
    </div>
    <div class="intro-animate">
      <img src="./Asset 16.svg" alt="my image" />
    </div>
  </div>
</div>
<h2 class="pro">Languages and Tools</h2>
<div class="language">
  <div
  data-image="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/html5/html5-original-wordmark.svg"
  data-encode="fals"
>
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/html5/html5-original-wordmark.svg"
    alt="html5"
    class="images"
  />
</div>
  
<div
  data-image="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/css3/css3-original-wordmark.svg"
  data-encode="fals"
>
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/css3/css3-original-wordmark.svg"
    alt="css3"
    class="images"
  />
</div>
  
<div
  data-image="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/javascript/javascript-original.svg"
  data-encode="fals"
>
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/javascript/javascript-original.svg"
    alt="javascript"
    class="images"
  />
</div>
  
<div
  data-image="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/sass/sass-original.svg"
  data-encode="fals"
>
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/sass/sass-original.svg"
    alt="Sass"
    class="images"
  />
</div>
  
<div
  data-image="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/react/react-original-wordmark.svg"
  data-encode="fals"
>
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/react/react-original-wordmark.svg"
    alt="React"
    class="images"
  />
</div>
  
<div
  data-image="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/express/express-original-wordmark.svg"
  data-encode="fals"
>
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/express/express-original-wordmark.svg"
    alt="express"
    class="images"
  />
</div>
  
<div
  data-image="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/mongodb/mongodb-original-wordmark.svg"
  data-encode="fals"
>
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/mongodb/mongodb-original-wordmark.svg"
    alt="mongodb"
    class="images"
  />
</div>
  
<div
  data-image="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/npm/npm-original-wordmark.svg"
  data-encode="fals"
>
  <img
    src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/npm/npm-original-wordmark.svg"
    alt="npm"
    class="images"
  />
</div>
</div>
<h2 class="pro">Projects</h2>
  
  <div class="project">
    <div class="box">
            <img class="gif" src="nexter.gif">
            <button class="title" onclick="window.open('https://catrunamarius.github.io/Nexter/', '_top') ">Nexter</button>
            <button class="github" onclick="window.open('https://github.com/CatrunaMarius/Nexter')">View code</button>
            <div class="code">
             <img class="badge sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&amp;logo=sass&amp;logoColor=white">
             <img class="badge html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&amp;logo=html5&amp;logoColor=white">
            </div>
         </div>
         <div class="box">
            <img class="gif" src="natours.gif">
            <button class="title" onclick="window.open('https://catrunamarius.github.io/Natours/', '_top') ">Natours</button>
            <button class="github" onclick="window.open('https://github.com/CatrunaMarius/Natours')">View code</button>
            <div class="code">
              <img class="badge sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&amp;logo=sass&amp;logoColor=white">
              <img class="badge html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&amp;logo=html5&amp;logoColor=white">
            </div>
        </div>
        <div class="box">
            <img class="gif" src="trillo.gif">
              <button class="title" onclick="window.open('https://catrunamarius.github.io/Trillo/', '_top') ">Trillo</button>
              <button class="github" onclick="window.open('https://github.com/CatrunaMarius/Trillo')">View code</button>
            <div class="code">
               <img class="badge sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&amp;logo=sass&amp;logoColor=white">
               <img class="badge html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&amp;logo=html5&amp;logoColor=white">  
             </div>
        </div>
         <div class="box">
            <img class="gif" src="e-Shopping.gif">
              <button class="title" onclick="window.open('https://catrunamarius.github.io/e-Shopping/', '_top') ">e-Shopping</button>
              <button class="github" onclick="window.open('https://github.com/CatrunaMarius/e-Shopping')">[View code]</button>
            <div class="code">
              <img class="badge sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&amp;logo=sass&amp;logoColor=white">
              <img class="badge redux" src="https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white" />
              <img class="badge React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />
            </div>
        </div>
    </div>
    <button id="button" class="btn btn--green">Read more</button>
    <div id="wrapper" class="project more">
      <div id="list" class="box">
          <img class="gif" src="Secrets.gif">
            <button class="title" onclick="window.open('https://secretsnodejs.herokuapp.com/', '_top') ">Secrets</button>
            <button class="github" onclick="window.open('https://github.com/CatrunaMarius/Secrets')">View code</button>
        <div class="code">
           <img class="badge sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&amp;logo=sass&amp;logoColor=white">
           <img class="badge html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&amp;logo=html5&amp;logoColor=white">
          </div>
     </div>
      <div class="box">
        <img class="gif" src="TinDog.gif">
          <button class="title" onclick="window.open('https://catrunamarius.github.io/TinDog/', '_top') ">TinDog</button>
          <button class="github" onclick="window.open('https://github.com/CatrunaMarius/TinDog')">View code</button>
       <div class="code">
         <img class="badge sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&amp;logo=sass&amp;logoColor=white">
         <img class="badge html5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&amp;logo=html5&amp;logoColor=white">
        </div>
     </div>
  </div>
  </div>
  <h2 class="pro">Contac Me</h2>
  <div class = "contact">
    <a href="mailto:catruna.marius.robert@gmail.com"> <img class="images" src="https://cdn.worldvectorlogo.com/logos/official-gmail-icon-2020-.svg" /> </a>
    <a href="https://www.linkedin.com/in/catruna-marius-robert-a7088ba7"> <img class="images" src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" /> </a>
    <a href="https://codesandbox.io/u/catruna.marius.robert"> <img class="images" src="https://cdn4.iconfinder.com/data/icons/logos-brands-5/24/codesandbox-4096.png" /> </a>
  </div>
</div>

</div>
</foreignObject>
</svg>



<!-- </svg>   -->
