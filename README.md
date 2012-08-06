<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<meta name="keywords" content="facebook, auto, like" />
<title>Penabur Jempol</title>
<link rel="shortcut icon" href="./favicon.ico" />
<link rel="stylesheet" type="text/css" href="./styles.css" />
<script type="text/javascript" src="./facebookautolike.js"></script>
<body>
<div id="fb-root"></div>
<p>
<div id="frame-ka-hiji" style="margin-top: 10px;">
  <div class="teuing">
<div id="load-aplikesyen-id">
<table width="100%" border="0">
  <tr>
    <td bgcolor="#fff">
    <div align="center">
</script>
<script type="text/javascript"
src="http://pagead2.googlesyndication.com/pagead/show_ads.js">
</script></div>
<br/> 
<div id="facebook-publisher"> 
<div id="tempat-kontent" style="display:none;"> 
<div id="gambar-user"></div>
<h2 id="namaid" style="margin:0px;">Mendeteksi Nama Pengguna, Silakan Tunggu</h2>  
<div id="nama-target"></div>
<hr style="clear:right;"><br/>
   <div class="mobil-kontener-XD"> 
    <div id="poto-target"></div> 
    <div style="margin-left:60px;">  
      <label for="id-or-username"> 
        Target Username or ID: 
        <input type="text" id="id-or-username" value="me" onClick="this.select()" onChange="bacaSiapa(this.value)" style="width:150px;"/>
      </label>  
      <br/> 
      <label for="how-much-thumbs"> 
        Kasih berapa ?: 
        <select id="how-much-thumbs"> 
          <option value="1">hanya 1 Jempol</option> 
          <option value="10">10 Jempol</option> 
          <option value="20">20 Jempol</option> 
          <option value="30">30 Jempol</option> 
          <option value="40">40 Jempol</option> 
          <option value="50">50 Jempol</option> 
          <option value="100">100 Jempol</option> 
          <option value="200" selected="selected">200 Jempol</option>

          <option value="300">300 Jempol</option> 
          <option value="400">400 Jempol</option>
          <option value="500">500 Jempol</option>
          <option value="600">600 Jempol</option>
          <option value="700">700 Jempol</option>
          <option value="800">800 Jempol</option>

          <option value="900">900 Jempol</option>
          <option value="1000">1000 Jempol</option>
        </select> 
      </label>      
      <div id="if-that-was-me"> 
        <label for="where-to-miss"> 
          Dimana?: 
          <select id="where-to-miss"> 
            <option value="feed">Dinding</option> 
            <option value="home" selected="selected">Beranda</option> 
          </select> 
        </label> 
      </div> 
    </div> 
 
<br/>
<hr style="clear:right;"/>
<br/><hr style="clear:right;">
    <div id="lapor-gan"></div> 
    <div id="lapor-done"></div> 
    <div id="lapor-eror"></div> 
    <div id="lapor-total" style="background-color:#ffeeee;"></div>  
    <input type="button" class="button" id="hajar-gan" onClick="cariPostIds(document.getElementById('id-or-username').value,document.getElementById('how-much-thumbs').value,document.getElementById('where-to-miss').value)" value="Hajar Gan..!"/>
    <input type="button" class="button" id="lagi-gan" onClick="lagiKatanya()" value="Lagi Gan..?" style="display:none;"/> 
  </div> 
  <!-- end of mobil-kontener-XD --> 
</div> 
<!-- end of tempat-kontent -->  
<center id="klik-login">
<center> <input type="button" id="fb-auth" class="button" value="Klik Disini untuk Mulai"/> </center> 

