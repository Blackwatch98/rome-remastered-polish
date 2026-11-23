# Total War: ROME REMASTERED – Spolszczenie 🇵🇱

Projekt fanowskiego spolszczenia gry **Total War: ROME REMASTERED**.

## 📖 O projekcie

Celem projektu jest przygotowanie polskiej wersji językowej gry Total War: ROME REMASTERED, umożliwiającej rozgrywkę w języku polskim.

Planowane tłumaczenie obejmuje:
- Interfejs użytkownika i menu
- Nazwy oraz opisy jednostek
- Nazwy oraz opisy budynków
- Wydarzenia i komunikaty kampanii
- Opisy frakcji i elementy dyplomacji
- Dodatki Barbarian Invasion oraz Alexander

## 🚧 Status projektu

**W przygotowaniu – etap początkowy.**

W repozytorium jest wersja testowa dla podstawowego Rome. Zmienia jeden napis w menu głównym.

## Postęp tłumaczenia

**Łączny postęp w obszarach z policzonym zakresem**

- Przetłumaczone **1/4611 (0,02%)**.
- Sprawdzone ręcznie **1/4611 (0,02%)**.

| Obszar w podstawowym Rome | Przetłumaczone | Sprawdzone ręcznie | Zakres |
| --- | ---: | ---: | --- |
| Menu główne i jego podmenu | 1/37 (2,7%) | 1/37 (2,7%) | Klucze `Rome.InGame.UI_FERAL_LP_*` w `Localizable_Game.strings`, poza etykietami kampanii BI i Alexander |
| Nazwy jednostek | 0/265 (0%) | 0/265 (0%) | Klucze nazw z `export_units.txt` |
| Opisy jednostek | 0/530 (0%) | 0/530 (0%) | Klucze z końcówką `_descr` lub `_descr_short` z `export_units.txt` |
| Budynki i ulepszenia | 0/3164 (0%) | 0/3164 (0%) | `export_buildings.txt` |
| Dyplomacja | 0/408 (0%) | 0/408 (0%) | `diplomacy.txt` |
| Regiony i osady kampanii imperialnej | 0/207 (0%) | 0/207 (0%) | `imperial_campaign_regions_and_settlement_names.txt` |
| Wydarzenia kampanii | — | — | `event_strings.txt`, `event_titles.txt`, `historic_events.txt`, `major_events.txt` |
| Postacie, cechy i świta | — | — | `names*.txt`, `export_vnvs.txt`, `export_ancillaries.txt` |
| Interfejs kampanii, bitew i ustawień | — | — | Pozostałe klucze Feral oraz m.in. `expanded*.txt`, `strat.txt`, `battle.txt` i `tooltips.txt` |
| Samouczki, porady i napisy | — | — | `export_prologue*.txt`, `export_advice*.txt` i pliki `*subtitles.txt` |

Liczymy unikalne klucze w ustalonym zakresie. Obie kolumny dzielą liczbę gotowych lub ręcznie sprawdzonych wpisów przez liczbę wszystkich wpisów w tym zakresie. Po zmianie tekstu lub jego wyświetlania sprawdź dany wpis ponownie, zanim zaliczysz go do drugiej kolumny. Kreska oznacza obszar, dla którego trzeba jeszcze ustalić komplet kluczy.

Liczby pochodzą z angielskich plików podstawowego Rome. Menu liczymy na razie według wskazanej grupy kluczy. Porównanie z ekranami gry może ujawnić kolejne napisy. Gdy dojdziemy do Barbarian Invasion i Alexander, postęp policzymy osobno dla każdego dodatku na podstawie jego własnych plików.

## 📦 Instalacja

### Test lokalny na Windows

1. Skopiuj cały folder [`Rome-PL`](Rome-PL) do `%LOCALAPPDATA%\Feral Interactive\Total War ROME REMASTERED\Mods\My Mods\`. Plik `modinfo.json` powinien być bezpośrednio w folderze `My Mods\Rome-PL`.
2. Uruchom grę przez Steam. W oknie startowym otwórz **Mod Manager**, wybierz **ROME REMASTERED - Spolszczenie** i włącz mod. Do wygenerowania manifestu (`filelist.json`) użyj przycisku **Regenerate Manifest**. Powtórz ten krok po zmianie plików moda.
3. Uruchom podstawowe **Rome** z angielskim językiem gry. W menu głównym przycisk **Load Game** powinien wyświetlać **Wczytaj grę**.

## 🤝 Współpraca

Projekt jest otwarty na zgłaszanie błędów, sugestii tłumaczeń oraz propozycji ulepszeń.
