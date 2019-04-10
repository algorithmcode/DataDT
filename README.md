# DataDT
DataDT provides Free API for querying forex historical data, JSON format....

Forex Pairs:AUDCAD,AUDUSD,CADCHF,EURCAD,EURCHF,GBPUSD,NZDUSD,USDCAD,USDCHF,USDJPY,XAGUSD,XAUUSD
Timeframe:1,5,15,30,60,240,day,week,month

Return Data format:
```
{"DATE_TIME":"2018-04-03 00:00:00","OPEN":1.291,"HIGH":1.29234,"LOW":1.2781,"CLOSE":1.2806,"VOLUME":104249}
```

1.Get AUDCAD 5 minutes Historical data from '20190403' to '20190408':
```
http://www.datadt.com/api/data/AUDCAD/5/20190403/20190408?api_token=P155CNi3xSkTO9bctwZOBHglGez4dpmf
```

2.Get USDCAD day Historical data from '20180403' to '20190408':
```
http://www.datadt.com/api/data/USDCAD/day/20180403/20190408?api_token=P155CNi3xSkTO9bctwZOBHglGez4dpmf
```




