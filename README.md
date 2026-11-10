# Vampire: The Masquerade - Bloodlines: Traduzione italiana

Traduzione italiana non ufficiale di **Vampire: The Masquerade - Bloodlines** per la **Unofficial Patch 12.0**: dialoghi, sottotitoli, menu, descrizioni di oggetti, discipline e abilità. L'audio resta in inglese.

Non è una traduzione solo letterale: cerca di mantenere l'atmosfera del gioco e il tono dei dialoghi, senza snaturare i personaggi. I nomi di discipline, termini e concetti del gioco di ruolo sono presi, dove possibile, dalla guida ufficiale italiana *Vampiri: La Masquerade*, 5ª edizione.

**Pagina ufficiale con guida e aggiornamenti:** https://steamcommunity.com/sharedfiles/filedetails/?id=3837442580

## Download

Scarica lo zip dall'ultima versione nella sezione [Releases](../../releases/latest).

## Requisiti

- Vampire: The Masquerade - Bloodlines (Steam o GOG).
- **Unofficial Patch 12.0, versione esatta `VTMBup120.9.exe`**, installata *prima* della traduzione. L'installer controlla che i file di Unofficial Patch siano quelli originali della 12.0.9 e, se non lo sono, si ferma senza scrivere nulla.

## Installazione

1. Chiudi il gioco.
2. Estrai lo zip ed esegui `Installa_Traduzione_Italiana.exe`.
3. Segui la procedura guidata. La cartella del gioco viene cercata da sola; se non la trova, indica quella che contiene `Vampire.exe`.
4. Avvia il gioco come sempre con Unofficial Patch (opzione di avvio: `-game Unofficial_Patch`).

Windows può avvisare che l'applicazione non è riconosciuta, perché il programma non è firmato digitalmente: scegli *Ulteriori informazioni* e poi *Esegui comunque*.

## Disinstallazione

Prima di sostituire i file, l'installer salva gli originali in `Unofficial_Patch\IT_translation\backup`. Puoi rimuovere la traduzione in uno di questi modi:

- Impostazioni di Windows > App > "Vampire: The Masquerade - Bloodlines - Traduzione italiana";
- rieseguendo l'installer e scegliendo *Disinstalla*;
- eseguendo `Unofficial_Patch\IT_translation\Disinstalla_Traduzione_Italiana.exe`.

I file originali vengono ripristinati identici e quelli aggiunti dalla traduzione vengono eliminati. I salvataggi non vengono mai toccati.

## Verifica del download

Gli hash SHA-256 dei file sono indicati nelle note di ogni release. Per controllare lo zip in PowerShell:

```powershell
Get-FileHash .\VTMB_Traduzione_Italiana_v1.0.0.zip -Algorithm SHA256
```

## Cosa contiene

Solo testi tradotti e differenze (patch) rispetto ai file di Unofficial Patch. Non contiene audio, modelli, mappe né altri file del gioco.

## Segnalazioni

Per errori o problemi usa la sezione [Issues](../../issues) oppure i commenti della [guida su Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3837442580). Indica la versione di Unofficial Patch, la versione della traduzione e dove (personaggio, luogo, frase) hai trovato il problema.

## Note legali

Vampire: The Masquerade - Bloodlines è un marchio dei rispettivi proprietari. Questa è una traduzione italiana non ufficiale, senza scopo di lucro, e non è affiliata ai detentori dei diritti.
