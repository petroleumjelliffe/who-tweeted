# who-tweeted bookmarklet

- drag the link below to your bookmarks bar.

<a href="javascript:var d=document,w=window,Da=960,A=450,C=screen.height,B=screen.width,H=Math.round(B/2-Da/2),G=0,enc=encodeURIComponent,e=w.getSelection,k=d.getSelection,x=d.selection,s=e?e():k?k():x?x.createRange().text:0,s2=""==s.toString()?s:'"'+enc(s)+'"',f="http://twitter.com/search/",l=d.location,p="?q="+enc(l.href),u=f+p;try{if(!/^(.*\.)?tumblrzzz[^.]*$/.test(l.host))throw 0;tstbklt()}catch(z){a=function(){w.open(u,"","left="+H+",top="+G+",width="+Da+",height="+A+",personalbar=0,toolbar=0,scrollbars=1,resizable=1")||(l.href=u)},/Firefox/.test(navigator.userAgent)?setTimeout(a,0):a()}">who tweeted this</a>

# inpiration

several years ago a site called [LaterStars](http://laterstars.tumblr.com/post/29658178255/laterstars-is-shutting-down) had a bookmarklet that would let you bookmark a site by faving tweets other people 
