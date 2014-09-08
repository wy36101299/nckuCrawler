nckuCrawler
===========

nckuCrawler with OOP 官網-全部公告自動生成json檔，格式如下

    "日期": "2014-09-06",
    "標題": "<a href=\"http://reg.acad.ncku.edu.tw/files/13-1055-127164-1.php?Lang=zh-tw\">國立成功大學104學年度碩士班甄試入學招生簡章</a>",
    "公告單位": "註冊組"

###執行環境
python 3.x

###檔案差異
nckuCrawler.py  
使用OOP  
nckuCrawler_notOOP.py  
不使用OOP

###如何使用
--------------

    $ python nckuCrawler.py start end

start 和 end 是網址index的數字
https://www.ptt.cc/bbs/Gossiping/index.html
可自由決定要爬取的index範圍

###example
--------------

    $ python3 pttcrawler.py 2 50
    
則會爬取
http://web.ncku.edu.tw/files/501-1000-1048-2.php 至
http://web.ncku.edu.tw/files/501-1000-1048-50.php
之間的內容。
