# Come contribuire

Regole brevi per lavorare in squadra su questo repository.

1. **GitHub Flow.** `main` funziona sempre. Ogni modifica nasce in un branch creato da `main`, entra con una pull request e, dopo il merge, il branch si cancella.
2. **Una issue per modifica.** Prima apri un’issue che dice che cosa va fatto; poi crei un branch con il suo numero, per esempio `feat/1-accessibilita`.
3. **Conventional Commits.** Messaggi `tipo: descrizione`, in italiano, al presente: `feat`, `fix`, `docs`, `style`, `chore`. Un commit per ogni modifica che ha senso da sola.
4. **Una pull request per issue.** Nella descrizione scrivi `Closes #N` con il numero dell’issue: al merge l’issue si chiude da sola.
5. **Review obbligatoria.** Nessuno fa merge del proprio lavoro senza la review di un compagno: `main` è protetto e chiede una approvazione. Chi revisiona apre la scheda dei file modificati, controlla il risultato e sceglie se commentare, approvare o chiedere modifiche.
6. **Conflitti.** Se la pull request è in conflitto con `main`, porta `main` nel tuo branch (`git fetch origin` e `git merge origin/main`), risolvi, controlla il risultato e fai push. Mai `--force` su `main`.
7. **Niente dati personali.** Il repository è pubblico: niente email personali, telefoni, indirizzi, password o chiavi. Nei commit usi l’indirizzo `noreply` di GitHub.
8. **Versioni.** Ogni versione ha una voce in `CHANGELOG.md` (formato Common Changelog) e un tag annotato, per esempio `v1.0.0`.

© 2026 Luca Sacchi Ricciardi · CC BY-NC-ND 4.0
