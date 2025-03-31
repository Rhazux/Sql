2. Popis entit a jejich vztahů

Clanek:
id – Unikátní identifikátor článku.
nadpis – Název článku.
perex – Krátké shrnutí.
obsah – Celý obsah článku.
datum_vytvoreni – Kdy byl článek vytvořen.
datum_upravy – Kdy byl naposledy upraven.

Kategorie
id – Unikátní ID kategorie.
nazev – Název kategorie (např. "Novinka", "Blog").

Galerie
id – Unikátní ID obrázku.
clanek_id – Odkaz na článek.
obrazek_url – URL adresa obrázku.

Soubory ke stažení
id – Unikátní ID souboru.
clanek_id – Odkaz na článek.
soubor_url – URL souboru.

Clanek_Kategorie
Propojuje články a kategorie, protože jeden článek může spadat do více kategorií.

Clanek_Vazba
Používá se pro propojení článků mezi sebou, například pokud jeden článek odkazuje na jiný.

3. E-R diagram
Pro znázornění struktury databáze lze vytvořit E-R diagram v Draw.io, Lucidchart nebo MySQL Workbench. Návrh zahrnuje všechny klíčové entity a jejich vztahy.
