# Kapittelprøve 3 – Trekanter og Pytagoras

**Nivå:** Krevende  
**Arbeidstid:** 90 minutter  
**Poeng:** 50 poeng  
**Hjelpemidler:** Skrivesaker og kalkulator

Dette er en krevende prøve. Den tester ikke bare om du kan bruke formler, men om du kan velge metode, kombinere flere ideer, oppdage feil og begrunne matematiske påstander.

**Vis framgangsmåte i alle oppgaver.** Et riktig svar uten forklaring gir ikke nødvendigvis full uttelling. Figurer er ikke nødvendigvis tegnet i målestokk.

## Del A – Presisjon og metodevalg

### Oppgave 3.K.1 – Trekanten som nesten ikke finnes (6 poeng)

To sider i en trekant er 7,2 cm og 11,5 cm. Den tredje siden har et helt antall centimeter.

a) Bestem alle mulige lengder den tredje siden kan ha.

b) En elev hevder at 18 cm ikke er mulig. Forklar presist hvorfor eleven tar feil.

c) Hvor mange mulige heltallige lengder finnes det?

??? note "Løsningsforslag 3.K.1"
    La den ukjente siden være $x$. Trekantulikheten gir

    $$
    11,5-7,2<x<11,5+7,2
    $$

    $$
    4,3<x<18,7
    $$

    Siden $x$ er et helt antall centimeter, er mulighetene

    $$
    \underline{\underline{5,6,7,\ldots,18\text{ cm}}}
    $$

    Det er 14 muligheter. Lengden 18 cm er faktisk mulig fordi $7,2+11,5=18,7>18$. En elev som hevder at 18 cm ikke går, har brukt ulikheten feil.

### Oppgave 3.K.2 – Finn feilen (6 poeng)

En trekant har sidene 8 cm, 15 cm og 17 cm. En elev skriver:

$$
8^2+15^2=17^2
$$

«Trekanten er rettvinklet fordi dette stemmer.»

En annen elev svarer: «Du kan bare bruke Pytagoras hvis du allerede vet at trekanten er rettvinklet.»

Hvem har rett? Vurder begge påstandene, og forklar forskjellen mellom Pytagoras' læresetning og den omvendte Pytagoras-setningen.

??? note "Løsningsforslag 3.K.2"
    Den første eleven har riktig konklusjon, men begrunnelsen må knyttes til den **omvendte Pytagoras-setningen**. Den lengste siden er 17 cm, og

    $$
    8^2+15^2=64+225=289=17^2.
    $$

    Derfor er trekanten rettvinklet.

    Den andre eleven beskriver den vanlige Pytagoras-setningen, som brukes når trekanten allerede er kjent som rettvinklet. Den omvendte setningen brukes motsatt vei: Vi kjenner sidene og undersøker om trekanten er rettvinklet.

    **Konklusjon:** Den første eleven har rett i konklusjonen. Den andre eleven blander sammen de to setningene.

## Del B – Kombiner flere ideer

### Oppgave 3.K.3 – En trekant med en skjult rett vinkel (8 poeng)

Trekant $ABC$ har sidene $AB=13$ cm, $AC=14$ cm og $BC=15$ cm. Høyden fra $A$ treffer siden $BC$ i punktet $D$.

a) Sett $BD=x$ og uttrykk $DC$ ved hjelp av $x$.

b) Bruk Pytagoras i de to rettvinklede trekantene til å lage to likninger.

c) Finn $x$ og høyden $AD$.

d) Finn arealet av trekanten $ABC$.

??? note "Løsningsforslag 3.K.3"
    Siden $BC=15$, får vi

    $$
    DC=15-x.
    $$

    La høyden være $h$. Pytagoras gir

    $$
    x^2+h^2=13^2
    $$

    og

    $$
    (15-x)^2+h^2=14^2.
    $$

    Vi trekker den første likningen fra den andre:

    $$
    (15-x)^2-x^2=14^2-13^2
    $$

    $$
    225-30x=27
    $$

    $$
    x=6,6.
    $$

    Da blir

    $$
    h^2=169-6,6^2=125,44
    $$

    $$
    h=11,2.
    $$

    Arealet er

    $$
    A=\frac{15\cdot11,2}{2}=84.
    $$

    $$
    \underline{\underline{A=84\text{ cm}^2}}
    $$

### Oppgave 3.K.4 – Formlikhet og Pytagoras i samme problem (8 poeng)

En loddrett lyktestolpe kaster en skygge på 8 m. Samtidig står en loddrett pinne på 1,5 m og kaster en skygge på 2 m. Bakken er plan, og solstrålene kan regnes som parallelle.

a) Forklar hvorfor trekantene som dannes, er formlike.

b) Finn høyden på lyktestolpen.

c) Finn avstanden fra toppen av lyktestolpen til enden av skyggen.

d) En elev bruker Pytagoras direkte på høyden 1,5 m og skyggen 2 m for å finne høyden på lyktestolpen. Forklar hvorfor dette ikke er en gyldig framgangsmåte.

