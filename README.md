<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors">
    <meta name="generator" content="Hugo 0.84.0">
    <title>Nextech Website</title>

    <link href="C:\Users\casham\Documents\GitHub\Nexttech-website\css" rel="stylesheet2.0" type="text/css">
    <link rel="canonical" href="https://getbootstrap.com/docs/5.0/examples/carousel/">
    
    <link rel="canonical.2" href="C:\Users\casham\Documents\GitHub\Nexttech-website\css">


    

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">



<link rel="apple-touch-icon" href="/docs/5.0/assets/img/favicons/apple-touch-icon.png" sizes="180x180">
<link rel="icon" href="/docs/5.0/assets/img/favicons/favicon-32x32.png" sizes="32x32" type="image/png">
<link rel="icon" href="/docs/5.0/assets/img/favicons/favicon-16x16.png" sizes="16x16" type="image/png">
<link rel="manifest" href="/docs/5.0/assets/img/favicons/manifest.json">
<link rel="mask-icon" href="/docs/5.0/assets/img/favicons/safari-pinned-tab.svg" color="#7952b3">
<link rel="icon" href="/docs/5.0/assets/img/favicons/favicon.ico">
<meta name="theme-color" content="#7952b3">


    <style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }
    </style>


   
    <link href="carousel.css" rel="stylesheet">
  </head>
  <body>
  
<header>
  <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Nextech</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav me-auto mb-2 mb-md-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true"></a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
</header>

