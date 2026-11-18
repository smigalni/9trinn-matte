# ADR 0002: Zensical som publiseringsrammeverk

- Status: Vedtatt for første tekniske prototype
- Dato: 2026-11-16

## Kontekst

R1-repoet `matte` og T-matte-repoet `tmatte` bruker allerede Zensical med TOML-konfigurasjon, MathJax og Markdown-basert innhold. 9.-trinnsboka trenger et lett, statisk publiseringsoppsett som støtter matematisk notasjon, navigasjon og utskrift.

## Beslutning

Bruk Zensical som publiseringsrammeverk for den første prototypen av `9trinn-matte`.

## Begrunnelse

- Gjenbruker kjent arbeidsflyt og eksisterende erfaring fra de andre bokrepoene.
- Holder elevboka statisk og enkel å publisere.
- Støtter Markdown, navigasjon, utvidelser og MathJax.
- Unngår å introdusere et nytt rammeverk uten et konkret behov.

## Konsekvenser og begrensninger

- Konfigurasjonen følger foreløpig mønsteret i `tmatte`.
- Zensical-versjonen er låst til `0.1.1` i `requirements.txt` for reproducerbare bygg. Versjonsoppgraderinger skal gjøres bevisst etter kontroll av changelog.
- Felles CSS er foreløpig en lokal førsteimplementasjon. Den skal senere synkroniseres eller distribueres kontrollert fra `math-platform`, slik at bøkene ikke utvikler ulike designstandarder.
- Lærerinnlogging og AI-funksjoner ligger utenfor en ren statisk bok og skal vurderes som egne systemkomponenter senere.
- GitHub Actions har en build-workflow som skal kjøre `zensical build` på pull requests og push til `main`.
- GitHub Pages-deploy er ikke konfigurert eller testet i denne beslutningen.

## Reversering

Beslutningen kan endres dersom pilotkapittelet viser at Zensical ikke støtter nødvendige krav til interaktivitet, tilgjengelighet eller utskrift.
