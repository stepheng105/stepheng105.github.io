

Here are some photos of me and some of my hobbies! Hover over an image to see a brief description.

<div class="masonry">
    <img 
        src="static/assets/img/trumpet_solo_1.jpg" 
        alt="Me playing a solo for at the Lunar New Year parade in San Francisco." 
        title="I was a section leader for the Cal Poly Mustang Band. This is me playing a solo for our performance at the Lunar New Year parade in San Francisco."
    />
    <img 
        src="static/assets/img/gloomhaven.jpg" 
        alt="One of the larger board games I like to play with my friends called Gloomhaven." 
        title="Me and my friends love large nerdy board games. This is one of the larger board games we play called Gloomhaven."
    />
    <img 
        src="static/assets/img/brass_quintet.JPG" 
        alt="Me alongside the Cal Poly brass quintet performing Anthony DiLorenzo's Fire Dance." 
        title="Me alongside the Cal Poly brass quintet performing Anthony DiLorenzo's Fire Dance for donors of the music department."
    />
    <img 
        src="static/assets/img/jmm_poster.jpg" 
        alt="My research group, research advisor and me and presenting our work at the 2024 JMM conference in San Francisco." 
        title="This is me, my research group, and my research advisor Dr. Vincent Bonini after presenting our work at the 2024 JMM conference in San Francisco."
    />
    <img 
        src="static/assets/img/ray.jpg" 
        alt="A cute Ray I saw at the Aquarium of the Pacific in Long Beach." 
        title="This is just a cute Ray I saw at the Aquarium of the Pacific in Long Beach."
    />
    <img 
        src="static/assets/img/me_and_nick_mustang_band.JPG" 
        alt="This is Me and a friend furiously dancing during one of our Mustang Band postgame performances." 
        title="This is me and a friend furiously dancing during one of our Mustang Band postgame performances."
    />
    <img 
        src="static/assets/img/hike_with_kelley.jpg" 
        alt="A photo of me and my Girlfriend atop Madonna Mountain." 
        title="This is a photo of me and my Girlfriend atop Madonna Mountain."
    />
    <img 
        src="static/assets/img/awards.jpg" 
        alt="A photo of me and my friends receiving our awards." 
        title="This is me and my friends receiving our awards at the yearly math department banquet."
    />
    <img 
        src="static/assets/img/rock_climbing.jpg" 
        alt="Me rock climbing." 
        title="This is me rock climbing at the local rock climbing gym (I'm not very good, but it's still fun)."
    />
    <img 
        src="static/assets/img/cal_poly_poster.jpg" 
        alt="Me presenting a poster at the Cal Poly poster symposium." 
        title="This is me presenting my research group's poster on Paley graphs at the Cal Poly poster symposium."
    />
    <img 
        src="static/assets/img/bowling_scores.JPG" 
        alt="Me and my friends' bowling scores" 
        title="These are some bowling scores for me and my friends from a recent bowling class. We have been going for a while now, and we've been slowly improving!"
    />
    <img 
        src="static/assets/img/jellies.jpg" 
        alt="Some cool jellies from the Monterey Bay aquarium" 
        title="These are some cool jellies I saw at the Monterey Bay aquarium (If you couldn't tell, I love marine life and marine biology)!"
    />
    
</div>

<style>
  .masonry {
    column-gap: 10px; /* Space between columns */
  }

  .masonry img {
    width: 100%;
    margin-bottom: 10px; /* Space between rows */
    display: block; /* Ensures no inline gap */
  }

  /* Adjust the number of columns based on screen size */
  @media (min-width: 900px) {
    .masonry {
      column-count: 3; /* 3 columns for medium screens */
    }
  }

  @media (max-width: 900px) {
    .masonry {
      column-count: 2; /* 2 columns for smaller screens */
    }
  }

  @media (max-width: 480px) {
    .masonry {
      column-count: 1; /* 1 column for very small screens */
    }
  }
</style>

<script>
  // JavaScript to adjust image height based on their aspect ratio
  window.addEventListener('load', function() {
    const masonry = document.querySelector('.masonry');
    const images = masonry.querySelectorAll('img');
    images.forEach(img => {
      img.style.height = img.offsetWidth * (img.naturalHeight / img.naturalWidth) + 'px';
    });
  });
</script>

