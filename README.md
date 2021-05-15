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
I will also be incorporating a simple lyrics API called Lyrics.ovh.  The song title and artist name are easily incorporated into the request URL. Spaces are accounted for and url is created from data in Songster API request.

ie. https://api.lyrics.ovh/v1/Queen/We Will Rock You 

```
{
    "lyrics": "Buddy you're a boy make a big noise\r\nPlayin' in the street gonna be a big man some day\r\nYou got mud on yo' face\r\nYou big disgrace\r\nKickin' your can all over the place\r\nSingin'\n\n\n\nWe will we will rock you\n\nWe will we will rock you\n\n\n\nBuddy you're a young man hard man\n\nShouting in the street gonna take on the world some day\n\nYou got blood on yo' face\n\nYou big disgrace\n\nWavin' your banner all over the place\n\n\n\nWe will we will rock you\n\nSing it\n\nWe will we will rock you\n\n\n\nBuddy you're an old man poor man\n\nPleadin' with your eyes gonna make\n\nYou some peace some day\n\nYou got mud on your face\n\nBig disgrace\n\nSomebody betta put you back into your place\n\n\n\nWe will we will rock you\n\nSing it\n\nWe will we will rock you\n\nEverybody\n\nWe will we will rock you\n\nWe will we will rock you\n\nAlright"

}
```


## Wireframes

Upload images of your wireframes to an image hosting site or add them to an assets folder in your repo and link them here with a description of each specific wireframe.

### MVP/PostMVP

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP 
*These are examples only. Replace with your own MVP features.*

- Find and use external api 
- Render data on page 
- Allow user to choose favorites 

#### PostMVP  
*These are examples only. Replace with your own Post-MVP features.*

- Add second API
- Use local storage to save user favorites

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|May 14-16| Prompt / Wireframes / Priority Matrix / Timeframes | Incomplete
|May 17| Project Approval / Core Application Structure (HTML, CSS, etc.) | Incomplete
|May 18| Pseudocode / actual code | Incomplete
|May 19| Initial Clickable Model  | Incomplete
|May 20| MVP | Incomplete
|May 21| Presentations | Incomplete

## Priority Matrix

Include a full list of features that have been prioritized based on the `Time and Importance` Matrix.  Link this image in a similar manner to your wireframes

## Timeframes

Tell us how long you anticipate spending on each area of development. Be sure to consider how many hours a day you plan to be coding and how many days you have available until presentation day.

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe. Throughout your project, keep track of your Time Invested and Actual Time and update your README regularly.

| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Adding Form | H | 3hrs| 3.5hrs | 3.5hrs |
| Working with API | H | 3hrs| 2.5hrs | 2.5hrs |
| Total | H | 6hrs| 5hrs | 5hrs |

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of and a brief description.  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  
