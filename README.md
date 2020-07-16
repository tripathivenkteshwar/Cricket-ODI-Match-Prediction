# Cricket-ODI-Match-Prediction
<br>
Predict the winner of ODI- Match
<br>
Winning is the goal of any sport. Cricket is one the most watched sport now a days. Winning in Cricket depends on various factors like home ground advantage, performances in the past, experience in the match, performance at the specific venue, performance against the specific team and the current form of the team and the player.
Methods to model batsmen, bowlers and teams, using various career statistics and recent performances of the players.
<br>

### Dependence required:

* [BeautifulSoup](https://pypi.org/project/beautifulsoup4/)
* [Pandas](https://pypi.org/project/pandas/)
* [Requests](https://pypi.org/project/requests/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [scikit-learn](https://scikit-learn.org/stable/)

### Data scraped from:

* [Wikipedia  (List of One Day International cricket grounds)](https://en.wikipedia.org/wiki/List_of_One_Day_International_cricket_grounds)

* [ESPNcricinfo](https://stats.espncricinfo.com/ci/engine/stats/index.html?ballsmax1=300;ballsval1=balls;class=2;filter=advanced;floodlit=1;floodlit=2;home_or_away=1;home_or_away=2;home_or_away=3;innings_number=1;innings_number=2;opposition=1;opposition=2;opposition=25;opposition=3;opposition=4;opposition=5;opposition=6;opposition=7;opposition=8;orderby=start;page="+str(i)+";result=1;spanmax2=31+Dec+2011;spanmin2=01+Jan+2011;spanval2=span;team=1;team=2;team=25;team=3;team=4;team=5;team=6;team=7;team=8;template=results;type=team;view=results)

### Data info

Model is restricted to only top 9 ODI-playing teams, namely, Australia, South Africa, India, England, Sri Lanka, Pakistan, New Zealand, Bangladesh and West Indies.

The dataset includes matches played between 2008 and 2020. Matches played between 2008 and 2011 are considered for players base strength.
The training dataset contains all the matches played during the years 2011 to 2018, the test dataset contains all the matches played in the year 2018-2020. 
There are a total of 527 matches in training dataset and 166 matches in test dataset.

<h3>Player Features and their Notations</h3>
<img src="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/img/notations.JPG")
<br>
Reference:
<a href="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/Madan_Gopal_Jhanwar.pdf" alt="Research">Link</a>
<br>

<h3>Batsmen Performance</h3>
Batting ability of a player has a signicant contribution in shaping the outcome of a match. First,  examine his career performances to determine his potency as a contender. Second, consider his recent match scores to analyze his prevailing form: where form of a batsman determines his contribution to the team in recent matches, which in turn reflects his condence levels.
<br>

<img src="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/img/batsman.JPG">
Reference:
<a href="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/Madan_Gopal_Jhanwar.pdf" alt="Research">Link</a>
<br>
<h3>Bowlers Performance</h3>
<br>
<img src="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/img/bowlers.JPG">
Reference:
<a href="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/Madan_Gopal_Jhanwar.pdf" alt="Research">Link</a>
<br>
<h3>Team Strength</h3>
<br>
<img src="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/img/team%20strength.JPG">
<br>
Reference:
<a href="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/Madan_Gopal_Jhanwar.pdf" alt="Research">Link</a>
<br>
<h3> Reference</h3>
<a href="https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/Madan_Gopal_Jhanwar.pdf" alt="Research">https://github.com/tripathivenkteshwar/Cricket-ODI-Match-Prediction/blob/master/Madan_Gopal_Jhanwar.pdf</a>
<br>
<a href="https://www.espncricinfo.com/" alt="Data">https://www.espncricinfo.com/</a>
<br>
<a href="https://en.wikipedia.org/wiki/List_of_One_Day_International_cricket_grounds" alt="Ground">https://en.wikipedia.org/wiki/List_of_One_Day_International_cricket_grounds</a>
 <br>
