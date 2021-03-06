<p align="center">
  <a href="http://datascience.disco.unimib.it/it/"><img src = "https://github.com/malborroni/Foundations_of_Computer-Science/blob/master/images/DSunimib.png" width = "100%"></a>
</p>
<br>
<h1 align="center">
  <br>
  Foundations of Computer Science (FoCS) - Project
  <br>
</h1>

<p align="center">
  <a href="#overview">Overview &nbsp;</a> |
  <a href="#instructions">&nbsp; Instructions &nbsp;</a> |
  <a href="#datasets">&nbsp; Datasets &nbsp;</a> |
  <a href="#conclusion">&nbsp; Conclusion &nbsp;</a> |
  <a href="#aboutme">&nbsp; About me &nbsp;</a>
</p>

<br>

<a name="overview"></a>
## &#9741; &nbsp; Overview

Here you can find my solution to a project carried out to complete the examination of a class of the Master's Degree Course in Data Science that I am attending at University of Milano-Bicocca. <br>
The project consists in the resolution of a certain number of exercises that vary according to the number of the workteam, having two datasets available (that can be found in the "Datasets" section). <br>
In my case, I approached the project individually, so I only had to resolve the first 12 exercises. <br>
The various exercises require the correct use of Python, the famous programming language, with all the libraries we decided to use, among which we must mention *numpy* and *pandas*, saw during the lectures of the course. <br>
The main purpose of this project is to manipulate the aforementioned datasets and to extract from the data the most varied informations regarding the **Google Play Store** and its applications.


<a name="instructions"></a>
## &#9741; &nbsp; Instructions

Starting from the *Google Play Store dataset*, all groups and individuals must do the following:



| References  | To do list                                                                     | Team size    | Status      |
|:------------|:-------------------------------------------------------------------------------|:------------:|:-----------:|
| Exercise 1  | _Convert the app sizes to a number_                                            | 1            | &#10004;    |
| Exercise 2  | _Convert the number of installs to a number_                                   | 1            | &#10004;    |
| Exercise 3  | _Transform “Varies with device” into a missing value_                          | 1            | &#10004;    |
| Exercise 4  | _Convert Current Ver and Android Ver into a dotted number (e.g. 4.0.3 or 4.2)_ | 1            | &#10004;    |
| Exercise 5  | _Remove the duplicates_                                                        | 1            | &#10004;    |
| Exercise 6  | _For each category, compute the number of apps_                                | 1            | &#10004;    |
| Exercise 7  | _For each category, compute the average rating_                                | 1            | &#10004;    |
| Exercise 8  | _Create two dataframes: one for the genres and one bridging apps and genres. So that, for instance, the app Pixel Draw - Number Art Coloring Book appears twice in the bridging table, once for Art & Design, once for Creativity_      | 1            | &#10004;    |
| Exercise 9  | _For each genre, create a new column of the original dataframe. The new columns must have boolean values (True if the app has a given genre)_                                                                 | 1            | &#10004;    |
| Exercise 10 | _For each genre, compute the average rating. What is the genre with highest average?_                       | 1            | &#10004;    |
| Exercise 11 | _For each app, compute the approximate income, obtain as a product of number of installs and price_         | 1            | &#10004;    |
| Exercise 12 |  _For each app, compute its minimum and maximum Sentiment_polarity_             | 1           | &#10004;    |
|             |                                                                                 |             |             |
| Exercise 1  | _For each app, compute the average number of words in its reviews_              | 2           | &#10006;    |
| Exercise 2  | _For each app, compute its longest review_                                      | 2           | &#10006;    |
| Exercise 3  | _For each app, compute the ratio between the number of installs and the number of reviews_                  | 2            | &#10006;    |
| Exercise 4  | _Cluster the apps according to the major android version (the first two digits — e.g. for 4.0.3 the major version is 4.0)_                                                                                | 2           | &#10006;    |
| Exercise 5  | _For each cluster, compute the average date and the last date of an update._    | 2           | &#10006;    |
| Exercise 6  | _Excluding the free apps, what is the content rating with highest average price?_                           | 2   | &#10006;    |
|             |                                                                                 |             |             |
| Exercise 1  | _What is the genre with the highest total income?_                              | 3           | &#10006;    |
| Exercise 2  | _What is the genre with the highest fraction of free apps (over the number of all apps)?_                   | 3   | &#10006;    |
| Exercise 3  | _For each rating, compute the average income_                                   | 3           | &#10006;    |
| Exercise 4  | _For each (Content Rating, Genre) pair, compute the number of reviews and the average rating_               | 3   | &#10006;    | 

