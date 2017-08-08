### 'api' for football-data-visualization App.    
I generated these JSON files from CSV files by NODE.JS    
Base URL for request: `'https://raw.githubusercontent.com/morsko1/football-data-api/master/api/'`    
### Example   
if you need to request standings data of English Premier League 2016-2017:    
`'https://raw.githubusercontent.com/morsko1/football-data-api/master/api/2016-2017/england/premier-league/standings.json'`   
you will get JSON file with such content:    
```
{
  "id": 1,
  "name": "England Premier League",
  "season": "2016-2017",
  "country": "england",
  "league": "premier-league",
  "standings": [
    {
      "id": 3,
      "name": "Chelsea",
      "games": 38,
      "wins": 30,
      "losses": 5,
      "draws": 3,
      "goalsHome": 55,
      "goalsAway": 30,
      "goalsHomeAllowed": 17,
      "goalsAwayAllowed": 16,
      "pointsHome": 51,
      "pointsAway": 42,
      "winsHome": 17,
      "lossesHome": 2,
      "drawsHome": 0,
      "winsAway": 13,
      "lossesAway": 3,
      "drawsAway": 3,
      "goalsTotal": 85,
      "goalsTotalAllowed": 33,
      "pointsTotal": 93
    },
    {
    ...
    },
    
    ```
