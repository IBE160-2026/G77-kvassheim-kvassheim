# Tilbakemelding på product brief

| | |
|---|---|
| **Gruppe** | G77 – G77-kvassheim-kvassheim |
| **Product brief** | Ingen product brief funnet på `main` per 2026-10-06 (siste commit `a716c06`) |
| **Tilbakemelding fra** | Faglærer i IBE160 (utarbeidet med KI-støtte) |
| **Dato** | 2026-10-06 |

## Samlet vurdering

- **Bør revideres før dere går videre.** Rett punktene markert «Endre» før dere lager PRD og arkitektur.

Vi fant ingen product brief eller tilsvarende dokument (proposal, prosjektbeskrivelse eller prosjektidé) på `main` i repoet per 2026-10-06. Repoet inneholder BMAD-rammeverket (`_bmad/`, `.claude/` og `.bmad-loop/`), så verktøyet er installert, men vi fant ingen planleggingsdokumenter laget med det. Det finnes derfor ikke noe å gi tilbakemelding på ennå. Denne tilbakemeldingen forklarer hva som mangler, og hva dere bør gjøre nå.

**Det som er bra:**

1. Repoet er satt opp i organisasjonen IBE160-2026, med README og `.gitignore`, så dere har et sted å samle arbeidet.
2. BMAD er allerede installert, så dere kan starte product brief-skillen direkte i Claude Code. Det er fortsatt tid til å komme i gang. En god brief nå gir et mye bedre utgangspunkt enn en rask brief sent i semesteret.

**De viktigste endringene:**

1. **Endre:** Skriv en product brief og commit den til `main`. Bruk BMAD-skillen for product brief med Claude Code, og legg resultatet i planleggingsmappen (for eksempel `_bmad-output/planning-artifacts/briefs/`).
2. **Endre:** Ta med en begrunnet vurdering av vanskelighetsgrad og gjennomførbarhet, kalibrert mot forslagslista «Prosjektforslag for IBE160 Programmering med KI».
3. **Endre:** Commit jevnlig fremover, slik at prosessen fra idé til kode blir synlig i historikken.

## Hvorfor product brief er viktig for mappen

Product brief er utgangspunktet for PRD, arkitektur, stories og til slutt koden. Del 1 av mappen (applikasjon og prosess, 70 %) vurderes blant annet på om sensor kan følge en sporbar vei fra plan til ferdig app (kriteriet «Prosess og KI-styring» teller 30 %). Den vurderes også på om appen gjør det dere har beskrevet, om den er testet, om den er godt designet, og om den kan kjøres etter README. Uten en brief mangler starten på denne kjeden, og det blir vanskelig å vise en realistisk og iterativ prosess. Det er mye enklere å rette nå enn sent i semesteret.

## Hva briefen bør inneholde

Følg BMAD-flyten: product brief → PRD → arkitektur → epics og stories → implementering med Claude Code. Faglærers eksempelprosjekt viser hvordan dette kan se ut: https://github.com/IBE160-2026/beergame (se `.docs/planning-artifacts/briefs/`).

Briefen bør ha disse delene:

| Del av brief | Hva den bør svare på |
|---|---|
| Executive Summary | Hva er appen, og hvilket problem løser den? |
| The Problem | Et konkret problem med reelle situasjoner og brukere. |
| The Solution | Hva brukeren opplever og får gjort. Beskriv brukeropplevelsen, ikke bare teknologi. |
| What Makes This Different | En ærlig sammenligning med det som finnes i dag. |
| Who This Serves | Én tydelig primærbruker og hva den trenger. |
| Success Criteria | Kriterier som kan sjekkes eller testes, for eksempel «en bruker kan registrere X og se det i oversikten». |
| Scope | Hva som er med i første versjon, og hva som eksplisitt ikke er det. |
| Vision | Hvor produktet kan gå senere, uten å blåse opp omfanget i v1. |

I tillegg bør briefen ha en **begrunnet vurdering av vanskelighetsgrad og gjennomførbarhet**:

- **Vanskelighetsgrad:** Sammenlign med forslagslista. Enkle prosjekter er for eksempel 1) AI Study Buddy, 6) To-do-liste med smarte etiketter og 8) Foredragsnotater → sammendrag og quiz. Middels er 2) AI CV- og søknadsassistent og 7) Kurs-FAQ-chatbot. Vanskelige er 3) KI-styrt simulering av prosjektledelse, 4) KI-støttet MRP II og 5) KI-styrt sensurering. Et enkelt prosjekt gir stor sjanse for å bli ferdig, men krever mer i design, testing og dokumentasjon for å nå helt opp. Et vanskelig prosjekt gir større mulighet, men også større risiko.
- **Gjennomførbarhet:** Kan første versjon bli ferdig og stabil i løpet av semesteret, med tid til BMAD-flyten, testing og README? Kan dere selv kontrollere at koden Claude Code lager, gir riktige svar? Kan sensor kjøre appen lokalt etter README uten deres nøkler eller betalte kontoer? Bruker appen en språkmodell, trengs det en testmodus eller mock-svar.

Prosjektidé og vanskelighetsgrad: Vi fant ingen spor av prosjektidé i README, filer eller commit-meldinger, så vi kan ikke gi en foreløpig vurdering av vanskelighetsgrad eller gjennomførbarhet ennå.

## Neste steg for gruppen

1. Velg prosjektidé, enten fra forslagslista eller en egen idé, og beskriv kjerneflyten i 3–5 steg.
2. Lag product brief med BMAD (product brief-skillen i Claude Code). Ta med alle delene over og en begrunnet vurdering av vanskelighetsgrad og gjennomførbarhet. Commit den til `main` så snart som mulig.
3. Ta kontakt med faglærer eller hjelpelærer hvis dere er usikre på idé, omfang eller oppsett, og gå så videre til PRD.

Legg product brief i repoet når den er klar, og oppdater den underveis, slik at historikken viser hvordan planen utviklet seg. Det er en del av prosessen sensor ser etter.