??? note "Løsningsforslag 3.K.4"
    a) Begge trekantene har en rett vinkel fordi stolpen og pinnen står loddrett på plan bakke. Vinkelen mellom bakken og solstrålene er lik i begge trekantene. Trekantene er derfor formlike.

    b) Målestokkfaktoren fra den lille trekanten til den store er $8:2=4$.

    $$
    h=1,5\cdot4=6
    $$

    c) Avstanden fra toppen til skyggeenden er hypotenusen:

    $$
    c=\sqrt{6^2+8^2}=\sqrt{100}=10
    $$

    $$
    \underline{\underline{10\text{ m}}}
    $$

    d) Pytagoras på den lille trekanten gir avstanden fra toppen av pinnen til skyggeenden, ikke høyden på lyktestolpen. Først må vi bruke formlikhet for å finne høyden på stolpen.

### Oppgave 3.K.5 – Når en trekant blir umulig (7 poeng)

En rettvinklet trekant har kateter $a$ og $b$ og hypotenus 13 cm. Den ene kateten er 5 cm.

a) Finn den andre kateten.

b) Kateten på 5 cm økes med $d$ cm, mens den andre kateten holdes fast. Skriv et uttrykk for den nye hypotenusen.

c) Hvor stor kan $d$ maksimalt være dersom trekanten fortsatt skal ha en positiv høyde og en positiv hypotenus?

d) Forklar hvorfor hypotenusen blir lengre når $d$ øker, så lenge trekanten eksisterer.

??? note "Løsningsforslag 3.K.5"
    a)

    $$
    b^2=13^2-5^2=169-25=144
    $$

    $$
    b=12\text{ cm}
    $$

    b) Den nye hypotenusen er

    $$
    c'=\sqrt{(5+d)^2+12^2}
    $$

    c) For at trekanten skal ha positiv høyde, må den horisontale kateten være mindre enn hypotenusen:

    $$
    5+d<13
    $$

    Dermed må $d<8$. Det finnes ingen største tillatte verdi dersom $d$ kan være et reelt tall; 8 er grenseverdien, men er ikke tillatt.

    d) Når $d>0$, øker $(5+d)^2$, mens $12^2$ er uendret. Derfor øker kvadratet av hypotenusen, og dermed øker også hypotenusen.

## Del C – Bevis og generalisering

### Oppgave 3.K.6 – Bevis en påstand om formlikhet (9 poeng)

To trekanter er formlike. Forholdet mellom tilsvarende sider fra den lille til den store trekanten er $k$, der $k>0$.

a) En side i den lille trekanten er 4 cm. Hvor lang er den tilsvarende siden i den store trekanten?

b) Forklar hvorfor arealet av den store trekanten er $k^2$ ganger arealet av den lille.

c) En elev sier: «Hvis sidene blir dobbelt så lange, blir arealet dobbelt så stort.» Vis med et generelt resonnement hvorfor eleven tar feil.

??? note "Løsningsforslag 3.K.6"
    a) Den tilsvarende siden er $4k$ cm.

    b) La grunnlinjen og høyden i den lille trekanten være $g$ og $h$. I den store trekanten blir både grunnlinjen og høyden multiplisert med $k$:

    $$
    A_{liten}=\frac{gh}{2}
    $$

    $$
    A_{stor}=\frac{(kg)(kh)}{2}
    =k^2\frac{gh}{2}
    =k^2A_{liten}.
    $$

    c) Når $k=2$, blir arealfaktoren $2^2=4$, ikke 2. Arealet blir fire ganger så stort.

### Oppgave 3.K.7 – Undersøk en påstand (6 poeng)

En elev sier:

«Hvis en trekant har sidene 6 cm, 8 cm og 10 cm, er den alltid rettvinklet, uansett hvordan vi tegner den.»

a) Er påstanden riktig? Begrunn svaret.

b) Hva kan endres når vi tegner trekanten på nytt, og hva kan ikke endres?

c) Forklar forskjellen mellom en matematisk egenskap og hvordan en figur ser ut på arket.

??? note "Løsningsforslag 3.K.7"
    a) Ja. Den lengste siden er 10 cm, og

    $$
    6^2+8^2=36+64=100=10^2.
    $$

    Den omvendte Pytagoras-setningen viser at trekanten er rettvinklet.

    b) Plasseringen og retningen på tegningen kan endres. Sidelengdene og vinklene bestemmes av trekantens form og sidelengder. Trekanten kan roteres eller speilvendes uten at den matematiske egenskapen endres.

    c) En tegning er en representasjon. Den kan være skjev eller ikke tegnet i målestokk. En matematisk begrunnelse bygger på oppgitte egenskaper og setninger, ikke på øyemål.

## Egenkontroll

Før du ser på løsningsforslagene, vurder om du kan:

- bruke trekantulikheten også når sidene ikke er heltall
- skille mellom Pytagoras og den omvendte setningen
- kombinere Pytagoras med algebra
- begrunne formlikhet med vinkler
- forklare hvorfor en metode passer eller ikke passer
- generalisere fra et eksempel til en generell påstand

**Poeng:** 50. Læreren fastsetter eventuell karakter ut fra samlet kompetanse, ikke bare poengsummen.
