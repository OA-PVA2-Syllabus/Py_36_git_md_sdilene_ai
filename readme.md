# Zadání týmového projektu na téma AI

## Cíl projektu
Vytvořit týmový projekt, ve kterém každý student vytvoří samostatnou kapitolu na téma AI. Každá kapitola bude umístěna v unikátním souboru a všechny kapitoly budou propojeny odkazem v souboru README. Projekt bude obsahovat základní úvod, představení týmu a rozdělení odpovědností.

## Struktura projektu
1. **README soubor**:
   - Úvod do projektu
   - Představení členů týmu a jejich odpovědností
   - Odkazy na jednotlivé kapitoly

2. **Kapitoly**:
   - Každý člen týmu vytvoří jednu kapitolu na zadané téma
   - Každá kapitola bude v samostatném markdown souboru
   - Kapitoly budou propojeny v README souboru

## Zadání pro jednotlivé členy týmu
Každý student vytvoří svou kapitolu individuálně. 

<details>
<summary><strong>Nevíte jaké zvolit téma kapitoly?</strong></summary>


### Návrh témat 
Pokud si nevíte rady, můžete vyúžít následující témata
- Definice AI
- Historie AI
- Základní pojmy a technologie
- Prompty a jejich tvorba
- AI v software developmentu (např. programátoři, analytici, projektoví manageři)
- AI v průmyslu (např. zdravotnictví, finance, doprava)
- AI v každodenním životě (např. virtuální asistenti, chytré domy)
- Příklady a případové studie
- Predikce vývoje AI
- Etické a sociální otázky
- Možné dopady na trh práce a společnost
- apod
</details>

## Požadavky na obsah
- Každá kapitola musí obsahovat:
  - Úvod
  - Hlavní část s podrobným vysvětlením
  - Závěr
  - Citace a zdroje informací
- Formátování musí být v souladu s pravidly Markdown:
  - Nadpisy, odstavce, seznamy, odkazy, obrázky, citace a bloky kódu
- Každý soubor musí být pojmenován podle zadání a umístěn v kořenovém adresáři projektu

## README soubor
- **Úvod do projektu**
  - Stručné představení tématu
  - Cíl projektu

- **Představení týmu**
  - Jména členů týmu
  - Stručný popis odpovědností každého člena

- **Odkazy na jednotlivé kapitoly**
  - Seznam odkazů na jednotlivé soubory s kapitolami

## Rozdíl mezi individuální a týmovou prací
- **Individuální práce**:
  - Každý student pracuje samostatně na svém úkolu.
  - Odpovědnost za kvalitu a včasné dokončení práce nese jednotlivý student.
  - Komunikace a koordinace nejsou nutné.

- **Týmová práce**:
  - Studenti spolupracují na společném cíli.
  - Odpovědnost je rozdělena mezi členy týmu.
  - Vyžaduje efektivní komunikaci a koordinaci mezi členy týmu.
  - Nutnost plánování a rozdělení úkolů tak, aby byly dodrženy termíny a celková kvalita práce.

## Doporučený postup pro týmovou práci
  
  1. **Vytvoření repozitáře**:
     - Jeden člen týmu vytvoří nový repozitář na GitHubu.
     - Nastaví repozitář jako veřejný nebo soukromý a přidá ostatní členy týmu jako spolupracovníky.
     - Vytvoří základní strukturu projektu s README souborem.

  2. **Klonování repozitáře**:
     - Každý člen týmu si naklonuje repozitář do svého lokálního počítače pomocí příkazu:
       ```sh
       git clone <URL_repozitáře>
       ```

  3. **Vytvoření nové větve**:
     - Každý člen týmu vytvoří novou větev pro svou práci:
       ```sh
       git checkout -b <jmeno_vetve>
       ```

  4. **Práce na kapitole**:
     - Každý člen týmu pracuje na své kapitole ve své větvi.
     - Pravidelně ukládá změny pomocí příkazů:
       ```sh
       git add .
       git commit -m "Popis změny"
       ```

  5. **Push změn do repozitáře**:
     - Po dokončení práce na kapitole každý člen týmu pushne své změny do GitHubu:
       ```sh
       git push origin <jmeno_vetve>
       ```

  6. **Vytvoření Pull Requestu**:
     - Na GitHubu vytvoří každý člen týmu Pull Request ze své větve do hlavní větve (např. `main`).
     - Ostatní členové týmu zkontrolují Pull Request a případně navrhnou úpravy.

  7. **Sloučení změn**:
     - Po schválení Pull Requestu sloučí změny do hlavní větve.
     - Každý člen týmu si poté aktualizuje svůj lokální repozitář:
       ```sh
       git checkout main
       git pull origin main
       ```

  8. **Dokončení a kontrola projektu**:
     - Zkontrolujte, zda jsou všechny kapitoly propojeny v README souboru.
     - Proveďte finální úpravy a zkontrolujte celkovou kvalitu projektu.
     - Připravte finální verzi projektu k odevzdání.
