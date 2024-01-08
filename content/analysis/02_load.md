Laddningstid och användbarhet
=======================
I denna rapport ska vi utvärdera hur laddningstiden påverkar användarvänligheten för 3 utvalda webbplatser.

Urval
-----------------------

Vi valde oss av hemsidorna “kids national geografic, svt play och wikipedia". Valet av hemsidan kids national geografic var främst för några misstankar om att de inte lagt så mycket tid på just prestanda för en sådan webbplats. Valet av svt play var främst då vi vet att de använder sig av mycket bilder samt har mycket livesändning vilket kan påverka stor del av användbarheten. Till sist Wikipedia, denna hemsida är en väldigt populär sida som används av många som kräver snabb laddningstid vilket gjorde på hur bra den faktiskt är.

Metod
-----------------------

Vi använde oss av “Pagespeed insights” för att mäta webbplatsernas olika värden samt se vad för förbättrings möjligheter som finns. Vi testade sidorna 3 gånger och tog deras medelvärden för värdena då det var olika varje gång. Vi använder oss även av Google kalkylark för att jämföra värdena från de olika hemsidorna.

Resultat
-----------------------

Resultatet av hemsidornas mätningar enligt Pagespeed:
<iframe class="excel" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ3AMvs26Fl7IWWNvZLrOOX8zKoKiT9Lf1kKYMEJ7fy9LR-iCJAB0tzUmNK61o3siGoVpN9Pb7IvlNT/pubhtml?widget=true&amp;headers=false"></iframe>

wikipedia
------------------
<img src="%base_url%/assets/img/wiki.png" alt="andra" style="height: 200px;">
Förbättringar för wikipedia enligt Pagespeed:

<li>Reduce unused CSS : 0.17s</li>
<li>Serve images in next-gen formats : 0.16s</li>


svt play
-----------------
<img src="%base_url%/assets/img/svtplay.png" alt="andra" style="height: 200px;">
Förbättringar för Svtplay enligt Pagespeed:

<li>Reduce initial server response time 1.17s</li>
<li>Reduce unused JavaScript 0.96s</li>
<li>Properly size images 0.48s</li>

kids national geographic 
-------
<img src="%base_url%/assets/img/ngk.png" alt="kids" style="height: 200px;">
Förbättringar för Natinal geographic kids enligt Pagespeed:

<li> Reduce unused JavaScript 6.79s</li>
<li>Eliminate render-blocking resources 2.67s</li>
<li>Defer offscreen images 2.66s</li>
<li>Minify CSS 1.18s</li>
<li>Reduce unused CSS 1.18s</li>
<li>Minify JavaScript 0.89s</li>
<li>Enable text compression 0.78s</li>

Analys
-----------------------

Att Wikipedia var absolut bäst var inget som chockade någon av oss. Det är en webbplats som används av miljoner varje dag, så att optimering av laddningstid och användarvänlighet är i fokus är givet. Dessutom så har startsidan inte speciellt mycket innehåll att ladda in endast 0.8MB vilket såklart underlättar. 

Svt Plays resultat var ändå väntat men även oväntat. I och med att det har så många bilder på sin hemsida då alla program/dokumentärer/filmer har en egen bild tar det längre tid. Det som chockade oss var nog att prestandan var så pass låg, trots att det är ganska givet då det är många bilder men i och med att det är så pass populär hemsida förväntade vi oss lite bättre värden. Laddningstiden var ändå ok, vi förväntade oss inte annat dock. Den främsta förbättringen som hade behövts är att minska initial server response time då det var uppe i 1.17s samt oanvänd javascript som var uppe i nästan en hel sekund. Genom att rikta in sig på dessa områden kan webbplatsen förbättra sin prestanda avsevärt, vilket skulle ge användarna en snabbare och mer responsiv upplevelse.

Kids national geografic gav sämst värden utav de 3 webbplatserna. Vi väntande oss ändå att värdena skulle vara sämre då det inte är helt vanliga/ populär hemsida. Webbplatsen fick bra mycket förbättringsförslag, vissa med mer påvärkan än andra. En av de mest påverkande förbättringsförslagen var att reducera oanvänd JavaScript, vilket skulle minska laddningstiden med hela 6.79 sekunder. Dessutom framhävdes behovet av att eliminera render-blocking resources (vilket skulle spara 2.67 sekunder) och att fördröja inläsningen av bilder som inte syns direkt på skärmen (vilket skulle förbättra laddningstiden med 2.66 sekunder). Genom att genomföra dessa förändringar skulle sidan förbättras avsevärt när det gäller laddningstider och därmed erbjuda användarna en snabbare och smidigare upplevelse

Referenser
-----------------------

<li>pagespeed - mätningar av webbplatserna</li>
<li>google kalkylark - verktyg där vi skrev upp resultat</li>

Övrigt
-----------------------

Ett arbete genomfört av mig Zoë Waters och William Stenquist, student på Blekinge Tekniska Högskola.