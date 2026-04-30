# Progetto: Sara Services — Classifica Viaggio Premio

## GitHub
- **Repository:** `Sara-Admin/public`
- **Sottocartella nel repo:** `SaraServices_Classifica-ViaggioPremio/`
- **URL:** https://github.com/Sara-Admin/public/tree/main/SaraServices_Classifica-ViaggioPremio
- **Account GitHub da usare per il push:** `crestonisara`

## Procedura push
Quando l'utente chiede di fare push su GitHub, eseguire questi passi:

1. Passare all'account `crestonisara`:
   ```bash
   gh auth switch --user crestonisara
   ```
2. Clonare il repo in una cartella temporanea (se non già presente):
   ```bash
   gh repo clone Sara-Admin/public /tmp/sara-public -- --depth=1
   ```
3. Copiare i file aggiornati nella sottocartella:
   ```bash
   cp index.html rappel.html logo.png /tmp/sara-public/SaraServices_Classifica-ViaggioPremio/
   ```
4. Commit e push dal clone:
   ```bash
   cd /tmp/sara-public && git add SaraServices_Classifica-ViaggioPremio/ && git commit -m "..." && git push
   ```
