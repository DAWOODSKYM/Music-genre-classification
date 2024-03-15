# Music-genre-classification
This is a step by step project on Machine Learning Tools and Techniques
# Problem Statement
Many of us utilize music streaming applications for our music listening needs. These platforms often curate personalized playlists tailored to each user's preferences. But what drives the creation of these personalized playlists? One common approach involves implementing a Music Genre Classification System. This entails developing a machine learning model capable of categorizing music samples into distinct genres by analyzing various audio features.

# Project goal
The primary objective of this task is to construct an optimal machine learning system for genre prediction in music. The goal is to classify music tracks into one of ten genres based on provided audio features. Each track's data includes both textual elements such as artist and track names, as well as numerical descriptors like duration, alongside diverse audio features. The aspiration is for our model to discern the correlation between music genres and these audio characteristics.

# The data
The data used is a processed version of the music genres data. It has the following features.
-  **duration_ms:** The duration of the track in milliseconds.
- key: The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation . E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.
- **mode:** Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
- **time_signature:** An estimated overall time signature of a track. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure).
- **acousticness:** A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
- **danceability:** Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall - regularity. A value of 0.0 is least danceable and 1.0 is most danceable.
- **energy:** Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.
- **instrumentalness:** Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly “vocal”. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
- **liveness:** Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
- **loudness:** The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db.
- **speechiness:** Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
- **valence:** A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
- **tempo:** The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
- **id:** The Spotify ID for the track.
- **type:** The object type: “audio_features”
- **popularity:** The popularity of the track. The value will be between 0 and 100, with 100 being the most popular. The popularity is calculated by algorithm and is based, in the most part, on the total number of plays the track has had and how recent those plays are. Generally speaking, songs that are being played a lot now will have a higher popularity than songs that were played a lot in the past. Artist and album popularity is derived mathematically from track popularity. Note that the popularity value may lag actual popularity by a few days: the value is not updated in real time.
# Project methodology
 - Exploring and understanding the Data
 - Developing and testing our machine learning system
 - Reflecting on our findings
Follow these steps in the [Notebook](https://github.com/DAWOODSKYM/Music-genre-classification/blob/main/Music_Genres_Classsification.ipynb)
_____________________________________________________________________________________________________________________
> If Music is a Place — then Jazz is the City,
 <br>Folk is the Wilderness,</br>
 <br>Rock is the Road,</br>
 <br>Classical is a Temple.</br>
<br>😎 :feelsgood:</br>
<br>*Vera Nazarin*</br>

