# NLP-based-Movie-Recommendation-Engine

<h5>This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.</h5>

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the 
IMDB id of the movie in the API, Web scraping was done to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews

<h4> Searching the movie </h4>

![image](https://user-images.githubusercontent.com/87670223/164998500-00202d25-122f-421e-a917-934ba88a7ca5.png)


<h4> Getting sentiments on the reviews of the movie </h4>

![image](https://user-images.githubusercontent.com/87670223/164998539-8d6a7007-5700-4527-83f5-35d777c965f4.png)


<h4> Getting the recommendation for similar movies </h4>

![image](https://user-images.githubusercontent.com/87670223/164998567-b1e8088c-91b3-4946-bf9d-ce5253d07e12.png)

<h3>How to run the project?</h3>
1. Clone this repository in your local system.
2. Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt.
3. Replace YOUR_API_KEY in both the places (line no. 23 and 43) of static/recommend.js file.
4. Open your terminal/command prompt from your project directory and run the main.py file by executing the command python main.py.
5. Go to your browser and type http://127.0.0.1:5000/ in the address bar.
6. Hurray! That's it.
