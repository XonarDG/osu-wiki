# Rozhraní

Tento článek vysvětluje vše, co potřebujete vědět o používání herního klienta osu!. Najdete zde informace ohledně obrazovky výběru skladby, ukazatele žebříčků a obrazovky výsledného skóre. Po spuštění herního klienta se zobrazí následující obrazovka:

![](img/intro-screen.jpg "Úvodní obrazovka")

## Hlavní menu

![](img/main-menu.jpg "Hlavní menu")

- \[1\] [osu! sušenka](/wiki/Client/Interface/Cookie). Po kliknutí na ní se zobrazí hlavní menu. Pulsuje podle [BPM](/wiki/Beatmapping/Beats_per_minute) hudby a kolem se roztahují sloupce, které vizualizují zvukové spektrum. Pokud se nepřehrává žádná skladba, pulzuje pomalým tempem 60 BPM.
- \[2\] Kliknutím na `Play` (nebo stisknutím `P`) si můžete zahrát hru osu! sami nebo s ostatními.
- \[3\] Kliknutím na `Edit` (nebo stisknutím `E`) upravíte [beatmapu](/wiki/Beatmap).
- \[4\] Kliknutím na `Options` (nebo stisknutím `O`) otevřete postranní panel [nastavení](/wiki/Client/Options).
- \[5\] Kliknutím na `Exit` (nebo stisknutím `Esc`) ukončíte hru.
- \[6\] Náhodný užitečný tip.
- \[7\] [ppy](https://ppy.sh/) logo s autorskými informacemi. Odkazuje na [osu! webovou stránku](https://osu.ppy.sh/home).
- \[8\] Pokud se vyskytnou problémy s připojením na [Bancho server](/wiki/Bancho_(server)) zobrazí se zde ikona rozbitého řetězu.
- \[9\] [Herní chat](/wiki/Client/Interface/Chat_console) a vlevo od něj tlačítko pro jeho rozšíření, které zobrazuje seznam aktuálně online uživatelů. Dá se také vyvolat pomocí `F8` a `F9`.
- \[10\] Hra obsahuje svůj vlastní přehrávač hudby, který náhodně přehrává skladby z vaší knihovny. Popis tlačítek níže.
- \[11\] Počet dostupných [beatmap obtížností](/wiki/Beatmap/Difficulty), doba, po kterou hrajete, a váš systémový čas.
- \[12\] Váš profil. Kliknutím na něj se zobrazí [možnosti uživatele](#user-options).

---

Herní přehrávač má následující tlačítka:

| Tlačítko | Popis |
| :-: | :-- |
| ![](img/jukebox/previous-track.jpg "Previous track") | Předchozí skladba |
| ![](img/jukebox/play.jpg "Play") | Play |
| ![](img/jukebox/pause.jpg "Pause") | Pause |
| ![](img/jukebox/stop.jpg "Stop the music!") | Zastavení přehrávání a přesunutí skladby na začátek |
| ![](img/jukebox/next-track.jpg "Next track") | Následující skladba |
| ![](img/jukebox/view-song-info.jpg "View song info") | Přepínač mezi trvalým zobrazením informací o aktuální skladbě a jejich zhasnutím po určité době. |
| ![](img/jukebox/jump-to-window.jpg "Jump To window") | Přeskočení na konkrétní skladbu. Skladby můžete vyhledávat nebo filtrovat podle kolekce. |

Herní přehrávač lze ovládat také pomocí [klávesových zkratek](/wiki/Client/Keyboard_shortcuts#jukebox).

## Možnosti uživatele

![](img/user-options.jpg "User options")

Na tuto obrazovku se dostanete kliknutím na svůj profil v levé horní části hlavní nabídky. Kteroukoli položku můžete vybrat stisknutím jejího příslušného čísla:

- `1. View Profile`: Zobrazí váš profil na webových stránkách.
- `2. Sign Out`: Odhlášení z vašeho účtu. Po odhlášení vás hra vyzve k opětovnému přihlášení.
- `3. Change Avatar`: Otevře [stránku na úpravu avataru](https://osu.ppy.sh/home/account/edit#avatar).
- `4. Close`: Zavře toto dialogové okno.

## Play menu

![](img/play-menu.jpg "Play menu")

Po vybrání `Play` v hlavním menu, dostanete tři možnosti:

- Klikněte `Solo` (nebo stiskněte `P`) pro samostatné hraní. Tato možnost vede na [obrazovku výběru skladby](#song-select).
- Klikněte `Multi` (nebo stiskněte `M`) pro hraní s více hráči. Tato možnost vede do [Multi](/wiki/Client/Interface/Multiplayer) Lobby.
- Klikněte `Back` pro návrat do hlavního menu.

## Místnost pro více hráčů

*Hlavní stránka: [Multi](/wiki/Client/Interface/Multiplayer)*

![](img/multi-lobby.jpg "Multiplayer lobby")

Místnost pro více hráčů, anglicky "Multiplayer lobby", umožňuje hrát spolu nebo proti ostatním hráčům.

## Výběr skladeb

![](img/song-selection.jpg "Song select")

Anglicky "Song select".
Ikona momentálně vybraného [herního módu](/wiki/Game_mode) jde vidět v možnostech dole vlevo, nad `Mode`. Ikona módu lze také matně vidět uprostřed obrazovky. V osu! jsou čtyři herní módy:

- ![](/wiki/shared/mode/osu.png) je [osu!](/wiki/Game_mode/osu!)
- ![](/wiki/shared/mode/taiko.png) je [osu!taiko](/wiki/Game_mode/osu!taiko)
- ![](/wiki/shared/mode/catch.png) je [osu!catch](/wiki/Game_mode/osu!catch)
- ![](/wiki/shared/mode/mania.png) je [osu!mania](/wiki/Game_mode/osu!mania)

Než budete pokračovat, tato obrazovka obsahuje příliš mnoho prvků, než aby bylo možné je poznamenat pomocí snadno viditelných čísel. V následujících podkapitolách se zaměříme vždy na jednu část obrazovky, a to shora dolů a zleva doprava.

### Informace beatmapy

![](img/metadata-comparison.jpg)

Tato část zobrazuje **informace o aktuálně vybrané obtížnosti.** Po vstupu do obrazovky výběru skladeb se automaticky zvolí skladba, která hrála v hlavním menu. Ikona vlevo nahoře reprezentuje [kategorii beatmapy](/wiki/Beatmap/Category), která je na tomto obrázku [hodnocená](/wiki/Beatmap/Category#ranked).

Název skladby se obvykle zobrazuje romanizovaně (dolní obrázek), ale pokud zapnete v [Nastavení](/wiki/Client/Options) možnost `Preferovat metadata v originálním jazyce`, název se ukáže v unicódu (horní obrázek). Název obtížnosti je mezi hranatými závorkami (`[]`). Tvůrce mapy je pod názvem mapy, níže najdeme další informace. Zleva doprava, hodnoty jsou:

- **Délka**: Celková délka mapy od začátku do konce včetně přestávek. Nezaměňovat s [drain time](/wiki/Gameplay/Drain_time).
- **BPM**: *Úhozy za minutu*, tempo skladby. Pokud jsou zde uvedeny dvě hodnoty a jedna v závorce, znamená to, že se BPM v průběhu skladby mění. Zobrazuje nejpomalejší a nejrychlejší BPM. Honota v závorce je nejčastější BPM v beatmapě.
- **Objekty**: Celkový počet [objektů](/wiki/Hit_object) v beatmapě.
- **Kruhy**: Celkový počet [kruhů](/wiki/Hit_object/Hit_circle) (osu! a osu!taiko), [fruits](/wiki/Hit_object/Fruit) (osu!catch), nebo normálních not v (osu!manii) v beatmapě.
- **Slidery**: Celkový počet [sliderů](/wiki/Hit_object/Slider) (osu!), drumrolls (osu!taiko), [fruit streams](/wiki/Hit_object/Juice_stream) (osu!catch), nebo hold not (osu!mania) v beatmapě.
- **Spinnery**: Celkový počet [spinnerů](/wiki/Hit_object/Spinner) (osu!), dendens (osu!taiko), nebo [banana showers](/wiki/Hit_object/Banana) (osu!catch) v beatmapě.
- **OD**: [Overall difficulty](/wiki/Beatmapping/Overall_difficulty) beatmapy.
- **HP**: [HP drain rate](/wiki/Beatmapping/HP_drain_rate). Více o [health](/wiki/Gameplay/Health).
- **Stars**: [Star rating](/wiki/Beatmapping/Star_rating) beatmapy. Počet hvězd je také snadno viditelný na záložce beatmapy.

### Seskupování a seřezování

![](img/beatmap-filters.jpg)

Kliknutím na jednu ze záložek **seřadíte nebo seskupíte seznam skladeb podle vybráného kritéria**.

#### Seskupení

Tyto možnosti seskupí beatmapy do různých skupin:

| Seskupení | Popis |
| :-: | :-- |
| `Žádné seskupení` | Beatmapy nebudou seskupeny, ale budou stále seřazeny podle Seřazení |
| `Podle Obtížnosti` | Beatmapy budou seskupeny podle jejich Star ratingu. |
| `Podle Umělce` | Beatmapy budou seskupeny podle prvního písmena názvu umělce skladby. |
| `Nedávno Hrané` | Beatmapy budou seskupeny podle toho kdy jste je naposledy hráli. |
| `Kolekce` | Zobrazí kolekce které jste vytvořili. *Pozor! Toto skryje veškeré mapy které nejsou v kolekci/ích.* |
| `Podle BPM` | Beatmapy budou seskupeny do skupin po 60 BPM. |
| `Podle Autora` | Beatmapy budou abecedně seskupeny podle prvního písmena názvu autora. |
| `Podle Data Přidání` | Beatmapy budou seskupeny podle data přidání, od dneška až po 5 a více měsíců zpět |
| `Podle Délky` | Beatmapy budou seskupeny podle délky: 1 minut(a) nebo méně, 2 minut(a) nebo méně, 3, 4, 5, 10, a přes 10 minut. |
| `Podle Módu` | Beatmapy budou seřazeny podle jejich herního módu. |
| `Podle Dosáhnutého Ranku` | Beatmapy budou seskupeny podle nejlepšího dosaženého [ranku](/wiki/Gameplay/Grade). |
| `Podle Názvu` | Beatmapy budou abecedně seskupeny podle prvního písmena jejich názvu. |
| `Oblíbené` | Zobrazí pouze mapy které jste si online oblíbili. |
| `Moje Mapy` | Zobrazí pouze mapy které jste namapovali (tj. ty u kterých se jméno autora shoduje s vaším jménem ve hře). |
| `Status Hodnocení` | Beatmapy budou seskupeny podle jejich statusu: hodnocené, kvalifikované, nevyřízené, nepředložené, nebo loved.  |

Prvních 5 je vyvolatelných pomocí záložek pod Skupina a Seřadit.

#### Seřezování

Seřadí mapy v určitém řádu.

| Kritérium řazení | Popis |
| :-: | :-- |
| `Podle Umělce` | Beatmapy budou abecedně seřazeny podle názvu umělce. |
| `Podle BPM` | Beatmapy budou seřeazeny od nejvyššího po nejnižší, pokud má mapa více BPM bere se to nejvyšší. |
| `Podle Autora` | Beatmapy budou abecedně seřazeny podle jejich autora. |
| `Podle Data Přidání` | Beatmapy budou seřazany podle toho kdy byly přidány, od nejstraší po nejnovější. |
| `Podle Obtížnosti` | Beatmapy budou seřazeny podle jejich Star ratingu, od nejjednodušší po nejtěžší. *Pozor! Toto rozdělí obtížnosti beatmap.* |
| `Podle Délky` | Beatmapy budou seřazeny podle jejich délky, od nejkratší po nejdelší. |
| `Podle Dosáhnutého Ranku` | Beatmapy budou seřazeny podle na nich dosaženém ranku, od nejhoršího po nejlepší. |
| `Podle Názvu` | Beatmapy budou abecedně seřazeny podle jejich názvu. |

### Hledání

![](img/search-bar.jpg)

*Poznámka: Při hledání nemůžete mít otevřený chat nebo postraní panel nastavení, pokud tomu tak bude všechno co napíšete bude vnímáno jako chatovací text nebo hledání v postraním panelu nastavení. *

Po vyhledání se zobrazí pouze beatmapy splňující vámi zadanými kritérii. Ve výchozím stavu bude každé hledání srovnáváno s umělci, názvy, autory, a tagy beatmapy.

Kromě hledání jste taky schopni používat filtry, pomocí kterých můžete hledat v dalších metadatech, a to spojením jednoho z podporovaných filtrů se srovnávacím znaménkem a hodnotou(např. `ar=9`).

Podporované filtry:

| Filtr | Popis |
| :-: | :-- |
| `artist` | Název umělce |
| `creator` | Název autora |
| `title` | Název skladby |
| `difficulty` | Název obtížnosti |
| `ar` | [Approach Rate](/wiki/Beatmapping/Approach_rate) |
| `cs` | [Circle Size](/wiki/Beatmapping/Circle_size) |
| `od` | [Overall Difficulty](/wiki/Beatmapping/Overall_difficulty) |
| `hp` | [HP drain rate](/wiki/Beatmapping/HP_drain_rate) |
| `key`, `keys` | Počet kláves (pouze beatmapy osu!mania nebo jejich koverty) |
| `star`, `stars` | [Star rating](/wiki/Beatmapping/Star_rating) |
| `bpm` | BPM, *úhozy za minutu* |
| `length` | Délka v sekundách |
| `drain` | [Drain time](/wiki/Gameplay/Drain_time) v sekundách |
| `mode` | Herní mód. Může být `osu`, `taiko`, `catch`, nebo `mania`, nebo `o`/`t`/`c`/`m` ve zkratkách. |
| `status` | Status beatmapy. Může být `ranked`, `approved`, `pending`, `notsubmitted`, `unknown`, nebo `loved`, nebo `r`/`a`/`p`/`n`/`u`/`l` ve zkratkách. |
| `played` | Čas uběhlý od posledního zahrání ve dnech. |
| `unplayed` | Zobrazí pouze nehrané mapy. Musí se použít porovnání bez hodnoty (např. `unplayed=`). Porovnání je ignorováno. |
| `speed` | Uložená rychlost beatmapy v osu.manii. Pro nehrané mapy vždy 0 nebo pokud je možnost [`Pamatovat si na osu!manii rychlost dráhy`](/wiki/Client/Options#gameplay) vypnutá. |

Podporovaná srovnání:

| Srovnání | Popis |
| :-: | :-- |
| `=` nebo `==` | Je rovno |
| `!=` | Není rovno |
| `<` | Méně než |
| `>` | Více než |
| `<=` | Méně nebo rovno |
| `>=` | Více nebo rovno |

Můžete také vyhledat ID číslo obtížnosti a dostat jeden výsledek, tedy pokud hledanou mapu máte.

### Žebříčky

![](img/leaderboards.jpg)

 V žebříčcích se mohou nacházet:

- Oznámení `Not Submitted` oznamuje že beatmapa nebyla nahrána na osu! webovou stránku pomocí [Beatmap Submission System](/wiki/Submission) nebo byla vymazána autorem.
- Oznámení `Update to latest version` se ukáže pokud je pro beatmapu dostupná nová verze. Klikněte pro stáhnutí aktualizace.
  - *Upozornění: Po aktualizaci mapy se vymažou veškerá lokální scóre na mapě. Replaye se dají uložit pravým kliknutím na scóre.*
- Oznámení `Latest pending version` znamená že mapa sice je nahraná na osu! webovou stránku, ale není hodnocená.
- Pokud existují replaye, respektive skóre, odpovídající nastavení žebříčkům, budou zobrazeny namísto ostatních oznámení. Toto je možno vidět na obrázku výše.
  - Pod veřejnými žebříčky (např. Globální, Státní, etc.), je zobrazeno vaše nejlepší skóre i s vašim umístěním na žebříčku beatmapy.
- Oznámení `No records set!` znamená že pro aktuální nastavení žebříčku nejsou žádné replaye dostupné (najčastěji se objevuje v lokálním žebříčku pokud byla beatmapa právě stáhnuta nebo změnena).

Zde jsou všechna nastavení žebříčku:

- Lokální
- Státní\*
- Globální
- Globální (podle zvoleného módu)\*
- Přátelé\*

\*Vyžaduje [osu!supporter](/wiki/osu!supporter).

Kliknutím na ikonu bublin se vyvolá  **rychlý webový přístup k této beatmapě**:

- Stiskněte `1` nebo klikněte na `Beatmap Listing/Scores` pro otevření stránky beatmapy ve vašem webovém prohlížeči.
- Stiskněte `2` nebo klikněte na `Beatmap Modding` pro otevření [modding](/wiki/Modding) stránky beatmapy.
- Stiskněte `3`, `Esc` nebo klikněte na `Cancel` pro vrácení do obrazovky výběru skladby.

### Beatmap menu

![](img/beatmap-cards.jpg)

Beatmapové menu zobrazuje všechny dostupné beatmapy. Odlišné beatmapy mohou mít jiné barvy:

| Barva boxu | Popis |
| :-: | :-- |
| **Růžová** | Tato beatmapa nebyla dosud hrána. |
| **Oranžová** | Alespoň jedna obtížnost beatmapy byla dokončena. |
| **Světle modrá** | Beatmapa má více než jednu obtížnost. |
| **Bílá** | Aktuálně vybraná obtížnost. |

Seznam beatmap můžete posunovat kolečkem u myši, kurzorovými klávesami, tažením a podržením levého tlačítka myší nebo držením pravého tlačítka myši (známé jako absolutní scrollování), které posune seznam na Y pozici myši. Kliknutím na mapu vyberete mapu, poté ji klikněte znovu, nebo stiskněte `Enter` nebo klikněte osu! cookie v pravém dolním rohu pro spuštění beatmapy.

### Herní nástroje

![](img/game-mode-selector.jpg "Seznam dostupných herních módů")

![](img/gameplay-toolbox.jpg)

Tato část se může nazývat Sadou Herních Nástrojů. Budeme se věnovat jednotlivým tlačítkům zleva doprava.

Stikněte `Esc` nebo klikněte tlačítko `Back` pro vrácení do hlavního menu.

Klikněte na tlačítko `Mode` a otevře se vám seznam herních módů v osu!. Alternativně můžete stisknout `Ctrl` společně s `1` (osu!), `2` (osu!taiko), `3` (osu!catch), nebo `4` (osu!mania) a změnit tím herní mód. Přepnutím do jiného herního módu se přepnou i [žebříčky](/wiki/Ranking), což lze také vidět na změně vašeho ranku.

![](img/game-modifiers.jpg "Okno výběru modifikací")

Klikněte na tlačítko `Mods` nebo stiskněte `F1` pro otevření **[okno výběru modifikací](/wiki/Game_modifier)**.

In this screen, you can apply modifications ("mods" for short) to gameplay. Some mods lower difficulty and apply a multiplier that lowers the score you achieve. Conversely, some mods increase the difficulty, but apply a multiplier that increases the score you achieve. Finally, some mods modify gameplay in a different way. [Relax](/wiki/Game_modifier/Relax) and [Auto Pilot](/wiki/Game_modifier/Autopilot) fall in that category.

Place your mouse on a mod's icon to see a short description of its effect. Click on an icon to select or deselect that mod. Some mods, like Double Time, have multiple variations — click on the mod again to cycle through them. The score multiplier value displays the combined effect all selected mods will have on your score. Click `Reset all mods` or press `1` to deselect all currently selected mods. Click `Close` or press `2` or `Esc` to return to the song selection screen.

Click the `Random` button or press `F2` to have the game **randomly scroll through all of your beatmaps and pick one.**

*Note: You can press `Shift` + the `Random` button or `F2` to go back to the beatmap you had selected before you randomised your selection.*

![](img/beatmap-options.jpg "Possible commands for a beatmap")

Click the `Beatmap Options` button, press `F3` or right-click your mouse while hovering over the beatmap to bring up the **beatmap options menu for options on the currently selected beatmap**.

- Press `1` or click the `Manage Collections` button to bring up the collection manager — here, you can manage pre-existing collections, as well as add or remove the currently selected beatmap or mapset to or from a collection.
- Press `2` or click `Delete...` to delete the \[1\] currently selected difficulty, \[2\] delete the currently selected beatmap, or \[3\] delete **all VISIBLE beatmaps**.
  - Note that deleted beatmaps are moved to the Recycle Bin.
- Press `3` or click `Remove from Unplayed` to mark an unplayed beatmap as played (that is, change its box colour from pink to orange).
- Press `4` or click `Clear local scores` to delete all records of the scores you have achieved in this beatmap.
- Press `5` or click `Edit` to open the selected beatmap in osu!'s editor.
- Press `6` or `Esc` or click `Close` to return to the song selection screen.

Click on **your user panel** to access the **user options menu**.

Click on the **[osu! cookie](/wiki/Client/Interface/Cookie)** to **start playing the selected beatmap**.

## Results screen

![](img/results-osu.jpg "Accuracy in osu!")

This is the results screen shown after you have successfully passed the beatmap. You can access your online results by scrolling down or pressing the obvious button.

Below are the results screens of the other game modes.

![](img/results-taiko.jpg "Accuracy in osu!taiko")

![](img/results-mania.jpg "Accuracy in osu!mania")

![](img/results-catch.jpg "Accuracy in osu!catch")

### Extended results screen

![](img/extended-results-screen.jpg "An example of an online osu! score")

This is your online leaderboard. You can go here by scrolling down from the results screen. Your local scoreboard will show your name and the score as usual.

- \[1\] Your user panel. It shows your [performance points (pp)](/wiki/Performance_points), global rank, total score, overall [accuracy](/wiki/Gameplay/Accuracy), and level bar.
- \[2\] `Save replay to Replays folder`: You can watch the replay later either by opening it from a local leaderboard, or by going to `Replays` directory and double clicking it.
- \[3\] `Add as online favourite`: Include the beatmap into your list of favourites, which is located on your osu! profile page under the `Beatmaps` section.
- \[4\] Local leaderboard: All your results are stored on your computer. To see them, navigate to the [song selection screen](#song-select) and select `Local Rankings` from the drop-down menu above the scoreboard.
- \[5\] `Beatmap Ranking` section. Available only for maps with online leaderboards ([qualified](/wiki/Beatmap/Category#qualified), [ranked](/wiki/Beatmap/Category#ranked), or [loved](/wiki/Beatmap/Category#loved)). You also need to be online to see this section. See below for more details.
- \[6\] `Overall Ranking` section. It's available only for beatmaps with online leaderboards. You also need to be online to see this section. See below for more details.
- \[7\] Information about the beatmap with its play count and pass rate.
- \[8\] Beatmap rating. Use your personal discretion based on whether you enjoyed the beatmap or not. Best left alone if you can't decide.
- \[9\] Click here to return to the song selection screen.

---

The categories in the ranking panel are as follows:

| Category | Beatmap Ranking | Overall Ranking |
| :-: | :-- | :-- |
| `Overall` | Your position on the map's leaderboard. Note that scores with [mods](/wiki/Game_modifier) also appear on this same leaderboard. | Your [global rank](/wiki/Ranking#performance-points-ranking) against everyone in the world. |
| [`Accuracy`](/wiki/Gameplay/Accuracy) | How accurately you played the beatmap. This is only counted when your old score is surpassed. | A weighted average of the accuracy of your best scores. |
| `Max Combo` | The longest combo on the map you played. | The longest combo over all beatmaps you have played. |
| [`Ranked Score`](/wiki/Gameplay/Score/Ranked_score) | Your [best result](/wiki/Gameplay/Score/Ranked_score) on the beatmap. | The number of points earned from all ranked beatmaps that you have ever played, with every map being counted exactly once. |
| [`Total Score`](/wiki/Gameplay/Score/Total_score) | Not taken into account, since it does not affect your position in online rankings. | Same as ranked score, but it takes into account all beatmaps available on the osu! website, including underplayed or failed beatmaps. This counts towards your [level](/wiki/Gameplay/Score/Total_score#level). |
| [`Performance`](/wiki/Performance_points) | The amount of [unweighted pp](/wiki/Performance_points#why-didn't-i-gain-the-full-amount-of-pp-from-a-map-i-played?) you would receive for the play. | Your total amount of performance points, and how much pp the submitted play was worth. |

### Medals

*Main page: [Medals](/wiki/Medals)*

![](img/medal-unlock.jpg "Unlocking a medal")

Sometimes, when specific conditions are met, you may receive a medal.
