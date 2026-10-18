# Objectiu 10 · Aplicació d'estudi FIB

Aplicació gratuïta, estàtica i en català per al primer parcial de PRO1, IC, Física i FM. Inclou calendari desglossat en tasques curtes, 157 entrades de problemes Jutge.org (155 codis únics), enllaços a teoria i exàmens, 91 targetes de repàs inicials, formulari de Física (CC i CA), i còpia de seguretat de progrés.

## Publicació gratuïta a GitHub Pages

1. Descomprimeix l'arxiu ZIP. Crea un repositori **públic** nou a GitHub, per exemple `objectiu10`.
2. Puja **tot el contingut de la carpeta `objectiu10`** a l'arrel del repositori: `index.html`, `app.js`, `style.css`, `data.js`, `manifest.webmanifest`, `icon.svg`, `sw.js` i la carpeta `materials`.
3. A **Settings → Pages → Build and deployment**, tria **Deploy from a branch**, branca **main**, carpeta **/(root)**, i desa.
4. Obre `https://EL-TEU-USUARI.github.io/objectiu10/`. La publicació pot trigar uns minuts.
5. A Safari d'iPhone: icona de compartir → **Afegir a la pantalla d'inici**.

## Notes importants

- Les dades de progrés es guarden al `localStorage` del navegador i dispositiu. A **Eines → Exporta progrés** pots generar un JSON de còpia de seguretat. Importa'l al nou dispositiu si canvies de navegador.
- Les notificacions de sistema no estan implementades: l'app no envia alertes automàtiques, ni se sincronitza entre aparells.
- La interfície i les targetes són en català; els PDF originals (alguns en castellà i anglès) conserven la llengua d'origen.
- Jutge.org no queda connectat automàticament: cal marcar manualment si un exercici s'ha fet sense ajuda, amb ajuda o queda pendent.
- Tres simulacres principals i una prova breu el dia de l'examen per assignatura. El 29/10 el simulacre d'IC és després de PRO1; el 03/11 el de FM és després de Física.
- La jornada del 25/10 concentra moltes tasques: revisa l'estimació i descansa. La memòria de conceptes del 20/10 i del 25/10 és un objectiu, no una garantia.
- El formulari és una base extensa de consulta però cal contrastar les convencions de signes i les condicions de cada exercici amb els apunts del professor.
- Pots usar `python -m http.server 8000` dins de la carpeta per provar-la localment des d'un ordinador. No obrint `index.html` amb `file://` si vols provar la instal·lació PWA.
