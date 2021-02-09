# spotify-charts <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/Spotify_logo_without_text.svg/1024px-Spotify_logo_without_text.svg.png" width=20>
|<img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/05/Flag_of_Brazil.svg/1200px-Flag_of_Brazil.svg.png" width=25>|[Ler isto em português](https://github.com/Eric-Mendes/spotify-charts/blob/main/README.md "README.md em português")|
|---|:--|
## Introduction
Brazil's territory is really large, therefore it's expected that different regions/cities have different cultures.<br/>
Spotify has playlists with the newest and most popular songs in [São Paulo](https://open.spotify.com/playlist/5DqR5bAbk7mTq5jnvJsjel?si=_Vw9iZ-MT0unvZetXHirqA "Playlist: Viral São Paulo BR"), [Curitiba](https://open.spotify.com/playlist/4iXBmc9lmaFnjBKK9aCXg3?si=R4fJeKTIThC-ctMIFtis6Q "Playlist: Viral Curitiba BR"), [Belo Horizonte](https://open.spotify.com/playlist/4Zn9LFbwTguxz4XeAWTDi1?si=bLoHGsGkTh644-9GaUhf0w "Playlist: Viral Belo Horizonte BR"), [Brasília](https://open.spotify.com/playlist/0X039tyQfxhPtVWoZUqqzX?si=FZtLpzbxTnmyf_B9U1ki_A "Playlist: Viral Brasília BR") and [Rio de Janeiro](https://open.spotify.com/playlist/6GNmpxMYl4hD90GwGINyla?si=wdQailsfQEC--UratCDy6Q "Playlist: Viral Rio de Janeiro BR").
This is a study about the songs in these playlists. <br/>

## Data
The data used in this project was obtained through [Spotify's Web API](https://developer.spotify.com/documentation/web-api/ "Go to Spotify's Web API docs"). First I got each song in each playlist, and then I got each of those song's features. This process generated 2 (two) datasets. Both are in the [data](https://github.com/Eric-Mendes/spotify-charts/tree/main/data "Go to this folder") folder.

## Goals
With this project I intend to make some data-analyses to see if the songs differ a lot between playlists. <br/>After this primary study, I want to use what I've learned to assemble a simple classifier that'll classify any song in one of the 5 (five) classes (cities). This may help artists, because then they'd know where their song fits best, making them able to focus their marketing more on that region/city.

## Motivation
I have participated in a [hackathon](https://www.codestage.com.br/ "Hackathon code/stage") organized by [Sony Music Brazil](https://www.sonymusic.com.br/ "Go to Sony's Music Brazil website") and [Shawee](https://shawee.io/pt/ "Go to Shawee's website"). They had asked us to come up with data-science based solutions for problems in the music industry. My team didn't win, but I'm a musician, so I kept thinking about these "solutions". This is how I've decided to create this project.
