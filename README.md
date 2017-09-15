<style>
            body {
                        background-image: url("https://i.makeagif.com/media/7-21-2015/Wa5D67.gif");
                        }

p {
    font-family: "Cursive", sans;
}

  body {
    position: relative;
    width: 100%;
    border: 1px solid white;
    display: block;
  }

  body > *  {
    margin: auto;
    width: 500px;
    display: block;
    overflow: auto;
  }

  body > script {
    display: none
  }

body {
     color: white;
     }
</style>

<b>

<script>


/*
RAINBOW TEXT Script by Matt Hedgecoe (c) 2002
Featured on JavaScript Kit
For this script, visit http://www.javascriptkit.com
*/

// ********** MAKE YOUR CHANGES HERE

var text="MY TRIBUTE TO DANNY DEVITO" // YOUR TEXT
var speed=0.01 // SPEED OF FADE

// ********** LEAVE THE NEXT BIT ALONE!


if (document.all||document.getElementById){
document.write('<span id="highlight">' + text + '</span>')
var storetext=document.getElementById? document.getElementById("highlight") : document.all.highlight
}
else
document.write(text)
var hex=new Array("00","14","28","3C","50","64","78","8C","A0","B4","C8","DC","F0")
var r=1
var g=1
var b=1
var seq=1
function changetext(){
rainbow="#"+hex[r]+hex[g]+hex[b]
storetext.style.color=rainbow
}
function change(){
if (seq==6){
b--
if (b==0)
seq=1
}
if (seq==5){
r++
if (r==12)
seq=6
}
if (seq==4){
g--
if (g==0)
seq=5
}
if (seq==3){
b++
if (b==12)
seq=4
}
if (seq==2){
r--
if (r==0)
seq=3
}
if (seq==1){
g++
if (g==12)
seq=2
}
changetext()
}
function starteffect(){
if (document.all||document.getElementById)
flash=setInterval("change()",speed)
}
starteffect()
</script>


<div><span style="color:#da00ff;">T</span><span style="color:#dd16fe;">H</span><span style="color:#e02cfd;">I</span><span style="color:#e343fc;">S</span><span style="color:#e759fb;"> </span><span style="color:#ea6ffa;">I</span><span style="color:#ed85f9;">S</span><span style="color:#d96ad8;"> </span><span style="color:#c450b7;">M</span><span style="color:#b03595;">Y</span><span style="color:#9b1b74;"> </span><span style="color:#870053;">W</span><span style="color:#900964;">E</span><span style="color:#981274;">B</span><span style="color:#a11b85;">S</span><span style="color:#a92495;">I</span><span style="color:#b22da6;">T</span><span style="color:#ba36b6;">E</span></div>

.transparent {
	/* Required for IE 5, 6, 7 */
	/* ...or something to trigger hasLayout, like zoom: 1; */
	width: 100%; 
		
	/* Theoretically for IE 8 & 9 (more valid) */	
	/* ...but not required as filter works too */
	/* should come BEFORE filter */
	-ms-filter:"progid:DXImageTransform.Microsoft.Alpha(Opacity=50)";
	
	/* This works in IE 8 & 9 too */
	/* ... but also 5, 6, 7 */
	filter: alpha(opacity=50);
	
	/* Older than Firefox 0.9 */
	-moz-opacity:0.5;
	
	/* Safari 1.x (pre WebKit!) */
	-khtml-opacity: 0.5;
    
	/* Modern!
	/* Firefox 0.9+, Safari 2?, Chrome any?
	/* Opera 9+, IE 9+ */
	opacity: 0.5;
}

<img src="https://pbs.twimg.com/profile_images/535222646963572736/KZItD1f-.png" alt="Ya boi Danny" width="300"> 

<img src="https://media.giphy.com/media/l0EozQZTvsWiTLies/giphy-downsized-large.gif" alt="Egg" width="300"> 


<p>Danny DeVito is a famous actor and comedian, he was born on November 17, 1944, he appeared in such classics like "It's always sunny in Philadelphia", "Taxi", "Matilda", "The Lorax", "Hercules" and much more.</p>

<p>Danny DeVito's first role he ever played was Martini in the 1975 film "One Flew Over the Cuckoo's Nest" but he didn't get well known until he played one of his most famous rolls as Louie De Palma in the TV show "Taxi"</p>

<p>Danny Devito also helped produce some movies, including "Pulp Fiction" and "Get Shorty"</p>

<iframe width="450" height="480" src="https://www.youtube.com/embed/xzlVvhbrx7k" frameborder="0" allowfullscreen></iframe>

