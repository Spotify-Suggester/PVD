# Product Vision Document

This is the template for the Product Vision Document that teams complete after their initial icebreaker. The PVD is crucial to the planning phase and **is mandatory for all groups to complete and submit to their Project Lead before starting their project.**

# ☝️ Proposal

---

- What problem does your app solve?
    Provide a curated list of song / playlist based on user's input / favorite songs / liked songs
- Be as specific as possible; how does your app solve the problem?
    Curated song list based on user's mood (input)
    Linear regresion (train on what the song is based on genre, mood, dancibility, beat, classification, tempo)
    React UI / Backend: Authentication
    React UI: Create playlist, add liked / favorite, add or remove songs, recomended songs
    Backend tables: Playlist, User, Song, Favorites table
    Marketing: Landing Page, About / Team Page


- What is the mission statement?

    Curate the best list of songs

# 💡 Features

---

- What features are required for your minimum viable product?
    
    **DS:**

    1. Build a model to recommend songs based on similarity to user input (I like song `x`, here are `n` songs like it based on these similar features)
    2. Create visualizations using song data to highlight similarities and differences between recommendations.

    **Web:**

    1. User registration / login flow
    2. User can save their favorite songs to their profile in the Web backend
    3. Once the user has their favorites saved the DS API can make suggestions based on the audio features of their favorites.
    4. User can request suggested songs based on what they are in the mood for ( acousticness, danceability, duration, energy, etc)
    5. User can edit and delete their favorites.

- What features may you wish to put in a future release?

    Most repeated songs list
    Favorites from the last months of listened songs
    Social features, share songs, playlist
    Integration with Spotify
    Export recommendation list of songs
    Link to external source to purchase song/album
    Custimazible layouts
    Dark/light theme or more colorful themes
    Location recommendation based playlist (ie, at the gym, school)
    Comment on songs at specific time (DAT DROP)
    Provide songs lyrics

- What do the top 3 similar apps do for their users?

    Spotify
        Provide list of playlist by mood, genre, repeated, favorites, workout


    Pandora
        Adjust playlist based on liked history

    iTunes
        Purchable library

# 🛠 Frameworks - Libraries

---

- What 3rd party frameworks/libraries are you considering using?
    Spotify API
    https://developer.spotify.com/documentation/web-api/

    DS
    Flask
    Numpy
    Pandas
    Sci Kit Learn
    Neurosomething
    Tensor Flow
    
    WEB
    React
    Styled components? Bootstrap? Semantic UI? Material UI? Tailwind?
    Context API
    React-Hook-Form
    Heroku
    PG
    Knex 
    Web token




- Do the APIs you need require you to contact them to gain access?
    TODO

- Are you required to pay to use said API(s)?
    NO

# 🧮  For Data Scientists

---

- Describe the established data source with at least rough data able to be provided on day one.
    TODO for DS Students to discuss
- Write a description for what the data science problem is. What uncertainty or prediction are you trying to discover? How could this data be used to find a solution to this problem?
    How to get enough data to be able to prodict recommendation.
- What kind of target output can you deliver to the Web/UX/iOS teams to work with? Is it in JSON format or something else?
    TODO

# 🎯 Target Audience

---

- Who is your target audience? Be specific.
    Everyone that loves music, spotify users
- What feedback have you gotten from potential users?
    Needs to have compeling features
- Have you validated this problem and your solution with a target audience? Describe how.
    TODO

---

# 🔑 Prototype Key Feature(s)

---

- How long do you think it will take to implement these features?
    2 weeks + feature creep
- Do you anticipate working on stretch functionality after completion of a Minimal Viable Product?
    Yes
