# CLAUDE.md

Repo: infofrankrijk-klussen-archief

## Wat dit is
Statische pagina met het klus- en forumarchief van Infofrankrijk: een lijst YouTube-video's per categorie en een link naar een NotebookLM-notebook.

## Live adres
Niet in de repo vastgelegd

## Opbouw
- index.html: de archiefpagina, met de lijst mediaLijst in een script
- generator.html: hulpformulier (Infofrankrijk Video Tool) dat een blokje code maakt voor mediaLijst
- search-preview.png: voorbeeldafbeelding
- LICENSE

## Techniek
Eén statische HTML-pagina zonder build. Tailwind via cdn.tailwindcss.com, Font Awesome via cdnjs, Google Fonts, JavaScript inline.

## Externe diensten en namen van omgevingsvariabelen
Geen omgevingsvariabelen. Externe diensten: YouTube (embeds), Google NotebookLM (link), Tailwind CDN, cdnjs, Google Fonts.

## Hoe het live gaat
Niet in de repo vastgelegd (geen CNAME, workflow of vercel.json).

## Regels en besluiten
- generator.html (bron: bestand zelf): het gegenereerde blokje wordt bovenaan de lijst mediaLijst in index.html geplakt. Categorieën in de generator: Basis, Techniek, Sanitair, Restauratie, Verwarming, Administratie.

## Laatst nagelopen
Laatst nagelopen: 5 november 2026
