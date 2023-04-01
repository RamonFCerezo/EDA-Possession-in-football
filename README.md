<h1>Exploratory Data Analysis (EDA)</h1>
<div id="header" align="center">
  <img src="https://github.com/RamonFCerezo/EDA-Possession-in-football/blob/main/img/Ball%20Possession.png" width="800"/>
</div>

After the glorious years for FC Barcelona and the Spanish National Team, whose style was based on controlling the ball possession, rivals learnt to defend themselves against it. And now, it is difficult to define if ball possession is a relevant factor to win matches or not.

To study that, three hypothesis are set:
  <ol>
    <li><strong>Main hypothesis:</strong> Is possession crucial when it comes to winning games?</li>
    <li><strong>Complementary hypothesis 1:</strong> Is the relationship between possession and victories the same in league games as in knockout games? What about in finals?</li>
    <li><strong>Complementary hypothesis 2:</strong> Is having the ball considered an offensive resource?</li>
  </ol>
  
<h2>Project Structure</h2>

```
img/
├── Ball Possession.png
src/
├── data/
│ ├── LaLiga/
│ ├── Bundesliga/
│ ├── Premier League/
│ ├── Serie A/
│ ├── Ligue 1/
│ ├── World Cup/
│ ├── Euro Cup/
│ ├── Champions League/
│ ├── Europa League/
│ ├── Conference League/
│ ├── Leagues (merged)/
│ ├── Play-Offs/
│ └── All/
├── notebooks/
│ ├── Final_insights.ipynb
│ ├── Insights.ipynb
│ ├── data_clean.ipynb
│ └── data_clean2.ipynb
├── utils/
| ├── Presentation Spanish.pptx
└──  memoria.ipynb 
readme.md
```

<h2>Process</h2>
<p>This project began with the task of finding appropriate data to study, which required extensive research to obtain. The second step was to clean the data until it became useful for generating insightful information that helped us answer our hypotheses. However, there were challenges, such as dealing with a large dataset that spanned over 30 files, identifying and removing duplicate entries, and converting data to the proper format. Once the data was cleaned, I began creating visualizations and graphs to make the complex data easier to understand for any audience. All these steps can be viewed in the "<a href="https://github.com/RamonFCerezo/EDA-Possession-in-football/blob/main/src/Memoria.ipynb">memoria.ipynb</a>" file. Finally, I created the presentation and delivered it in January 2023.</p>

<h2>Libraries used</h2>
<div>
<img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="Numpy" **alt="Numpy" width="180" height="180"/>
<img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original-wordmark.svg" title="Pandas" **alt="Pandas" width="180" height="180"/>
<img src="https://github.com/RamonFCerezo/EDA-Possession-in-football/blob/main/img/matplotlib.svg" title="Pandas" **alt="Pandas" width="220" height="180"/>
<img src="https://github.com/RamonFCerezo/EDA-Possession-in-football/blob/main/img/Seaborn.svg" title="Pandas" **alt="Pandas" width="180" height="180"/>
</div>

<h2>Sources</h2> 
<a href="https://instatsport.com/">Instat</a>

<br></br>
<p>I hope this EDA has been of interest to you. Feel free to share it, ask me any doubt or work on it!</p>
