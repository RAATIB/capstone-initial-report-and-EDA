# capstone-initial-report-and-EDA
Professional Certificate in ML/AI Capstone Initial Report and EDA

# Can we predict how well a song will do on Spotify by assessing it's musical characteristics?

Raatib Tanvir | Dec 5 2025 | Professional Certificate in Machine Learning and Artificial Intelligence

**Assignment notebook:**
https://github.com/RAATIB/capstone-initial-report-and-EDA/blob/c1991634dfc9e9ed3d657acafd91a5d273780b77/spotify%20analysis%20Raatib%20Tanvir%20Capstone%20ML%3AAI.ipynb


## Introduction and Problem Statement:
In this project, we utilized data processing tools and a machine learning model to determine whether certain aspects of a track on Spotify, like "energy" and "danceability", could predict how commercially successful that song would be on Spotify.

Our analysis provided ***useful information for artists and their companies, indicating which features may contribute to a song's success and to what degree.***

Our analysis was specified to include only numeric features of a song, like a score for "energy", or a song's key signature and duration, for example.

Our conclusions lead us to **actionable steps for artists and company** to help secure commercial success in a competitive landscape, giving direction for producers and songwriters to **assess and predict which tracks can help them stand out to a crowd** and stay afloat in a market of constant innovation!


## Strongest Indicators of Success (Per Linear Regression)

### Danceability and Time signature (Positive indicators) vs. Speechiness (Negative Indicators)

* Our analysis indicates that a songs **danceability is a strong indicator of it's success. The more danceable a song is, the more likely it is to succeed.** Likewise, a higher time signature is more likely to succeed by a significant degree. In practice, after assessing the data, **this means a time signature of 4 will perform better than a time signature of 3** in terms of commercial success.
* On the other hand, **speechiness can be a large cause of detriment for a song. Artists should avoid sections of speech** in their music when gearing for virality or popularity.


## Moderate Indicators of Success

### Liveness and acousticness
* Our analysis shows promising information for live and acoustic tracks. **Liveness and acousticness both significantly contribute to a song's popularity, implying that audiences want live and acoustic versions of music.** This may imply that a more genuine or authentic spin on a song leads to success. It is not as strong of an indicator as danceability or time signature, though, so those should be prioritized when producing for popularity.


## Summary of Insights from Initial Model:
*Here, we'll summarize how numeric features of a song predict a song's success.*

* Strongest Positive Indicators: Danceability and a higher time signature are very strongly beneficial for a song's popularity.
* Strongest Negative Indicator: Speechiness tends to very strongly decline the popularity of a song.
* Moderate Positive Indicator: Liveness and acousticness are aspects that can decently improve the popularity of a song. Data tells artists that a live or acoustic Spotify version tends to succeed!
* Lack of Indication: Artists can rely on diverse tempo, key, mode, loudness, valence, instrumentalness, AND duration! These do not strongly affect the popularity of a song.


## Further Modeling
* To discover **whether more complex machine learning models could give us deeper insights** into this problem, we engaged with several other techniques to find actionable information for artists and management.
* Specifically, we tested machine learning models such as decision tree classifiers, random forest regressors, and artificial neural networks. These are more complex machine learning models that can be attuned to find very special and specific trends in data. In the case of music popularity, ***insights into the effectiveness of these models can guide business leaders to devote resources adequately towards machine learning analysis***. Such insights can guide business leaders designing similar projects seeking to convert data into deliverables and marketing techniques.


* Our experiences comparing "Classifiers" and "Regressors" indicated that seeking actionable insights in Spotify track data and similar music world data can be heavily defined by the type of data being used. Engineers engaging in business projects should know that certain datasets can prove exceedingly difficult to address with classifiers, and that heavily numeric data can be more adequately addressed using regressors. Even so, ***data that gives us actionable insights like the ones above may actually be easier to address using simpler models***!


* Our experiences with artificial neural networks demonstrated the need for guidance. Business leaders should seek to understand the difference in complexity of a given problem, and that artificial neural networks tend to be very complex machine learning models that use a lot of computational resources and need a lot of fine-tuning to build a model that adequately reflects real-world scenarios.
* Essentially, business leaders in the music space should seek engineers and other individuals with a knowledge background that allows them to fine-tune neural networks towards unique problem, and accept that ***simpler models may give us very insights that cannot easily be deepened through the use of very complex models***. Business leaders should seek consultation with individuals who have deep technical knowledge of these more complex models before engaging with them in a business project!

