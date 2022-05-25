# Teknikjakten
Testjakt där vi kan experimentera med koden utan att behöva ändra i färdiga projekt.

För att starta surfa till:
bjuvsbibliotek.github.io/testjakt

Umeå biblioteks tutorial för att ladda ner och installera
de program du behöver. (Avsnittet om hur du använder
github.com är dock förlegad, sidan ser inte ut som de
beskriver den längre):
https://digiteket.se/kurs/bygg-din-egen-teknikjakt/

Google är din bästa vän när du har en specifik fråga du
fastnat på. Vill du få överblick över vad som är möjligt
rekommenderar jag:
w3schools.com
De har tutorials, exempel och övningar till HTML, CSS,
javascript (de 3 språk vi använder i våra projekt) och
mycket mer.


**PROGRAM OCH INLOGG**

- Visual Studio Code
Används för att läsa och redigera kod. All grön text
är kommentarer som inte gör någonting i koden. Det
brukar användas för att dokumentera vad olika kodsnuttar
handlar om och är då till hjälp för att hitta i koden.

- GitHub Desktop, github.com
Github är ett verktyg för att publicera, lagra och slå ihop
olika versioner av samma kodfil. Användbart när flera kodar
i samma fil eller man kodar på flera datorer. Desktop används
för att enkelt ladda upp ändrade filer till webb-versionen (push)
eller ladda hem eventuella ändringar till datorn (pull).
Inlogg finns i I:mappen. Kopplad till Bjuvs lånediskmejl, med
Bjuvs gmail som reserv. Första gången du försöker logga in från
din dator kan du behöva verifiera dig, den koden hamnar då i
lånediskmejlen.

Alla filer finns just nu på datorn närmast dörren ut till
själva biblioteket (Catarinas ände av kontoret).
Där finns även Visual Studio Code för att redigera koden och
GitHub Desktop för att publicera koden. Publicerad kod hamnar
på github.com. Inloggningsuppgifter finns i I:mappen.
Användarnamnet är BjuvsBibliotek och kontot är knutet till
Bjuvs lånediskmejl i första hand med Bjuvs gmail som reserv.

På Skrivbordet ligger även en mapp med mallen till projektet
som skaparna av Teknikjakten har gjort, utan ändringar.
Filer som gjorts om för Bjuvs bibliotek ligger under:
Den här datorn -> Dokument -> GitHub



**VISUAL STUDIO CODE**

Går att ladda ner här:
https://code.visualstudio.com/

