Cebuano Bubble Pop — UI assets versie

Starten op computer:
  1. Pak deze zip uit.
  2. Open Terminal in deze map.
  3. Run: python3 -m http.server 8000
  4. Open: http://localhost:8000/index.html

Mappen:
  audio/              -> zet hier je mp3/wav uitspraakbestanden
  assets/ui/          -> voorlopige UI PNGs die in het spel gebruikt worden
  assets/words/       -> zet hier woordafbeeldingen, bv. adlaw.png
  gifs/               -> optionele bewegende GIFs, bv. adlaw.gif
  images/             -> extra afbeeldingen

Bestandsnamen:
  adlaw.mp3, Adlaw.mp3, asa_ka.mp3, maayong_buntag.mp3
  adlaw.png, balay.png, tubig.png

Opmerking:
  De tweede UI batch zit erbij als assets/ui/ui_assets_sheet_batch2.png.
  Dat is voorlopig een referentie/sprite sheet, nog niet opgesneden in aparte knoppen.


Nieuwe extra bestanden:
  game_preview.gif       -> geanimeerde preview van de game
  assets/ui/icon_repeat.png
  assets/ui/icon_star.png
  assets/ui/icon_level.png
  assets/ui/icon_round.png
  assets/ui/icon_check.png
  assets/ui/icon_cross.png
  assets/ui/icon_hint.png
  assets/ui/bubble_pink.png
  assets/ui/bubble_orange.png

De index.html is bijgewerkt voor betere weergave op smartphone, tablet en pc.


Voorlopige complete versie:
- De game gebruikt nu echte woord-PNGs voor 10 basiswoorden.
- Visual-vragen kiezen vaker woorden waarvoor echte PNGs bestaan.
- Het spel blijft goed werken op smartphone, tablet en pc.

Nieuwe lijsten:
- TODO_PNG_LIST.txt
- AVAILABLE_WORD_PNGS.txt


V4 complete placeholder-versie:
- Elk woord in de game heeft nu een PNG-bestand.
- Veel woorden gebruiken echte gegenereerde illustraties.
- Waar nog geen echte afbeelding was, staat een tijdelijke placeholder in dezelfde mapstructuur.
- Zie REAL_WORD_PNGS_PRESENT.txt en PLACEHOLDER_PNGS_TO_REPLACE.txt.
- De game zoekt ook naar hyphen/underscore varianten, bv. kan-on.png én kan_on.png.


V6 aanpassingen:
- schonere speelachtergrond zonder rare transparante randen
- GIFs/beelden in bubbels worden niet meer afgeknipt
- bubbels zweven subtiel
- desktopweergave rustiger en minder rommelig


V7 aanpassingen:
- top panels en menu kregen pastel-blauwe spelachtergrond-look
- progressiebalk opnieuw gestyled en mooier geïntegreerd
- lettertype aangepast naar een rondere, vriendelijkere look


V8 aanpassingen:
- audioknop eleganter rechts in het woordpaneel geplaatst
- menu en skip samengebracht in een stijlvolle onderste dock
- op mobiel blijft de dock rechtsonder voor bruikbaarheid


V9 aanpassingen:
- targetwoord krijgt meer verticale ruimte en wordt niet meer afgesneden
- footercontainer is visueel verwijderd; enkel de twee knoppen blijven zichtbaar


V10 polish:
- HUD bovenaan compacter en rustiger
- targetwoord krijgt betere ruimte en uitlijning
- bubbels iets kleiner en netter verdeeld op desktop
- footerknoppen zonder omlijsting, met betere spacing
- responsive layout verder verfijnd voor smartphone, tablet en pc


V11 complete image integration:
- Alle huidige woord-PNGs zijn verwerkt.
- De tijdelijke placeholders zijn vervangen door echte gegenereerde beelden.
- Afbeeldingen zijn opgeschoond naar transparante 512x512 PNGs voor gebruik in de bubbles.
- Bestandsvarianten zoals kan-on/kan_on/kanon en tan-aw/tan_aw/tanaw zijn toegevoegd.
