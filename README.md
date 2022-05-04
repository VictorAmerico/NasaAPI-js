# Nasa API-js
Linkamos a api da nasa com nosso codigo

# INICIO

## HTML (1/2)
~~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <script src="main.js"></script>
    <title>Nasa api key</title>
</head>
<body>
    <header>
        <section id="hero-animated" class="hero-animated  d-flex  align-items-center">
            <div class="container d-flex flex-column justify-content-center align-items-center text-center position-relative">
             <center> <img src="/assets/hero-carousel-3.svg" class="img-fluid animated"></center>
              <h2>Welcome to <span>NASA API KEY</span></h2>
              <p>Testezinho gostosinhu keyzinhaaa cigarrrinhuuuuuuuuuuuuuu ain ain</p>
              <div class="d-flex">
                <a href="" class="btn-get-started scrollto" style="text-decoration: none;" id="seash">Começar</a>
                <a href="https://www.youtube.com/watch?v=CVhFh9KAPZw&t=7s&ab_channel=TuubeeYoouu" class="glightbox btn-watch-video d-flex align-items-center"><i class="bi bi-play-circle"></i><span>Ain cigarrinhu</span></a>
              </div>
            </div>
          </section>
    </header>
</body>
</html>
~~~~

## CSS (1/2)

~~~css
h1{
    text-align: center;
    color: white;
}

body{
    background-color: black;
}

.text-center{
    text-align: center;
}
/*--------------------------------------------------------------
# Animated Hero Section


KEY: UcSkWbpB0BacVcrekq14FRadmiUAjMJGQuTODwOI
--------------------------------------------------------------*/
.hero-animated {
    width: 100%;
    padding: 60px 0 20px;

  }
  .hero-animated h2 {
    margin: 0 0 10px 0;
    font-size: 48px;
    font-weight: 300;
    color: white;
    font-family: 'Times New Roman', Times, serif;
  }
  .hero-animated h2 span {
    color: white;
  }
  .hero-animated p {
    color: rgba(255,255,255, 0.8);
    margin: 0 0 30px 0;
    font-size: 20px;
    font-weight: 400;
  }
  .hero-animated .animated {
    margin-bottom: 60px;
    animation: up-down 2s ease-in-out infinite alternate-reverse both;
  }
  @media (min-width: 992px) {
    .hero-animated .animated {
      max-width: 45%;
    }
  }
  @media (max-width: 991px) {
    .hero-animated .animated {
      max-width: 60%;
    }
  }
  @media (max-width: 575px) {
    .hero-animated .animated {
      max-width: 80%;
    }
  }
  .hero-animated .btn-get-started {
    font-size: 16px;
    font-weight: 400;
    display: inline-block;
    padding: 20px 60px;
    border-radius: 4px;
    transition: 0.5s;
    color: white;
    background: blue;
    font-family: 'Times New Roman', Times, serif;
  }
  .hero-animated .btn-get-started:hover {
    background: rgba(255,255,255, 0.8);
  }
  .hero-animated .btn-watch-video {
    font-size: 16px;
    transition: 0.5s;
    margin-left: 25px;
    font-family: 'Times New Roman', Times, serif;
    color: rgb(247, 0, 0);
    font-weight: 600;
  }
  .hero-animated .btn-watch-video i {
    color: white;
    font-size: 32px;
    transition: 0.3s;
    line-height: 0;
    margin-right: 8px;
  }
  .hero-animated .btn-watch-video:hover {
    color: white;
  }
  .hero-animated .btn-watch-video:hover i {
    color: rgba(255,255,255, 0.8);
  }
  @media (max-width: 640px) {
    .hero-animated h2 {
      font-size: 32px;
    }
    .hero-animated p {
      font-size: 18px;
      margin-bottom: 30px;
    }
    .hero-animated .btn-get-started, .hero-animated .btn-watch-video {
      font-size: 14px;
    }
  }
  
  @-webkit-keyframes up-down {
    0% {
      transform: translateY(10px);
    }
    100% {
      transform: translateY(-10px);
    }
  }
  
  @keyframes up-down {
    0% {
      transform: translateY(10px);
    }
    100% {
      transform: translateY(-10px);
    }
  }
~~~
## Imagem usada para bg
![markdown](/hero-carousel-3.svg)
