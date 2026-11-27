# Traduzione italiana di Vampire: The Masquerade - Bloodlines (Unofficial Patch 12.0)

Traduzione italiana non ufficiale di **Vampire: The Masquerade - Bloodlines** per la [Unofficial Patch](https://www.moddb.com/mods/vtmb-unofficial-patch) 12.0: dialoghi, sottotitoli, menu, descrizioni di oggetti, discipline e abilità. L'audio resta in inglese.

Non è una traduzione solo letterale: cerca di mantenere l'atmosfera del gioco e il tono dei dialoghi, senza snaturare i personaggi. I nomi di discipline, termini e concetti del gioco di ruolo sono presi, dove possibile, dalla guida ufficiale italiana *Vampiri: La Masquerade*, 5ª edizione.

**Altre pagine** (solo presentazione: download, istruzioni e aggiornamenti stanno qui su GitHub):
- [ModDB](https://www.moddb.com/mods/traduzione-italiana-di-vampire-the-masquerade-bloodlines)
- [Guida su Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3837442580)

## Download

Scarica lo zip dall'ultima versione nella sezione [Releases](../../releases/latest).

## Requisiti

- **Windows XP (SP3) o successivo, 32 e 64 bit.**
- Vampire: The Masquerade - Bloodlines (Steam o GOG).
- La [Unofficial Patch](https://www.moddb.com/mods/vtmb-unofficial-patch) **con il Plus Patch**, installata *prima* della traduzione (il solo Basic Patch non è supportato), nella versione esatta per cui è fatta la traduzione. L'installer controlla che i file di Unofficial Patch siano quelli originali e, se non lo sono, si ferma senza scrivere nulla.

| Unofficial Patch | Traduzione |
|---|---|
| 12.0.14 (`VTMBup120.14.exe`) | [v1.1.1](../../releases/tag/v1.1.1) |
| 12.0.13 (`VTMBup120.13.exe`) | [v1.1.0](../../releases/tag/v1.1.0) |
| 12.0.9 (`VTMBup120.9.exe`) | [v1.0.0-r2](../../releases/tag/v1.0.0-r2) |

## Installazione

1. Chiudi il gioco.
2. Estrai lo zip ed esegui `Installa_Traduzione_Italiana.exe`.
3. Segui la procedura guidata. La cartella del gioco viene cercata da sola; se non la trova, indica quella che contiene `Vampire.exe`.
4. Avvia il gioco come sempre con Unofficial Patch (opzione di avvio su Steam: `-game Unofficial_Patch`).

L'installer controlla ogni file, salva gli originali in `Unofficial_Patch\IT_translation\backup` e, se qualcosa va storto o interrompi l'operazione, ripristina tutto. Tocca solo file dentro `Unofficial_Patch`: i salvataggi non vengono mai toccati.

Se aggiorni Unofficial Patch dopo aver installato la traduzione, disinstalla prima la traduzione (UP chiede di cancellare la sua cartella e andrebbero persi i backup), poi installa la versione della traduzione adatta alla nuova UP.

## Antivirus e avvisi di Windows

L'installer non è firmato digitalmente: Windows (SmartScreen) può mostrare "app non riconosciuta" (scegli *Ulteriori informazioni* e poi *Esegui comunque*) e alcuni antivirus possono segnalarlo con avvisi generici di tipo euristico, come succede spesso a programmi di questo tipo. Il rapporto VirusTotal dell'exe è nelle note di ogni release. Se Microsoft Defender blocca o elimina il file, controlla prima che l'SHA-256 dello zip coincida con quello delle note; se coincide e vuoi procedere, apri *Sicurezza di Windows* > *Protezione da virus e minacce* > *Cronologia protezione*, seleziona l'elemento bloccato e scegli *Azioni* > *Consenti nel dispositivo*, poi estrai di nuovo lo zip. Se non te la senti, non installare: la traduzione è facoltativa.

Per controllare lo zip in PowerShell:

```powershell
Get-FileHash .\VTMB_Traduzione_Italiana_v1.1.1.zip -Algorithm SHA256
```

## Disinstallazione

Puoi rimuovere la traduzione in uno di questi modi:

- Impostazioni di Windows > App > "Vampire: The Masquerade - Bloodlines - Traduzione italiana";
- rieseguendo l'installer e scegliendo *Disinstalla*;
- eseguendo `Unofficial_Patch\IT_translation\Disinstalla_Traduzione_Italiana.exe`.

I file originali vengono ripristinati identici e quelli aggiunti dalla traduzione vengono eliminati. Se un file è stato modificato dopo l'installazione (Unofficial Patch riscrive da sola alcuni file, ad esempio `strings.txt`, `stats.txt` e `haven_pc.txt`, a seconda del personaggio), la procedura te lo segnala e ti lascia scegliere se sovrascriverlo o lasciarlo.

## Cosa contiene

Solo testi tradotti e differenze (patch) rispetto ai file di Unofficial Patch. Non contiene audio, modelli, mappe né altri file del gioco.

## Segnalazioni

Per errori o problemi usa la sezione [Issues](../../issues). Indica la versione di Unofficial Patch, la versione della traduzione e dove (personaggio, luogo, frase) hai trovato il problema.

## Note legali

Vampire: The Masquerade - Bloodlines è un marchio dei rispettivi proprietari. Questa è una traduzione italiana non ufficiale, senza scopo di lucro, e non è affiliata ai detentori dei diritti.
