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

<h2>Libraries used</h2>
<div>
<img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="Numpy" **alt="Numpy" width="180" height="180"/>
<img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original-wordmark.svg" title="Pandas" **alt="Pandas" width="180" height="180"/>
<img src="https://github.com/RamonFCerezo/EDA-Possession-in-football/blob/main/img/matplotlib.svg" title="Pandas" **alt="Pandas" width="220" height="180"/>
<img src="https://github.com/RamonFCerezo/EDA-Possession-in-football/blob/main/img/Seaborn.svg" title="Pandas" **alt="Pandas" width="180" height="180"/>
</div>

<h2>Sources</h2> 
<a href="https://instatsport.com/">Instat Website</a>
