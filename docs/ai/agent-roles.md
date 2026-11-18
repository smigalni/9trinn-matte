# AI-roller for 9. trinn-boka

## Formål

Rollene beskriver avgrensede ansvarsområder i arbeidsflyten. De kan utføres av én modell i ulike arbeidsfaser eller av separate agenter når det gir en reell fordel. Vi skal ikke late som om separate agenter er aktive dersom arbeidet utføres i én vanlig assistentsesjon.

## Roller

### Curriculum Agent
- Leser gjeldende MAT01-06.
- Kartlegger kompetansemål, forklaringstekster, forkunnskaper og progresjon.
- Foreslår dekning og årsplan.
- Skal ikke dikte opp læreplanmål eller fremstille forslag som offisielle krav.

### Mathematics Reviewer
- Kontrollerer definisjoner, utregninger, oppgaver og løsningsforslag.
- Prøver alternative metoder og randtilfeller.
- Rapporterer tvetydige oppgaver og skjulte forutsetninger.

### Pedagogy Reviewer
- Vurderer nivå, progresjon, forkunnskaper, misoppfatninger og representasjoner.
- Kontrollerer balansen mellom trening, utforsking og problemløsing.

### Content Author
- Skriver teori, eksempler, oppgaver og løsningsforslag etter godkjent plan.
- Følger bokas språk- og designstandarder.

### Editorial Reviewer
- Kontrollerer norsk språk, instruksjoner, konsistens og fagterminologi.

### QA Reviewer
- Kontrollerer bygg, lenker, rendering, mobil og utskrift.
- Rapporterer bare tester som faktisk er utført.

## Arbeidsdeling og uavhengighet

For viktig matematisk kontroll skal reviewer ikke bare gjenta forfatterens begrunnelse. Kontrollen skal forsøke en selvstendig løsning. Ved større leveranser bør læreplan-, matematikk- og pedagogisk kontroll skilles i egne steg, selv om samme modell utfører dem.

## Skills som bør utvikles

Første kandidater:
- `map-curriculum`: kartlegg kompetansemål og progresjon.
- `design-math-section`: planlegg en læringsseksjon.
- `author-math-content`: produser teori, eksempler og oppgaver.
- `generate-exercises`: lag varierte oppgaver og løsningsforslag.
- `verify-mathematics`: uavhengig matematisk kontroll.
- `review-pedagogy`: kontroller nivå og læringsprogresjon.
- `review-rendered-book`: kontroller bygget bok visuelt og teknisk.

Dette er en første spesifikasjon av rollene. Den første gjenbrukbare skill-instruksen er opprettet i `ai/skills/map-curriculum/SKILL.md`. Den er en versjonskontrollert arbeidsinstruks som kan lastes av en agent; den er ikke i seg selv en kjørende agent eller et separat runtime-system. De øvrige skills utvikles når tilsvarende arbeidsflyter er modne.
