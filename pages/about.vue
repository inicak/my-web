<template>
    <div>
        <div class="navbar">
            <NuxtLink to="/#">Home</NuxtLink>
            <NuxtLink to="/about">About</NuxtLink>
            <NuxtLink to="/playlists">Playlists</NuxtLink>
            <NuxtLink to="/song-analysis">Song Analysis</NuxtLink>
            <NuxtLink to="/top-songs">Top Songs</NuxtLink>
            <NuxtLink to="/artist-analysis">Artist Analysis</NuxtLink>
            <NuxtLink to="/top-artists">Top Artists</NuxtLink>
            <NuxtLink to="/spotify">Spotify</NuxtLink>
        </div>
        
        <div class="about-me-image">
            <img src="inica.ico" alt="Inica with headphones." width="400" height="520" style="padding: 50px; float: right;">
        </div>

        <h1 class="headertext">About Me!</h1>

        <p class="homepagetext">Hi! My name is Inica and I am a student at Barnard College. 
        I am currently studying Economics and Computer Science.</p>

        <p class="homepagetext">Like any sane person, I love music, and personally believe I have great music taste (hehe.) 
        This site is dedicated to my musical ramblings and is essentially a shrine for my playlists.</p>

        <p class="homepagetext">I'm passionate about using media and music to communicate ideas, specifically political ones, and hope to pursue these
        interests both recreationally and through my career. I have experience in being a podcast host and editor, and hope to host
        a radio show sometime in the future.</p>

        <p class="homepagetext"> You can email me at inica.kotasthane@gmail.com or find me on LinkedIn <a class="homepagetext" href="https://www.linkedin.com/in/inica-kotasthane/" target="_blank">here.</a> </p>

        <style>
            @import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');
            
            .about-me-image {

            }
            
            .headertext {
        font-size: 50px;
        font-family: 'Rubik';
        color:#7251b5;
        text-align:center;
            }

            .homepagetext {
		font-size: 25px;
		color: #7251b5;
        font-family: 'Rubik';
        padding-left: 20px;
        text-align:center;
	        }

            .navbar {
        width: 98.5%;
        background-color: #b9fbc0;
        overflow: auto;
        float: center;
        padding: 10px;
        color: #7251b5;
        text-decoration: none;
        font-size: 20px;
        font-family: 'Rubik';
        display: flex;
        justify-content: space-around
        }

         body {
            background-color: #b9fbc0;
        }
        </style>

    </div>
</template>