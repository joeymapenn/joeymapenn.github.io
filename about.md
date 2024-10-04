---
layout: about
permalink: /about/
title: A little bit more about me.
tags: about
headshot: /images/headshot.jpg
---

### Where I'm from
I was born in Henan, China 🇨🇳, and came to the United States in 2021 to pursue my studies. I have since completed a degree in Financial Engineering at the University of Southern California, where I worked with Prof. Petros Ioannou, focusing on the application of machine learning algorithms to asset pricing.

### What I do now
I am currently pursuing graduate studies at the University of Pennsylvania, with research interests in probabilistic machine learning and a variety of computational economics problems. Additionally, I have a strong interest in quantitative finance, particularly in using natural language processing techniques to analyze alternative data, such as textual and crowdsourced sources, to mine alpha signals.

### What I do in spare time
I’m a beginner in fitness and would love to hear about your experiences! When I’m not working or doing research, I go hiking ⛰️ every week. I’m planning to hike in South America soon—imagine lying on a boat, floating on the Amazon River, and watching the stars 🌌.

<!-- 
<div id="stats" class="hidden">
Check out my [Coffee Notes]({{ site.baseurl }}/blog/)
<h3 id="dashboard"><code>#dashboard</code></h3>

<h2>Just finished.</h2>

<p>Curious what I'm reading? Here's my most recent reads, updating daily. And my <a href="https://www.goodreads.com/user/show/88184044-jonathon-belotti)" target="_blank" rel="noopener noreferrer">Goodreads profile</a> has more history.</p>

<div id="recent-finished-books"></div>

<h2>Top tracks.</h2>

<p>Curious what I'm currently listening to? Here's my top tracks on Spotify, updating daily.</p>

<ol id="top-spotify-tracks"></ol>

</div>

<script>
/**
 * @param {String} HTML representing a single element
 * @return {Element}
 */
function htmlToElement(html) {
    var template = document.createElement('template');
    /* Never return a text node of whitespace as the result */
    html = html.trim();
    template.innerHTML = html;
    return template.content.firstChild;
}

function populateDashboardHTML(data) {
    const topSpotifyTracksList = document.querySelector('#top-spotify-tracks');
    data.spotify.forEach(track => {
        topSpotifyTracksList.appendChild(htmlToElement(`
            <li>
                <a target="_blank" rel="noopener noreferrer" href="${track.link}"><strong>${track.name}</strong></a> 
                <p>${track.artist}</p>
            </li>
        `));
    });

    const recentFinishedBooks = document.querySelector('#recent-finished-books');
    data.goodreads.slice(0, 3).forEach(book => {
        recentFinishedBooks.appendChild(htmlToElement(`
            <a target="_blank" rel="noopener noreferrer" class="book-item" target="_blank" rel="noopener noreferrer" href="${book.link}">
            <div class="cover-container">
                <img class="grow-me" src="${book.cover_image_link}">
            </div>
            <div class="book-info">
                <h4>${book.title}</h4>
                <p>${book.authors[0]}</p>
            </div>
            </a>
        `));
    });
}

fetch('https://thundergolfer--thundergolferdotcom-about-page-web.modal.run')
  .then((response) => {
    if (!response.ok) {
      throw new Error(`HTTP error! Status: ${response.status}`);
    }

    return response.json();
  })
  .then((data) => {
    populateDashboardHTML(data);
    /* Reveal the now populated stats section. */
    document.getElementById("stats").classList.remove("hidden");
  });

</script>

<style>
#stats {
  background-color: #f7f7f9;
  border-radius: 1rem; 
  padding: 1.5em;
  margin-top: 2.5em;
}

#dashboard {
  margin: 0rem;
}

#dashboard code {
  background-color: #f7f7f9;
}

#recent-finished-books {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
}

#recent-finished-books a {
    color: #111;
}

.book-item {
    margin-left: 0.4em;
    margin-right: 0.4em;
}

.book-item div {
    width: 200px;
}

.book-info h4 {
    color: #222;
}

.book-info p {
    color: #555;
}

.grow-me {
  border-radius: 4px;
  transition: all .2s ease-in-out;
}

.grow-me:hover {
  transform: scale(1.02);
}

#top-spotify-tracks {
    padding-left: 1em;
}

#top-spotify-tracks li {
    color: #888;
    border-bottom: 1px solid #ededed;
    margin-top: 1rem;
}

#top-spotify-tracks a {
    color: #111;
}

#top-spotify-tracks a:hover {
    color: #1DB954; /* Spotify green */
}

#top-spotify-tracks p {
    color: #555;
}

.hidden {
    display: none;
}

@media screen and (max-width: 900px) {
  #recent-finished-books {
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .book-item div {
    width: 400px;
  }

  .book-item {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .cover-container, .book-info {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #top-spotify-tracks {
    padding-left: 1.2em;
  }
}
</style> -->
