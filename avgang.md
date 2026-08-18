# Personvernerklæring — Avgang

*Gjelder fra: 17. august 2026* · [English version](avgang-en.md)

## Oppsummering

Avgang samler ikke inn, lagrer eller deler noen personopplysninger om deg.

---

## Data samlet inn av utvikleren

**Ingen.** Utvikleren av Avgang samler ikke inn, lagrer, behandler eller deler noen personopplysninger. Appen har ingen analyse, krasjrapportering, reklame-SDK-er eller servere driftet av utvikleren.

## Posisjon

Avgang ber om tilgang til enhetens posisjon utelukkende for å finne de nærmeste kollektivholdeplassene. Posisjonen din behandles kun på enheten din og sendes aldri til utvikleren eller lagres utenfor enheten din.

Søket etter nærmeste holdeplass gjøres på enheten din, mot en holdeplassliste som følger med appen og oppdateres jevnlig — koordinatene dine sendes verken til Entur eller til noen andre for å gjøre dette. Forbeholdene til behandling på enheten er funksjonene som er beskrevet under Apple Maps nedenfor — særlig det valgfrie gåtid-anslaget, som er den eneste funksjonen som sender din egen posisjon noe sted. Den er avslått som standard.

## Tredjepart — Entur

For å vise sanntidsavganger henter appen data fra det offentlige API-et til Entur (entur.no). Forespørsler inneholder identifikatorer for holdeplassene du ser på, men ikke posisjonen din. For detaljer om hvordan Entur behandler data, se [Enturs personvernerklæring](https://www.entur.org/om-entur/personvern/).

Avgangsdata leveres av Entur under [Norsk lisens for offentlige data (NLOD) 2.0](https://data.norge.no/nlod/no/2.0).

## Tredjepart — Apple Maps

Appen bruker Apples MapKit-rammeverk til å tegne kart og, valgfritt, til å beregne gåtid. Kartbildene ligger ikke i appen, men hentes fra Apples servere ved behov. Det betyr at Apple mottar informasjon om hvilket kartområde som etterspørres. Tre funksjoner snakker med Apples servere: den første er påslått som standard, de to andre er avslått som standard. Alle kan slås av i appens innstillinger.

- **Bakgrunnen på avgangsskjermen.** Denne er **påslått som standard**. Kortet som viser neste avgang, tegnes over et lite kart av området rundt holdeplassen — omtrent 400 meter, sentrert på selve holdeplassen og ikke på deg. Det som sendes, er holdeplassens egen koordinat, som er offentlige data fra Nasjonalt stoppestedsregister; din egen posisjon sendes ikke. Merk likevel at appen normalt viser holdeplassen nærmest deg, slik at kartområdene som etterspørres over tid vil gjenspeile steder du har vært. Apple mottar ikke koordinatene dine, men forespørslene kommer fra enheten din og følger reisene dine. Bildene mellomlagres på enheten din i omtrent to uker, slik at samme holdeplass normalt bare hentes én gang i denne perioden. Slår du av «Vis kartbilde bak avgangskortet» i innstillingene, stopper dette helt — da hentes ingen kartbilder til denne skjermen.
- **Kart-fanen.** Hvis du slår på den valgfrie kart-fanen, vises et interaktivt kart som åpnes sentrert på posisjonen din og markerer hvor du er. Apple mottar dermed hvilket kartområde du ser på, som i det øyeblikket omtrent gjenspeiler hvor du befinner deg. Posisjonen din sendes fortsatt ikke til utvikleren. Denne fanen er avslått som standard.
- **Gåtid til holdeplassen.** Hvis du slår på «Vis gåtid til stasjonen» i innstillingene, viser to skjermer et anslag på hvor mange minutter det tar å gå til holdeplassen, på kortet som viser selve avgangen: avgangsskjermen og skjermen for en enkelt avgang. For å beregne dette sender enheten din posisjonen din, sammen med holdeplassens koordinat, til Apple som en forespørsel om gårute. Dette er den eneste funksjonen i appen som sender din egen posisjon; den er **avslått som standard**, og ingen slike forespørsler gjøres før du slår den på. Resultatene mellomlagres på enheten din slik at forespørselen ikke gjentas ved hver oppdatering. Posisjonen din sendes fortsatt ikke til utvikleren, og aldri til Entur.

Hvordan Apple behandler disse forespørslene, er beskrevet i [Apples personvernerklæring](https://www.apple.com/legal/privacy/). Se også Apples [juridiske merknad om kartdata](https://gspe21-ssl.ls.apple.com/html/attribution-1.html).

## Analyse og krasjrapportering

Ingen. Appen bruker ingen tredjeparts analyse- eller krasjrapporteringsverktøy.

## Barn

Appen samler ikke bevisst inn opplysninger om noen, inkludert barn under 13 år.

## Endringer i denne erklæringen

Dersom erklæringen endres, vil den oppdaterte versjonen publiseres på denne adressen med ny gyldighetsdato.

## Kontakt

Spørsmål om denne personvernerklæringen kan sendes til [avganger@p.xxd.no](mailto:avganger@p.xxd.no).
