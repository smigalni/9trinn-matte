# Kapittel 3: Trekanter, Pytagoras og geometriske undersøkelser

> **Status:** Første faglige utkast – ikke godkjent for publisering  
> **Kompetansemål:** M9-03, M9-04 og M9-05  
> **Forutsetter:** Grunnleggende trekantbegreper, vinkler, forhold og enkel algebra. Nødvendige forkunnskaper repeteres underveis.

## Dette skal du lære

Etter kapitlet skal du kunne:

- beskrive trekanter ved hjelp av sider og vinkler
- undersøke og forklare sammenhenger mellom sidelengder
- bruke Pytagoras i rettvinklede trekanter
- bruke formlikhet og Pytagoras i praktiske situasjoner
- velge og begrunne hvilken metode som passer
- undersøke hvordan en geometrisk løsning endres når forutsetningene endres
- forklare og argumentere for egne løsninger

## Før du begynner

Prøv oppgavene uten hjelpemidler. Hvis noe er vanskelig, bruk repetisjonen før du går videre.

1. Hvor mange grader er summen av vinklene i en trekant?
2. Hva kjennetegner en rett vinkel?
3. Regn ut $6^2$ og $\sqrt{49}$.
4. En tegning er 4 cm lang, mens den virkelige lengden er 8 m. Hvor mange meter svarer 1 cm på tegningen til?
5. Skriv et uttrykk for «tre ganger et tall pluss 2».

**Kort repetisjon:** En rett vinkel er $90^\circ$. Vinkelsummen i en trekant er $180^\circ$. Å kvadrere et tall betyr å multiplisere tallet med seg selv. Kvadratroten av et tall er tallet som ganget med seg selv gir det opprinnelige tallet.

---

## 3.1 Hva vet vi om trekanter?

En trekant har tre sider og tre vinkler. Vi kan beskrive trekanter på flere måter. Noen ganger er det sidene som er viktige, andre ganger vinklene.

### Trekanttyper etter sider

- **Likesidet trekant:** Alle tre sidene er like lange. Alle vinklene er $60^\circ$.
- **Likebeint trekant:** To sider er like lange. Vinklene ved grunnlinjen er like store.
- **Uliksidet trekant:** Alle sidene har forskjellig lengde.

### Trekanttyper etter vinkler

- **Spissvinklet:** Alle vinklene er mindre enn $90^\circ$.
- **Rettvinklet:** Én vinkel er $90^\circ$.
- **Stumpvinklet:** Én vinkel er større enn $90^\circ$.

En trekant kan beskrives både etter sidene og etter vinklene. En likebeint trekant kan for eksempel være spissvinklet eller rettvinklet.

### Vinkelsummen

Vinklene i en trekant har alltid summen

$$
A+B+C=180^\circ
$$

**Eksempel 1**

To vinkler i en trekant er $48^\circ$ og $67^\circ$. Hvor stor er den tredje vinkelen?

Vi vet at vinkelsummen er $180^\circ$:

$$
180^\circ-48^\circ-67^\circ=65^\circ
$$

Den siste vinkelen er $65^\circ$.

### Utforsk: Likebeinte trekanter

Tegn en likebeint trekant. Mål vinklene ved grunnlinjen. Tegn en ny likebeint trekant med en annen form og mål igjen.

- Hva legger du merke til?
- Hvorfor må vinklene ved grunnlinjen være like store?
- Kan du forklare sammenhengen uten å bare vise til måling?

**Husk:** Måling kan hjelpe oss å oppdage et mønster. For å være sikre på at en sammenheng alltid gjelder, trenger vi et matematisk argument.

---

## 3.2 Sammenhenger mellom sidelengdene

I en trekant henger sidelengdene sammen. Det er ikke mulig å velge tre vilkårlige lengder og alltid få en trekant.

### Trekantulikheten

Summen av lengdene til to sider må være større enn lengden til den tredje siden.

Hvis sidene er $a$, $b$ og $c$, må alle disse ulikhetene være oppfylt:

$$
a+b>c,\qquad a+c>b,\qquad b+c>a
$$

**Eksempel 2**

Kan vi lage en trekant med sidene 3 cm, 4 cm og 8 cm?

Vi undersøker de to korteste sidene:

$$
3+4=7
$$

Siden $7$ ikke er større enn $8$, kan sidene ikke danne en trekant.

### Særlige trekantforhold

Noen trekanter har så regelmessige vinkler at vi kan finne bestemte forhold mellom sidene.

I en likesidet trekant er alle vinklene $60^\circ$. Hvis vi tegner høyden fra toppen, deler høyden trekanten i to like rettvinklede trekanter.

