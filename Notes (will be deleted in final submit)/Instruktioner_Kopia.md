
Amandas Notes (Hela mappen skall tas bort i final version):

Inlämningsuppgift: Kundprojekt

I denna inlämning ska ni utgå från en s.k. "brief" från en kund, och ta fram en webbplats utifrån en given design.
One-pager -> Sidan ska vara en s.k. "onepager", dvs. du ska bara scrolla upp och ner på sidan för att komma till sida 2. Du ska inte skapa nya HTML-filer för respektive sida.
-------------------------------------------------------

Brief/bakgrund
Du har precis fått jobb på webbyrån Justin Time AB. Byråns kund Kantarella Löwenskog har gett dig i uppdrag att ta fram en webbplats åt hennes nya företag, 
och webbplatsens design tas fram av kunden själv. 🤦 
Kantarella har precis blivit klar med sitt designarbete och tagit semester, liksom byråns projektledare Karin, så det är ju just typiskt. 
Du får helt enkelt improvisera på de bitar som är otydliga i briefen angående designen.

Brief: 
Hej! 
Kul att vi äntligen är igång med projektet. Jag har lagt bilder och resurser i mappen som jag bifogar, 
du hittar det i repot som vår utvecklare mallat. Toppen om sidan kan vara responsiv.
Färgkoden till den gröna färgen är 100%, 0%, 78%, 0% och den gula 0%, 5%, 79%, 0%.
Formulärets cancel-knapp ska ha färgen 263°, 100%, 73%.

Jag vill att när man för musen över salladsbilden så ska pilen åka lite neråt. 
Men inte "hoppa" utan det ska vara en smooth rörelse. Sen när man tar bort musen så åker pilen tillbaka. 
Lite snappy sådär, inget jättelångsamt. Men inte för fort heller så man inte hinner se.
Vi vill ha lite dynamisk rubbe-effekt så toppen om texten på huvudrubben kan ligga omlott. 
Du ser på skissen där det står "chickpeas".

Typsnittet är Jockey One. Du kan säkert hitta det själv. 
Det andra typsnittet är Roboto Condensed.

På menyn vore det snyggt om alla balkarna rörde sig lite i sidled 
när man för musen över dem, ett par pixlar bara.
Fint om menyn kan animeras till en stäng-ikon när menyn öppnas.

Sorry för tight deadline men du vet hur kunder är! 
Bråttom bråttom. Lycka till och happy halloween va!
Hälsningar Karin 

PS. Kundens kompanjon kör webben utan CSS så kolla att sidan ser schysst ut även utan CSS, du vet - läsbar. 
Och kolla så det går att tabba å sånt. Ja du vet, du har ju koll på det där med tillgänglighet. 

PS2. Vänstersidans titel/meny ska följa med på sidan när man scrollar! 
Kan du lösa det? Också bra om den öppna menyn alltid ligger fixerad. Vi hörs!
---------------------------------------------------------

Notera

1. Länkarna i menyn ska inte leda någonstans. Du behöver inte kunna stänga menyn när du klickat på en länk (bara via menyknappen).
2. Du behöver inte kunna stänga cookie-texten.
3. Du behöver inte lägga in något JavaScript på sidan.
4. Sidan ska vara en "onepager", du ska inte ha flera sidor. Dvs. första sidan täcker upp hela skärmens höjd på desktop. Scrollar du, dyker textsidan upp.
5. När man klickar på "Explore menu" så ska sidan åka ner till menyn.

----------------------------------------------------------

Bryt ner uppgiften i en arbetsgång, och strukturera upp informationen du har från briefen. Du måste inte läsa en grötig text gång på gång, men såhär kan det se ut när man får en överlämning från en kund.
Ibland saknas det information, t.ex. startsidan på mobilen. Titta på resurserna du har, och dra slutsatser av hur den kan tänkas se ut.
😌 Ta ett djupt andetag, gör en checklista & don't panic!

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------------------


Checklista - För dagen: 
* Skriv ner instruktioner (x)
* Skapa checklistor, kan fyllas på i ett senare skede (x)
* Lektion kl. 13.00 ()

* Skriv ner semantiska taggar och dess specar ()
* Se över layout, rita boxar i paint på biderna, spara under Antecknignar-mappen ()
* Börja på HTML skelett på vägen hem med bara div ()
* Byt alla div till lämplig semantiskt element - se lista ()
* Skriv in ()


--------------------------------------------------------------------------------------------------



Checklista HTML:
1. Skelett - Commit ()
2. Fyll i siffror i textblock för att hålla ordning på ordning ()
3. Bilder, vilka ska kallas i html? Lägg in dem, srcset! - Commit ()
4. Bilder, alt text + sizes check - Commit ()
---------------- Efter mobile CSS ----------------------- 
5. Byt till riktigt text i innehåll - Commit 
    (risk för att någon tagg försvinner om man är för snabb, bra med backup) ()