<main>

  <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="https://imgur.com/wdM5n9P.png" alt="Avatar" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" preserveAspectRatio="xMidYMid slice" focusable="false"><rect width="100%" height="100%" fill="#777"/></svg>

        <div class="container">
          <div class="carousel-caption text-start">
            <h1></h1>
            <p></p>     
               </div>
        </div>
      </div>
      <div class="carousel-item">
        <img src="https://imgur.com/lochRoR.jpg" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" preserveAspectRatio="xMidYMid slice" focusable="false"><rect width="100%" height="100%" fill="#777"/></svg>

        <div class="container">
          <div class="carousel-caption">
            <h1>Another example headline.</h1>
            <p>Some representative placeholder content for the second slide of the carousel.</p>
            <p><a class="btn btn-lg btn-primary" href="#">Learn more</a></p>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <svg class="bd-placeholder-img" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" preserveAspectRatio="xMidYMid slice" focusable="false"><rect width="100%" height="100%" fill="#777"/></svg>

        <div class="container">
          <div class="carousel-caption text-end">
            <h1>One more for good measure.</h1>
            <p>Some representative placeholder content for the third slide of this carousel.</p>
            <p><a class="btn btn-lg btn-primary" href="#">Browse gallery</a></p>
          </div>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>


 
  <div class="container marketing">

    
    <div class="row">
      <div class="col-lg-4">
        <img src="https://imgur.com/lochRoR.jpg" width="140" height="140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title>
          <rect width="100%" height="100%" fill="#777"/><text x="50%" y="50%" fill="#777" dy=".3em"></text></svg>





        <h2>Me</h2>
        <p>Short drtail about me my name is youri alan guerrier i do robotics,track,student council,E Sports,Debate club.</p>
      </div>

      <div class="col-lg-4">
        <img src="https://imgur.com/vZNdN77.jpg" width="140" height="140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title><rect width="100%" height="100%" fill="#777"/><text x="50%" y="50%" fill="#777" dy=".3em"></text></svg>

        <h2>Friends</h2>
        <p>I meet some of the most wonderful people while i was in this program.</p>
      </div>

      <div class="col-lg-4">
        <img src="https://imgur.com/Y7B0Jbq.gif" width="140" height="140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: 140x140" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title><rect width="100%" height="100%" fill="#777"/><text x="50%" y="50%" fill="#777" dy=".3em"></text></svg>

        <h2>Projects</h2>
        <p>These are some of the projects i have done while being in this program.</p>
      </div>
    </div>


   

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7">
        <h2 class="featurette-heading">Who am I...<span class="text-muted">It’ll blow your mind.</span></h2>
        <p class="lead">Hello i'm going to be honest with you the hardest part of this is talking about myself but here we go... My name is youri alan Guerrier I am a foreigner
          i was born in haiti located under Preto Ric. When i first got to america i wasnt into computer at first i was amaed by the trains, the plains, the buses, the buildings 
          everything was new to me. I started to get into computer science about two years ago… My teacher that i looked up to in warren central high school named Mr.law told me about Nextech i joined last year for the coding challenge. 
          There was a race car driver who was talking to us about how he started coding and everything and I was like damn maybe one day.
          I can do something great like he did so I joined this year. Meeting new people boeing online and in person at the same time was wonderful Honestly it's better than school everyone at work is like a family to me and we can all agree this is better than school but i learned from my boss that i've grown not just as a person but in general and i really loved that jill pointed that out to me coming into this program has grown everyone even if they dont notice it making friends who you only have known for 5 weeks now or talking to the T.As and getting to know them and meeting people who hell they have the coolest jobs in the world if i do say so myself.
           I’m glad i joined Nextech this year also if there comes another year were i could do this all over again i would. 
        </p>
      </div>
      <div class="col-md-5">
        <img src="https://imgur.com/iMkEPKG.jpg" width="500" height="675" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: 500x500" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title><rect width="100%" height="100%" fill="#eee"/><text x="50%" y="50%" fill="#aaa" dy=".3em"></text></svg>

      </div>
    </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7 order-md-2">
        <h2 class="featurette-heading">Friends<span class="text-muted">/coworkers</span></h2>
        <p class="lead">I dont wanna call the people i work with friends honestly or coworkers they are more of a family to me. I had a blast doing activitys such as
          going downtown for the Scavenging hunt 

          Staying in doors and goof around 
          
          Going down a 3 floor slade 
          
          Giving my name out and adding an animal that started with the first letter 
          
          All of these are wonderful times. I learned alot about the people who came to speak. There is a reason behind why I ask people what color they like because knowing someone's color could tell you just a little about themselves whether they don’t know you are Black. Many attribute black with darkness, but those whose favorite color is black or whose favorite color is a black undertone are most likely expressing their depression or are mourning over a loss. On a brighter note, the hue black can also indicate power, creativity, elegance, and sexuality. Black, then, is a shade frequently donned to suggest a person’s nature as mysterious, aloof, or independent. If black is your preference, you may like how it makes you feel powerful and mysterious.
          <b>White</b>. Those whose favorite color is white may be aware that the meaning of white includes purity, birth, and innocence. However, having the preference of white or simply liking the hue white can also mean that you are organized, independent, and logical. White is a very clean feeling, as it is bare and bright. So, you are likely a very clean and organized person if your preferred hue is white.
          
          <b>Red</b>. As most people know, red is the hue that symbolizes intense desire and aggression; therefore, if your favorite color is red, you are someone who is driven, adventurous, and active. To some, red can feel angry or evil, as many villains in movies or cartoons wear red and black. But, for others, it can represent love because of the primary colors associated with Valentine’s Day. In other words, red can mean positive or negative things, depending on who is looking at it. If this is your favorite color, you may want to look into both aspects of red. 
          <b>Purple</b>. Purple is a favorite color among many. In fact, it’s one of the top favorites amongst people. And, this hue's meaning goes far back in history. This hue symbolizes mystery and spirituality, as well as royalty. Purple dyes used to be so rare and expensive that only monarchs could afford to wear them. Those whose favorite color is purple tend to reflect royalty as they require great emotional security, but are helpful to others. Many people who have the preference as purple have several purple things whether they be pens, pencils, and shirts. This is because purple can be used to express individuality because of its deep roots to royalty. People whose favorite is purple are generally unique and want to stand out. 
          <b>Pink</b>. Pink is the hue of romance. Anyone whose favorite color is pink expresses themselves well and shows the world that they believe in and want to be loved unconditionally or accepted by society. If pink is your hue, you are probably a romantic at heart. Many glasses are pink-tinted, which can put a romantic filter on life. When your preference is pink, you may also be more flirty and feminine, while some people think that when their preference is pink, and they see it, they feel euphoria. 
          <b>Orange.</b> If your favorite color is orange, you are a social person with a vibrant personality, as this shade represents energy, warmth, and enthusiasm. Orange is typically seen as happy, often associated with sunshine and the Spring season. If your preference is orange, you may blend the characteristics of red and yellow personalities; as orange is a blend of red and yellow. 
          <b>Blue</b>. The most popular favorite color is blue, which symbolizes peace and tranquility.This may be why blue is commonly used as wall paint in bedrooms. If your preference is blue, you are a calm, trustworthy, and loyal person as you promote unity and security. Having the favorite color as blue may be because you enjoy the peace it brings. 
          <b>Green</b> A more common symbol of jealousy and greed, green’s meaning can also signify nature, good luck, fertility, and rebirth. Overall, if your favorite color is green, you are committed to others, but can be conceited or preoccupied with your reputation.
          <b>Yellow.</b>b If your favorite color is yellow, you are likely very energetic and happy. This represents joy, optimism, and friendship. Having yellow as your preferred shade says that you enjoy sharing with others, but are eager to emphasize your individuality.
          <b>Gray</b>. Gray can be seen as depressing, sad, or moody. However, when it comes to home décor, this shade can be chic, modern, and stylish. But, if your favorite color is gray, you may have a low mood at times or enjoy neutral tones because they don’t draw too much attention to you. When your favorite color is gray, this may also indicate that you have a hard time making up your mind. 
          <b>Brown</b>. Brown is, as mentioned above, a natural shade that represents earthy and organic materials. So, if your preference is brown, you may be drawn to nature or enjoy a simpler way of living. Brown preference also implies you enjoy security in life.
          
        </p>
      </div>
      <div class="col-md-5 order-md-1">
        <img src="https://imgur.com/QSJ6UYt.jpg" width="470" height="500" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: 500x500" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title><rect width="100%" height="100%" fill="#eee"/><text x="50%" y="50%" fill="#aaa" dy=".3em"></text></svg>

      </div>
    </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7">
        <h2 class="featurette-heading">Projects<span class="text-muted">...</span></h2>
        <p class="lead">some of the projects i've worked on withen this community of wonderful people were tick tack tow and peng pong game i've also been working on video editing on Youtube just to mess around with it thr wall paper to the right was done on wall paper engine by me and some friends. The hardest part of this was making it into a GIF 
          <p> <a href="https://www.youtube.com/watch?v=0W-pMmvZIyw"> Youtube project</a></href></p>
          <p><a href="https://popcode.org/?snapshot=edbaa13c-9a66-4789-8ba1-405d08489a14"> Popcode frist Website img</a></href></p>
          <p><a href="https://popcode.org/?snapshot=3ac7fe66-950c-4cb2-9551-bb24cf6c4b0f">Popcode calculator0</a></href></p>
      </div>
      <div class="col-md-5">
        <img src="https://imgur.com/a4b72BY.jpg" width="500" height="500" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: 500x500" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title><rect width="100%" height="100%" fill="#eee"/><text x="50%" y="50%" fill="#aaa" dy=".3em"></text></svg>

      </div>
    </div>

    <hr class="featurette-divider">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">


  </div>

    <script src="/docs/5.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
      
  </body>
</html>
