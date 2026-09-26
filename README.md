[README.md](https://github.com/user-attachments/files/32684944/README.md)
# Dentro la cipolla 🧅

Gioco didattico sui livelli del sistema operativo (modello a cipolla), pensato per una classe quarta di Informatica.

Lo studente è una richiesta appena digitata e deve attraversare i livelli del sistema operativo, dall'interprete dei comandi fino all'hardware:

1. **Interprete dei comandi**: terminale Linux simulato (`pwd`, `ls`, `cd`, `mkdir`, `touch`, `cp`, `mv`, `rm`, `man`).
2. **File system**: tabella del file system, blocchi dell'SSD, recupero dei file e formattazione.
3. **Input/Output**: driver delle periferiche, coda di stampa, comandi `lsusb`, `lpstat`, `dmesg`.
4. **Memoria**: allocazione, deallocazione, protezione e swap su 8 GB di RAM.
5. **Kernel**: scheduling Round Robin e gestione degli interrupt.
6. **Boss finale**: il viaggio completo di un comando e domande di ripasso.

## Come si usa

Basta aprire `index.html` in un browser: non serve installare nulla.
I progressi vengono salvati nel browser di ogni studente.
La casella "Modalità docente" apre tutti i livelli, utile per mostrarli alla LIM.

## Pubblicazione con GitHub Pages

1. Carica `index.html` e `README.md` in un repository pubblico.
2. Vai in **Settings › Pages**.
3. In **Source** scegli **Deploy from a branch**, branch `main`, cartella `/ (root)`, e salva.
4. Dopo un paio di minuti il gioco è online all'indirizzo `https://NOME-UTENTE.github.io/NOME-REPOSITORY/`.
