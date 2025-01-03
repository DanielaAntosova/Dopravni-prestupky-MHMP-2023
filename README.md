# 📊 Mini projekt ROZPRACOVANY
[🔗Dopravní přestupky MHMP 2023](https://opendata.praha.eu/datasets/https%3A%2F%2Fapi.opendata.praha.eu%2Flod%2Fcatalog%2F1aba6dfc-0662-4dca-9326-07698e9af0fb)

## Jaká to jsou data? 🧐  

MHMP = Magistrát hl. m. Prahy
 
## Co si na projektu procvičím? 🛠️📚💡

- zpracování dat v **Keboola**
- zpracování dat v **SQL Snowflake** 📊
- tvorba vizualizace v **Power BI** 📈
- git 🖇️💾

## Co zajímavého se podařilo zjistit?
- celkový počet přestupků je cca 947 tis.
- nejvíce přestupků se děje na Praze 4
- nejvyšší počet přestupků se děje v lokalitě Brusnický tunel směr Troja (36 tis.)
- v každém dni roku se stal alespoň jeden přestupek
- nejvíce přestupků se stalo 19.4.2023 (3 705). Jednalo se o středu - běžný pracovní den.

## Bude třeba dost čistit - sloupce:
- u sloupce **CASSK** formát zobecnit na HH:MM
- **MISTOSK**:

  
- rozdělit na ulici (čistím tam, kde je aspoň 10 výskytů, aby to bylo rozumné)
- číslo,
- typ umístění (u domu/u sloupu veřejného osvětlení),
- číslo sloupu veřejného osvětlení

  
- **PRAHA** - sjednotit
- **MPZ** - sjednotit, zda opravdu každý textový řetězec odpovídá nějaké zemi a zaměřit se na znaky, které nedávají smysl
- **TOVZN** - udělat nějaký sloupec, kde bude základní značka
- **PRAVFOR** - dát k tomu něco normálního, aby tomu člověk rozuměl
