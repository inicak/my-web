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

        <h1 class="headertext">Current Top Artists</h1>

        <center>
            <table class="homepagetext">
            <tr>
                <td>1</td>
                <td>Selena Gomez & The Scene</td>
                <td>Band</td>
            </tr>
            <tr>
                <td>2</td>
                <td>SZA</td>
                <td>Artist</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Demi Lovato</td>
                <td>Artist</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Selena Gomez</td>
                <td>Artist</td>
            </tr>
            <tr>
                <td>5</td>
                <td>The Weeknd</td>
                <td>Artist</td>
            </tr>
            <tr>
                <td>6</td>
                <td>Moe Shop</td>
                <td>Artist</td>
            </tr>
            <tr>
                <td>7</td>
                <td>I DONT KNOW HOW BUT THEY FOUND ME</td>
                <td>Band</td>
            </tr>
            <tr>
                <td>8</td>
                <td>Mindless Self Indulgence</td>
                <td>Band</td>
            </tr>
            <tr>
                <td>9</td>
                <td>Tame Impala</td>
                <td>Artist</td>
            </tr>
            <tr>
                <td>10</td>
                <td>Glass Animals</td>
                <td>Band</td>
            </tr>
            </table>
        </center>

        <style>
            @import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');

            .headertext {
        font-size: 50px;
        font-family: 'Rubik';
        color:#7251b5;
        text-align:center;
            }

            .labeltext {
		font-size: 35px;
		color: #b9fbc0;
        font-family: 'Rubik';
	        }

            .homepagetext {
		font-size: 25px;
		color: #b9fbc0;
        font-family: 'Rubik';
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

        table, th, td {
            border: 5px #b9fbc0;
            border-collapse: collapse;
        }
        th, td {
            background-color: #7251b5;
            padding-top: 7.5px;
            padding-left: 25px;
            padding-right: 25px;
            padding-bottom: 7.5px;
        }

        tr {
        border-bottom: 5px solid #b9fbc0;
        }

        </style>

    </div>
</template>