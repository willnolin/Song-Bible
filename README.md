# Song-Bible
Learn a song

 Project Overview

## Project Name

Song Bible

## Project Description

This app will provide material to learn a specific song by a specific artist.  User will be able to search for an artist, choose a song and view available data for that song.  The app will display the song lyrics, chords, tabs and metadata information (if available!). 

## API and Data Sample

Songsterr API returns data array on a specific pattern (name) with a specified parameter.  In this case, an artist. Request returns an array of songs.  

ie. http://www.songsterr.com/a/ra/songs.json?pattern=Radiohead

```{
        "id": 97,
        "type": "Song",
        "title": "Creep",
        "artist": {
            "id": 48,
            "type": "Artist",
            "nameWithoutThePrefix": "Radiohead",
            "useThePrefix": false,
            "name": "Radiohead"
        },
        "chordsPresent": true,
        "tabTypes": [
            "PLAYER",
            "TEXT_GUITAR_TAB",
            "CHORDS",
            "TEXT_BASS_TAB"
        ]
    },
    {
        "id": 16501,
        "type": "Song",
        "title": "Paranoid Android",
        "artist": {
            "id": 48,
            "type": "Artist",
            "nameWithoutThePrefix": "Radiohead",
            "useThePrefix": false,
            "name": "Radiohead"
        },
        "chordsPresent": true,
        "tabTypes": [
            "PLAYER",
            "TEXT_GUITAR_TAB",
            "CHORDS",
            "TEXT_BASS_TAB"
        ]
    },
    {
        "id": 436709,
        "type": "Song",
        "title": "My Iron Lun",
        "artist": {
            "id": 48,
            "type": "Artist",
            "nameWithoutThePrefix": "Radiohead",
            "useThePrefix": false,
            "name": "Radiohead"
        },
        "chordsPresent": false,
        "tabTypes": [
            "PLAYER"
        ]
    },
 ```
I will also be using a simple lyrics API called Lyrics.ovh.  The song title and artist name are easily incorporated into the request URL. Spaces are accounted for and url is created from data in Songster API request.

ie. https://api.lyrics.ovh/v1/Queen/We Will Rock You 

```
{
    "lyrics": "Buddy you're a boy make a big noise\r\nPlayin' in the street gonna be a big man some day\r\nYou got mud on yo' face\r\nYou big disgrace\r\nKickin' your can all over the place\r\nSingin'\n\n\n\nWe will we will rock you\n\nWe will we will rock you\n\n\n\nBuddy you're a young man hard man\n\nShouting in the street gonna take on the world some day\n\nYou got blood on yo' face\n\nYou big disgrace\n\nWavin' your banner all over the place\n\n\n\nWe will we will rock you\n\nSing it\n\nWe will we will rock you\n\n\n\nBuddy you're an old man poor man\n\nPleadin' with your eyes gonna make\n\nYou some peace some day\n\nYou got mud on your face\n\nBig disgrace\n\nSomebody betta put you back into your place\n\n\n\nWe will we will rock you\n\nSing it\n\nWe will we will rock you\n\nEverybody\n\nWe will we will rock you\n\nWe will we will rock you\n\nAlright"

}
```


## Wireframes

![alt text](https://res.cloudinary.com/willnolin/image/upload/c_thumb,w_200,g_face/v1621178951/Homepage_cijq9c.png "homepage")

![alt text](https://res.cloudinary.com/willnolin/image/upload/c_thumb,w_200,g_face/v1621178966/after_song_click_ushuyd.png "after search")

![alt text](https://res.cloudinary.com/willnolin/image/upload/c_thumb,w_200,g_face/v1621178965/after_search_kz1hsr.png "after click")
#### MVP 
  * Allow user to search for Artist
  * Allow user to choose Song
  * Display song lyrics and tabs on the webpage

#### PostMVP  
  * hovering over songs displays availability of lyrics or tabs
  * once song is chosen, display album art and other metadata from that song
  * button for lyrics scrolling at a specific speed
  * allow user to lookup chord diagrams

## Project Schedule

|  Day | Deliverable | Status
|---|---| ---|
|May 14-16| Prompt / Wireframes / Priority Matrix / Timeframes | Complete
|May 17| Project Approval / Core Application Structure (HTML,CSS. js) API calls working properly | Incomplete
|May 18| Pseudocode / actual code / functionality / MVP | Incomplete
|May 19| Style Style Style / Start Post-MVP | Incomplete
|May 20| Post-MVP| Incomplete
|May 21| Presentations | Incomplete

## Priority Matrix
![alt text](https://res.cloudinary.com/willnolin/image/upload/v1621128421/Song-Bible-Priority-Matrix_cqmmf0.png "priority matrix")

## Timeframes

Tell us how long you anticipate spending on each area of development. Be sure to consider how many hours a day you plan to be coding and how many days you have available until presentation day.


| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Working with API | H | 3hrs| | |
| Make API call with data from API (second call) | H | 2hrs | | |
| Figure out how to display Tabs or Chords | H | 3hrs | | |
| Intergate lyrics API | H | 3hrs| | |
| Display Lyrics on the page| H | 3hrs| |  |
| Integrating user search | H | 3hrs| | |
| Style search container with flexbox | H | 3hrs | | |
| Style results container with flex | H | 3hrs | | |
| Continue styling page | H | 3hrs | | |
| Add extra data on page | L | 3hrs | | |
| Display extra data | L | 3hrs | | |
|Stylize extra data | L | 3hrs | | |
| Total | H | 35hrs |  | |

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of and a brief description.  

```

```

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  
