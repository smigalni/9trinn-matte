# ADR 0001: Ett bokrepo per trinn

- Status: Vedtatt
- Dato: 2026-11-16

## Kontekst

Bøkene for 8., 9. og 10. trinn skal kunne utvikles og publiseres uavhengig, samtidig som de deler pedagogiske og tekniske standarder.

## Beslutning

- Dette repoet, `9trinn-matte`, eier faginnhold og bokspesifikke valg for 9. trinn.
- `8trinn-matte` og `10trinn-matte` skal være egne repoer når de opprettes.
- `math-platform` eier felles standarder, design, maler, verktøy og kvalitetssikringsarbeidsflyt.
- En eventuell felles inngangsportal kan lenke til de selvstendige bøkene, men skal ikke gjøre bokrepoene tett koblet.
- Hvert bokrepo skal kunne bygges og publiseres uavhengig.

## Konsekvenser

Fordeler:
- Uavhengige utgivelser og endringstakt.
- Tydelig eierskap til faginnhold.
- Enklere samarbeid og senere vedlikehold.

Kostnader:
- Felles standarder må versjoneres eller distribueres på en kontrollert måte.
- Progresjon mellom trinnene må forvaltes eksplisitt, ikke bare gjennom separate bokplaner.

## Åpne spørsmål

- Hvordan felles progresjonsmodell skal forvaltes mellom bokrepoene.
- Hvordan felles design og verktøy skal versjoneres.
- Hvordan en eventuell portal skal implementeres.
