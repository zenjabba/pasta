# PASTA
Audio and Subtitle Track Changer for Plex

## What is PASTA?
Do you watch TV Shows with multiple languages and subtitles and wish you could change them for the entire show, rather than needing to do it for *every. single. episode*? 
Or maybe you aren't sure what the difference is between those 2 <strong>English (SRT)</strong> and <strong>English (SRT)</strong> subtitle files. Then PASTA is for you!
PASTA allows you to connect to your Plex server and view more details about the audio tracks and subtitles, as well as set the tracks and subtitles or entire shows, or single episodes very quickly.
        
## How do I use PASTA?
I built PASTA to be as step-by-step as possible and to take you through it, so you should be able to just close this pop-up and follow along.
There are some things I would like to point out, however:
<ul>
    <li>This currently does <strong>not</strong> support logging in via username / password (I will look into that at a later date). Currently you must use the IP address, or if your Plex server is addressable by a valid name address, then use that.</li>
    <li>You must use the Plex Token for authentication. It's the only way I have this working so far. I've included a link with instructions on how to get a Plex Token below the required field.</li>
    <li>This works <strong>MUCH</strong> faster if you are on the same network as the Plex Server.</li>
    <li>You can also run this locally yourself. Just download the source code from github (see the next section).</li>
</ul>

## About PASTA
When I first began developing this for myself, I was calling it *Audio Track Automation for Plex*, so adding "subtitles" to it, and rearranging the letters gave birth to PASTA.
PASTA was born out of a desire, one that I had seen others have as well, but that I had only seen one other solution for. However, it was in command line and I wanted something a bit more appealing to look at, and something I could use from anywhere. Initially I was only building this for myself but I thought that others might find use for it as well, so here we are!

PASTA runs entirely client-side. This means that you are not passing anything to someones server to do this (other than the Plex Server), and it also means I don't have to worry about standing up a server to do that side of things either :). PASTA runs off of Github Pages. Feel free to have a look, download it yourself and use it locally, or make suggestions. I'm by no means finished with PASTA - I still have plenty of ideas for how I can add more to it, as well as fix any bugs that crop up. Feel free to log any issues / feature requests on the Github as well.
