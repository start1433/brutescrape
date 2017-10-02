====================================================================================
__________                __           _________                                        
\______   \_______ __ ___/  |_  ____  /   _____/ ________________  ______   ____
 |    |  _/\_  __ \  |  \   __\/ __ \ \_____  \_/ ___\_  __ \__  \ \____ \_/ __ \
 |    |   \ |  | \/  |  /|  | \  ___/ /        \  \___|  | \// __ \|  |_> >  ___/
 |______  / |__|  |____/ |__|  \___  >_______  /\___  >__|  (____  /   __/ \___  >
        \/                         \/        \/     \/           \/|__|        \/

Brutescrape | A web scraper for generating password files based on plain text found
               in specific web pages.
Written by Peter Kim <Author, The Hacker Playbook>
                     <CEO, Secure Planet LLC>

Usage | python brutescrape.py
====================================================================================

使用方法:
将网址写入"sites.scrape" 文件中，格式如下

	http://www.site.com,http://www.site2.com,http://www.site3.com/index.php,http://www.site4.com/admin

后直接运行

	python brutescrape.py

会生成	"passwordList.txt". 
