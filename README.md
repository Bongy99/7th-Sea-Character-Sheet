# 7th Sea – Scheda Eroe

App Android (Capacitor) con scheda Eroe di 7th Sea Seconda Edizione.

## Come ottenere l'APK
1. Crea un repository su GitHub e carica **tutto il contenuto** di questa cartella
   (compresa la cartella nascosta `.github`).
2. Vai nella scheda **Actions**. Il workflow "Build APK" parte da solo a ogni push
   (oppure avvialo con "Run workflow").
3. A build finita (3-6 minuti) apri l'esecuzione e scarica l'artefatto
   **seventh-sea-apk** in fondo alla pagina: è uno zip con `app-debug.apk`.
4. Invia l'APK agli amici. Su Android devono consentire
   "Installa app da origini sconosciute" per il browser o il gestore file usato.

## Modificare l'app
Tutta l'app è in `www/index.html`. Modificalo, fai commit e l'APK si rigenera.

I dati sono salvati sul dispositivo di ciascun giocatore.

## WebApp per iPhone / iPad (GitHub Pages)
1. Nel repository: **Settings → Pages → Source → GitHub Actions**
   (con un account gratuito il repository deve essere **pubblico**).
2. Al prossimo push (o da Actions → "Deploy WebApp" → Run workflow) l'app viene
   pubblicata su `https://TUO-UTENTE.github.io/NOME-REPOSITORY/`.
3. Gli amici aprono il link **con Safari**, toccano **Condividi → Aggiungi alla schermata Home**:
   l'app si apre a schermo intero e funziona anche offline.

Nota: i dati sono salvati nel dispositivo, e l'app installata sulla Home ha un archivio
separato da quello di Safari. Conviene usare sempre e solo l'icona installata.


## Importare i manuali (catalogo)
Nella scheda, sezione **3. Background e Vantaggi**, usa **Manuali** e scegli i PDF di 7th Sea Seconda Edizione
(Manuale Base, Impero della Mezzaluna, Terre dell'Oro e del Fuoco, Nazioni di Théah 1 e 2, Nuovo Mondo): puoi
sceglierne più d'uno insieme. L'app legge sul dispositivo Background, Vantaggi, Arcani, bonus di nazione e le liste di
stregoneria, Stili di Duello e Manovre di Duello (dal Manuale Base; compaiono nel Riepilogo quando l'Eroe ha il Vantaggio Sala d'Armi); il testo dei manuali **non** è incluso nell'app e resta solo sul tuo dispositivo.

## Schede Malvagio (GM)
Nella scheda **GM → Malvagi** puoi creare Malvagi con Forza, Influenza, Ferite (Forza + Drammatiche), Vantaggi (5 + Forza punti), Arcani, Stregonerie/Stili/Manovre (Grado = metà Forza), Macchinazioni e Qualità Mostruose. I dati sono salvati con il GM e inclusi nell'Esporta.
Nella scheda **GM → Squadre** gestisci le Squadre di Sgherri: Forza attuale/iniziale, Tipo con Capacità (Punti Pericolo), unione e divisione, Squadre di Mostri con Qualità.
