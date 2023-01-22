<h1 align="center">
  <a href='https://radar.game/#/games'>Radar Game</a> api
  <br>
</h1>


## Endpoint
`https://meping.ir/api`


## Games list
### Games etails list
**Method:** `GET` </br>
**URL:** ```/games?page=1```
#### output examples:
```json
{"current_page":1,"data":[{"id":204,"name":"Fifa mobile","banner":"\/pictures\/Fifa-mobile\/banner.jpg","ip":null,"age_suffering":3,"score_count":4,"display_status":0,"category":[{"category":"Sports"}],"score":"3.9","score_status":true,"region":"Foreign"},{"id":206,"name":"CSGO","banner":"\/pictures\/Counter-Strike\/banner.jpg","ip":null,"age_suffering":14,"score_count":5,"display_status":0,"category":[{"category":"Shooter"}],"score":"3.6","score_status":true,"region":"Foreign"},{"id":207,"name":"Among Us","banner":"\/pictures\/Among-Us\/banner.jpg","ip":null,"age_suffering":10,"score_count":5,"display_status":0,"category":[{"category":"Survival"}],"score":"3.6","score_status":true,"region":"Foreign"},{"id":298,"name":"Quiz of Kings","banner":"\/pictures\/Quiz-of-Kings\/banner.jpg","ip":null,"age_suffering":4,"score_count":5,"display_status":0,"category":[{"category":"Puzzler"}],"score":"3.3","score_status":true,"region":"IR"},{"id":65,"name":"FIFA 23","banner":"\/pictures\/Fifa\/banner.jpg","ip":null,"age_suffering":3,"score_count":5,"display_status":0,"category":[{"category":"Sports"}],"score":"3.1","score_status":true,"region":"Foreign"},{"id":66,"name":"eFootball Series","banner":"\/pictures\/eFootball-Series\/banner.jpg","ip":null,"age_suffering":3,"score_count":5,"display_status":0,"category":[{"category":"Sports"}],"score":"3.9","score_status":true,"region":"Foreign"},{"id":85,"name":"Rainbow Six","banner":"\/pictures\/Rainbow-Six-Series\/banner.jpg","ip":null,"age_suffering":12,"score_count":5,"display_status":0,"category":[{"category":"Shooter"}],"score":"3.7","score_status":true,"region":"Foreign"},{"id":370,"name":"Dota2","banner":"\/pictures\/Dota2\/banner.jpg","ip":null,"age_suffering":16,"score_count":1,"display_status":0,"category":[],"score":"3.9","score_status":true,"region":"Foreign"}],"first_page_url":"http:\/\/meping.ir\/api\/games?page=1","from":1,"last_page":17,"last_page_url":"http:\/\/meping.ir\/api\/games?page=17","links":[{"url":null,"label":"« Previous","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=1","label":"1","active":true},{"url":"http:\/\/meping.ir\/api\/games?page=2","label":"2","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=3","label":"3","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=4","label":"4","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=5","label":"5","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=6","label":"6","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=7","label":"7","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=8","label":"8","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=9","label":"9","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=10","label":"10","active":false},{"url":null,"label":"...","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=16","label":"16","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=17","label":"17","active":false},{"url":"http:\/\/meping.ir\/api\/games?page=2","label":"Next »","active":false}],"next_page_url":"http:\/\/meping.ir\/api\/games?page=2","path":"http:\/\/meping.ir\/api\/games","per_page":8,"prev_page_url":null,"to":8,"total":134}
```


### Game detail
**Method:** `GET` </br>
**URL:** ```/games/{game:int=248}```
#### output examples:
```json
[{"id":248,"name":"Minecraft","banner":"\/pictures\/Minecraft\/banner.jpg","description":null,"ip":null,"status":0,"sort":0,"support_level":"true","age_suffering":10,"score_count":5,"display_status":0,"created_at":"2022-12-20T18:48:37.000000Z","updated_at":"2023-01-01T17:51:31.000000Z","deleted_at":null,"category":[{"category":"Role-playing"},{"category":"Sandbox"}],"score":"4.7","score_status":true,"region":"IR"}]
```
### Games categories
**Method:** `GET` </br>
**URL:** ```/categories```

## isp 
### your isp
**Method:** `GET` </br>
**URL:** ```/operator```
#### output examples:
```json
[{"operator":"TCI"}]
```
### All available isp list
**Method:** `GET` </br>
**URL:** ```/operators```
#### output examples:
```json
[{"id":1,"name":"\u0627\u06cc\u0631\u0627\u0646\u0633\u0644","value":"IranCell-AS","color":"#FFCE00","updated_at":"2022-12-19T08:58:41.000000Z"},{"id":2,"name":"\u0647\u0645\u0631\u0627\u0647 \u0627\u0648\u0644","value":"MCCI","color":"#54C5D0","updated_at":"2022-12-19T08:58:41.000000Z"},{"id":3,"name":"\u0631\u0627\u06cc\u062a\u0644","value":"RighTel","color":"#992B6B","updated_at":"2022-12-19T08:58:41.000000Z"},{"id":4,"name":"\u0645\u062e\u0627\u0628\u0631\u0627\u062a","value":"TCI","color":"#FF003D","updated_at":"2022-12-19T08:58:41.000000Z"},{"id":5,"name":"\u0634\u0627\u062a\u0644","value":"Shatel","color":"#002A63","updated_at":"2022-12-19T08:58:41.000000Z"},{"id":6,"name":"\u0622\u0633\u064a\u0627\u062a\u06a9","value":"Asiatach","color":"#808082","updated_at":null},{"id":7,"name":"\u067e\u064a\u0634\u06af\u0627\u0645\u0627\u0646","value":"Pishgaman","color":"#006836","updated_at":null},{"id":8,"name":"\u067e\u0627\u0631\u0633 \u0622\u0646\u0644\u0627\u064a\u0646","value":"ParsOnline","color":"#F2EFEF","updated_at":null},{"id":9,"name":"\u0641\u0646 \u0622\u0648\u0627","value":"FanAva","color":"#a58dda","updated_at":null},{"id":10,"name":"\u0647\u0627\u06cc \u0648\u0628","value":"HiWeb","color":"#ef50bd","updated_at":null},{"id":11,"name":"\u062f\u0627\u062a\u06a9","value":"Datech","color":"#ED8232","updated_at":null},{"id":12,"name":"\u0632\u064a\u062a\u0644","value":"Zitel","color":"#02EF9E","updated_at":null}]
```
## Ping resault
### Game server detail
**Method:** `GET` </br>
**URL:** ```/game-server/{game:int=248}```
#### output examples:
```json
[[{"id":307,"game_id":248,"server_id":"EU","ip":"185.116.156.173","created_at":"2022-12-20T21:15:52.000000Z","updated_at":"2022-12-20T21:15:52.000000Z","deleted_at":null}]]
```
### Game server ping resaults
**Method:** ```GET``` </br>
**URL:** ```/{date:str}-{type:str}/{isp:str}/{game:int=248}```

```python
isp = ['IranCell-AS',
'TCI',
'Pishgaman',
'HiWeb',
'Datech',
'ParsOnline',
'Shatel',
'MCCI',
'RighTel',
'Asiatach',
'FanAva',
'Zitel']

type = ['chart',
'packet',
'content']

date = ['minute',
'hours',
'day',
'week',
'month']
```
## Resault
### Your ping in game resault
**Method:** `GET` </br>
**URL:** ```/result-ping/{resault:int}```

## License
`radar_game_api` is collected with 💚 by the [alyrezo](https://twitter.com/alyrezo)
