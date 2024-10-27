# Overview
This app shows which movie torrents are available for download based on the HTML of an IMDB Watchlist page. It uses the YTS API.



# Version Control
- 1.1.1 - Refactoring & Validation (HTML/CSS).
- 1.1.0 - Non Refactored Code (HTML/CSS).
- 1.0.0 - R&D code.



# TODO
- [-] Moving UI elements (meta data to genre)
- [-] HTML & CSS - Refactor & Validate
- [-] JS
- [-] JS - Refactor & Validate
- [-] Tool Tips
- [-] Refactor & Validate
- [-] Testing & QA
- [-] Refactor & Validate
- [-] ReadMe & Git doc
- [-] Open Graph featured image
- [-] Smooth expand details/summary
- [x] Set active state styles for buttons & links



# Notes

## Required Data 
- data.data.movie
    - id
    - url
    - imdb_code
    - title
    - year
    - rating
    - runtime
    - genres[]
    - description_full
    - yt_trailer_code
    - language
    - medium_cover_image
- data.data.movie.torrents
    - url
    - quality
    - type
    - video_codec
    - bit_depth
    - audio_channels
    - seeds
    - peers
    - size