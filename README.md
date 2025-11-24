# 📚 Kurz-Selenium: Základy Selenium WebDriver pre UI Automatizáciu

[![Selenium](https://img.shields.io/badge/Tool-Selenium%20WebDriver-43B02A.svg?logo=selenium)](https://www.selenium.dev/)
[![Testing Type](https://img.shields.io/badge/Type-UI%20Automation-FFC300.svg)](https://en.wikipedia.org/wiki/User_interface_testing)
[![Language](https://img.shields.io/badge/Language-Python-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)

## 📝 Prehľad projektu

Tento repozitár obsahuje praktické cvičenia, príklady kódu a záverečný projekt z **kurzu Selenium WebDriver**. Projekt slúži na demonštráciu pochopenia základov automatizácie front-endu (UI) a implementácie profesionálnych testovacích vzorov.

## 🧠 Kľúčové naučené koncepty

Projekt pokrýva a implementuje nasledujúce kritické koncepty v automatizácii:

* **Page Object Model (POM):** Implementácia architektonického vzoru pre oddelenie logiky testu od selektorov stránok.
* **Selektory a Lokátory:** Efektívne vyhľadávanie elementov (napr. pomocou XPath, CSS Selector, ID).
* **Synchronizácia:** Správne používanie **Explicit Wait** (očakávaní) na zvýšenie stability testov.
* **Test Runner:** Základné nastavenie a spúšťanie testov pomocou `pytest` (alebo iného test runnera, ak je použitý).
* **Navigácia a Interakcia:** Praktické príklady klikania, zadávania textu, spracovania upozornení a práca s dropdown menu.

## 🛠 Spustenie projektu a predpoklady

Na spustenie tohto kódu potrebujete mať nainštalované nasledujúce nástroje:

* **Jazyk:** [Python 3.x] (alebo iný jazyk, ak bol použitý v kurze)
* **Správca balíčkov:** `pip`
* **Závislosti:** Musíte mať nainštalovaný Selenium WebDriver a príslušný prehliadač (Chrome/Firefox).

### Postup spustenia:

1.  **Klonovanie repozitára:**
    ```bash
    git clone [https://github.com/ivanrac/Kurz-Selenium.git](https://github.com/ivanrac/Kurz-Selenium.git)
    cd Kurz-Selenium
    ```

2.  **Inštalácia závislostí:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Spustenie testov:**
    ```bash
    # Príkaz na spustenie všetkých testov
    pytest
    ```
    *(Alebo príslušný príkaz podľa použitého test runnera.)*
