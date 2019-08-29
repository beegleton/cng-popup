# cng-popup 
Automatisk video-popup till <a href="https://info.cng.se" target="_blank">info.cng.se</a>.</br>
Skapad 2019-09-29 by Beegleton.

<h3>Installera i Snowfire (redan gjort)</h3>

1. Infoga HTML-kod i HTML-block högst upp på startsidan.

2. Infoga JS-script i HEAD.

3. Infoga CSS i style.

<h3>Att byta ut videon</h3>

1. Se till att du är inloggad i redigeringsläget och gå sedan in på <a href="https://info.cng.se/a;editor" target=_blank">
https://info.cng.se/a;editor</a>.

2. Scrolla ner och klicka på "Assets" i menyn till vänster.</br>

3. Klicka på "Välj fil" och ladda upp videofilen från datorn. Filen ska vara i MP4-format och bör inte vara längre än 30 sek, gärna kortare så att inte besökarna tappar intresset.
Filstorleken bör hållas under 10 MB. För tips kring optimering och konvertering, läs avsnittet "Överkurs" längre ner på sidan.

Både Android och iOS kräver att videon ska loopas och vara utan ljud för att autoplay-funktionen ska fungerai mobilen, läs mer om detta här:
https://blog.synq.fm/html5-video-looping-autoplay-on-ios-and-android

4. När filen är uppladdad, högerklicka på "View"-knappen och välj "Kopiera länkadress".

5. Klicka på "Meny"-knappen uppe i vänstra hörnet och sedan "Webbsida" för att komma tillbaka till startsidan.

6. Klicka på videon och koden för klippet dyker upp. Markera sökvägen (url:en) till det gamla videoklippet och klistra in den nya.
Raden som ska ändras börjar med <em>src</em>. Sökvägen (url:en) ska ha ett cituationstecken på vardera sida om sig.

7. Klicka på "Spara" och ladda om sidan.

8. Klart! Om du inte ser någon ändring kan du behöva rensa cachen i din webbläsare eller öppna sidan i Inkognitoläge.

<h3>Överkurs</h3>

För att komprimera videoklipp rekommenderar vi Handbrake. Det är ett gratisverktyg som finns att <a href="https://handbrake.fr/downloads.php" target="_blank">ladda ner här</a>.

Här kommer en kort beskrivning av hur du kan ställa in Handbrake för att komprimera videofilen innan du laddar upp den på hemsidan:

<img src="https://d29ly7uq16xz5t.cloudfront.net/editor/dist/16284/uploads/how-to-hb.png?t=6c4c3d631549579c40daa61a32a02ded">

1. Välj videofilen på datorn.

2. Bestäm namn och vart du vill att den nya filen ska sparas.

3. Klicka på "Picture Settings".

4. Ändra bredden (width) till 600 (höjden justeras då automatiskt).

5. Kontrollera att checkrutan "Web optimized" är ibockad och att video codec är satt till "H.264 (x264)". 
Klicka sedan på "Start".

Ladda sedan upp den komprimerade filen enligt steg 3 i föregående avsnitt och fortsätt sedan med de efterföljande stegen.

<em>Stöter du på problem, tveka inte att kontakta oss! Antingen på 011-333 0510 eller <a href="mailto:kontakt@beegleton.com">kontakt@beegleton.com</a>.</em>
