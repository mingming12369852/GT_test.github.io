#GT_test

<h1>開源_零汙染 地標顯示Demo</h1>
<tr>

目前 firebase 上有的資料。<br>

<h4>Database Name</h4>
[x] City_repair_station<br>
[x] Free_store<br>
[x] Not_plastic<br>
[x] No-discovery<br>
[x] Lron_box_lunch<br>
[x] Green_Island_Water_Station<br>
[ ] GoodDay_without_shopping<br>
[ ] Say_no_to_plastics<br>
[ ] Ubag_partner<br>
[ ] Symbiotic_map<br>
[ ] Old_bookstore_map<br>
[ ] Plastic_map<br>
[ ] Zero_abandoned_life<br>

<tr>
<h4>How to Install</h4> <br>

    <script src="https://www.gstatic.com/firebasejs/5.7.0/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/5.7.0/firebase-database.js"></script>
    <script src="js/openPointData.js"></script>
</h4>注意!</h4><br>

Map 預覽請使用 OSM Leaflet，並請ID 命名為"map"<br>
不知道如何安裝?
:https://leafletjs.com/
<tr>
使用方法

```

Hello;測試使否安裝成功

getData(name);//輸入資料庫中對應Name,會為你自動標示在Leaflet地圖中

抓取的第一筆資料會是Array[0];
下方number = 0;
抓取的第二筆資料會是Array[1];
下方number = 1;
...以此類推


Clear(number);//隱藏

Display(number);顯示

範例:
Map_tool.Hello();
>>>"this me"
```


DEMO<br>
https://mingming12369852.github.io/GT_test.github.io/<br>

[配色](https://lh4.googleusercontent.com/lpFisKIsiABK1mwfj3UfmEfdypYfnBEGbCYlsJc3Gy6GOjQqIpN8JiToI2uqizrm2c57UmtUviyWzm-eR9Tlrc1nsHlMZa4njO9XcyXx)<br>
輔色:#E26D5A  <br>
主色:#BDC667 <br>
底色:#F3E9DC <br>
標題:#23E37<br>
內文:#43291F<br>
