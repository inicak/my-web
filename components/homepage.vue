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
            <a href="https://open.spotify.com/user/15p6i8yrvhn8ejg7ztiee69xa?si=WpHcqPpESlSqFJM-IpEdUQ">Spotify</a>
          </div>

        <center>
            <h1 class="headertext">Stay in Tune with Inica!</h1>
            <p class="homepagetext">Welcome, internet user, to a site filled with music. Explore pre-existing playlists, see what my top songs and artists are, and persue through some of my musical opinions!</p>
            <p class="homepagetext">If you like what you see, feel free to follow me on Spotify!</p>
        </center>

        <style>
            @import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');
            
            .headertext {
        font-size: 100px;
        font-family: 'Rubik';
        color:#7251b5;
            }

            .homepagetext {
		font-size: 35px;
		color: #7251b5;
        font-family: 'Rubik';
        padding-left: 50px;
        padding-right: 50px;
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
