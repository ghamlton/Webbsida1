# Webbsida 1

## Vad är detta för hemsida?  
Denna hemsida är ett skolprojekt som skapades i början av min utbildning inom webbutveckling. Hemsidan består av tre olika delar:
* En startsida (index.html) där jag skriver lite om mig själv och mina intressen
* En sida om min hobby (hobby.html) där jag beskriver mitt intresse med bilder, text, en faktatabell
* En kontaktsida (kontakt.html) med ett kontaktformulär för att nå mig, alterativt min mailadress om man vill maila till mig direkt

## Hur skapades denna hemsida?
Denna hemsida har skapats med **100% HTML** och ingenting annat. I framtiden så kommer den hemsida att byggas på med eventuell CSS och möjligtvis JavaScript. 

## Var du kan hitta hemsidan
I nuläget så är hemsidan uppe här på [GitHub Pages](https://ghamlton.github.io/Webbsida1/) och på [Netlify](https://ghamlton-webbsida1.netlify.app/). 

## Svar på frågor i laboration 2
### Vad är skillnaden mellan git add och git commit?
När du använder _git add_ så lägger du till nya/ändrade filer i s.k staging area. Staging area ligger alla filer som sedan ska committas med _git commit_. _Git commit_ kan beskrivas som en sparad version av ett projekt vid en specifik tidpunkt. Varje commit innehåller ett meddelande som beskriver vilka ändringar som gjordes. 
### Varför använder man branches istället för att jobba direkt i main?
Det finns flera olika anledningar att arbeta i separata branches. En stor anledning är att kunna jobba självständigt från s.k _main_ och kunna experimentera med nya funktioner. Då behöver man inte oroa sig för att förvränga koden i _main_ då man jobbar
### Vad händer rent praktiskt när man gör en merge?
Förenklat så betyder det att man kombinerar ändringarna man gjort i en branch in i en annan branch. Om du har t.ex två branches _dev_ och _main_ så har du också olika tidslinjer av commits på vardera branch. När du t.ex mergear _dev_ in i _main_ så kommer historiken av commits från varje branch att kombineras in i en singulär tidslinje av commits. Se bilden nedanför som visualiserar detta tydligare.
![Git merge diagram](https://dam-cdn.atl.orangelogic.com/AssetLink/d54018nq423762vgh32g4m2o0d4iti3g.png "Diagram av en merge")
### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
### Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
Du exkluderar filer från versionshantering genom att använda en .gitignore fil. Du skriver in filens/filernas namn in i .gitignore, och då ignorar Git de filerna när du gör en commit. 
