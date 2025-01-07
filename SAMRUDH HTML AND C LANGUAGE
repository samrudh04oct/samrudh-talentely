<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ANIme - Home</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
  <style>  
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      background: url(photos/45.jpg);
      background-size: cover;
      height: 100%;
      font-family: 'Arial', sans-serif;
      overflow-x: hidden;
      background-color: #141414;
    }

   
    .side-nav {
      height: 100%;
      width: 60px;
      position: fixed;
      top: 0;
      left: 0;
      background-color: #141414;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: space-between;
      z-index: 1000;
      padding-top: 60px;
      padding-bottom: 30px;
    }

    .side-nav a {
      text-decoration: none;
      color: white;
      margin: 20px 0;
      font-size: 24px;
      transition: color 0.3s;
    }

    .side-nav a:hover {
      color: #e50914;
    }

    .side-nav i {
      font-size: 30px;
      transition: color 0.3s;
    }

    .side-nav i:hover {
      color: #e50914;
    }


    header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background: rgba(0, 0, 0, 0.8);
      padding: 10px 5%;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      position: relative;
      left: -60px;
      font-size: 1.8rem;
      color: #e50914;
    }

    header nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-size: 1rem;
      transition: color 0.3s;
    }

    header nav a:hover {
      color: #e50914;
    }

    .hero {
  position: relative;
  height: 450px;
  background: url(photos/shanks-5k-one-piece-5120x2880-18352.jpg) no-repeat center center/cover;
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  padding: 40px 5%;
  color: #fff;
  transition: background-image 1s ease-in-out;
}

