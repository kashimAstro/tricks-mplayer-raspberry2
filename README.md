# tricks-mplayer-raspberry2

#playlist file
<pre>mplayer -lavdopts threads=3 -fs -playlist playlist.txt</pre>
<br>

#play single file 
<pre>mplayer -lavdopts threads=3 -fs file.avi</pre>
<br>

#play single file infinite loop
<pre>mplayer -lavdopts threads=3 -fs -loop 0 file.avi</pre>
<br>
