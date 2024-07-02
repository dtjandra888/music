# Desktop music player application

Don't want to use spotify on computers anymore, lags my PC when playing games and their desktop app is not good. This will also be a step towards not having to pay for spotify premium.

## Key functionalities
- Cross-platform (linux and windows)
- Need to be able to download music from spotify/youtube/soundcloud
- Playlists
- Decent clean looking UI
- Can't compromise on music quality
- Integrates with OS music tooling (can scrap this if I can't figure it out for cross platform)

## Technologies that can be used
- Main application
    - Qt (Cross-platform, fast, but will likely need to build some more complex parts of the app myself)
- Need some kind of way to extract data from spotify api, youtube, and soundcloud
    - Backend
        - FastAPI, Django, or Go (want to learn go but have never used)
    - C++ library if it exists or is not too complicated
- Storage across devices (Cloud)
    - Postgresql
    - AWS or an ElephantSQL replacement (there shouldn't be too many songs so a free service will likely suffice)
- Git for version control



## TODOS
1. Need to decide if I want this as a local app, or if I want to store data on the cloud so it can be used across devices
2. Need to decide if I need a backend or not
3. Figure out how the Spotify and youtube APIs work, and if I can even extract/download songs from it
