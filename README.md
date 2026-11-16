# Ruota della Sfortuna

Una ruota della fortuna personalizzabile, interamente in italiano. Funziona nel browser (GitHub Pages) oppure come app per Windows.

## Funzionalità

- Aggiunta, modifica e rimozione delle voci (nomi, numeri, parole, caratteri accentati).
- La ruota si aggiorna a ogni modifica.
- Animazione di rotazione con durata casuale.
- Risultato mostrato al termine del giro.
- Pulsanti per svuotare la lista e ripristinare lo stato iniziale.
- Le voci vengono salvate sul dispositivo.

## Struttura

| File | Descrizione |
|------|-------------|
| `index.html`, `style.css`, `script.js` | L'applicazione |
| `main.js`, `package.json` | Involucro Electron per Windows |
| `.github/workflows/main.yml` | Pubblicazione su GitHub Pages |
| `.github/workflows/build-windows.yml` | Build dell'app per Windows |

## Licenza

MIT. Vedi il file [LICENSE](LICENSE).
