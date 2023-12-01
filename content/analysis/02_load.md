---
Title: Laddning
Description: Analysing the loading.
---
Laddning
=======================

Denna uppgift gick ut på att analysera tre olika sajters laddnings tid, datastorlek och sidsnabbhet.

Urval
-----------------------

Som uppföljning på den förra uppgiften ville jag se hur samma webbsajter presterade laddnings mässigt. Av särskilt intresse då jag var nöjd med utseendet på samtliga.<br>
skk.se, hundstallet.se och hundens.se fick alltså återigen min uppmärksamhet.

Metod
-----------------------

De verktyg jag använde mig av var Google Pagespeed samt devtools-> network i mozillas firefox.
Google gav mig resultat för både mobil och dator. 
I firefox tog jag alla värden tre gånger, med shift+ctrl+r, och räknade ut medel. Resultaten noterades i google sheets och finns tillgängliga nedan. 

Resultat
-----------------------

###Google Pagespeed

| Sajt | Version | SpeedIndex | Prestanda |
| ------------ | ------------ | ------------ | ------------ |
| skk.se | Dator | 2,9s | 70 |
| skk.se | Mobil | 10,3s | 38 |

Noterar att laddningen på dator kan anses acceptabel medan mobilt var det sämre. 

<br>

| Sajt | Version | SpeedIndex | Prestanda |
| ------------ | ------------ | ------------ | ------------ |
| hundstallet.se | Dator | 1,3s | 96 |
| hundstallet.se | Mobil | 4,0s | 52 |

Bra på dator och acceptabelt på mobil.

<br>

| Sajt | Version | SpeedIndex | Prestanda |
| ------------ | ------------ | ------------ | ------------ |
| hundens.se | Dator | 2,7s | 77 |
| hundens.se | Mobil | 6,9s | 60 |

Acceptabelt på både dator och mobil.

<br>

<div class="embed-container">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRZAZdE_VnUwrPuHj7oxv5T5KCBdWt29w4C11ncBA9ZKmKhgt5wP2vfVpICmDsK1Jv-OCgf7NgqIYA1/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" title="youtubeFrame"></iframe>
</div>

| Skärmdump skk.se |
| ------------ | 
| ![skk.se screen-capture](%base_url%?image/skk-500.jpg) |

<br>

| Skärmdump hundstallet.se |
| ------------ | 
| ![hundstallet.se screen-capture](%base_url%?image/hundstallet-500.jpg) |

<br>

| Skärmdump hundens.se |
| ------------ | 
| ![hundens.se screen-capture](%base_url%?image/hundens-500.jpg) |

<br>

Både hundstallet.se och hundens.se var vad jag uppfattar statiska. I princip samma data laddades in varje gång.
Skk.se däremot skiljde sig lite med olika begäran från gång till gång. En annan bild visade sig vid en av omladdningarna bland annat. Just skk.se utmärkte sig även med dålig prestanda mobilt.

Analys
-----------------------

Oavsett resultaten är jag mer än nöjd med hur samtliga sidor laddades in och åskådliggjordes i min webbläsare. Då jag bor en bit ut på landet där det finns en lång historik med långsam uppkoppling är några sekunders väntan inget jag lägger märke till. 
Men även om jag tittar på alla mätvärden är jag nöjd. Jämfört med andra sajter rör det sig om små datamängder som överförs. Belastningen på miljön måste anses vara nästintill obefintlig. 
Laddnings tiden det tog kunde givetvis varit bättre och då speciellt mobilt på skk.se.

Om jag ändå ska komma med några tips om vad som kan förbättras får jag ta hjälp av Pagespeed insights rapporterna.<br>
skk.se har inte alt text på samtliga bilder och serverns svarstid borde förbättras. De bilder som inte syns kan laddas in senare.

hundstallet.se borde använda bilder med rätt storlek samt se till att alt text finns på samtliga bilder.

hundens.se har inte width och height på bilderna.

Som vinnare får jag utse hundstallet.se som fick på det hela bäst resultat. Men personligen tycker jag skillnaden sajterna emellan är så liten att en ranking är onödig.<br>
Gränsen för acceptabel laddning går nog vid 8-10s får jag nog säga.  


Referenser
-----------------------


Övrigt
-----------------------

Rapportförfattare: Filip Wretenby
