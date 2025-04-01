# git - Working with remotes
- i repository remotiu sono versioni del tuo progetto che sono ospitate su internet
 
-la collaborazione con altri programmatori implica la gestione  di questi repository remoti e il push e il pull di dati
Fondamentale è saper **sincronizzare il nostro lavoro locale con unr eposutory remoto.**

*comandi principali*

`git remote -v`  --> visualizza i server remoti collefati al nostro repository
## aggiungerre o rimuovere un repository remoto##

`git remote add <nome> <url>`

## caricare il lavoro locale sul repository remoto

`git push <remote> <ramo-locale>` 

## aggiornare la copia locale del repository, allineando con la versione remota

`git pull <remote> <ramo-locale>`
