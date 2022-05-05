# Teknikjakten
Testjakt där vi kan experimentera med koden utan att behöva ändra i färdiga projekt.

För att starta surfa till:
bjuvsbibliotek.github.io/testjakt



**Program och inlogg**

- Visual Studio Code
Används för att läsa och redigera kod. All grön text
är kommentarer som inte gör någonting i koden. Det
brukar användas för att dokumentera vad olika kodsnuttar
handlar om och är då till hjälp för att hitta i koden.

- GitHub Desktop, github.com
Github är ett verktyg för att publicera, lagra och slå ihop
kodfiler. Användbart när flera kodar i samma filer eller man
kodar på flera datorer. Desktop används för att enkelt ladda
upp ändrade filer till webb-versionen (push) eller ladda hem
eventuella ändringar till datorn (pull). Inlogg finns i
I:mappen. Kopplad till Bjuvs lånediskmejl, med Bjuvs gmail
som reserv.

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



**Visual Studio Code**

Går att ladda ner här:
https://code.visualstudio.com/

Det går att öppna enstaka filer men jag föreslår att du väljer
"File->Open folder". Då har du alla filer i ditt projekt
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
visar hur man lägger in videor eller länkar.



**GitHub**

GitHub Desktop går att ladda ner här:
https://desktop.github.com/

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
att projektet är tomt (readme och license räknas inte) när du klonar,
annars vill det inte. Det är också viktigt att det inte redan finns
en repository med samma namn i GitHub Desktop.

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