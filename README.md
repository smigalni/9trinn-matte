# 9. trinn – matematikk

Et gratis, digitalt og faglig kvalitetssikret læremiddel i matematikk for 9. trinn.

Dette repoet eier innholdet for 9. trinn. Det er selvstendig fra bøkene for 8. og 10. trinn, og bruker `math-platform` som felles fundament for standarder, design, verktøy og kvalitetssikring.

## Status

**Pilotfase – kapittel 3 er skrevet som et første elevrettet utkast, men er ikke faglig eller pedagogisk godkjent for publisering.** Nettstedet bruker Zensical, i tråd med `matte` og `tmatte`.

Elevvisningen skal bare inneholde lærestoff. Læreplananalyse, kapittelplaner, standarder, AI-instruksjoner og redaksjonelle vurderinger er interne arbeidsdokumenter og skal ikke bygges inn i elevboken.

Arbeidet videreføres slik:
1. Revidere pilotkapittel 3 etter lærerreview og kontrollere alle matematiske oppgaver og løsninger.
2. Kontrollere figurer, MathJax, mobilvisning og utskrift.
3. Bruke erfaringene fra piloten til å fastsette endelig kapittelstruktur og produsere resten av boken.

## Produktretning

- Elevboka skal være gratis og kunne brukes uten AI.
- Digital publisering er førsteprioritet.
- Innholdet skal også kunne skrives ut på en god måte.
- En egen lærerdel med innlogging kan komme senere.
- Lærerdelen skal kunne inneholde lærerveiledning, undervisningsopplegg, ekstraoppgaver og vurderingsressurser.
- AI-generert materiale skal være tydelig skilt fra godkjent bokinnhold. Læreren skal kunne kontrollere og redigere før materiale deles eller skrives ut.

## Dokumentasjon

- [Visjon](VISION.md)
- [Produktplan](BOOK_PLAN.md)
- [Læreplan og progresjon](docs/curriculum_map.md)
- [Sporbar kompetansemålkartlegging](docs/curriculum/9th-grade-coverage.md)
- [Kapittelstruktur – seks kapitler som arbeidsgrunnlag](docs/architecture/chapter-map-proposal.md)
- [ADR 0002 – seks hovedkapitler](docs/architecture/adr-0002-six-chapters.md)
- [Gjenbrukbar kapittelmal](docs/templates/chapter-template.md)
- [Pilotspesifikasjon for kapittel 3](docs/chapters/ch03-pilot-spec.md)
- [Første elevrettede utkast til kapittel 3 – ikke godkjent](docs/chapters/ch03-triangles.md)
- [AI-arbeidsflyt](AI_WORKFLOW.md)
- [Bokstandard](docs/standards/9trinn-matte.md)
- [Agentroller](docs/ai/agent-roles.md)
- [AI-agentinstruksjoner](AGENTS.md)
- [Første skill: læreplanlegging](ai/skills/map-curriculum/SKILL.md)
- [Arkitekturbeslutning 0001](docs/decisions/0001-repository-scope.md)
- [Bidragsveiledning](CONTRIBUTING.md)

## Lokal forhåndsvisning

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
zensical serve
```

Åpne `http://localhost:8000`. Bygg statisk nettsted med `zensical build`.

## Teknisk beslutning

- [ADR 0002 – Zensical som publiseringsrammeverk](docs/decisions/0002-zensical-publishing.md)

## Felles plattform

Se [math-platform](https://github.com/smigalni/math-platform). Bokrepoet skal ikke kopiere eller eie felles plattformkode uten en bevisst beslutning.
