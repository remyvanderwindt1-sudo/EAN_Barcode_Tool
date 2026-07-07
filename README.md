# EAN-13 naar PDF labels (50mm x 25mm)

Deze tool zet een CSV/XLSX bestand om naar een PDF met:

- 1 label per pagina
- instelbaar paginaformaat in mm (standaard **50mm x 25mm**)
- bovenaan: **Naam / Kleur / Maat**
- daaronder: **EAN-13 barcode**
- onder de barcode: **duidelijk leesbare EAN-cijfers**

## Gebruik

1. Open `index.html` in je browser.
2. Upload een `.csv`, `.xlsx` of `.xls` bestand.
3. Controleer de preview + foutenlijst.
4. Stel eventueel **Breedte/Hoogte** in (bijv. `62` en `29`).
5. Klik op **Genereer PDF**.

## Vereiste kolommen

Minimaal deze velden moeten aanwezig zijn:

- `EAN` (13 cijfers, geldige EAN-13 checkdigit)
- `Naam`
- `Kleur`
- `Maat`

De tool accepteert ook varianten zoals `ean`, `ean13`, `name`, `color`, `size`.

## CSV voorbeeld

Zie `voorbeeld.csv`.
