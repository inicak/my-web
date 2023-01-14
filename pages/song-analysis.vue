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

        <h1 class="headertext">Song Analysis</h1>

        <center>
            <table class="homepagetext" style="width:90%">
            <tr>
                <td>Careless Whisper</td>
                <td>George Michael</td>
                <td>Beyond just the iconic saxophone intro, this song has amazing vocals that truly communicate how guilty feet have got no rhythm.</td>
            </tr>
            <tr>
                <td>Ganz oder gar nicht</td>
                <td>Wolfgang Petry</td>
                <td>My friend once played this on aux, and I've never been the same. I don't even know what language this song it's in, but you can't knock it 'til you've tried it.</td>
            </tr>
            <tr>
                <td>I'm Still Standing</td>
                <td>Taron Egerton</td>
                <td>Yes, this is the version from "Sing." The gorilla really did not have to go as hard as he did, but sorry Elton, the cover is better than the original.</td>
            </tr>
            <tr>
                <td>Runner</td>
                <td>Tennis</td>
                <td>With beautiful, airy vocals and haunting lyrics, this song is one that fills your car's empty passenger seat as you drive on a foggy morning.</td>
            </tr>
            <tr>
                <td>Peach</td>
                <td>Oscar Scheller</td>
                <td>With a beat you can tap your foot to and an addicting chorus, this is a great aux selection for trips with friends.</td>
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