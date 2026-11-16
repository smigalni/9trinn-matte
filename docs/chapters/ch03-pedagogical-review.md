# Pedagogisk gjennomgang – kapittel 3

**Dato:** 16. november 2026  
**Gjennomgått versjon:** `feature/curriculum-map-mat01-06`, PR #1, commit `701f4e3a53a4861a9c09ded06c0ddcc58deac327`  
**Dokument:** `docs/chapters/ch03-triangles.md`  
**Status:** Første pedagogiske review – kapittelet er fortsatt et utkast og ikke godkjent.

## Kort konklusjon

Kapittelet har en fornuftig hovedprogresjon: trekantbegreper → sidelengder → Pytagoras → formlikhet → endrede forutsetninger. Det er en god start, og eksemplene har stort sett ryddig matematisk framgangsmåte.

Det er likevel for tidlig å godkjenne kapitlet. Den viktigste svakheten er at M9-04 og særlig M9-05 foreløpig er dekket mer gjennom forklaring og noen få oppgaver enn gjennom en tydelig, trinnvis læringsprosess der elevene selv undersøker, beskriver og argumenterer. Kapitlet trenger også bedre støtte før de mer abstrakte resonnementene.

## Funn – prioritert

### 1. Høy prioritet: bygg opp M9-04 som utforsking, ikke bare som en regel

**Observasjon:** Kapitlet introduserer trekantulikheten og beviser egenskapen om like grunnvinkler i en likebeint trekant. Senere utledes 30°–60°–90°-forholdet ved hjelp av Pytagoras. Dette er relevant innhold, men elevene får få oppgaver der de systematisk undersøker flere trekanttyper og selv formulerer sammenhenger mellom sidelengdene.

**Hvorfor det betyr noe:** Udirs forklaring til M9-04 trekker fram undersøkelser av trekanter som deles i rettvinklede trekanter, 30°–60°–90°-trekanter, likebeinte og likesidede trekanter. Elevene skal utforske, beskrive og argumentere – ikke bare bruke et ferdig utledet sideforhold.

**Anbefalt endring:**
- Legg inn en kort utforskingssekvens før eller rundt bevisene: tegn/mål flere likebeinte trekanter med ulik toppvinkel, og sammenlign sidene og grunnvinklene.
- La elevene undersøke hva som skjer når en likesidet trekant deles av en høyde, før den formelle utledningen.
- Legg inn minst én oppgave der eleven må beskrive et fast sideforhold med egne ord og deretter begrunne hvorfor det gjelder.
- Skill tydelig mellom det elevene kan oppdage ved måling, og det som må bevises.

### 2. Høy prioritet: M9-05 trenger en praktisk «hva hvis?»-situasjon

**Observasjon:** Eksempel 8 og utforskingsoppgaven undersøker hvordan hypotenusen endres når katetene endres. Den algebraiske delen med
`c'^2-c^2=2ad+d^2`
er korrekt når `a>0` og `d>0`, men oppgaven blir raskt abstrakt. Den praktiske dimensjonen i M9-05 er svak.

**Anbefalt endring:**
- Start med en konkret situasjon, for eksempel en stige mot en vegg: Hva skjer med høyden når avstanden fra veggen økes, mens stigens lengde holdes fast?
- Be elevene undersøke med tegning, måling eller en enkel tabell før algebraen introduseres.
- La elevene endre én størrelse om gangen og holde de andre fast.
- Knytt deretter situasjonen til et uttrykk eller en formel, og be eleven forklare hvorfor løsningen endres.
- Behold den nåværende algebraiske oppgaven som en fordypningsoppgave, ikke som første møte med M9-05.

### 3. Høy prioritet: gjør bevisene tilgjengelige og forklar hvilke kongruensargumenter som brukes

**Observasjon:** Beviset for like grunnvinkler bruker at to trekanter er kongruente fordi de har tre par like lange sider. Utledningen av 30°–60°–90°-forholdet sier at to rettvinklede trekanter har samme hypotenus og samme høyde, og derfor er kongruente.

**Risiko:** Dette forutsetter at eleven kjenner og kan bruke relevante kongruenskriterier. Det siste argumentet bruker spesielt hypotenus–katet-kriteriet for rettvinklede trekanter. Hvis dette ikke er etablert i kapittel 2, blir beviset et sprang.

**Anbefalt endring:**
- Kontroller hva kapittel 2 faktisk lærer om kongruens og kongruenskriterier.
- Vis eksplisitt hvilket kriterium som brukes i hvert bevis, eller gi en kort forklaring/repetisjon før det brukes.
- I 30°–60°–90°-utledningen: forklar hvorfor høyden deler grunnlinjen i to like lange deler; ikke la dette framstå som en automatisk egenskap ved en høyde.
- Vurder å gjøre den fullstendige algebraiske utledningen til en tydelig fordypningsdel dersom den er for krevende for mange elever.

### 4. Middels prioritet: forkunnskapssjekken lover repetisjon som ikke er konkretisert

**Observasjon:** Innledningen sier «Hvis noe er vanskelig, bruk repetisjonen før du går videre», men det følger bare en kort repetisjon av rett vinkel, vinkelsum, kvadrering og kvadratrot. Forhold/proporsjoner, enkel algebra og kongruens får ikke tilsvarende støtte.

