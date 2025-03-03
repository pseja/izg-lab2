# Navod ke kompilaci
- Ke kompilaci je pozadovano Visual Studio 2019 nebo GCC 7.0.0+ a CMake 3.12.0+

## Linux
(unzip v tomto repozitáři už není potřeba)
- Rozbaľte archív cvičenia: unzip izg_lab02.zip
- Zmente pracovný adresár na zložku cvičenia: cd izg_lab02/

- Vytvorte priečinok pre zostavenie aplikácie: mkdir build
- Zmente pracovný adresár na build: cd build/
- Vytvorte súbory potrebné na zostavenie: cmake ..
- Zkompilujte aplikáciu: make -j
- Spustite aplikáciu: ./izg_lab_02

V případě problémů se spuštěním zkontrolujte, zda máte požadované závislosti pro renderování pomocí SDL, zejména ověřte aktuálnost grafických ovladačů. SDL není potřeba instalovat, je přibaleno ke kostře programu. Kompletní závislosti pro Ubuntu 20.04 lze nalézt zde:

https://packages.ubuntu.com/en/source/focal/libsdl2

Většina balíčků je již součástí základního systému, překladače či grafického ovladače, avšak na některých distribucích mohou některé chybět a způsobovat pády.
## Windows
- Rozbaľte archív kostry programu do zložky Downloads (nutné pri práci v CVT)
- Otvorte aplikáciu cmake-gui
- Pomocou tlačítka "Browse source" vyberte zložku so zdrojovými kódami (priečinok kde je rozbalený ZIP archív cvičenia)
- Pomocou tlačítka "Browse build" zadajte cestu ku zdorovým kódom so sufixom build/ (napríklad C:/Downloads/izg_lab02/build/)
- Kliknite na tlačítko Generate, a vyberte možnosť VisualStudio 17 (verzia 2022)
- V priečinku build/ sa bude nachádzať súbor izg_lab_02.sln
- Cez súbor izg_lab_02.sln otvorte projekt vo VisualStudio 2022
- Pomocou klávesy F5 zkompilujete a spustíte aplikáciu

