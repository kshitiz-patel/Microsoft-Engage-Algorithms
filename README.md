# Microsoft Engage 2022: Algorithms 
## NMovies: A Content-Based Movie Recommender System using Cosine Similarity
### Overview:
**NMovies:** An online movie recommender app based on the concept of **Cosine Similarity**. It basically generates similarity scores based upon those scores movies are suggested to the user. 
Where similarity score is a numerical value ranges between zero to one which helps to determine how much two items are like each other on a scale of zero to one. This similarity score is obtained by measuring the similarity between the text details of both items. So, the similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
All the details of the movies (title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB.

## Important Links:
GitHub Repository URL: https://github.com/kshitiz-patel/Microsoft-Engage-Algorithms <br/>
Website URL: https://nmovies-engage2022.herokuapp.com/<br/>
Video Demo: []<br/>

## Functions & Features:
This is a single page web app made using AJAX request which on loading lands on the index.html where the user will find a search bar inbuit with **manual as well as voice based search** to search his/her favorite movie.
### Recommendation System:

### Auto-Search Complete:
This Auto-search feature is built using JavaScript, which basically takes the input from the user and searches it in a movie array and shows the related items to the user based upon the query entered.

### Voice based Search:
It Uses the **Web Speech API** to perform the Speech to Text function which then gives back the text in the input field as per the voice instruction given by the user. To enable the voice recognition just press the mic button in the search bar and speak out want you want to watch.

### Random Movie Suggestions:
Sometimes users want to watch something but don’t know what to watch. So here is the solution by just pressing the **Surprise Me** button at the top right corner of the navigation bar the user will get a random movie suggestion which is done through a random function.

### Sentiment Analysis of Review:
Initially, the reviews are fetched from IMDb Database using the movie ID, and then using the Naive Bayes Model the reviews are analyzed whether they are positive or negative. For a positive review, it assigns 1 to the review and assigns 0 to a negative review then it’s displayed to the user using JavaScript ate the frontend.

## Architecture of the Web App:
<img src="https://drive.google.com/file/d/1F7S3jb5C3zuWue3nUHpX2y66NLaAVQ3z/vie">

## Technologies Used:
#### Frontend Technologies: <img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/> <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/> <img alt="Bootstrap 5" src="https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white"/> <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img alt="jquery" src="https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white"/>

#### Backend Technologies: <img alt="Python" src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/> <img alt="Flask" src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white"/> 

#### Dataset Provider: <img alt="Kaggle" src="https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white"/> 
#### Version control: <img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/>

#### IDE: <img alt="Visual Studio Code" src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white"/> <img alt="PyCharm" src="https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green"/> 

#### Hosting: <img alt="Heroku" src="https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white"/>
#### API: TMDB

## Installation/Environment Setup:
#### 1. Clone App
  
  * Write the following command and press enter.
  
  ```
    $ git clone 
  ```
  
#### 2. Setting up the files
* To make the app work the following files are also required to be downloaded and pasted in the root directotry. This is because of the large file size.
https://drive.google.com/drive/folders/1VyfED1hUGwxbC46Nc4tGlx54vBYTOl5p?usp=sharing


#### 3. Install Requirements.txt
* Install all the libraries mentioned in the [requirements.txt](https://github.com/kishan0725/Movie-Recommendation-System-with-Sentiment-Analysis/blob/master/requirements.txt)

```
pip install -r requirements.txt
```

#### 4. Run the files locally
* Open your terminal/command prompt from the project directory and run the file `main.py` by executing the following command

```
py main.py
```

#### 5. Open terminal & Run Commands
* Now its done, just Go to your browser and type the following URL in the address bar and you are good to go.

```
http://127.0.0.1:5000/
```

## Scope of Improvements:
