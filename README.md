# 📊 Mini projekt ROZPRACOVANY
[🔗Dopravní přestupky MHMP 2023](https://opendata.praha.eu/datasets/https%3A%2F%2Fapi.opendata.praha.eu%2Flod%2Fcatalog%2F1aba6dfc-0662-4dca-9326-07698e9af0fb)

## 🧐Jaká to jsou data?   

MHMP = Magistrát hl. m. Prahy
 
## 🛠️📚💡Co si na projektu procvičím? 

- zpracování dat v **Keboola**
- zpracování dat v **SQL Snowflake** 📊
- tvorba vizualizace v **Power BI** 📈
- git 🖇️💾

## 🧹Čištění dat:

Při zpracování dat je nutné provést následující úpravy a čištění jednotlivých sloupců:

### Formátování a standardizace

- **⏳CASSK** – Přeformátovat časová data na jednotný formát **HH:MM**.
- **📌PRAHA** – Sjednotit hodnoty.
- **🌍MPZ** – Ověřit, zda každý textový řetězec odpovídá konkrétní zemi, a odstranit nesmyslné znaky.

### Strukturování sloupce `MISTOSK`

Sloupec `MISTOSK` je potřeba rozdělit na následující podsloupce:
- **🏙️Ulice** – Očistit a standardizovat názvy (zachovat pouze ty, které mají alespoň 10 výskytů).
- **🏠Číslo** – Extrahovat číselné označení.

### Další úpravy

- **🚗TOVZN** – Vytvořit nový sloupec obsahující pouze základní značku auta.
- **📖PRAVFOR** – Přidat popis nebo převod hodnot do srozumitelnější podoby.


Toto čištění a standardizace zajistí konzistentní a dobře strukturovaná data, která budou lépe použitelná pro další analýzy.

## Co zajímavého se podařilo zjistit?

![Dashboard screen](https://github.com/DanielaAntosova/Dopravni-prestupky-MHMP-2023/blob/main/Printscreen_dashboardu_prestupku.png "Dashboard_printscreen")

[🔗Dashboard v Power BI](https://github.com/DanielaAntosova/Dopravni-prestupky-MHMP-2023/blob/main/Prestupky.pbix)

![Dashboard screen](https://github.com/DanielaAntosova/Dopravni-prestupky-MHMP-2023/blob/main/Printscreen_dashboardu_prestupku_Tableau.png "Dashboard_printscreen Tableau")



**📊Statistiky přestupků v Praze za rok 2023:**

- ⚠️Celkový počet přestupků: přibližně 947 tisíc.
- 📍Nejvíce přestupků bylo zaznamenáno v městských částech:
  - **Praha 4 – 207 tisíc**
  - Praha 6 – 167 tisíc
  - Praha 5 – 117 tisíc

- 🛣️Nejproblematičtější lokality:
  - **Tunel Cholupice** – 41 tisíc 
  - **Brusnický tunel** (směr Troja) – 36 tisíc 
  - **Jižní spojka** (směr centrum) – 30 tisíc 
- 📖Nejčastější druhy přestupků:
  - Neprokázání se **doklady** potřebnými k řízení a provozu vozidla – 519 tisíc
  - Překročení **rychlosti** v obci o 40+ km/h – 326 tisíc
  

**⏳Časové souvislosti:** 
- Každý den v roce byl zaznamenán **alespoň jeden přestupek**.
- ⬆️Nejvíce přestupků bylo spácháno **19. dubna 2023 (3 705 přestupků)**. Tento den připadal na středu, tedy běžný pracovní den.
- ⬆️Nejvíce přestupků bylo v **dubnu (96 tisíc)** a **říjnu (90 tisíc)**.
- ⬇️Nejnižší počet byl v **prosinci (49 tisíc)**.
- Přestupky rostly na jaře, klesaly v létě, opět rostly na podzim a na konci roku výrazně klesly. 
  - Tento pokles v prosinci může souviset s vánočními svátky a změnami v chování lidí, zatímco jarní a podzimní růsty mohou být spojeny s vyšší aktivitou v těchto obdobích roku.

**🌍Počet přestupků podle registrační značky země**
- **Česká republika** dominuje s 796 tisíci přestupky (85%), což je výrazně více než ostatní kategorie.
- **Ukrajina** je na 2. místě s 44 tisíci (5%) přestupky (asi v důsledku ruské invaze)
- **Neznámá (neuvedená)** registrační značka je 3. s 24 tisíci případy.

Celkově graf ukazuje, že většina přestupků pochází od **domácích** řidičů, zatímco zahraniční vozidla tvoří jen menší podíl. 🚗📊

**🚗Počet přestupků podle značky auta**
- **Škoda** má nejvyšší počet přestupků – 204 tisíc (22%), což je více než dvojnásobek oproti druhé značce.
  - Dominance Škody je logická, protože jde o nejčastější značku aut v Česku, což se odráží i v počtu přestupků.
- **Volkswagen** je na druhém místě se 106 tisíci přestupky (11%).
  - Volkswagen je rovněž velmi populární značka na českých silnicích, což vysvětluje jeho druhé místo.
- **Mercedes-Benz** je třetí s 69 tisíci přestupky (8%).
  - Mercedes-Benz má sice méně přestupků než předchozí dvě značky, ale stále patří mezi nejčastější.

**🏎️Přestupky vozů značky Ferrari v Praze:**

- **Počet přestupků**: 131
- **Lokalita**: Řidiči Ferrari nejčastěji porušují předpisy v **Praze 1**, následované Prahou 4 a Prahou 6.
- Nejčastější **místa** přestupků:
  - **K Barrandovu – pražský okruh**
  - Ulice **Haštalská**
  - **Jižní spojka** (směr Krč)

V typu přestupků a zemi původu řidičů se Ferrari neliší od celkového průměru.