**Anbefalt endring:**
- Legg til korte minieksempler for forhold og enkel algebra, eller fjern løftet om at alle vanskelige punkter har repetisjon.
- Koble hvert diagnostisk spørsmål til en konkret repetisjonsdel.
- Ikke gjør testen til en port som hindrer eleven i å fortsette.

### 5. Middels prioritet: metodevalget mellom formlikhet og Pytagoras må trenes mer

**Observasjon:** Kapitlet forklarer forskjellen godt, men eleven får få oppgaver der begge metodene kan virke aktuelle og må velge metode ut fra opplysningene.

**Anbefalt endring:**
- Legg inn et par sammenligningsoppgaver der eleven må forklare hvorfor én metode passer bedre.
- Ha minst én oppgave der formlikhet er nødvendig fordi lengder ikke kan måles direkte, og én der Pytagoras er naturlig.
- Unngå at oppgavens ordlyd avslører metoden for tydelig.

### 6. Middels prioritet: oppgaveprogresjon og differensiering

**Observasjon:** A–D-inndelingen er ryddig, men oppgave 14–16 er svært åpne og mangler konkrete kriterier for hva en god besvarelse skal inneholde. Flere oppgaver i A og B er rutineoppgaver, mens spranget til D er stort.

**Anbefalt endring:**
- Legg inn en eller to mellomliggende resonneringsoppgaver før de åpne utforskingene.
- Gi støttepunkter i D-oppgavene: hva skal varieres, hva skal registreres, og hva skal begrunnes?
- For åpne oppgaver: oppgi hva en god løsning bør inneholde, ikke bare ett fasitsvar.
- Vurder å dele oppgave 16 i en grunnoppgave og en videre utforsking.

### 7. Lavere prioritet: presisjon i formuleringer og matematisk språk

- I 3.4 bør forholdet 2:1 knyttes tydelig til hvilken figur som er størst, slik at retningen på målestokken ikke blir uklar.
- I eksempel 5 bør det stå eksplisitt at 13 cm er den lengste siden før den brukes som `c`.
- I oppgave 10 bør elevene få forklare at 13 cm er den lengste siden og at omvendt Pytagoras brukes.
- I oppgave 16 bør det presiseres at grunnlinjen holdes fast og at trekanten konstrueres med de oppgitte vinklene.
- «Sammenhenger mellom sidelengdene» bør knyttes tydelig til både trekantulikheten, likebeinte/likesidede trekanter og det spesielle sideforholdet.

## Matematisk stikkprøvekontroll

Følgende sentrale resonnementer er kontrollert i denne gjennomgangen:

- Trekantulikheten i eksempelet 3, 4 og 8 cm: korrekt avvisning.
- Pytagoras-eksemplene 6–8–10 og 5–12–13: korrekte.
- Finn katet i 5–12–13-eksempelet: korrekt.
- 30°–60°–90°-forholdet (1:\sqrt{3}:2): matematisk korrekt, gitt at kongruensargumentet for høyden er etablert.
- Målestokk 1:50 000 og 3 cm på kartet: 1,5 km, korrekt.
- Skyggeoppgaven: 4,5 m, gitt at bakken er plan og solstrålene kan regnes parallelle.
- Algebraisk sammenligning (c'^2-c^2=2ad+d^2): korrekt for (a>0), (d>0).
- Oppgave 16: de oppgitte tredje vinklene 100°, 90° og 70° er korrekte, og alle tre trekantene er geometrisk mulige.

Dette er en stikkprøve og en gjennomgang av synlige resonnementer, ikke en fullstendig uavhengig kontroll av alle oppgaver og fasitsvar.

## Læreplanvurdering

Den offisielle Udir-siden for MAT01-06 etter 9. trinn støtter tydelig innholdet om:
- praktisk bruk av formlikhet og Pytagoras
- sammenhenger mellom sidelengdene i trekanter
- utforsking av hvordan endrede geometriske forutsetninger påvirker løsninger både praktisk og algebraisk

Udirs forklaringstekster framhever praktiske situasjoner, systematisk variasjon av én størrelse om gangen, og at eleven skal argumentere for hvorfor løsninger endres. Det er særlig dette siste punktet kapittelutkastet bør styrke.

Kilde: https://www.udir.no/lk20/mat01-06/kompetansemaal-og-vurdering/kv1028?lang=nob

## Anbefalt rekkefølge for neste revisjon

1. Revider 3.5 med en praktisk inngang og en gradvis overgang til algebra.
2. Styrk utforskingen av sidelengdeforhold i 3.1–3.3.
3. Kontroller og forklar kongruenskriteriene som bevisene bygger på.
4. Legg inn konkret repetisjon av forhold og enkel algebra.
5. Forbedre metodevalgsoppgaver og støtten til åpne oppgaver.
6. Kjør ny matematisk kontroll av alle oppgaver og løsninger.
7. Be en lærer med erfaring fra 9. trinn vurdere nivå, omfang og progresjon.

## Avgrensning

Denne reviewen endrer ikke selve elevkapitlet. Den er et arbeidsdokument for neste revisjon. Kapitlet skal fortsatt være merket som utkast inntil matematisk kontroll, lærerreview, elevutprøving og visuell/teknisk kontroll er gjennomført.