Da får vi en rettvinklet trekant med vinklene $30^\circ$, $60^\circ$ og $90^\circ$.

Hvis den opprinnelige likesidede trekanten har sidelengde $2a$, blir den korteste kateten $a$, og hypotenusen er $2a$. Lengden av den andre kateten begrunner vi med Pytagoras i neste del av kapitlet.

Dermed er sideforholdet

$$
1:\sqrt{3}:2
$$

Når vi har begrunnet lengden av den lengste kateten, får vi sideforholdet $1:\sqrt{3}:2$. Dette gjelder for alle rettvinklede trekanter med vinklene $30^\circ$, $60^\circ$ og $90^\circ$.

**Eksempel 3**

En rettvinklet trekant har vinklene $30^\circ$, $60^\circ$ og $90^\circ$. Hypotenusen er 10 cm. Finn de to katetene.

Forholdet er $1:\sqrt{3}:2$. Hypotenusen svarer til 2 deler. Én del er derfor

$$
10:2=5
$$

Katetene er

$$
5\text{ cm}\quad\text{og}\quad 5\sqrt{3}\text{ cm}
$$

Den lengste kateten er omtrent $8{,}66$ cm.

**Viktig:** Ikke bruk dette sideforholdet på en vilkårlig rettvinklet trekant. Det gjelder bare når vinklene er $30^\circ$, $60^\circ$ og $90^\circ$.

---

## 3.3 Pytagoras' læresetning

Pytagoras' læresetning beskriver sammenhengen mellom sidene i en rettvinklet trekant.

Siden som ligger mot den rette vinkelen, kalles **hypotenusen**. De to andre sidene kalles **kateter**.

Hvis katetene er $a$ og $b$, og hypotenusen er $c$, gjelder:

$$
a^2+b^2=c^2
$$

Dette gjelder bare for rettvinklede trekanter.

### Hvorfor virker læresetningen?

Hvis vi tegner et kvadrat på hver side i en rettvinklet trekant, er arealet av kvadratet på hypotenusen lik summen av arealene av kvadratene på katetene.

Det gir sammenhengen

$$
a^2+b^2=c^2
$$

![En rettvinklet trekant med kvadrater på katetene og hypotenusen.](../images/pythagoras-areas.svg)

*Figuren viser arealene på de tre kvadratene. Summen av arealene på katetene er lik arealet på kvadratet på hypotenusen.*

### Eksempel 4 – Finn hypotenusen

En rettvinklet trekant har kateter på 6 cm og 8 cm. Hvor lang er hypotenusen?

Vi bruker Pytagoras:

$$
6^2+8^2=c^2
$$

$$
36+64=c^2
$$

$$
100=c^2
$$

Vi tar kvadratroten:

$$
c=\sqrt{100}=10
$$

Hypotenusen er 10 cm.

### Eksempel 5 – Finn en katet

En rettvinklet trekant har hypotenus 13 cm og én katet 5 cm. Finn den andre kateten.

Vi setter inn:

$$
5^2+b^2=13^2
$$

$$
25+b^2=169
$$

$$
b^2=169-25=144
$$

$$
b=\sqrt{144}=12
$$

Den andre kateten er 12 cm.

Vi bruker den positive kvadratroten fordi en sidelengde må være positiv.

### Kan vi kontrollere om en trekant er rettvinklet?

Ja. Hvis sidene er $a$, $b$ og $c$, der $c$ er den lengste siden, kan vi undersøke om

$$
a^2+b^2=c^2
$$

**Eksempel 6**

En trekant har sidene 5 cm, 12 cm og 13 cm. Er trekanten rettvinklet?

$$
5^2+12^2=25+144=169
$$

Og

$$
13^2=169
$$

Sammenhengen stemmer. Trekanten er rettvinklet.

### Hvorfor er sideforholdet i en 30°–60°–90°-trekant 1 : √3 : 2?

Vi kan nå begrunne forholdet vi undersøkte i 3.2. Tenk på en likesidet trekant med sidelengde $2a$. Høyden deler trekanten i to rettvinklede trekanter. Den korteste kateten er $a$, og hypotenusen er $2a$.

La den lengste kateten være $h$. Med Pytagoras får vi

$
a^2+h^2=(2a)^2
$

$
h^2=4a^2-a^2=3a^2
$

Siden en sidelengde er positiv, er

$
h=a\sqrt{3}
$

Sidene i den rettvinklede trekanten er altså $a$, $a\sqrt{3}$ og $2a$. Når vi deler alle sidene på $a$, får vi forholdet

$
1:\sqrt{3}:2
$

### Vanlige feil

