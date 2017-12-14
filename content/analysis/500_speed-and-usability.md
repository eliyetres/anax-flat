Speed and usability
==============================================

Urval
---------------------

Jag valde de sidor som jag använde i den tidigare uppgiften. Min första tanke var att välja sociala medier eller webbplatser som skolan använder sig utav men insåg att alla dessa kräver inlogg och inte visar något utan det. Jag använde mig utav Pagespeed för att kolla förslag på optimeringar och Devtools för att sedan räkna ut genomsnitt för sidans laddningstid.

Samtliga sidor laddas vädigt snabbt, även om sidorna använder många bilder.
Sidorna verkar ha hållt sig till att använda jpeg för foton och png till andra typer av bilder. Sidan gör 99 requests.

[metro.se](metro.se)
---------------------

* Pagespeed mobil: 53/100
* Pagespeed desktop: 77/100
* Devtools laddningstid genomsnitt: 2.41s
* Devtools storlek: 638 kb

Metros sida innehåller inte så många bilder eller mycket text verkar inte ha komprimerat varken sina bilder, typsnitt, stylesheets eller scripts, men sidan är den som innehåller minst bytes. Sidan laddar dock inte in så mycket text och bilder som de andra sidorna gör, utan bara det man direkt ser när man kommer in på sidan. När man sedan scrollar neråt så laddas mer information allt eftersom. Sidan gör 115 requests.

[FIGURE src="image/metro.png?w=400&co=8" class="center"] 

[DI.se](DI.se)
---------------------

* Pagespeed mobil: 53/100
* Pagespeed desktop: 69/100
* Devtools laddningstid genomsnitt: 6.42s
* Devtools storlek: 35.8 mb

DI  innehåller en hel del information och när man scrollar neråt så laddas mer. Sidan har redan komprimerat samtliga bilder på hemsidan, men enligt PageSpeed endast bara till viss del (mellan 15-60%) och rekommenderar att de komprimeras mer. Sidan innehåller många script som uppdateras, t.ex. för att visa status för börsmarknad. PageSpeed rekommenderar att komprimera innehållet tillsammans med gzip. Sidan gör även 205 requests så det hade kunnat minska. PageSpeed varnade även för blockerande script som måste laddas före allt annat.

[FIGURE src="image/di.png?w=400&co=8" class="center"] 

[DN.se](DN.se)
---------------------

* Pagespeed mobil: 53/100
* Pagespeed desktop: 67/100
* Devtools laddningstid genomsnitt: 2.41s
* Devtools storlek: 1.3 mb

Sidan för DN innehåller en del bilder, mycket text och scripts. Allt verkar dock delvis vara komprimerat redan, men enligt PageSpeed är det möjligt att kompirmera alla bilder ca 22%. Den varnar för att sidan har 6 blockerande script och att dessa skulle kunnas kompirmeras med 69%.

[FIGURE src="image/dn.se.png?w=400&co=8" class="center"] 

[Länk till stylesheet](img/Data.xlsx)
