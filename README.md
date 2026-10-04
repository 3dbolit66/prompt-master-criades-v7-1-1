# Prompt Master Criades V7.1.1

Correcció de V7.1.0.

## Fix principal
El motor bilingüe quedava en blanc perquè el JavaScript intentava llegir un control intern inexistent (`wear`) quan construïa l'escena narrativa. Això provocava un error d'execució just després de generar el prompt d'imatge.

V7.1.1 elimina aquesta referència incorrecta. En prémer **Generar**, el camp **TEXT GENERAT · ESPAÑOL + ENGLISH** s'ha d'omplir directament amb el text final en castellà i anglès.

## GitHub Pages
El ZIP inclou `index.html` a l'arrel.
