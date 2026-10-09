# WA IELTS

Landing page del master brand WA IELTS, destinata a `www.waielts.com` dopo la migrazione del dominio.

- `index.html`: pagina unica, HTML, CSS e JavaScript vanilla, senza dipendenze esterne a parte Google Fonts (Plus Jakarta Sans). Direzione visiva ispirata a Mindvalley, fusa con il sistema di marca reale già in uso su `practice.waielts.com` (viola `#6c18cc`, pulsanti a pillola, stesso font).

Contenuti basati su:
- lo Strategic Blueprint v1.3 (17 agosto 2026) del founder, letto da Notion il 9 ottobre 2026;
- il sito reale `waieltsacademy.com.au` (Home, About Us, Packages, Private Lessons, About IELTS), letto integralmente il 9 ottobre 2026: team di 6 coach, 6 pacchetti di pricing reali in AUD, 3 testimonianze vere, contatti reali (WhatsApp, email);
- `practice.waielts.com` (già live) come riferimento del sistema di marca;
- Mindvalley come riferimento estetico.

## Sezioni e interazioni

Hero, fascia di trasformazione, differenziatori, programma a tab per le 4 abilità IELTS, team, pricing, carosello testimonianze, ecosistema prodotti, FAQ ad accordion, call to action. Interazioni implementate in JS vanilla: scroll-reveal via IntersectionObserver, nav con stato attivo in base alla sezione visibile (scroll-spy), tab del programma, accordion FAQ, carosello testimonianze con rotazione automatica.

Per vederla in locale basta aprire `index.html` nel browser.

## Note aperte

- **Migrazione dominio**: questa pagina assume che `waielts.com` diventi il dominio root di questo sito e che l'attuale piattaforma di pratica si sposti su `practice.waielts.com`. La migrazione DNS/hosting è un'azione separata, da fare lato infrastruttura.
- **Prenotazioni e acquisti**: i pulsanti "Book free info session" e "Select" sui pacchetti puntano alle pagine reali già funzionanti su `waieltsacademy.com.au`, perché questo sito non ha ancora un proprio motore di prenotazione/pagamento. Da aggiornare quando ne avrà uno nativo.
- **Immagini**: su richiesta esplicita, questa versione non include fotografia reale di persone. Il team è rappresentato con iniziali, non foto.
