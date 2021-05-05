# Characterization and forecast of online music consumption dynamics
Most relevant Jupyter Notebooks developed for my Master thesis project at Sony Computer Science Lab.

In each Notebook a detailed documentation is available.

**Abstract**:

A data-set of 2251 songs released between 2020/01/15 and 2020/03/24 is analyzed
to formulate short and long term predictions of popularity using machine learning
techniques. These public data were collected from Spotify, the largest subscription
music streaming service with 96 million subscribers and 170 million users overall,
and from YouTube, one of the most popular online video-sharing platforms. The
first part of the work has a purely predictive character and makes extensive use of
machine learning, to solve classification and regression problems. In particular, we
detect the features which are the most informative for characterizing the Spotify
Popularity, an integer number in a range between 0 and 100 indicating the success
of the track inside the streaming-platform. Also, given a track and its related
video on YouTube, we build a neural network for inferring the number of views
at a given day taking into account all the information available from Spotify. As
last, the converse analysis is performed, i.e. the Spotify popularity is predicted
taking as input some of the YouTube statistics. Although machine learning models
achieve good performances, the brutal use of these algorithms does not allow to go
beyond the mere prediction. In the second part of the work, we then investigate the
interconnections present between the different time-series composing the data-set.
Thus, we quantify the amount of information transferred from the YouTube views
time-series to the Spotify popularity time-series, and viceversa. The final result
is a directed graph showing the flows of information between all the time-series
analyzed. The main achievements, as well as the drawbacks of the models adopted
are discussed.


