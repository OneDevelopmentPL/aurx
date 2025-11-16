# aurx - Menedżer pakietów AUR / AUR Package Manager

## PL - Polski

### Opis
**aurx** to prosty menedżer pakietów AUR dla Arch Linux i pochodnych, podobny do `yay`.  
Umożliwia instalację, aktualizację i usuwanie pakietów z AUR oraz oferuje interaktywne menu w terminalu.

### Funkcje
- Instalacja pakietów: `aurx inst <pakiet>`  
- Aktualizacja pakietów: `aurx update <pakiet>`  
- Aktualizacja wszystkich pakietów: `aurx update all`  
- Aktualizacja samego aurx: `aurx update me`  
- Usuwanie pakietów: `aurx rem <pakiet>`  
- Interaktywne menu: `aurx x`  
- Informacje o aurx: `aurx about`

### Instalacja
1. Pobierz najnowszą wersję `install_aurx.sh` z [releases](https://github.com/OneDevelopmentPL/aurx/releases).  
2. Nadaj skryptowi prawa wykonywalności:
    ```bash
    chmod +x install_aurx.sh
    ```
3. Uruchom instalator:
    ```bash
    ./install_aurx.sh
    ```
- Skrypt pobierze aurx z GitHub, skopiuje go do `/usr/local/bin` i nada prawa wykonywalności.  
- Po instalacji sprawdź działanie:
    ```bash
    aurx about
    ```

### Wymagania
- System: Arch Linux lub pochodne  
- Python 3  
- git  
- makepkg (`base-devel`)

---

## EN - English

### Description
**aurx** is a lightweight AUR package manager for Arch Linux and derivatives, similar to `yay`.  
It allows installing, updating, and removing AUR packages and provides an interactive terminal menu.

### Features
- Install packages: `aurx inst <package>`  
- Update packages: `aurx update <package>`  
- Update all packages: `aurx update all`  
- Update aurx itself: `aurx update me`  
- Remove packages: `aurx rem <package>`  
- Interactive menu: `aurx x`  
- About aurx: `aurx about`

### Installation
1. Download the latest `install_aurx.sh` from [releases](https://github.com/OneDevelopmentPL/aurx/releases).  
2. Make it executable:
    ```bash
    chmod +x install_aurx.sh
    ```
3. Run the installer:
    ```bash
    ./install_aurx.sh
    ```
- The script will download aurx from GitHub, copy it to `/usr/local/bin`, and set executable permissions.  
- After installation, check if it works:
    ```bash
    aurx about
    ```

### Requirements
- System: Arch Linux or derivatives  
- Python 3  
- git  
- makepkg (`base-devel`)

---

### Kontakt / Contact
- Projekt: [OneDevelopmentPL / aurx](https://github.com/OneDevelopmentPL/aurx)  
- Issue Tracker: [GitHub Issues](https://github.com/OneDevelopmentPL/aurx/issues)
