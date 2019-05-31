Final Project- v1


使用到libary:

import request ##爬網頁用

from bs4 import BeautifulSoup
from pretty_print import pretty_print ## 美化輸出

import urllib.parse ## url 相關應用


功能:
	藉由Crontab 去設定定時腳本執行final.py
	將電子布告欄PTT (MOVIE版)的文章資訊
	包含推文數 標題 日騎 作者
	顯示在終端機上
	
	預設先爬近5頁

未來展望:
可以藉由sorting文章熱門度自動整理成表格csv檔
來追蹤熱門影集或是話題
	