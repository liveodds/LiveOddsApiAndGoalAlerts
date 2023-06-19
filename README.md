## Welcome to Live Odds / Stats Api And Goal Alerts



###  You can use our api in order to get live score and odds. Live stats from live games, inluding cards, corners, attacks, dangerous attacks!
### **** NEW Prediction api ###

You can now user our api to get inplay predictions!



###### INSTANT GOAL ALERTS API
Subscribe to this api to get instant goal alerts!


###  Free access for 5 days!

Contact me via using [e-mail](mailto:liveodds2@gmail.com) or in [Telegram](https://t.me/LiveOddsAndAlerts "Telegram") for prices and packages

# Goal alert api
 http request that produces text/event-stream
 ```
 	curl -H "Authorization: Bearer your key here " http://ip:port/api/stats/data

```

Sample response

```
event:Goal
data:[{"home":"homeTeam1","away":"awayTeam1","homeScore":1,"awayScore":0}]

event:Goal
data:[{"home":"homeTeam2","away":"awayTeam2","homeScore":1,"awayScore":1}]
```
# Sample live stats response
```
[
  {
    "league": "Vietnam Women Championship",
    "minute": 90,
    "totalShots": 22,
    "totalGoals": 6,
    "home": "Son La Women",
    "away": "Ha Noi Women",
    "homeAttacks": 60,
    "awayAttacks": 101,
    "homeDangerousAttacks": 28,
    "awayDangerousAttacks": 106,
    "homePossession": 29,
    "awayPossession": 71,
    "homeYellows": 1,
    "awayYellows": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 0,
    "awayCorners": 5,
    "homeScore": 1,
    "awayScore": 5,
    "homeShots": 4,
    "awayShots": 18,
    "homeShotsOnTarget": 2,
    "awayShotsOnTarget": 12,
    "totalShotsOnTarget": 14,
    "totalShotsOffTarget": 8
  },
  {
    "league": "Jordan Division 1",
    "minute": 63,
    "totalShots": 18,
    "totalGoals": 4,
    "home": "Al-Arabi Irbid",
    "away": "Al Yarmouk",
    "homeAttacks": 101,
    "awayAttacks": 83,
    "homeDangerousAttacks": 48,
    "awayDangerousAttacks": 23,
    "homePossession": 57,
    "awayPossession": 43,
    "homeYellows": 1,
    "awayYellows": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 2,
    "awayCorners": 1,
    "homeScore": 2,
    "awayScore": 2,
    "homeShots": 12,
    "awayShots": 6,
    "homeShotsOnTarget": 5,
    "awayShotsOnTarget": 2,
    "totalShotsOnTarget": 7,
    "totalShotsOffTarget": 11
  },
  {
    "league": "North Macedonia First League",
    "minute": 68,
    "totalShots": 11,
    "totalGoals": 0,
    "home": "KF Shkupi Skopje",
    "away": "Vardar Skopje",
    "homeAttacks": 110,
    "awayAttacks": 78,
    "homeDangerousAttacks": 43,
    "awayDangerousAttacks": 33,
    "homePossession": 60,
    "awayPossession": 40,
    "homeYellows": 2,
    "awayYellows": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 5,
    "awayCorners": 4,
    "homeScore": 0,
    "awayScore": 0,
    "homeShots": 4,
    "awayShots": 7,
    "homeShotsOnTarget": 0,
    "awayShotsOnTarget": 2,
    "totalShotsOnTarget": 2,
    "totalShotsOffTarget": 9
  },
  {
    "league": "North Macedonia First League",
    "minute": 67,
    "totalShots": 19,
    "totalGoals": 2,
    "home": "Shkendija Tetovo",
    "away": "Belasica Strumica",
    "homeAttacks": 114,
    "awayAttacks": 68,
    "homeDangerousAttacks": 80,
    "awayDangerousAttacks": 25,
    "homePossession": 65,
    "awayPossession": 35,
    "homeYellows": 1,
    "awayYellows": 3,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 3,
    "awayCorners": 1,
    "homeScore": 2,
    "awayScore": 0,
    "homeShots": 12,
    "awayShots": 7,
    "homeShotsOnTarget": 4,
    "awayShotsOnTarget": 0,
    "totalShotsOnTarget": 4,
    "totalShotsOffTarget": 15
  },
  {
    "league": "Croatia 2.HNL",
    "minute": 68,
    "totalShots": 6,
    "totalGoals": 0,
    "home": "Bijelo Brdo",
    "away": "NK Dugopolje",
    "homeAttacks": 97,
    "awayAttacks": 96,
    "homeDangerousAttacks": 37,
    "awayDangerousAttacks": 40,
    "homePossession": 51,
    "awayPossession": 49,
    "homeYellows": 1,
    "awayYellows": 2,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 2,
    "awayCorners": 0,
    "homeScore": 0,
    "awayScore": 0,
    "homeShots": 2,
    "awayShots": 4,
    "homeShotsOnTarget": 0,
    "awayShotsOnTarget": 1,
    "totalShotsOnTarget": 1,
    "totalShotsOffTarget": 5
  },
  {
    "league": "Jordan Division 1",
    "minute": 61,
    "totalShots": 18,
    "totalGoals": 1,
    "home": "Blama",
    "away": "Al Karmel",
    "homeAttacks": 81,
    "awayAttacks": 77,
    "homeDangerousAttacks": 60,
    "awayDangerousAttacks": 25,
    "homePossession": 61,
    "awayPossession": 39,
    "homeYellows": 1,
    "awayYellows": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 5,
    "awayCorners": 4,
    "homeScore": 1,
    "awayScore": 0,
    "homeShots": 14,
    "awayShots": 4,
    "homeShotsOnTarget": 4,
    "awayShotsOnTarget": 1,
    "totalShotsOnTarget": 5,
    "totalShotsOffTarget": 13
  },
  {
    "league": "Zambia Super League",
    "minute": 21,
    "totalShots": 2,
    "totalGoals": 0,
    "home": "Red Arrows FC",
    "away": "Zesco United",
    "homeAttacks": 36,
    "awayAttacks": 21,
    "homeDangerousAttacks": 17,
    "awayDangerousAttacks": 15,
    "homePossession": 73,
    "awayPossession": 27,
    "homeYellows": 0,
    "awayYellows": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 0,
    "awayCorners": 1,
    "homeScore": 0,
    "awayScore": 0,
    "homeShots": 0,
    "awayShots": 2,
    "homeShotsOnTarget": 0,
    "awayShotsOnTarget": 1,
    "totalShotsOnTarget": 1,
    "totalShotsOffTarget": 1
  },
  {
    "league": "Uruguay Segunda B Nacional",
    "minute": 19,
    "totalShots": 3,
    "totalGoals": 0,
    "home": "La Luz",
    "away": "Uruguay Montevideo",
    "homeAttacks": 22,
    "awayAttacks": 23,
    "homeDangerousAttacks": 6,
    "awayDangerousAttacks": 7,
    "homePossession": 55,
    "awayPossession": 45,
    "homeYellows": 1,
    "awayYellows": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 0,
    "awayCorners": 0,
    "homeScore": 0,
    "awayScore": 0,
    "homeShots": 1,
    "awayShots": 2,
    "homeShotsOnTarget": 0,
    "awayShotsOnTarget": 0,
    "totalShotsOnTarget": 0,
    "totalShotsOffTarget": 3
  },
  {
    "league": "Chile Apertura/Clausura",
    "minute": 0,
    "totalShots": 0,
    "totalGoals": 0,
    "home": "Palestino",
    "away": "Union La Calera",
    "homeAttacks": 0,
    "awayAttacks": 0,
    "homeDangerousAttacks": 0,
    "awayDangerousAttacks": 0,
    "homePossession": 50,
    "awayPossession": 50,
    "homeYellows": 0,
    "awayYellows": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 0,
    "awayCorners": 0,
    "homeScore": 0,
    "awayScore": 0,
    "homeShots": 0,
    "awayShots": 0,
    "homeShotsOnTarget": 0,
    "awayShotsOnTarget": 0,
    "totalShotsOnTarget": 0,
    "totalShotsOffTarget": 0
  },
  {
    "league": "Italy Serie D",
    "homeScore": 0,
    "awayScore": 0,
    "minute": 0,
    "totalShots": 0,
    "totalGoals": 0,
    "homeShots": 0,
    "awayShots": 0,
    "home": "Trento",
    "away": "Union Feltre Asd",
    "homeAttacks": 0,
    "awayAttacks": 0,
    "homeDangerousAttacks": 0,
    "awayDangerousAttacks": 0,
    "homePossession": 0,
    "awayPossession": 0,
    "homeYellows": 0,
    "awayYellows": 0,
    "homeShotsOnTarget": 0,
    "awayShotsOnTarget": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 0,
    "awayCorners": 0,
    "totalShotsOnTarget": 0,
    "totalShotsOffTarget": 0
  },
  {
    "league": "Italy Serie D",
    "homeScore": 0,
    "awayScore": 0,
    "minute": 0,
    "totalShots": 0,
    "totalGoals": 0,
    "homeShots": 0,
    "awayShots": 0,
    "home": "Chieri 1955",
    "away": "ASDC Gozzano",
    "homeAttacks": 0,
    "awayAttacks": 0,
    "homeDangerousAttacks": 0,
    "awayDangerousAttacks": 0,
    "homePossession": 0,
    "awayPossession": 0,
    "homeYellows": 0,
    "awayYellows": 0,
    "homeShotsOnTarget": 0,
    "awayShotsOnTarget": 0,
    "homeRedCards": 0,
    "awayRedCards": 0,
    "homeCorners": 0,
    "awayCorners": 0,
    "totalShotsOnTarget": 0,
    "totalShotsOffTarget": 0
  }
]
```

# Sample json odds response

    [
      {
        "home": "XXXX",
        "away": "YYYY",
        "homeScore": 4,
        "awayScore": 0,
        "bets": [
          {
            "betType": "Over 4.5",
            "firstHalf": false,
            "odds": 2.25,
            "betDescription": ""
          },
          {
            "betType": "Over 5.5",
            "firstHalf": false,
            "odds": 7.45,
            "betDescription": ""
          },
          {
            "betType": "Over 5.5",
            "odds": 8.5,
            "firstHalf": false,
            "betDescription": "Home team to score second half"
          },
          {
            "betType": "Over 6.5",
            "odds": 46,
            "firstHalf": false,
            "betDescription": "Home team to score second half"
          },
          {
            "betType": "Over 0.5",
            "odds": 15.5,
            "firstHalf": false,
            "betDescription": "Away team to score second half"
          }
        ]
      }
    ]

