# who-tweeted bookmarklet

- drag the link below to your bookmarks bar.

<a href="javascript:var d=document,w=window,Da=960,A=450,C=screen.height,B=screen.width,H=Math.round(B/2-Da/2),G=0,enc=encodeURIComponent,e=w.getSelection,k=d.getSelection,x=d.selection,s=e?e():k?k():x?x.createRange().text:0,s2=""==s.toString()?s:'"'+enc(s)+'"',f="http://twitter.com/search/",l=d.location,p="?q="+enc(l.href),u=f+p;try{if(!/^(.*\.)?tumblrzzz[^.]*$/.test(l.host))throw 0;tstbklt()}catch(z){a=function(){w.open(u,"","left="+H+",top="+G+",width="+Da+",height="+A+",personalbar=0,toolbar=0,scrollbars=1,resizable=1")||(l.href=u)},/Firefox/.test(navigator.userAgent)?setTimeout(a,0):a()}">who tweeted this</a>

# how it works

- from any webpage, click the bookmarklet and a new window opens with a Twitter search for the URL you're on
- see what other people tweeted about the page
- fave or retweet them, and you have record of the link in you Twitter feed
- BONUS: the bookmarklet works on some mobile devices.  If you have Chrome Sync enabled, the bookmarklet will be synced and available from your phone.

# inpiration

several years ago a site called [LaterStars](http://laterstars.tumblr.com/post/29658178255/laterstars-is-shutting-down) had a bookmarklet that did  the above, but with a custom interface.  The service shuttered, but the idea is simple.  Who else tweeted about the page you're reading, and give you that list so you can fave orretweet so you have a record of it.

the code is literally a combination of bit.ly's and Twitter's bookmarklets for grabbing the document URL, and opening a new window.