- Å bruke Pytagoras i en trekant som ikke er rettvinklet.
- Å bruke en av katetene som hypotenus.
- Å glemme å ta kvadratroten når vi finner en sidelengde.
- Å legge sammen sidene i stedet for kvadratene av sidene.

---

## 3.4 Formlikhet i praktiske situasjoner

To figurer er formlike når de har samme form, men ikke nødvendigvis samme størrelse. Tilsvarende vinkler er like store, og forholdet mellom tilsvarende sider er konstant.

Hvis en side i den ene figuren er dobbelt så lang som den tilsvarende siden i den andre, er målestokken mellom figurene 2:1.

**Eksempel 7 – Målestokk**

På et kart er avstanden mellom to steder 3 cm. Kartet har målestokk 1:50 000. Hvor langt er det i virkeligheten?

1 cm på kartet svarer til 50 000 cm i virkeligheten.

$$
3\cdot 50\,000=150\,000\text{ cm}
$$

Vi gjør om til meter:

$$
150\,000\text{ cm}=1\,500\text{ m}=1{,}5\text{ km}
$$

Avstanden er 1,5 km.

### Når bruker vi formlikhet, og når bruker vi Pytagoras?

- Bruk **formlikhet** når figurer har samme form og vi kjenner forholdet mellom tilsvarende sider.
- Bruk **Pytagoras** når vi har en rettvinklet trekant og kjenner to av sidene.

Noen problemer kan løses med begge metoder. Da må vi undersøke hvilken informasjon vi har, og hvilken metode som gir den tydeligste løsningen.

![To formlike trekanter med tilsvarende vinkler og sidelengder markert.](../images/similar-triangles.svg)

*De tilsvarende vinklene er like store, og forholdet mellom tilsvarende sider er det samme.*

---

## 3.5 Hva hvis vi endrer forutsetningene?

I matematikk kan vi undersøke hva som skjer når vi endrer én opplysning om gangen. Dette kalles å utforske en problemstilling.

### Eksempel 8 – Hva skjer med hypotenusen?

En rettvinklet trekant har kateter $a=3$ og $b=4$.

$$
c=\sqrt{3^2+4^2}=5
$$

Hva skjer hvis vi dobler begge katetene?

Da blir katetene 6 og 8:

$$
c=\sqrt{6^2+8^2}
=\sqrt{36+64}
=10
$$

Hypotenusen blir også dobbelt så lang.

Dette er ikke tilfeldig. Når alle sidene i en trekant forstørres med samme faktor, blir trekanten formlik med den opprinnelige.

### Utforsk selv

En rettvinklet trekant har katetene $a$ og $b$.

1. Velg noen verdier for $a$ og $b$.
2. Regn ut hypotenusen.
3. Dobbel begge katetene. Hva skjer med hypotenusen?
4. Dobbel bare den ene kateten. Hva skjer nå?
5. Formuler en regel med egne ord.
6. Forklar hvorfor regelen stemmer ved hjelp av Pytagoras.
7. Hvis bare kateten $a$ økes til $a+d$, mens $b$ er uendret, blir den nye hypotenusen $c'=\sqrt{(a+d)^2+b^2}$. Sammenlign $c'$ med den opprinnelige hypotenusen. Forklar hvorfor hypotenusen øker når $d>0$.

Når du utforsker, skal du skille mellom det du observerer i eksemplene, og det du kan begrunne matematisk.

---

## 3.6 Blandede oppgaver

### A – Kom i gang

1. En trekant har vinklene $42^\circ$ og $71^\circ$. Finn den siste vinkelen.
2. Kan sidene 4 cm, 5 cm og 10 cm danne en trekant? Begrunn.
3. Finn hypotenusen når katetene er 9 cm og 12 cm.
4. Finn den ukjente kateten når hypotenusen er 10 cm og den andre kateten er 6 cm.
5. En tegning har målestokk 1:100. Hvor lang er en vegg i virkeligheten hvis den er 7 cm på tegningen?

### B – Bruk kunnskapen

6. En stige står 3 m fra en vegg. Stigen når 4 m opp på veggen. Hvor lang er stigen?
7. En rettvinklet trekant har sidene 7 cm, 24 cm og 25 cm. Undersøk om den er rettvinklet.
8. En modell er formlik med en bygning. Modellen er 40 cm høy, mens bygningen er 20 m høy. Hvor mange ganger større er bygningen enn modellen?
9. Et tre kaster en skygge på 6 m. En pinne som er 1,5 m høy, kaster samtidig en skygge på 2 m. Bruk formlikhet til å finne høyden på treet. Forklar hvilke forutsetninger du bruker.

### C – Tenk og begrunn

