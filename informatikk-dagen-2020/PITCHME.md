---?image=img/slide1.jpg

Note:
- vi løser problemer
- gjør hverdagen enklere. Men hvordan? 
- samle informasjon fra ulike steder og vise på samme sted
- gjøre det enklere å finne informasjon eller utføre arbeidsoppgaver
- automatisere manuelle prosesser (automatisk hente inn personinformasjon og
  kontoinformasjon når du søker om lån)
- digitalisere manuelle prosesser (app eller web i stedet for papir)
- ta vekk unødige steg i arbeidsprosesser
- google-websiden: også et system som utviklere har laget
- it's learning
- facebook, tiktok, snapchat, instagram
- mobil, pc, word osv. 
- Men hva gjør vi? Hvordan løser vi problemer? 
- hjelper folk med å forstå og kartlegger prosesser


---?image=img/slide2.jpg

Note:
- lager brukergrensesnitt: feks google: MANGE timer arbeid for noe lite
- brukergrensesnitt handler også om farger, fonter (bokstavtyper), utseende,
  psykologi, biologi og nevrologi (hvordan hjernen virker)
- programmer for mobil, pc osv. 
- det var den synlige delen. Men mye er usynlig for brukere
- igjen: google: lite brukergrensesnitt, enorme systemer i bakkant som finner
  alle websider, tolker innhold, indekserer innhold slik at det er søkbart,
  selve søketjenesten, bilder, video, tekst osv.
- kobler sammen "usynlige" systemer for å samle informasjon fra ulike kilder,
  feks: søke om kredittkort, trenger informasjon om annen kredittgjeld,
  personinformasjon, kjøretøy, boliger mm. 
- Vi lager programmer og systemer ved å skrive kode


---

```java
int computeCost(String beverageName, boolean isStudent, int amount) {
        if (!menu.containsKey(beverageName)) {
            throw new RuntimeException("No such drink exists");
        }

        assertTooManyCocktailsOrdered(beverageName, amount);

        Beverage beverage = menu.get(beverageName);
        int price = beverage.getPrice();

        if (isStudent && beverage.isEligibleForStudentDiscount()) {
            price = calculateStudentPrice(price);
        }
        return price * amount;
    }
}
```

Note:
- kode: instruksjoner som en datamaskin kan tolke, skrevet i et
  programmeringsspråk
- blir til syvende og sist oversatt til 1 og 0
- datamaskinen forstår dette og kan utføre det vi beskriver
- lyst til å prøve å programmere: prøv python eller javascript
- vi koder, men hvor jobber vi?


---?image=img/slide3.jpg

Note:
- offentlig sektor: kommunale tjenester (skoleplass søke/tildele), søknadssystem
  universitet, studielån, skatt, NAV, vann/avløp... 
- bank/finans: penger inn, penger ut, søknad om lån og kreditt, hvordan
  bankkonto virker både for private og bedrifter
- byggebransjen: systemer for å tegne hus, planlegge utnyttelse av råmateriale,
  design og produksjon av feks vinduer.. 
- medier: produsere og streame innhold (lyd, video, bilde, tekst), samle og
  analysere data (valg feks), spotify, netflix, TV2, NRK, youtube.. 
- helse: utveksling av data, lagring av data (feks journal), du får tilgang til
  journal og prøveresultat, samle og vise informasjon, hjelp til kirurgi
  (planlegge og øve på operasjon, hjelp under operasjon osv)
- Passer du til å jobbe innenfor IT? Hvilke egenskaper ser vi etter?


---?image=img/slide4.jpg

Note:
- trenger mange ulike egenskaper
- få har alle
- derfor: samarbeid viktig
- siden vi jobber opp mot mange ulike bransjer og mange ulike typer mennesker,
  trenger vi et stort spekter av folk som har ulike fysiske og psykiske
  egenskaper
- har feks kjempeproblemer med at en ekstremt stor del av IT-miljøet til nå har
  vært dominert av hvite, middelaldrende menn i den vestlige verden. 
- maskinlæringsalgoritmer diskriminerer feks pga språkbruk i dokumenter der
  kvinner og menn omtales ulikt, hvite/ikkevhite omtale ulikt
- vanskelig å se for seg hvordan personer med fysiske eller psykiske
  utfordringer bruker systemer og hvilke behov de har, særlig i offentlig sektor
  er dette viktig
- veldig kreativt yrke, mange som ikke tror det
- nå sitter dere vel alle og tripper: så hvordan kan du studere informatikk, som
  er en vei inn i IT-bransjen?


---?image=img/slide5.jpg

Note:
- generell studiekompetanse og REAL2 og 2 år fordypning i realfag


---?image=img/slide6.jpg

Note:
- fortelle litt om min arbeidsdag før vi åpner for spørsmål
- samarbeid: arbeidsmøter, diskuterer og forteller, tegner, koder sammen, 
- programmerer, enten alene eller med andre
- leter etter informasjon
- leter etter løsninger på problemer
- prøver og feiler
- tenker, alene og med andre


---?image=img/pultenMin.jpg

Note: 
- pulten min
- stor skjerm, kode, behagelig tastatur, tekopp, mulighet for å stå eller sitte


---?image=img/workshop_i_praksis.jpg

Note:
- fra workshop på prosjektet jeg jobber på nå, i trondheim, satt tre dager og
  jobbet sammen for å få oversikt på hva vi skulle begynne å lage
- sette oss inn i hva som skjer når en kredittkortkunde vil reklamere (klage) på
  en kredittkorttransaksjon (feks: blitt svindlet, kjenner ikke igjen
  transaksjon, har ikke fått vare osv.)
- vi skal lage systemer for å håndtere dette
- gjorde ulike øvelser, tegnet, sammenlignet tanker og ideer, begrensninger osv. 



---?image=img/prototyping_i_workshop.jpg

Note:
- vi tegnet opp ideer til brukergrensesnitt for å vise hvordan arbeidsflyt kunne
  være
- vi valgte ut de beste ideene som vi har jobbet videre med


---?color=#146478&image=kantega_logo.svg&size=50%

Note:
- hvor jobber jeg? i et konsulentselskap som heter Kantega
- konsulent betyr: å jobbe for andre bedrifter (noen gjør kort sikt, andre gjør
  langsiktige avtaler over flere år)
- jobbe med veldig ulike ting: feks har jeg jobbet med automatisk, digital
  postutsendelse, NDLA: baksystem
  som håndterer hvilken informasjon som hører til fag og ulike team i fag,
  kredittkortselskap, oljeselskap, grunnforskning, nasjonalbiblioteket
  (innehenting av aviser i digitalt format)
- andre har fast ansettelse i en bedrift og jobber med deres systemer, dyp
  kjennskap til systemet og de problemene systemet skal løse
- tusen takk for meg, spørsmål? 


