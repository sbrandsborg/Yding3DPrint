# Yding3DPrint

Dette repository indeholder koden til [yding3dprint.dk](https://yding3dprint.dk). Koden er gjort offentligt for at sikre fuld transparens omkring priser og beregninger.

Et simpelt statisk website med en prisberegner til 3D print. Siden giver information om Yding 3D Print og beregner en estimeret pris baseret på materialeforbrug og printtid.

## Sådan bruges siden
1. Åbn `index.html` i en moderne webbrowser.
2. Indtast dit forventede filamentforbrug og printtid.
   - Alternativt kan felterne forudfyldes via URL'en, f.eks. `index.html?filament=50&printtid=2&navn=Testprint`.
3. Klik på **Beregn Pris** for at se den beregnede pris.

## Udvikling
Koden kan valideres med [HTMLHint](https://github.com/htmlhint/HTMLHint):

```bash
npx --yes htmlhint index.html
```

Ændringer til filerne bør committes via git.

