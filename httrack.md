# 介紹
```
HTTrack是一個自由、開源的網路爬蟲以及離線瀏覽器。

使用者可以通過HTTrack把網際網路上的網站頁面下載到本地電腦上。
在預設設定下，HTTrack對網站頁面的下載結果是按照原始站點相對連結的結構來組織的。
用網頁瀏覽器開啟這個被下載下來的網站（也稱作鏡像）的頁面，就可以離線瀏覽了。

HTTrack也能對已經鏡像過的站點進行更新。或者是對中斷了的工作斷點續傳。
可以通過選項和過濾器（include/exclude）組態HTTrack的方方面面。
它還整合有幫助系統。它有一個基本的命令行版本和兩個GUI（為Windows設計的WinHTTrack和為Unix-like系統設計的WebHTTrack）；
命令行版本可以和Shell指令碼（Shell script）以及cron聯用。

HTTrack使用網路爬蟲下載網站。對於有robots.txt的網站，
如果不在程式執行時取消限制，預設設定下的程式不會把網站完全鏡像。
HTTrack能跟隨基本的JavaScript，或者Applet、Flash中的連結，

對於複雜的連結（使用函式和表達式建立的連結）、伺服器端的Image Map（Image Map）則無能為力。

```
# 安裝與使用
```
在許多Unix-like系統下，只需要用包管理工具安裝httrack即可。例如Debian使用
sudo aptitude install httrack

一個使用例子：
httrack "http://www.all.net/" -O "/tmp/www.all.net" "+*.all.net/*" -v

它的意思是：以http://www.all.net/ 为起始URL，输出到/tmp/www.all.net文件夹，范围是www.all.net域名下的所有文件，并显示所有错误信息（verbose）。更詳細的資訊請看官網上的Users Guide[3]。

https://www.youtube.com/watch?v=EygeNcS0RRU  影片教學
```
