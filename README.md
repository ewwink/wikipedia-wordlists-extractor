Wikipedia wordlists Dictionary Extractor
=============================

Extract Unique word Lists from Wikimedia (Wikipedia) backup database (XML):

> https://dumps.wikimedia.org/backup-index.html

	Wikipedia
	Wiktionary
	Wikiquote
	Wikibooks
	Wikisource
	Wikispecies
	Wikinews
	Wikiversity
	Wikivoyage
	Wikimedia Commons
	Wikidata
	MediaWiki
	Meta-Wiki
	Wikimedia Incubator
	Wikimedia Labs

To extract wordlists from Wikipedia latest articles (indonesia) go to 

> http://dumps.wikimedia.org/idwiki/latest/

>the first 2 character (id) from "idwiki" is country code

download and extract file `idwiki-latest-pages-articles.xml.bz2` 

next run the following bash script

    $ sh wiki-extract.sh idwiki-latest-pages-articles.xml
    
that's all you're done creating unique word Lists from Wikipedia

**For Windows users:**

    - if you want to run this script install cygwin https://cygwin.com/install.html
    - when installing cygwin don't forget to also install ncurses Utils package, it used for "clear" command 
    
==================================================
created by ewwink [Check Pagerank](http://www.cekpr.com)