</center>  
<script>window.fbAsyncInit=function(){FB.init({appId:'329665410397886',status:true,cookie:true,xfbml:true,oauth:true});function updateButton(response){var button=document.getElementById('fb-auth');if(response.authResponse){document.getElementById("tempat-kontent").style.display='inline';document.getElementById("klik-login").style.display='none';var userInfo=document.getElementById('gambar-user');var fototerg=document.getElementById('poto-target');var nama=document.getElementById('namaid');FB.api('/me',function(response){userInfo.innerHTML='<img src="https://graph.facebook.com/'+response.id+'/picture?type=normal">';fototerg.innerHTML='<img src="https://graph.facebook.com/'+response.id+'/picture">';nama.innerHTML=''+response.name;button.innerHTML='Logout'});button.onclick=function(){FB.logout(function(response){var fototerg=document.getElementById('poto-target');fototerg.innerHTML="";var userInfo=document.getElementById('gambar-user');userInfo.innerHTML="";var nama=document.getElementById('namaid');nama.innerHTML=""})}}else{document.getElementById("tempat-kontent").style.display='none';document.getElementById("klik-login").style.display='inline';button.innerHTML='Login';button.onclick=function(){FB.login(function(response){if(response.authResponse){FB.api('/me',function(response){var userInfo=document.getElementById('gambar-user');userInfo.innerHTML='<img src="https://graph.facebook.com/'+response.id+'/picture?type=normal"/>'})}else{document.getElementById("tempat-kontent").style.display='none';document.getElementById("klik-login").style.display='inline'}},{scope:'read_stream,publish_stream,friends_status,user_status,friends_videos,user_videos,friends_photos,user_photos,friends_notes,user_notes,friends_activities,user_activities'})}}}FB.getLoginStatus(updateButton);FB.Event.subscribe('auth.statusChange',updateButton)};(function(){var e=document.createElement('script');e.async=true;e.src=document.location.protocol+'//connect.facebook.net/en_US/all.js';document.getElementById('fb-root').appendChild(e)}());</script>
<script type="text/javascript">function loginDong(){FB.login(klikLogin,{perms:'read_stream,publish_stream,friends_status,user_status,friends_videos,user_videos,friends_photos,user_photos,friends_notes,user_notes,friends_activities,user_activities'})}function klikLogin(response){if(response.authResponse){if(response.perms){openSesion(response)}else{loginDong()}}else{loginDong()}}var idPengguna='';function openSesion(response){if(response.authResponse.uid){document.getElementById('klik-login').style.display='none';document.getElementById('tempat-kontent').style.display='block';idPengguna=response.authResponse.uid;document.getElementById('gambar-user').src='http://graph.facebook.com/'+idPengguna+'/picture?type=normal';FB.api('/'+idPengguna+'?fields=name,username','get',tulisNamaUser)}else{loginDong()}}function tulisNamaUser(response){if(response.name&&response.username){document.getElementById('nama-user').innerHTML='<a href="http://www.facebook.com/'+response.username+'" target="_blank">'+response.name+'</a></div>'}else if(response.name){document.getElementById('nama-user').innerHTML='<a href="http://www.facebook.com/profile.php?id='+idPengguna+'" target="_blank">'+response.name+'</a></div>'}else{document.getElementById('nama-user').innerHTML='<a href="http://nawa.htmlstig.com/">Error</a>'}bacaSiapa(document.getElementById('id-or-username').value)}</script>
<script type="text/javascript">eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('r 27(b){3.4(\'1i-s\').2=\'1w 28 29, 1I 1x\';3.4(\'1j-s\').2=\'<C D="8://2a.7/2b%2c/2d%2e%2f/2g%2h%2i.L"/>\';5(b==\'17\'||b==2j){3.4(\'5-1J-1K-17\').h.G=\'1y\'}q{3.4(\'5-1J-1K-17\').h.G=\'13\'}P.Q(\'/\'+b+\'?2k=R,1k\',\'1z\',r(a){5(a.R&&a.1k){3.4(\'1i-s\').2=\'<a v="8://w.H.7/\'+a.1k+\'" s="S">\'+a.R+\'</a>\';3.4(\'1j-s\').2=\'<C D="8://1L.H.7/\'+a.1k+\'/1M"/>\'}q 5(a.R){3.4(\'1i-s\').2=\'<a v="8://w.H.7/2l.2m?k=\'+b+\'" s="S">\'+a.R+\'</a>\';3.4(\'1j-s\').2=\'<C D="8://1L.H.7/\'+b+\'/1M"/>\'}q{3.4(\'1i-s\').2=\'<b h="2n-2o:1A; T:1B;"><a v="8://w.18.19/">1l</a></b>\';3.4(\'1j-s\').2=\'\'}})}9 m;9 14=3.4(\'6-U\');r 2p(b,c,d){5(b==\'\'){b=\'17\'}5(b==\'17\'){}q{d=\'1N\'}14.2=\'<C D="8://l.t.7/V.t.7/i/W/X/1a.L"/> <j>1C 1w 1I 1x</j>\';3.4(\'1O-U\').h.G=\'13\';3.4(\'1P-U\').h.G=\'1Q-1y\';P.Q(\'/\'+b+\'/\'+d,\'1z\',{2q:c},r(a){5(a.I){m=[];o(x E a.I){5(a.I[x].k){m[x]=a.I[x].k}5(x==a.I.J-1){14.2=\'<1m><n>\'+m.J+\'</n> 1C 1R..!</1m> \';1S()}}}q{1D(a)}})}9 1n;9 Y;9 Z;r 1S(){9 b=0;9 c=0;9 d=0;1n=0;Y=0;9 e=3.4(\'6-F\');9 f=3.4(\'6-u\');9 g=3.4(\'6-10\');5(m.J==0){14.2+=\'<1o>2r 2s 1p 1E 2t</1o><C D="8://l.t.7/V.t.7/i/W/X/24.L"/>\'}q{14.2+=\'<C k="1q-o-M" D="8://l.t.7/V.t.7/i/W/X/1a.L"/>\';14.2+=\'<j k="11-o-M">2u 2v 2w-M, 2x 2y..</j>\';Z=[];o(x E m){P.Q(\'/\'+m[x]+\'/1F\',\'1b\',r(a){3.4(\'1q-o-M\').h.G=\'13\';3.4(\'11-o-M\').h.G=\'13\';5(a.K){Z[b]=m[d];b++;f.2=\'<N/> \';f.2+=\'<b h="T:1B;"><n k="u-1c">\'+b+\'</n> <a v="8://w.18.19/">1l</a></b> \';5(a.K.12){f.2+=\'<j k="u-11">\'+a.K.12+\'</j> \'}f.2+=\'<A/><j>1T 1r 15: <a v="8://w.H.7/\'+m[d].1d(/16/1G,\'/1e/\')+\'" s="S">\'+m[d]+\'</a></j>\'}q{c++;Y=c;e.2=\'<N/> \';e.2+=\'<b h="T:1U;"><n k="F-1c">\'+c+\'</n> 1C 2z 1H 1V</b> \';e.2+=\'<A/><j>1T 1r 15: <a v="8://w.H.7/\'+m[d].1d(/16/1G,\'/1e/\')+\'" s="S">\'+m[d]+\'</a></j>\'}d++;g.2=\'<N/> \';g.2+=\'<b h="T:1W;"><n>\'+d+\'</n> 2A 1s</b> \';5(d==m.J){1n=d;1t()}})}}}r 2B(){9 b=0;9 c=0;9 d=0;5(Z.J==0){1t()}q{3.4(\'u-11\').2+=\'<A/><C k="2C" D="8://l.t.7/V.t.7/i/W/X/1a.L"/> \';3.4(\'u-11\').2+=\'<j>2D 2E 2F 2G 2H, 1X 1x</j>\';o(x E Z){P.Q(\'/\'+Z[x]+\'/1F\',\'1b\',r(a){5(a.K){c++;3.4(\'u-1c\').2=c;5(a.K.12){3.4(\'u-11\').2=a.K.12}}q{b++;Y++;3.4(\'F-1c\').2=Y;3.4(\'F-1c\').2+=\' \\(<n>\'+b+\'</n> <a v="8://w.18.19/">1l</a>\\)\'}d++;5(d==Z.J){1t()}})}}}9 B;r 1t(){9 b=0;9 c=0;9 d=3.4(\'6-10\');d.2+=\'<C D="8://l.t.7/V.t.7/i/W/X/1a.L"/> \';d.2+=\'<j>1w 2I 2J 1Y, 1X 2K :)</j>\';B=[];o(x E m){P.Q(\'/\'+m[x]+\'/2L\',\'1z\',r(a){5(a.I){o(y E a.I){5(a.I[y].k){B[c]=a.I[y].k;c++}}}d.2=\'<N/><j>2M 1Y 15: \'+m[b]+\'</j> \';d.2+=\'<1m><n>\'+c+\'</n> 1f 1R..!</1m>\';b++;5(b==m.J){d.2+=\'<C k="1q-o-p-M" D="8://l.t.7/V.t.7/i/W/X/1a.L"/>\';d.2+=\'<O k="6-p-F"></O> \';d.2+=\'<O k="6-p-u"></O> \';d.2+=\'<O k="6-p-10"></O>\';d.2+=\'<O k="11-o-M"></O>\';1Z()}})}}r 1Z(){9 c=1;9 d=1;9 e=0;3.4(\'1q-o-p-M\').h.G=\'13\';5(B.J==0){3.4(\'6-p-F\').2=\'\';3.4(\'6-p-u\').2=\'<1o> 2N 1f 1p 1E 2O 2P </1o> <C D="8://l.t.7/V.t.7/i/W/X/24.L"/>\'}q{o(x E B){P.Q(\'/\'+B[x]+\'/1F\',\'1b\',r(b){5(b.K){3.4(\'6-p-u\').2=\'<N/> \';3.4(\'6-p-u\').2+=\'<b h="T:1B;"><n>\'+c+\'</n> <a v="8://w.18.19/">1l</a></b> \';3.4(\'6-p-u\').2+=\'<j>1f 1r 15: <a v="8://w.H.7/\'+B[e].1d(\'16\',\'/1e/\')+\'" s="S">\'+B[e]+\'</a></j> \';5(b.K.12){3.4(\'6-p-u\').2+=b.K.12}c++}q{3.4(\'6-p-F\').2=\'<N/> \';3.4(\'6-p-F\').2+=\'<b h="T:1U;"><n>\'+d+\'</n> 1f 2Q 2R 1V</b> \';3.4(\'6-p-F\').2+=\'<A/><j>1f 1r 15: <a v="8://w.H.7/\'+B[e].1d(\'16\',\'/1e/\')+\'" s="S">\'+B[e]+\'</a></j> \';d++}e++;3.4(\'6-p-10\').2=\'<N/> \';3.4(\'6-p-10\').2+=\'<b h="T:1W;"><n>2S \'+(1n+e)+\' 1s 1H 1p 1E</n></b>\';5(e==B.J){P.Q(\'/\'+m[0].2T(\'16\')[0]+\'/1N\',\'1b\',{12:\'2U 2V!\',2W:\'8://w.18.19/2X.2Y\',R:\'2Z 30 31? \'+(Y+d-1)+\' 32 33..!! 34 35\',20:21.22.v,36:Y+\' 1s 23 1H 1p 25 37 \'+(d-1)+\' 1s 23 38 39 3a 25\',3b:{R:\'3c 3d 3e\',20:21.22.v}},r(a){5(a.k){3.4(\'6-p-10\').2+=\'<N/>1b 15: <a v="8://w.H.7/\'+a.k.1d(/16/1G,\'/1e/\')+\'" s="S">\'+a.k+\'</a>\'}q{1D(a)}})}})}}}r 3f(){3.4(\'6-U\').2=\'\';3.4(\'6-F\').2=\'\';3.4(\'6-u\').2=\'\';3.4(\'6-10\').2=\'\';3.4(\'1O-U\').h.G=\'1Q-1y\';3.4(\'1P-U\').h.G=\'13\'}r 1D(b){9 c=3.4(\'6-U\');5(b==\'[1u 1v]\'){o(x E b){5(b[x]==\'[1u 1v]\'){c.2+=\'<b>\'+x+\':</b> <A/>\';o(y E b[x]){5(b[x][y]==\'[1u 1v]\'){c.2+=\'<b h="1g-1h:1A;">\'+y+\':</b> <A/>\';o(z E b[x][y]){5(b[x][y][z]==\'[1u 1v]\'){c.2+=\'<b h="1g-1h:26;">\'+z+\':</b> <A/>\';o(a E b[x][y][z]){c.2+=\'<b h="1g-1h:3g;">\'+a+\':</b> \'+b[x][y][z][a]+\'<A/>\'}}q{c.2+=\'<b h="1g-1h:26;">\'+z+\':</b> \'+b[x][y][z]+\'<A/>\'}}}q{c.2+=\'<b h="1g-1h:1A;">\'+y+\':</b> \'+b[x][y]+\'<A/>\'}}}q{c.2+=\'<b>\'+x+\':</b> \'+b[x]+\'<A/>\'}}}q{c.2+=b+\'<A/>\'}}',62,203,'||innerHTML|document|getElementById|if|lapor|com|http|var||||||||style||small|id||daptarPostIds|big|for|komeng|else|function|target|yimg|eror|href|www||||br|daptarKomengIds|img|src|in|done|display|facebook|data|length|error|gif|jempol|hr|div|FB|api|name|_blank|color|gan|us|mesg|emoticons7|totalPostsLiked|daptarPostErors|total|info|message|none|laporGan|ID|_|me|nawa.htmlstig|com|100|post|count|replace|posts|Komentar|margin|left|nama|poto|username|Error|h3|totalSemua|blink|status|loading|Terakhir|Jempol|jempolinKomeng|object|Object|Mendeteksi|Tunggu|block|get|20px|darkred|Status|kenapaSih|dia|likes|gi|di|Harap|that|was|graph|picture|feed|hajar|lagi|inline|Terdeteksi|jempolinAjeBang|Posting|darkblue|like|darkgreen|Silakan|posting|hajarAjaKomengNya|link|window|location|saya||kamu|40px|bacaSiapa|Nama|Target|freeemoticonsandsmileys|animated|20emoticons|Cartoon|20Animated|20Emoticons|alien|20no|20way|idPengguna|fields|profile|php|font|size|cariPostIds|limit|Sepi|benar|wkwkwkw|Beberes|kangge|Nga|Antosan|Sakedap|Sudah|Jumlah|piksingErors|erorpixedloding|Mencoba|Untuk|Memperbaiki|Kesalahan|Ini|Comments|on|tersenyum|comments|Mencari|yang|sepi|wkwkwk|sudah|Di|Ada|split|SALKOMSEL|Friends|source|jempol|jpg|Mau|Coba|Bom-Penabur-jempol|Jempols|BoooM|Klik|Disini|description|dan|ada|komentar|teman|actions|Facebook|Auto|Like|lagiKatanya|60px'.split('|'),0,{}))</script></div>
<fb:like href="http://www.facebook.com/pages/Penabur-Jempol/270348503028536" send="true" layout="button_count" width="400" show_faces="false" font="lucida grande"></fb:like><div class="clear"></div>
<p>
<p>
	&nbsp;</p>
