﻿
# Map Mate
Description of [English Version is Here](#description-of-english-version).
### 1.これは何？
マップ表示を色々便利にしてくれます。  
(現在はミニマップに追加情報を表示するだけ)  
![改良されたミニマップ表示](https://github.com/Toukibi/ToSAddon/blob/ForImage/MapMate/image/MapMate_MiniMap.png?raw=true)
### 2.できること
* ミニマップに次の項目を追加表示します  
  * マップ名
  * ランク(星の数)
  * 推奨レベル
  * 探索率
  * 接続人数(要、右クリックメニューで設定)
* ミニマップのボタンや表示を小さくして情報を見やすくしています
* そのマップのデスペナ情報を表示(マップ名のツールチップに表示)

### 3.追加された右クリックメニューの一覧
1. 接続人数の自動更新に関するメニュー  
    次の場所を右クリックすると表示されます
    * マップ名
    * 接続人数表示部
    * 次回更新のカウントダウン表示

### 4.使用可能なコマンド一覧
基本のコマンドは **`/mapmate`** または **`/mmate`** です  

|コマンド|効果|
|---|---|
|/mmate reset|設定リセット|
|/mmate update|表示を更新|
|/mmate jp|日本語に切り替え|
|/mmate en|英語に切り替え|
|/mmate xx|xx に英語2文字を入れる<br>その言語に切り替え|
|/mmate ?|チャットログにヘルプを表示|

**英語と日本語以外を使うには**：  
他の言語モードを使えるようにするには、該当する言語のテキストリソースをプログラムソースに追記する必要があります。

### 5.導入方法
このアドオンは、アドオンマネージャJPに登録しています。  
アドオンマネージャJPを用いて導入してください  

---
## Description of English Version 
  
**Notice**: This add-on has **English display mode**.  
You can switch to English display mode by using command **`/mmate en`**  
### 1. What is this?
This add-on makes map display a lot convenient.  
(Currently it only displays additional information in the mini map)  
![Image of customized minimap view](https://github.com/Toukibi/ToSAddon/blob/ForImage/MapMate/image/MapMate_EnMiniMap.jpg?raw=true)
### 2.What can this be?
* Add the following items to the mini map.
  * Map name
  * The rank of current map. (Number of star marks)
  * Recommended level
  * Search progress
  * Number of connected people (required, set with right click menu)
* Reduces the mini-map buttons and displays to make information easier to see.
* Display Death-penalty-information of the map. (displayed on tooltip of map name)

### 3. List of additional right-click menu
1. Settings for automatic updates of connected persons  
    You can see it by right clicking on the following place.
    * Display area of the map name
    * Display area of the connected persons count
    * Display area of the next update countdown time

### 4. List of Command paramaters
Please call the following command. **`/mapmate`** or **`/mmate`**  

|Paramater|What happens result|
|---|---|
|/mmate reset|Reset the all settings.|
|/mmate update|The additional information displayed will be updated.|
|/mmate jp|Switch to Japanese mode.|
|/mmate en|Switch to English mode.|
|/mmate xx|Insert two English letters in xx<br>(ccTLD or language code recommended)<br>Switch to Other Language mode.|
|/mmate ?|Display the help-text to chat-log.|

<span style="color:red;">**In order to use language other than English and Japanese**</span>:  
In order to use **Other Language** mode, you need to **add a text resource to the program source**.

### 5. How to install？
This add-on is registered in Add-on Manager JP.  
Therefore, please install using the Add-on Manager JP.