# Song Recommendation System

This notebook features a music recommendation system based on musical characteristics, such as Acousticness, Danceability, Energy, Instrumentalness, Loudness, Speechiness, among others. The dataset contains information about the musical characteristics of various songs.

## Data set
The dataset was obtained from a music streaming platform and contains information about the following musical characteristics:

- Acousticness: Numeric variable, confidence measure from 0.0 to 1.0 if the track is acoustic. 1.0 represents high confidence that the track is acoustic.
- Danceability: Numerical variable, danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is the least danceable and 1.0 is the most danceable.
- Duration_ms: Numerical variable, the duration of the track in milliseconds.
- Duration_min: Numerical variable, the duration of the track in minutes.
- Energy: Numerical variable, Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks sound fast, loud and loud. For example, death metal is high energy, while a Bach prelude scores low on the scale. Perceptual characteristics that contribute to this attribute include dynamic range, perceived loudness, timbre, onset rate, and overall entropy.
- Explicit: Categorical variable, whether or not the track has explicit lyrics (true = yes (1); false = no(0), no OR unknown).
- Id: The Spotify ID for the track.
- Instrumentalness: Numerical variable, predicts if a track does not contain vocals. The sounds “Ooh” and “aah” are treated as instrumentals in this context. Rap or spoken word tracks are clearly "vocals". The closer the instrumentality value is to 1.0, the more likely the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
- Key: Numerical variable, the overall estimated key of the track. Integers are mapped to pitches using standard Pitch Class notation. For example. 0 = C, 1 = C#/Db, 2 = D, and so on. If no keys were detected, the value is -1.
- Liveness: Numerical variable, detects the presence of an audience in the recording. Higher vividness values represent a greater probability that the track was performed live. A value above 0.8 provides a strong probability that the band is active.
- Loudness: Numerical variable, overall volume of a track in decibels (dB). Volume values are averaged across the entire track and are useful for comparing the relative volume of tracks. Loudness is the quality of a sound that is the main psychological correlate of physical strength (amplitude). Typical values range from -60 to 0 dB.
- Mode: Numerical variable, the mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
- Popularity: Numerical variable, the popularity of a track is a value between 0 and 100, with 100 being the most popular. Popularity is calculated algorithmically and is largely based on the total number of plays the track has had and how recent those plays are.
- Speechiness: Numerical variable, speech detects the presence of spoken words in a track. The more exclusively spoken the recording (eg, talk show, audiobook, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are likely to be made up entirely of spoken words. Values between 0.33 and 0.66 describe tracks that can contain both music and speech, either in sections or in layers, including cases like rap music. Values below 0.33 are likely to represent music and other non-speech tracks.
- Time: Numeric variable, overall estimated time of a track in beats per minute (BPM). In musical terminology, tempo is the speed or rhythm of a given piece and is directly derived from the average duration of the beat.
- Valence: Numerical variable, Measured from 0.0 to 1.0 describing the musical positivity transmitted by a track. High valence tracks sound more positive (eg happy, cheerful, euphoric), while low valence tracks sound more negative (eg sad, depressed, angry).
- Year: Year the song was released.

## Contribution
Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request.
the pull request.
