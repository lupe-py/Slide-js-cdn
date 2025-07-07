<!DOCTYPE html>
<html lang="en">
<head>
   <style>
     .services {
  background: linear-gradient(135deg, #000000 0%, #0a0a0a 100%);
  color: white;
  padding: 60px 20px;
  font-family: 'Poppins', sans-serif;
  min-height: 100vh;
}

.serv-header {
  max-width: 900px;
  margin: 0 auto 60px auto;
  text-align: center;
}

.serv-header h1 {
  font-family: 'Orbitron', sans-serif;
  font-size: 80px;
  letter-spacing: 12px;
  color: #C4EF17;
  text-shadow:
    0 0 8px #C4EF17,
    0 0 20px #A4CE15;
  margin-bottom: 20px;
}

.serv-header p {
  font-size: 20px;
  color: #ddd;
  max-width: 700px;
  margin: 0 auto;
  line-height: 1.6;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
  gap: 30px;
  max-width: 1100px;
  margin: 0 auto;
}

.service-card {
  background: #111111;
  border: 2px solid #3AFF00;
  border-radius: 15px;
  padding: 30px 25px;
  box-shadow:
    0 0 10px rgba(196,239,23,0.3),
    inset 0 0 15px rgba(196,239,23,0.15);
  transition: transform 0.3s ease, box-shadow 0.4s ease;
  cursor: default;
}

.service-card:hover {
  transform: scale(1.01);
  box-shadow:
    0 0 30px #C4EF17,
    inset 0 0 25px #C4EF17,
    0 0 50px #A4CE15;
}

.icon {
  font-size: 48px;
  margin-bottom: 15px;
  color: #C4EF17;
  filter: drop-shadow(0 0 5px #C4EF17);
}

.service-card h2 {
  font-family: 'Orbitron', sans-serif;
  font-size: 24px;
  margin-bottom: 15px;
  color: #C4EF17;
  letter-spacing: 1.5px;
  text-transform: uppercase;
}

.service-card p {
  font-size: 16px;
  line-height: 1.5;
  color: #ccc;
}

.service-card>a{
    color: white;
    text-decoration: none;
}

.service-card>a:hover{
    text-decoration: underline;
}


.splide{
  background-color: red;
}

/* Responsive */
@media (max-width: 768px) {
  .serv-header h1 {
    font-size: 48px;
    letter-spacing: 8px;
  }

  .service-card {
    padding: 20px 15px;
  }

  .icon {
    font-size: 36px;
  }
}


.splide__track{
  width: 100%;
  padding-top:150px;
   padding-bottom:30px;
  background-image: url('/Photo/cover.png');
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
}
   </style>

    <link rel="stylesheet" href="/home.css"/>
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/lupe-py/Slide-js-cdn/splide.min.css">
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/lupe-py/Slide-js-cdn/splide-core.min.css">

      <link rel="stylesheet" href="/splide-core.min.css"/>
</head>
<body>

   <div class="services">
  <div class="serv-header">
    <h1>SERVICES</h1>
    <p>We provide creative and data-driven marketing solutions — from social media and SEO to web design and advertising — to help your brand grow and succeed online.</p>
  </div>


<section class="splide" aria-label="Splide Basic HTML Example">
  <div class="splide__track">
		<ul class="splide__list">
			<li class="splide__slide">

        <div class="service-card">
          <img src="/Photo/cover1.png" width="100%">
       <h2>Social Media Marketing</h2>
      <p>The whole community is interested in growing the FOX prize.The company is planning.</p><br>
      <a href="https://ertadigitalmarketing.com/service/social-media-marketing/">Read More</a>
    </div>

      </li>

			<li class="splide__slide">

        <div class="service-card">
      <video width="100%" muted>
        <source src="/Photo/sms marketing.mp4" type="video/mp4">
      </video>
      <h2>E-mail & SMS Marketing</h2>
      <p>Harness the power of social media to grow your business. Let us shape your winning strategy.</p><br>
      <a href="https://ertadigitalmarketing.com/service/e-mail-sms-marketing/">Read More</a>
    </div>

      </li>

      <li class="splide__slide">

        <div class="service-card">
      <video width="100%" muted>
        <source src="/Photo/logo.mp4" type="video/mp4">
      </video>
      <h2>Logo & Branding</h2>
      <p>We create custom logos and cohesive brand identities that capture your vision and leave a lasting impression.</p><br>
      <a href="https://ertadigitalmarketing.com/service/logo-branding/">Read More</a>
    </div>

      </li>

			
      </li>

      <li class="splide__slide">

        <div class="service-card">
      <video width="100%" muted>
        <source src="/Photo/smm strategy.mp4" type="video/mp4">
      </video>
      <h2>Social Media Strategy</h2>
      <p>Attract and convert faster with impactful graphic designs that engage customers and drive real results.</p><br>
      <a href="https://ertadigitalmarketing.com/service/social-media-strategy/">Read More</a>
    </div>

      </li>

      <li class="splide__slide">

        <div class="service-card">
      <video width="100%" muted>
        <source src="/Photo/content marketing.mp4" type="video/mp4">
      </video>
     <h2>Content Marketing</h2>
      <p>We create strategic content that builds trust, boosts brand awareness, and drives growth through meaningful audience engagement.</p><br>
      <a href="https://ertadigitalmarketing.com/service/content-marketing-service/">Read More</a>
    </div>

      </li>

      <li class="splide__slide">

        <div class="service-card">
      <video width="100%" muted>
        <source src="/Photo/web.mp4" type="video/mp4">
      </video>
      <h2>Website Design & E-commerce</h2>
      <p>We design responsive websites and e-commerce platforms that engage visitors and turn clicks into loyal customers.</p><br>
      <a href="https://ertadigitalmarketing.com/service/web-creation/">Read More</a>
    </div>

      </li>

      <li class="splide__slide">

        <div class="service-card">
      <video width="100%" muted>
        <source src="/Photo/seo.mp4" type="video/mp4">
      </video>
      <h2>SEO</h2>
      <p>Boost visibility and drive organic traffic with expert SEO that gets your business found by the right audience.</p><br>
      <a href="https://ertadigitalmarketing.com/service/seo/">Read More</a>
    </div>

      </li>

      <li class="splide__slide">

        <div class="service-card">
      <video width="100%" muted>
        <source src="/Photo/graphic design.mp4" type="video/mp4">
      </video>
      <h2>Graphic Design</h2>
      <p>We design bold, professional visuals that express your brand’s identity and boost engagement on every platform.</p><br>
      <a href="https://ertadigitalmarketing.com/service/graphic-design/">Read More</a>
    </div>

      </li>

      <li class="splide__slide">

        <div class="service-card">
      <video width="100%" muted>
        <source src="/Photo/smm advertising.mp4" type="video/mp4">
      </video>
      <h2>Social Media Advertising</h2>
      <p>We build high-quality websites that turn visitors into customers and boost your social media advertising success.</p><br>
      <a href="https://ertadigitalmarketing.com/service/social-media-advertising/">Read More</a>
    </div>

      
      
		</ul>
  </div>
</section>


<script src="https://cdn.jsdelivr.net/gh/lupe-py/Slide-js-cdn/splide.js"></script>


<script>

const splide = new Splide( '.splide', {
  type   : 'loop',
  drag   : 'free',
  focus  : 'center',
  perPage: 3,
  autoScroll: {
    speed: 1,
  },
} );

splide.mount();

document.addEventListener('DOMContentLoaded', function () {
    new Splide('.splide', {
      type   : 'loop',
      perPage: 4,
      gap    : '1.5rem',
      breakpoints: {
        1200: {
          perPage: 3,
        },
        992: {
          perPage: 2,
        },
        768: {
          perPage: 1,
        },
      },
    }).mount();
  });
   document.querySelectorAll('.service-card').forEach(card => {
  const video = card.querySelector('video'); 

  if (video) {
    card.addEventListener('mouseover', () => {
      video.play();
    });

    card.addEventListener('mouseout', () => {
      video.pause();
      video.currentTime = 0; 
    });
  }
});

</script>

    
</body>
</html>
