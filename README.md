#jukeDec 
jukebox, decentralized

Jukedec will incorporate a set of services that allow for an end-user to queue up songs on an internet radio stream by paying in SLP tokens. The payment then gets distributed, with half of it going to the artist, and the rest paying infrastructure costs. The library of audio is built from scratch, with the artists incentivized to upload their content to a federated system of independantly-run content servers through ease of use. 

## The Four Pieces

Library Server, Org Server, PWA, Streaming Endpoint

### Library Servers

A set of federated library servers (example being [jukeDec.com](http://jukedec.com) ) acts as the backbone of the audio hosting.

The administration & liability is then the responsibility of the individuals runnning these servers.

### Org Server

The org server is resposnible for distributing the PWA and acts as a caching endpoint for Library servers and Streaming endpoints. Responsible for maintaining JukeDec Token

### PWA

Progressive web app for users to buy tokens, pick vennues, query music database, and send songs to jukebox venues. 

![Example](http://frigginglorio.us/fil/jukedec/jukedec1.png) ![Example](http://frigginglorio.us/fil/jukedec/jukedec2.png) ![Example](http://frigginglorio.us/fil/jukedec/jukedec3.png)

### Streaming Endpoint

Icecast server setup? A venue (phisical or digital) Will register what is basically just a web radio stream.

## Links

[Slide Presentation](http://jukedec.githubpages.io/jukedec.html) - For BlockHack Global 2020 hackathon

[jukeDec.com](http://jukedec.com) - working PoC of Hugo SSG based on MP3 ID3 tags

[Setlers Demo](http://play.jukedec.com/Setlers/) - Static site created by 100% programatically

[Music Videogame](http://frigginglorious.github.io/iSwimMusicVideoGame/index.html) - User Acquisition: generating games/visualizations from audio