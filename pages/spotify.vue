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
        
        <center>
        <div>
            <img src="spot.ico" alt="Scannable Spotify profile link." width="400" height="500" style="padding: 50px;">
        </div>
        </center>

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