Det går att öppna enstaka filer men jag föreslår att du väljer
File -> Open folder. Då har du alla filer i ditt projekt
liggande i listen till vänster så du snabbt kan öppna, stänga
och kopiera efter behov. Det finns möjlighet att spara under
"File"-menyn eller med "Ctrl + S" men när jag suttit verkar allt
ha sparats efterhand. (När jag visade på Edits dator verkade det
dock inte spara automatiskt, men då var filen med osparade ändringar
markerad med en prick eller liknande vid filnamnet. Du kan kolla hur
dina ändringar i koden ser ut genom att öppna aktuell fil från
utforskaren. Borde räcka att dubbelklicka, annars försök "Öppna med"
och välj Google Chrome eller någon annan webbläsare. Du behöver
alltså inte publicera ändringarna till github.com innan du kan se
dem själv.

Grön text är kommentarer och "räknas inte" som kod även om den skulle
innehålla giltig kod. Den syns normalt inte heller på den publicerade
webbsidan (man se html för i princip vilken hemsida som helst genom
att högerklicka och välja "inspektera" eller "visa sidkälla", och då
syns även kommentarer så skriv inget hemligt). Används allmänt till
att förklara vad varje kodavsnitt gör för att underlätta både för någon
annan som går in och läser koden och för dig själv när du öppnar
projektet efter lång tid. Jag har lagt in ganska mycket kommentarer
eftersom jag tänkt att detta projektet ska användas som en mall när
du gör egna projekt. Däremot kan jag ha tagit bort stora kommentarer
om saker som inte är i fokus för att göra det lättare att hitta de
delar som är relevanta. Exempelvis att förklara hur man skriver själva
frågorna kanske känns mer relevant för mallarna för hur man gör
fritextsvar eller färdiga alternativ (som antagligen är de filer du
kommer att kopiera när du gör nya frågor) än för mallarna som bara
visar hur man lägger in videor eller länkar. Vi använder flera olika
språk och de har inte nödvändigtvis samma sätt att skriva kommentarer,
så om ett sätt inte funkar prova ett annat eller markera texten du vill
kommentera bort och använd "Toggle block comment" från Edit-menyn. Du
kan använda samma för att "avkommentera" också.
<!-- Kommentar som kan täcka en eller flera rader -->
/* Kommentar som kan täcka en eller flera rader */
// Kommentar på en rad, inget sluttecken

Det finns en sökfunktion inbyggt i VS Code, likadan som i Word. Använd
"Ctrl + F" och skriv in ordet du letar efter i rutan som dyker upp
i övre högra hörnet. Tryck ">" i vänstra kanten av sökrutan för att
även öppna en "ersätt"-ruta. Exempel:
Sök: Bujv
Ersätt: Bjuv
Du kan stega mellan varje förekomst av sökordet med hjälp av pilarna
och ersätta antingen en åt gången eller allihop på en gång.

Det är fullt möjligt att öppna flera Visual Studio Code samtidigt,
t. ex. om du vill ha testprojektet med mallarna öppet samtidigt
som ditt eget projekt, så att du lätt kan kopiera över kod eller
hela filer. Antingen högerklicka på programikonen i startfältet och
välj "New window" eller välj File -> New window i den programinstans
du redan har öppen.


**GITHUB**

GitHub Desktop går att ladda ner här:
https://desktop.github.com/

*första gången i ett nytt projekt*

För att skapa ett nytt projekt logga in på github.com och gå till
din profilsida. Jag har använt Familjen Helsingborgs orangea logga
som profilbild, och du kan se existerande repositories, lite 
statistik osv. Under fliken "Repositories (siffra)" kan du se alla
dina kodprojekt och även skapa nya med den gröna knappen "New".
- Repository name blir en del av URL-adressen till projektet, så försök
hålla det kort och med små bokstäver.
- Projektet ska vara "public".
- Kryssa i "Add a README file"
- Hoppa över "Add .gitignore"
- Välj MIT License. Det betyder att vem som helst kan göra nästan vad
som helst med vår kod, upphovsrättsligt talat. Det finns en licenstext
som ska vara med i projektet, kopierar du index.html från ett tidigare
projekt så ligger texten i en kommentar längst upp.
- Välj "Create repository".
- Gå till din GitHub Desktop applikation.
- Välj "File->Clone repository...". Du bör få upp en lista över alla
dina repositories från github.com. Välj den du precis skapade, var
du vill spara den på din dator och tryck sedan "Clone". Det är viktigt
att det inte redan finns en repository med samma namn i GitHub Desktop.

Det finns en sak du måste göra en gång per projekt, innan det kan
bli offentligt synligt. På github.com i ditt nya repository
(leta efter BjuvsBibliotek/projektnamnet), under 
Settings (horisontell meny) -> Pages (vertikal meny), rubriken Source
står det något i stil med "GitHub Pages is currently disabled".
Det finns en drop-down-meny inställd på "None" och bredvid det en knapp
som heter "Save".
- Ändra "None" till "main"
- Det dyker upp ännu en drop-down inställd på "/(root)". Låt den vara så.
- Tryck "Save".
När du gjort detta börjar bjuvsbibliotek.github.io/projektnamnet fungera
(förutsatt att du har en index.html i projektet). 

*återkommande*

Nu är Desktop-applikationen ihopkopplad med webbsidan och du kan
publicera alla dina ändring snabbt och enkelt. Desktop känner av alla
ändringar i den mapp du valt och sammanställer dem i en lista. Du kan
ändra vilket repository du arbetar med i "Current repository" (långt
uppe till vänster, precis under File). För att publicera en ändring
behöver du ge ändringen ett namn (obligatoriskt) och en summerande 
beskrivning (frivilligt) och sedan trycka på "Commit to main" (längst
ner till vänster). Välj därefter "Push origin". Färdigt.

Om du inte valt något annat när du initierade Desktop hamnar filerna
i Dokument->Github->Ditt projekt. Du kan också öppna utforskaren
(explorer) från Desktop, strax under där du tryckte "Push origin".

Notera att det tar ett par minuter efter publicering innan
ändringarna faktiskt slår igenom. På Githubs hemsida kan 
man gå till kodprojektet (leta efter "repository" och projektnamnet)
och under Settings -> Pages kan man se antingen en blå ruta
med texten "Your site is ready to be published" eller en grön
ruta med "Your site is published" beroende på om de senaste
ändringarna hunnit aktiveras ännu eller inte. När de aktiverats
kan du surfa till bjuvsbibliotek.github.io/projektnamnet och testa
hur det ser ut från användarens synvinkel.

*ta bort*

Om du någon gång behöver ta bort ett helt projekt av en eller annan anledning
finns det tre ställen att tänka på.

- github.com, gå till det projekt du vill ta bort (BjuvsBibliotek/projektnamn).
Under Settings -> General, scrolla hela vägen ner till rubriken Danger Zone.
Välj "Delete this repository" och följ instruktionerna för att bekräfta att
du verkligen vill radera projektet. 

- GitHub Desktop, tryck på "Current repository" (den skiftar mellan att visa
ev. ändringar i ditt aktuella projekt och en lista över alla dina projekt).
I listan, högerklicka på det projekt du vill ta bort och välj "Remove". 

- Utforskaren, default Dokument/GitHub/projektnamn eller där du själv valt att
lägga filerna. Ta bort mappen och/eller filerna precis som vanligt. 