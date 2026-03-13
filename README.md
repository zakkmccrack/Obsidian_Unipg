# 🏛️ Appunti Informatica UNIPG

> *"Trova in pochi clic tutte le informazioni che ti servono per preparare il tuo esame e accrescere la tua conoscenza dell'informatica.*
> 
> *Hai degli appunti scritti su Obsidian che vuoi condividere? Crea un branch, aggiungili e apri una Pull Request!*
> 
> *Lo sviluppo è ancora al principio, e non esiste uno standard di stile, neanche per il readme.*
> 
> *Costruiamo insieme questa cattedrale al genio umano."*

---

## Istruzioni per l'uso

Questa repository è strutturata per essere usata e visualizzata direttamente dentro **[Obsidian](https://obsidian.md/)**. 

Non è solo testo: accetta file `.md` (Markdown per Obsidian), `.pdf` (slide, documenti e dispense) e sorgenti `LaTeX` per le formule matematiche più pesanti. Tutto è unificato in un solo grande albero.

Per avere tutto pronto sul tuo PC in 3 semplici passi:

1. **Clona il progetto** sul tuo computer (apri il terminale nella cartella in cui vuoi salvare gli appunti):
   ```bash
   git clone [https://github.com/VOSTRO-NOME/NOME-REPO.git](https://github.com/VOSTRO-NOME/NOME-REPO.git)
   ```
2. **Scarica e apri [Obsidian](https://obsidian.md/)**.
3. Nella schermata iniziale di Obsidian, clicca su **"Apri cartella come vault"** (*Open folder as vault*) e seleziona la cartella che hai appena clonato.

Ora vedrai tutto l'albero degli appunti perfettamente organizzato e potrai navigarci dentro.

## Aggiungere i tuoi appunti

Vuoi aggiungere i tuoi appunti, delle slide utili o sistemare la formattazione di una pagina?

1. Fai un pull per assicurarti di avere l'ultima versione:
   ```bash
   git pull origin main
   ```
2. Crea un tuo branch per le modifiche:
   ```bash
   git checkout -b aggiunta-appunti-materia
   ```
3. Inserisci i tuoi file `.md`, PDF o LaTeX nelle cartelle corrispondenti al corso.
4. Fai commit, pusha il tuo branch e apri una Pull Request verso il `main`.

*(P.S. Cerca di dare nomi chiari ai file seguendo lo schema delle cartelle. Ricorda di ignorare la tua cartella `.obsidian` personale e di non pushare i file spazzatura di compilazione generati da LaTeX!!!!!!)*