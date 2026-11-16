# AI-arbeidsflyt

## Mål

AI skal hjelpe med å utvikle og kvalitetssikre boka, samtidig som prosessen er forståelig og lærende for prosjekteier. AI skal ikke gjøre ubekreftede antakelser om læreplan, faglig kvalitet eller status.

## Før arbeid

1. Les denne filen, `README.md`, `VISION.md`, `BOOK_PLAN.md`, `CURRICULUM_MAP.md` og relevante standarder.
2. Kontroller gjeldende versjon av Udirs læreplan når arbeid avhenger av læreplanen.
3. Undersøk eksisterende filer og implementasjon før nye konvensjoner foreslås.
4. Avklar om endringen gjelder 9.-trinnsboka eller felles plattform.
5. Ved større arbeid: lag en konkret plan og del arbeidet i kontrollerbare leveranser.

## Arbeidsflyt for faginnhold

1. **Læreplan:** identifiser relevante kompetansemål og forkunnskaper.
2. **Pedagogisk design:** definer læringsmål, progresjon, representasjoner og mulige misoppfatninger.
3. **Innholdsproduksjon:** lag teori, eksempler og oppgaver.
4. **Matematisk kontroll:** kontroller alle påstander, mellomregninger, svar og løsningsmetoder uavhengig.
5. **Pedagogisk/redaksjonell kontroll:** vurder språk, nivå, tydelighet og oppgavevariasjon.
6. **Teknisk og visuell kontroll:** bygg og inspiser faktisk rendering, mobilvisning og utskrift.
7. **Godkjenning:** ikke publiser nytt offisielt bokinnhold uten prosjekteiers godkjenning.

## Kvalitetsporter

En leveranse skal ikke merkes som ferdig før relevante kontroller er gjennomført:

- Læreplan: dekning og korrekt tolkning.
- Matematikk: korrekthet og entydighet.
- Pedagogikk: nivå, forkunnskaper og progresjon.
- Redaksjon: norsk språk, begreper og instruksjoner.
- Visuelt: formler, figurer, oppgaver, navigasjon og mobil.
- Teknisk: bygg, lenker og utskriftsfunksjon.

## Agentroller og skills

Se [agentroller](docs/ai/agent-roles.md). Rollene er foreløpig spesifikasjoner for arbeidsansvar, ikke separate autonome tjenester. Skills skal være gjenbrukbare, avgrensede arbeidsinstrukser. Vi innfører ikke et agentrammeverk eller MCP-server uten et konkret behov.

## Arbeidsrapport

Etter en arbeidsøkt skal rapporten skille mellom:
- Utført og bekreftet.
- Foreslått, men ikke vedtatt.
- Testet, med konkret test og resultat.
- Ikke testet eller blokkert.
- Beslutninger som krever prosjekteier.

Forklar kort hvilke AI-konsepter som faktisk ble brukt, og hvorfor. Ikke hev at en agent, skill, test, build eller deploy er kjørt hvis det ikke stemmer.