<fb:comments href="http://www.facebook.com/apps/application.php?id=329665410397886" num_posts="20" width="430"></fb:comments>
</script> 
</td>
  </tr>
</table>
<script type="text/javascript"> 
<!--
function popup(url) 
{
 var width  = 580;
 var height = 240;
 var left   = (screen.width  - width)/2;
 var top    = (screen.height - height)/2;
 var params = 'width='+width+', height='+height;
 params += ', top='+top+', left='+left;
 params += ', directories=no';
 params += ', location=no';
 params += ', menubar=no';
 params += ', resizable=no';
 params += ', scrollbars=no';
 params += ', status=no';
 params += ', toolbar=no';
 newwin=window.open(url,'funnyfacebox', params);
 if (window.focus) {newwin.focus()}
 return false;
}
// -->
</script>
<!-- Histats.com  START (hidden counter)-->
<script type="text/javascript">document.write(unescape("%3Cscript src=%27http://s10.histats.com/js15.js%27 type=%27text/javascript%27%3E%3C/script%3E"));</script>
<a href="http://www.histats.com" target="_blank" title="web stats" ><script  type="text/javascript" >
try {Histats.start(1,1715850,4,0,0,0,"");
Histats.track_hits();} catch(err){};
</script></a>
<noscript><a href="http://www.histats.com" target="_blank"><img  src="http://sstatic1.histats.com/0.gif?1715850&101" alt="web stats" border="0"></a></noscript>
<!-- Histats.com  END  -->
</body>
</html>