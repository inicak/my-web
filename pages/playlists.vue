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

        <h1 class="headertext">Playlists</h1>

        <center>
            <table class="homepagetext" style="width:90%">
            <tr>
                <td>haha fast car go vroom vroom</td>
                <td>For a fast-paced, high-intensity main character moment. Fight those villains, outsmart your enemies, and save the world.</td>
            </tr>
            <tr>
                <td>i'm gonna funk your mom</td>
                <td>Warning! If you listen to this playlist, you may experience the following side effects: swinging hips, bopping head, drumming fingers, increased serotonin, stroke, and sudden death.</td>
            </tr>
            <tr>
                <td>the holy trinity</td>
                <td>Hits and bangers from the Father (Demi Lovato), the Son (Miley Cyrus), and the Holy Spirit (Selena Gomez).</td>
            </tr>
            <tr>
                <td>MILFBAIT</td>
                <td>30 songs I put together for my radio show application to Barnard's freeform station (spoiler: I didn't get an offer.) Listen for some smooth R&B, some hard-hitting rock, and more!</td>
            </tr>
            <tr>
                <td>working super faswt</td>
                <td>Throwbacks for a much-needed study session to keep you motivated and on task.</td>
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