### **Notes**

1. It is mandatory to use [GitHub](https://github.com) for developing the project;
2. The project must be a jupyter notebook;
3. There is no restriction on the libraries that can be used, nor on the Python version;
4. Post any question on the [Discussions](https://elearning.unimib.it/mod/forum/view.php?id=238437) forum.

<a name="datasets"></a>
## &#9741; &nbsp; Datasets

Here you can find the Google Play Store datasets used for the project. <br>
Note that clicking on the link will redirect you to the raw format of the datasets, from which you can download the CSV files you need.

&nbsp;&nbsp;&nbsp; &#9667; &nbsp; [Google Play Store](https://raw.githubusercontent.com/malborroni/Foundations_of_Computer-Science/master/datasets/googleplaystore.csv)

&nbsp;&nbsp;&nbsp; &#9667; &nbsp; [Google Play Store: User reviews](https://raw.githubusercontent.com/malborroni/Foundations_of_Computer-Science/master/datasets/googleplaystore_user_reviews.csv)

Too see an example of what you can find on Google Play, click on the image below.

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=it.easystaff.unimib"><img src = "https://github.com/malborroni/Foundations_of_Computer-Science/blob/master/images/GPS.png" width = "35%"></a>
</p>


<a name="conclusion"></a>
## &#9741; &nbsp; Conclusion

There wasn't a specific goal to reach with this project, so I have not so much to tell as a conclusion. <br>
But surely it is important to say that this course, with this method of examination, gave me the opportunity to become familiar with a language that was new to me and that certainly has an important role in the idea of work that awaits me in the future.
Furthermore, extracting information from the datasets always offers the opportunity to reveal some hidden trends in the data, which is important to get a more precise and clear idea about the field of interest, with which you may not be totally confident.

<a name="aboutme"></a>
## &#9741; &nbsp; About me

Hi everybody, my name is Alessandro Borroni and I am a _Data Science_ student based in Milan, as the picture up there had already told you. <br>
I have a kind of great passion for _Photography_ and _Mathematics_. <br>
My previous goal consists in a degree in Business Economics, obtained at University of Milan-Bicocca. Thanks to this degree I developed, inter alia, an interest in _Statistics_ and _Finance_. <br>
<br>
Down here you can find some of my Social Media channels, check them out if you want!

## &nbsp;
<br>

<p align = "center">
  <a href = "https://www.linkedin.com/in/alessandro-borroni-212947186/"><img src="https://github.com/malborroni/Foundations_of_Computer-Science/blob/master/images/Linkedin%20logo.png" width = "2%"></a>
  <a href = "https://www.instagram.com/aleborroni/"><img src="https://github.com/malborroni/Foundations_of_Computer-Science/blob/master/images/174855.svg" width = "2%"></a>
  <a href = "https://www.kaggle.com/alessandroborroni/"><img src="https://github.com/malborroni/Foundations_of_Computer-Science/blob/master/images/thumbnail.png" width = "2%"></a>
  <a href = "https://github.com/malborroni/"><img src="https://github.com/malborroni/Foundations_of_Computer-Science/blob/master/images/GitHub.png" width = "2%"></a>
  <a href = "https://www.twitter.com/malborroni/"><img src="https://github.com/malborroni/Foundations_of_Computer-Science/blob/master/images/Twitter_bird_logo.png" width = "2%"></a>
  <a href = "https://www.facebook.com/alessandro.borroni.777"><img src="https://github.com/malborroni/Foundations_of_Computer-Science/blob/master/images/174848.svg" width = "2%"></a>
</p>