.hero-content {
  opacity: 1;
  transition: opacity 1s ease-in-out;
}

    .hero-content h1 {
      font-size: 3rem;
      text-transform: uppercase;
      margin-bottom: 10px;
    }

    .hero-content h2 {
      position: relative;
      left: 10px;
      font-size: 1.5rem;
      text-transform: uppercase;
      margin-top: 10px;
    }

    .hero-content button {
      position: relative;
      left: 10px;
      background-color: #e50914;
      border: none;
      padding: 10px 25px;
      font-size: 1.1rem;
      color: #fff;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }

    .hero-content button:hover {
      background: #b20710;
    }

    .section {
      background-image: url() ;
      background-size: cover;
      width: 120%;
      margin: 40px 5%;
      margin-left: 0px;
      right: 10px;
      padding: 60px 5%;
      color: #fff;
    }

    .section h2 {
      font-size: 2rem;
      margin-bottom: 15px;
      margin-left: 80px;
      color: #fff
    }

    .movies {
      display: flex;
      overflow: hidden;
      gap: 15px;
      position: relative;
      width: 100%;
      transition: transform 0.3s ease-in-out;
      
    }

    .movie {
      left: 80px;
      width: 200px;
      height: 300px;
      background-color: #333;
      border-radius: 10px;
      cursor: pointer;
      transition: transform 0.3s ease-in-out;
      position: relative;
      flex-shrink: 0;
    }

    .movie img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      border-radius: 10px;
    }

    .movie:hover {
      transform: scale(1.1);
    }

    .movie-title {
      position: absolute;
      bottom: 10px;
      left: 10px;
      color: #fff;
      font-size: 1rem;
      font-weight: bold;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
    }

    .arrow-left, .arrow-right {
      position: absolute;
      top: 50%;
      color: #fff;
      font-size: 2rem;
      z-index: 10;
      background: rgba(0, 0, 0, 0.5);
      border-radius: 50%;
      padding: 10px;
      transition: background 0.3s;
    }

    .arrow-left {
      left:10px;
    }

    .arrow-right {
      right: 250px;
    }

    .arrow-left:hover, .arrow-right:hover {
      background: rgba(255, 255, 255, 0.3);
    }

    .trending-now {
      left: 30px;
      background: url(photos/4.jpg)no-repeat center center/cover;
      background-size: cover;
      padding: 60px 5%;
      color: #fff;
    }

    .trending-now h2 {
      font-size: 2rem;
      margin-bottom: 15px;
      margin-left: 80px;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.8);
    }

    .trending-now .movies {
      margin-top: 20px;
    }

    footer {
      background: #000;
      color: rgba(255, 255, 255, 0.7);
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <div class="side-nav">
    <a href="home.html"><i class="fas fa-home"></i></a>
    <a href="#search"><i class="fas fa-search"></i></a>
    <a href="movies.html"><i class="fas fa-film"></i></a>
    <a href="#trending"><i class="fas fa-fire"></i></a>
    <a href="profile.html"><i class="fas fa-user"></i></a>
    <a href="editP.html"><i class="fas fa-cogs"></i></a>
   
  </div>

  <header>
    <h1>
        <span style="font-weight: bold; font-size: 2rem; letter-spacing: 0px;">ANI</span>
    <span style="font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1rem; color: #fff;">ME</span>
      </h1>
      <nav>
        <a href="home.html">Home</a>
        <a href="movies.html">Movies & Series</a>
        <a href="subs.html" style="font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; font-weight:lighter">Subscription</a> 
       
  
      </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Trending Now</h1>
      <h2>One Piece</h2>
      <button onclick="location.href='photos/monkey-d-luffy.1920x1080.mp4'">Play</button>
  </section>

  <section class="section">
    <h2>Continue Watching</h2>
    <div class="movies" id="movies-continue">
      <div class="movie"><a href="vpyn.html"><img src="photos/cards/yn.jpg" alt="Movie 1"><div class="movie-title">Movie 1</div></div></a>
      <div class="movie"><a href="suzume.html"><img src="photos/cards/suz.jpg"alt="Movie 2"><div class="movie-title">Movie 2</div></div></a>
      <div class="movie"><a href="grave.html"><img src="photos/cards/g.jpg" alt="Movie 3"><div class="movie-title">Movie 3</div></div></a>
      <div class="movie"><a href="deathnote.html"><img src="photos/cards/dea.jpg" alt="Movie 4"><div class="movie-title">Movie 4</div></div></a>
      <div class="movie"><a href="a silent voice.html"><img src="photos/cards/a.jpg" alt="Movie 5"><div class="movie-title">Movie 5</div></div></a>
      <div class="movie"><a href="opm.html"><img src="photos/cards/opm.jpg" alt="Movie 5"><div class="movie-title">Movie 5</div></div></a>

      <i class="arrow-left fas fa-chevron-left"></i>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
    
  </section>

  <section class="trending-now">
    <h2>Weekly Trending </h2>
    <div class="movies" id="movies-trending">
      <div class="movie"><a href="jujustu.html"><img src="photos/cards/juju.jpg" alt="Trending 1"><div class="movie-title">Trending 1</div></div></a>
      <div class="movie"><a href="naruto.html"><img src="photos/cards/na.jpg" alt="Trending 2"><div class="movie-title">Trending 2</div></div></a>
      <div class="movie"><a href="op.html"><img src="photos/cards/op.jpg" alt="Trending 3"><div class="movie-title">Trending 3</div></div></a>
      <div class="movie"><a href="myhero.html"><img src="photos/cards/my.jpg" alt="Trending 4"><div class="movie-title">Trending 4</div></div></a>
      <div class="movie"><a href="demon.html"><img src="photos/cards/dem.jpg" alt="Trending 4"><div class="movie-title">Trending 4</div></div></a>
      <div class="movie"><a href="blackclove.html"><img src="photos/cards/bc.jpg" alt="Trending 4"><div class="movie-title">Trending 4</div></div></a>

      <i class="arrow-left.t fas fa-chevron-left"></i>
      <i class="arrow-right.t fas fa-chevron-right"></i>
    </div>
  </section>

  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>
  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>

  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>

  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>

  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>

  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>

  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>

  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>

  <section class="section">
    <h2>Top Picks for You</h2>
    <div class="movies" id="movies-top-picks">
      <i class="arrow-left fas fa-chevron-left"></i>
      <div class="movie"><a href="AOT.html"><img src="photos/cards/aot.jpg" alt="Top Pick 1"><div class="movie-title">Top Pick 1</div></div></a>
      <div class="movie"><a href="solol.html"><img src="photos/cards/sl.jpg" alt="Top Pick 2"><div class="movie-title">Top Pick 2</div></div></a>
      <div class="movie"><a href="tokyo.html"><img src="photos/cards/ty.jpg" alt="Top Pick 3"><div class="movie-title">Top Pick 3</div></div></a>
      <div class="movie"><a href="seaven.html"><img src="photos/cards/sea.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="hh.html"><img src="photos/cards/hh.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <div class="movie"><a href="thewind.html"><img src="photos/cards/the.jpg" alt="Top Pick 4"><div class="movie-title">Top Pick 4</div></div></a>
      <i class="arrow-right fas fa-chevron-right"></i>
    </div>
  </section>


  <footer>
    <p>© 2024 ANIme. All rights reserved.</p>
  </footer>

  
<script>
  let isPlaying = false;

    function playVideo() {
      const heroSection = document.querySelector('.hero');
      heroSection.style.backgroundImage = 'url(photos/shanks-5k-one-piece-5120x2880-18352.jpg)';
      const video = document.createElement('video');
      video.src = 'videos/one-piece-trailer.mp4';
      video.setAttribute('autoplay', 'true');
      video.setAttribute('loop', 'true');
      video.setAttribute('muted', 'true');
      video.style.width = '100%';
      video.style.height = '100%';
      video.style.position = 'absolute';
      video.style.top = 0;
      video.style.left = 0;
      video.style.zIndex = -1;
      heroSection.appendChild(video);

      isPlaying = true;
      document.querySelector('.close-btn').style.display = 'block';
      document.querySelector('.hero-content').style.opacity = '0';
    }

    function closeVideo() {
      const video = document.querySelector('.hero video');
      if (video) {
        video.remove();
        document.querySelector('.close-btn').style.display = 'none';
        isPlaying = false;
        document.querySelector('.hero-content').style.opacity = '1';
        const heroSection = document.querySelector('.hero');
        heroSection.style.backgroundImage = 'url(photos/shanks-5k-one-piece-5120x2880-18352.jpg)';
      }
    }
  const heroSlides = [
  {
    imageUrl: 'photos/shanks-5k-one-piece-5120x2880-18352.jpg',
    title: 'One Piece',
    subTitle: 'Watch Now'
  },
  {
    imageUrl: 'photos/4.jpg',
    title: 'Naruto',
    subTitle: 'Watch Now'
  },
  {
    imageUrl: 'photos/movies.jpg',
    title: 'Blue',
    subTitle: 'Watch Now'
  }
];

let currentSlideIndex = 0;

function showNextSlide() {
  const heroElement = document.querySelector('.hero');
  const heroContent = heroElement.querySelector('.hero-content');
  const { imageUrl, title } = heroSlides[currentSlideIndex];

  
  heroContent.style.opacity = '0';

  setTimeout(() => {
    
    heroElement.style.backgroundImage = `url(${imageUrl})`;
    heroElement.querySelector('.hero-content h2').innerText = title;

   
    heroContent.style.opacity = '1';

    
    currentSlideIndex = (currentSlideIndex + 1) % heroSlides.length;
  }, 500); 
}

function startHeroBannerSlideshow() {
  setInterval(showNextSlide, 5000);
}

window.onload = startHeroBannerSlideshow;


const leftArrow = document.querySelector('.arrow-left');
const rightArrow = document.querySelector('.arrow-right');
const movieContainer = document.querySelector();
const movies = document.querySelectorAll('.movie');
const cardWidth = movies[0].offsetWidth + 15;

let currentIndex = 0;

rightArrow.addEventListener('click', () => {
  if (currentIndex < movies.length - 1) {
    currentIndex++;
    movieContainer.style.transform = `translateX(-${currentIndex * cardWidth}px)`;
  }
});

leftArrow.addEventListener('click', () => {
  if (currentIndex > 0) {
    currentIndex--;
    movieContainer.style.transform = `translateX(-${currentIndex * cardWidth}px)`;
  }
});

</script>
</body>
</html>