10. En elev sier: «Hvis tre sider i en trekant er 5 cm, 12 cm og 13 cm, må trekanten være rettvinklet.» Forklar hvorfor dette stemmer.
11. En annen elev bruker Pytagoras på en trekant med sidene 5 cm, 6 cm og 7 cm. Forklar hvorfor metoden ikke kan brukes slik.
12. En rettvinklet trekant har hypotenus 10 cm. Kan katetene være 6 cm og 8 cm? Begrunn.
13. Beskriv en praktisk situasjon der formlikhet er en bedre metode enn Pytagoras.

### D – Utforsk

14. Lag tre ulike rettvinklede trekanter. Undersøk hvordan hypotenusen endres når begge katetene økes med samme faktor.
15. Undersøk hvilke heltallige sidelengder som kan gi en rettvinklet trekant. Finn minst tre eksempler.
16. Tegn en trekant der grunnlinjen er 8 cm og vinkelen ved høyre endepunkt er 50°. Varier vinkelen ved venstre endepunkt fra 30° til 40° og 60°. Tegn trekantene og undersøk hvordan den tredje vinkelen og sidene endres. Hvilke vinkler er mulige, og hvorfor?

---

## Oppsummering

- Vinkelsummen i en trekant er $180^\circ$.
- Summen av to sider i en trekant må være større enn den tredje siden.
- Pytagoras gjelder bare i rettvinklede trekanter: $a^2+b^2=c^2$.
- Hypotenusen ligger mot den rette vinkelen og er den lengste siden.
- Formlikhet betyr samme form og et konstant forhold mellom tilsvarende sider.
- Når vi utforsker «hva hvis?», bør vi endre én forutsetning om gangen og begrunne det vi finner.

## Løsningsforslag

1. $180^\circ-42^\circ-71^\circ=67^\circ$.
2. Nei. $4+5=9$, som er mindre enn 10.
3. $c=\sqrt{9^2+12^2}=\sqrt{225}=15$ cm.
4. $b=\sqrt{10^2-6^2}=\sqrt{64}=8$ cm.
5. $7\cdot100=700$ cm = 7 m.
6. $c=\sqrt{3^2+4^2}=5$ m.
7. $7^2+24^2=49+576=625=25^2$. Ja.
8. 20 m = 2000 cm. $2000:40=50$. Bygningen er 50 ganger høyere.
9. Forholdet mellom høyde og skygge er likt: $h/6=1{,}5/2$. Dermed $h=4{,}5$ m. Vi antar at solstrålene er parallelle og at bakken er plan.
10. Fordi $5^2+12^2=13^2$. Den lengste siden er 13 cm.
11. Trekanten er ikke rettvinklet: $5^2+6^2=61$, mens $7^2=49$.
12. Ja. $6^2+8^2=36+64=100=10^2$.
13. Eksempel: å finne høyden på et tre ved å sammenligne skygger. Det er nødvendig å forklare at trekantene er formlike.
14. Når begge katetene ganges med en faktor $k$, blir hypotenusen også ganget med $k$: $c'=\sqrt{(ka)^2+(kb)^2}=k\sqrt{a^2+b^2}=kc$ for $k>0$.
15. Eksempler er $3$–$4$–$5$, $5$–$12$–$13$ og $8$–$15$–$17$. I hvert tilfelle er summen av kvadratene av de to korteste sidene lik kvadratet av den lengste.
16. Den tredje vinkelen blir henholdsvis $100^\circ$, $90^\circ$ og $70^\circ$. Alle tre trekantene er mulige fordi vinkelsummen er $180^\circ$ og alle vinklene er positive. Sidene endrer lengde selv om grunnlinjen er fast. Flere tegninger eller en konstruksjon kan brukes til å undersøke mønsteret.
I utforskingsoppgave 3.5 nr. 7 kan eleven sammenligne $c'^2=(a+d)^2+b^2$ med $c^2=a^2+b^2$. Differansen er $2ad+d^2$, som er positiv når $a>0$ og $d>0$. Derfor er $c'>c$.

---

## Faglig kontroll – foreløpig

Dette er et førsteutkast. Det er ikke godkjent for publisering. Før godkjenning må vi blant annet:
- kontrollere at alle delene dekker kompetansemålene M9-03, M9-04 og M9-05 presist
- kontrollere at omfang og nivå på 30°–60°–90°-forholdet er riktig for målgruppen
- kvalitetssikre alle figurer, som foreløpig bare er beskrevet med figurinstruksjoner
- kontrollere oppgave 9 og alle åpne utforskingsoppgaver med lærer
- gjennomføre uavhengig matematisk kontroll og elev-/lærerutprøving
