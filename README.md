# Paul Marti Musikk

Norskspråklige undervisningsressurser i musikk for ungdomstrinnet, utviklet av Paul Marti, musikklærer.

**Nettside:** https://paulmartimusikk.netlify.app/

## Innhold

| Ressurs | Beskrivelse | Fil |
|---|---|---|
| **Hovedside** | Inngang til ressursene. | `index.html` |
| **Samspillsmetodikk** | Tre veiledninger som tar elevene fra første lytting til ferdig bandøving, gehørbasert og steg for steg. | `samspillsmetodikk.html` |
| → Steg 1: Lytt. Herm. Spill. | Aktiv lytting, nynning, bodypercussion og lydhermende ord før instrumentene tas i bruk. | `bandstart-metodikk.html` |
| → Steg 2: Øv deg klar til bandet | Individuelle øvingsstrategier, puls, målrettet øving og øvingslogg. | `individuell-oving.html` |
| → Steg 3: Nå spiller vi sammen | Bandøvingen i praksis: groove-oppbygging, gjennomkjøring, fokusøving, tilbakemelding og avslutning. | `samspill-bandoving.html` |
| **Piano-akkordgenerator** | Interaktivt verktøy for å lage akkorddiagrammer med besifring, voicing og fingersetting. Eksporterer som PNG. | `piano-chord-generator.html` |

## Pedagogisk tilnærming

- Populærmusikk som utgangspunkt: besifring, tabs, låtstruktur (vers, refreng, bro) og backing tracks.
- Gehørbasert arbeid: lytte og herme før en spiller.
- Kroppslig pulsopplæring i rekkefølgen tramp → metronom → backing track.
- Norsk/tysk notasjon i akkordverktøyet (B/H), med mulighet for å bytte.

## Teknisk

- Statiske HTML-filer med innebygd CSS og JavaScript. Ingen server og ingen byggesteg.
- Pianoverktøyet tegner på canvas, eksporterer PNG i 3× oppløsning og kan kopiere bildet til utklippstavlen.
- Fonter: Bebas Neue og Barlow, lastet fra Google Fonts (SIL Open Font License).
- Hostet på Netlify.

For å se siden lokalt: åpne `index.html` i en nettleser, eller start en enkel lokal server, f.eks. `python3 -m http.server`.

## Lisens

Innhold og kode er utgitt under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Du kan fritt bruke, endre og dele, så lenge du oppgir kilde (Paul Marti).

## Om bruk av KI

Nettsiden er laget i samarbeid med **Claude** (Anthropic), i chat på claude.ai, 4.–6. mars 2026. Modellversjon er ikke registrert. Dette beskriver den første utviklingen.

- **Claude** skrev, så langt chatloggene viser, all kode og tekst, inkludert akkorddata, voicing-logikk og listen over lydhermende ord.
- **Paul** styrte med instruksjoner og rettinger: ideer og krav, de pedagogiske valgene (populærmusikk, gehør, stemme og kropp før instrument, tramp → metronom → backing track), norsk terminologi og notasjon (B/H/Bb), design, testing og kravet om KI-opplysning. Lisensvalget kom etter råd fra Claude.
- **Faglig grunnlag:** utviklet i samtale med Claude, som også ga en forskningsoppsummering. Kildehenvisningene derfra er ikke etterprøvd, og siden presenterer ikke materialet som forskningsbasert.
- **Testing:** manuelt av Paul. Det finnes ingen automatiserte tester, og Claude testet ikke i en ekte nettleser.
- **Inspirasjon:** pianoverktøyet er inspirert av chordgenerator.net (gitarakkorder). Koden er skrevet fra bunnen av.

Innholdet er ikke fagfellevurdert, og KI-generert tekst og kode kan inneholde feil.

## Tilbakemeldinger

Feil og forslag meldes som *issue* her på GitHub.
