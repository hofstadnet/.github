# AGENTS.md

Instruksjoner for kodeagenter og andre som jobber i repoet. Beskrivelsen av repoet står i [README.md](README.md).

## Prosjektet

Felles filer for organisasjonen hofstadnet: profilsiden, standardfiler for repoer uten egne og arbeidsflytmaler. Det
finnes ingen kode å bygge.

## Regler

- Følg de felles retningslinjene i https://github.com/hofstadnet/guidelines.
- Alle endringer går via pull request med grønne sjekker. Ikke push til `main`.
- Oppdater dokumentasjonen i samme pull request som endringen.
- Ingen hemmeligheter, tokens eller private opplysninger i repoet. Repoet er offentlig.
- Actions er låst til full commit-SHA med versjonen som kommentar. Når en action oppdateres i `.github/workflows/`,
  oppdateres samme SHA i `workflow-templates/` i samme pull request.
