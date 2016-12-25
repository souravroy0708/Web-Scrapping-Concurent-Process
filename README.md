Using python&#39;s multiprocessing and any one of threading/gevent module, task is to write a

web-scraper which takes a huge file as an input ( 1Million rows ) which contains a url in

each line.

The scraper then uses BeatuifulSoup to parse the content and finds if the content contains

&quot;jquery.js&quot;. If it does, dump the url into a file &quot;accepted.csv&quot; or if it doesn&#39;t, dump it into file

&quot;rejected.csv&quot;.  
