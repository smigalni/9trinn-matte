# Fagspesifikke standarder – 9trinn-matte

Dette dokumentet supplerer de felles standardene i [math-platform](https://github.com/smigalni/math-platform). Det skal ikke kopiere eller erstatte felles pedagogiske, tekniske eller visuelle regler.

## Læreplan og nivå

- Gjeldende grunnlag er MAT01-06, som gjelder fra 1. august 2026.
- Alle 11 kompetansemål etter 9. trinn skal ha sporbar dekning.
- Kompetansemål etter 8. trinn brukes til å identifisere forkunnskaper og behov for repetisjon.
- Kompetansemål etter 10. trinn brukes til å sikre progresjon, men 10.-trinnsstoff skal ikke automatisk forskutteres.
- Udirs forklaringstekster til kompetansemålene skal leses når et mål planlegges eller skrives.
- Skill tydelig mellom Udirs ordlyd, redaksjonell tolkning og forslag til innholdsstruktur.

## Språk og matematisk kommunikasjon

- Bruk klart, naturlig norsk bokmål.
- Forklar fagbegreper før de brukes i oppgaver.
- Bruk konsekvent notasjon og navngiving av figurer, sider, vinkler, variabler og enheter.
- Elevene skal få øve på å beskrive, begrunne og argumentere – ikke bare regne ut svar.
- Praktiske oppgaver skal ha realistiske forutsetninger og svar som kan tolkes i konteksten.

## Innholdsdesign

- Elevboka skal kunne brukes uten innlogging, AI eller digitale spesialverktøy.
- Digitalt innhold skal fungere på mobil, nettbrett og PC.
- Oppgaver og figurer skal også fungere ved utskrift i svart-hvitt.
- Ikke bruk farge som eneste bærer av matematisk informasjon.
- Repetisjon av forkunnskaper legges inn der den trengs, med korte forklaringer og oppgaver.
- Oppgaveprogresjon skal variere mellom regneferdighet, anvendelse, metodevalg, resonnering og utforsking.
- Vanskelighet skal ikke bare økes ved større tall eller mer regning.

## Geometri

- Figurer skal være matematisk konsistente og ha tydelige etiketter.
- Ikke la tegningen antyde at en lengde eller vinkel er gitt dersom den ikke er oppgitt.
- Oppgi når en figur ikke er tegnet i målestokk hvis det har betydning.
- Ved formlikhet skal samsvar mellom tilsvarende sider/vinkler være tydelig.
- Ved Pytagoras skal hypotenusen identifiseres eksplisitt når det er nødvendig.
- Bruk både visuelle undersøkelser og algebraiske begrunnelser der kompetansemålet krever det.

## Statistikk og sannsynlighet

- Bruk egne eller reelle datasett med tydelig kilde og lovlig gjenbruk.
- Skill mellom gjennomsnitt, median, typetall og variasjonsbredde.
- Oppgaver skal undersøke hvordan valg av skala, utvalg og presentasjon kan påvirke tolkning.
- Sannsynlighetsoppgaver skal skille mellom teoretisk sannsynlighet, observerte frekvenser og simulerte resultater.

## Programmering

- Programmeringsinnholdet skal støtte kompetansemålet etter 9. trinn om å simulere tilfeldige forsøk.
- Ikke framstill tekstbasert Python som et eksplisitt kompetansemål etter 9. trinn; målet om å lese og forklare Python-kode ligger etter 10. trinn.
- Forklar algoritmen og sammenhengen med forsøket før eller samtidig med koden.
- Elevene skal kunne forklare hva programmet simulerer, hvordan gjentakelser brukes, og hvordan resultatene tolkes.
- Bruk et programmeringsmiljø som kan velges etter pilot og lærerinnspill; ikke lås teknologien før behovet er vurdert.

## Lærerressurser og AI-generert innhold

- Lærerressurser er et separat produktområde fra den åpne elevboka.
- AI-genererte oppgaver og løsninger er utkast inntil lærer har gjennomgått og godkjent dem.
- Lærer skal kunne redigere, fjerne og regenerere innhold før deling eller utskrift.
- Godkjent redaksjonelt bokinnhold skal holdes adskilt fra lærerprodusert og ikke-godkjent AI-innhold.


## Kapittelarkitektur og sidemønster – obligatorisk

- Bruk kapittel 3 i R1-boken (`smigalni/matte`) som strukturell referanse, ikke bare som visuell inspirasjon.
- Hvert nummererte delkapittel skal være en egen Markdown-fil og en egen oppføring under kapittelet i navigasjonen. Ikke samle hele kapittel 3.x i én lang Markdown-side.
- Ha en egen oversiktsside for kapitlet med kort introduksjon, læringsmål, forkunnskaps-/inngangssjekk og lenker til delkapitlene. Oversiktssiden skal ikke erstatte delkapittelsidene.
- Bruk hierarkisk navigasjon: kapittel som overordnet gruppe, deretter oversikt og nummererte delkapitler i riktig rekkefølge. Blandede oppgaver, kapitteltest og muntlig forberedelse skal være egne sider når de inngår i kapittelplanen.
- Hver delkapittelside skal ha én tydelig H1-overskrift med nummer og tittel. Bygg siden med en kort faglig inngang, trinnvis teori i logiske underoverskrifter, relevante figurer/undersøkelser, tydelige regelbokser der det er nødvendig, gjennomarbeidede eksempler, lokale oppgaver og fasit rett etter hver oppgave. Bruk læringsmål eller kort repetisjon når det er relevant for delkapitlet.
- Ikke tving inn en regelboks eller et eksempel der fagstoffet ikke trenger det. Men når en regel eller et fullstendig regneeksempel finnes, skal det bruke de etablerte boksene.
- Nummerering av eksempler og oppgaver følger kapittel.del.løpenummer og starter på nytt i hvert delkapittel.
- Før du oppretter en ny struktur, undersøk den tilsvarende strukturen i R1-boken og gjenbruk den. Avvik skal være bevisste, begrunnet i alderstrinn/faglig innhold og dokumentert – ikke tilfeldige.

## Struktur og nummerering – tillegg for elevkapitler

- Følg alltid de nyeste fellesstandardene i `math-platform/docs/standards/`, særlig `design.md`, `pedagogy.md` og `quality.md`. Disse har forrang ved felles visuell og pedagogisk utforming.
- Bruk samme sidemønster som de godkjente R1-sidene: kort introduksjon, trinnvis teori, blå regelboks når en regel/formel skal framheves, turkist gjennomarbeidet eksempel, lokale oppgaver og fasit rett etter hver oppgave.
- Ikke samle alle lokale fasiter i slutten av kapitlet. Hver oppgave skal etterfølges av en sammenfoldet fasit/løsningsforslag (`??? note`) med metode, mellomregning og dobbel understrek under sluttsvaret.
- Bruk Zensical-admonitions konsekvent: `!!! important` for regler, `!!! example` for gjennomarbeidede eksempler, `!!! question` for elevoppgaver og `??? note` for fasit. Ikke lag egne konkurrerende bokstyper i bokspesifikk CSS.
- Bruk hierarkisk nummerering: `Eksempel 3.2.1` og `Oppgave 3.2.1` betyr kapittel.del.eksempel/oppgave. Nummereringen starter på nytt i hver del. Forkunnskapsoppgaver kan nummereres `3.0.x`.
- Deloppgaver skal stå på hver sin linje med `a)`, `b)`, `c)` osv. uten ekstra punktmarkør.
- I blandede oppgavesett kan nivåoverskriftene være Middels, Vanskelig og Svært vanskelig. Vanskelighetsfargene skal ikke brukes på vanlige oppgaver i en teoriseksjon.
- Ikke bruk svarte rammer rundt formler i blå regelbokser. Sluttsvar skal ha dobbel understrek.
- Kapittelsidene skal være selvstendige og fungere på mobil, PC og i utskrift. Ikke la formateringsmarkeringer lekke inn i navigasjon eller innholdsfortegnelse.
- Hvert ferdig kapittel skal ha en egen kapitteltest som dekker bredden i kapitlet, og en egen side med muntlig forberedelse: sentrale begreper, forklarings- og begrunnelsesoppgaver, metodevalg og samtaletrening. Fasiter skal være tilgjengelige i sammenfoldede felt.
- Boka skal ha ett samlet, kompakt formelark bakerst. Det skal bare inneholde formler og sammenhenger som faktisk er introdusert i boka, organiseres etter tema og utvides når nye kapitler blir ferdige. Utformingen skal fungere på én utskrivbar side når det er faglig forsvarlig.
