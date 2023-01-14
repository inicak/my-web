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

        <h1 class="headertext">Artist Analysis</h1>

        <center>
            <table class="homepagetext" style="width:90%">
            <tr>
                <td>Mariah the Scientist</td>
                <td>Strong vocals, raw emotion, and powerful background music makes Mariah the Scientist an artist to look out for. Her songs are nothing short of masterpieces, and can heal any broken heart.</td>
                <td>R&B</td>
            </tr>
            <tr>
                <td>Natasha Bedingfield</td>
                <td>Delivering iconic background tracks for 2000's rom-coms left and right, Natasha Bedingfield has a timeless voice that keeps you coming back for more. </td>
                <td>Pop</td>
            </tr>
            <tr>
                <td>Kavinsky</td>
                <td>Kavinsky's masterful use of synth brings you back to the 80s with a flashlight in your hand and a mystery to solve. Feel unstoppable with any of his songs playing.</td>
                <td>Electronic</td>
            </tr>
            <tr>
                <td>Melody's Echo Chamber</td>
                <td>With mesmerizing lyrics, original instrumentals, and a wonderful voice, Melody's Echo Chamber never fails to make you feel everything, yet nothing, all at once.</td>
                <td>Psychedelic Pop</td>
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
            border: 5px;
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