6. META taggar, se förra uppgiften, prata med Matthias - Commit ()
7. Validera för att hitta fel ()
8. Tillgänglighet - Lighthouse () 



--------------------------------------------------------------------------------------------------


Checklista CSS:
Start: 
1. Box reset 
2. Vilka styles är övergripande på sidan, group selectors?
 * Fonts - style + färg (Jockey One + Roboto Condensed) - ladda in i CSS?
    (Färgkoden 
     Gröna färgen är 100%, 0%, 78%, 0%.
     Den gula 0%, 5%, 79%, 0%. 
     Formulärets cancel-knapp ska ha färgen 263°, 100%, 73%.)
 * Bakgrundsfärg
 * 12 collumn grid att placera delar i? - Kolla upp nogrannare 
 * Padding för hela sida?

Övrigt från brief: 
* Dynamisk rubbe-effekt så toppen om texten på huvudrubben kan ligga omlott. Du ser på skissen där det står "chickpeas".
* Vänstersidans titel/meny ska följa med på sidan när man scrollar! Också bra om den öppna menyn alltid ligger fixerad. Vi hörs!

----------Mobil-----------
Ta ett parti i taget, inte en hel sida! 

1. Lägg borders på alla element för att kunna skilja dem åt lättare ()
2. Block eller flex? ()
3. Storlek och placering? ()
4. Bakgrund och borders? ()
5. Bilder? ()
6. Fontstorlek och font-färg i behov av edit? ()
7. Hover effekter? () 
8. Klick effekter? ()



---------------------------------------------------------------------------------------------------------------------------------------------------------------


CSS media querys 

----------Mobil Landscape -----------
1. Storlek? - @media screen and (min-width: 000 px) - () 
2. Body, skilnader: ()  
3. Sida 1, skillnader: () 
4. Sida 2, skillnader: ()
5. Sida 3, skillnader: ()
6. Sida 4, skillnader: ()

---------Padda--------------
1. Storlek? - @media screen and (min-width: 000 px) - () 
2. Body, skilnader: ()  
3. Sida 1, skillnader: () 
4. Sida 2, skillnader: ()
5. Sida 3, skillnader: ()
6. Sida 4, skillnader: ()

---------Desktop--------------
1. Storlek? - @media screen and (min-width: 000 px) - () 
2. Body, skilnader: ()  
3. Sida 1, skillnader: ()
    *När man för musen över salladsbilden så ska pilen åka lite neråt. (Hover effekt på img, smooth rörelse)
4. Sida 2, skillnader: ()
5. Sida 3, skillnader: ()
6. Sida 4, skillnader: ()
    *På menyn vore det snyggt om alla balkarna rörde sig lite i sidled när man för musen över dem, ett par pixlar bara.
    *Fint om menyn kan animeras till en stäng-ikon när menyn öppnas.



----------------------------------------------------------------------------------------------------------------------------------------


Checklista full project - Workflow: 
* För över instruktioner till ReadME så du kan jobba utan internet access. (X)
* Se alla videos och preppa inställningar för Compiler pre-tågresa hem. ()
* Spalta upp i vilken ordning saker bör göras () 

* Skelett på HTML + Kom fram till bra namngivningsprincip för classer som följer ett mönster för att lättare komma ihåg - Commit ()
* Lägg borders på alla divs + semantiska element i CSS för lättare hantering - Commit ()

* Mobile first - Böja anpassa innehåller till mobil, gör färdigt detta helt först - Commit x 3, en för varje sida ()
* Validera HTML och CSS för att reda nu rätta till fel = mindre att göra sen ()

--------Checka med klasskamrater, få feedback och jämnför notes---------------------

* @media för de olika screen sizes, lägg i botten på CSS, lägg i samma ordning som "basic" CSS för lättare editing framöver (Commit x 2, en för varje screen) ()
* Validera HTML och CSS ()
* Går det att tabba mm om man stänger av CSS? ()
* Gå igenom kod, kan jag korta ner den? 
    * Finns dubletter?
    * Kan man skriva om? Ex border-witdh + border-style + border-color => border: witdh style color, som en tag. 
* Läs igenom hela checklistan, dubbelkolla all HTML och CSS mot brief 2 ggr med paus emellan, gärna sömn + mat ()

--------Checka med klasskamrater, få feedback och jämnför notes---------------------

* Validera HTML och CSS - Skapa PDF för inlämning ()
* Ta screenshots på alla screen sizes i samtliga webbläsare (Chrome + Edge + Firefox + -Safari- + Brave) ()
* Tillgänglighetsanalys - Lighthouse, Screenshot()
* Pusha sista gång till GitHub()
* Lägg upp i It'sLearning()