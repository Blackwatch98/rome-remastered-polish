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

W repozytorium jest wersja testowa dla podstawowego Rome. Zawiera tłumaczenie zidentyfikowanych pozycji menu głównego i jego podmenu.

## Postęp tłumaczenia

| Gra lub dodatek | Przetłumaczone | Sprawdzone w grze | Status |
| --- | ---: | ---: | --- |
| Rome (gra podstawowa) | 1042/4821 (21,61%) | 996/4821 (20,66%) | Tylko obszary z ustalonym pełnym zakresem |
| Barbarian Invasion | — | — | W kolejce |
| Alexander | — | — | W kolejce |

Pliki źródłowe moda zawierają razem **2618 unikalnych kluczy liczonych w obrębie każdego pliku**. To 1558 w `en.strings`, 33 w `battle_descriptions.txt`, 42 w `expanded_bi.txt`, 190 w `shortcut.txt` i 795 w `export_units.txt`. Ta liczba obejmuje także rozpoczęte obszary i uwzględnia sytuacje, w których ten sam napis ma klucze w kilku plikach lub wariantach platformowych.

### Rome (gra podstawowa)

| Obszar w podstawowym Rome | Przetłumaczone | Sprawdzone w grze | Zakres |
| --- | ---: | ---: | --- |
| Menu główne i podmenu: nawigacja | 37/37 (100%) | 37/37 (100%) | Klucze `Rome.InGame.UI_FERAL_LP_*` w `Localizable_Game.strings`, poza etykietami kampanii BI i Alexander |
| Menu główne i podmenu: ekrany szczegółowe i okna dialogowe | 6 | 6 | Zidentyfikowane wpisy ustawień kampanii. Pełny zakres w ustalaniu. |
| Ustawienia grafiki (podstawowe) | 53 | 53 | Zidentyfikowane wpisy pierwszego ekranu dostępnego z menu głównego. Pełny zakres w ustalaniu. |
| Ustawienia grafiki (zaawansowane) | 138 | 138 | Zidentyfikowane etykiety, opcje i podpowiedzi, w tym warianty platformowe. Pełny zakres w ustalaniu. |
| Ustawienia dźwięku | 74 | 74 | Zidentyfikowane etykiety, opcje i podpowiedzi, w tym warianty platformowe. Pełny zakres w ustalaniu. |
| Ustawienia sterowania | 146 | 146 | Interfejs przypisywania skrótów oraz etykiety akcji z `Localizable_Game.strings`. Część etykiet z `data/text` jest w lokalnej paczce testowej. |
| Ustawienia rozgrywki | 105 | 105 | Zidentyfikowane etykiety, opcje i podpowiedzi, w tym warianty platformowe. Pełny zakres w ustalaniu. |
| Twórcy | 5 | 5 | Nagłówek, etykieta i podpowiedzi menu oraz wzmianka na panelu pomocy. |
| Wczytywanie gry | 57 | 57 | Okna wczytywania kampanii, bitew i powtórek, sortowanie oraz komunikaty o zapisach. Pełny zakres w ustalaniu. |
| Potwierdzenie wyjścia | 11 | 11 | Potwierdzenie zakończenia gry, przyciski i opcja ponownego otwarcia okna startowego, wraz z wariantami platformowymi. |
| Szybka bitwa | 74 | 74 | Etykiety menu, wybór frakcji, poprzednia szybka bitwa i podpowiedź rozpoczęcia bitwy. Pełny zakres w ustalaniu. |
| Bitwa niestandardowa | 456 | 456 | Konfiguracja warunków bitwy, drużyn i armii oraz zapis ustawień. Pełny zakres w ustalaniu. |
| Lokacje bitew niestandardowych | 51 | 51 | 38 nazw w menu i 13 tytułów lokacji w `en.strings`. Tytuły są także w źródłowym `battle_descriptions.txt`. |
| Bitwy historyczne | 34 | 34 | Menu wyboru bitwy i armii, podpowiedzi oraz zidentyfikowane opisy bitew podstawowego Rome. Pełny zakres w ustalaniu. |
| Tytuły i opisy bitew historycznych | 20/20 (100%) | 20/20 (100%) | Tytuł i opis każdego z 10 scenariuszy jednoosobowych podstawowego Rome w `Rome-PL/data/text/battle_descriptions.txt`. |
| Karty jednostek w bitwach | 102 | 102 | Statystyki, podpowiedzi, cechy i zdolności jednostek. |
| Cele i daty bitew | 20 | 20 | Cele, wymagania liczebności i formaty lat w menu oraz na ekranie bitwy. |
| Kampania imperialna | 155 | 155 | Wybór frakcji, ustawienia kampanii, warunki zwycięstwa i opisy modyfikatorów, w tym 38 tytułów i opisów 19 frakcji. Pełny zakres w ustalaniu. |
| Krótkie opisy frakcji i ich armii | 47 | 47 | 26 wpisów w `en.strings` i 21 w `expanded_bi.txt`. |
| Nazwy frakcji | 21 | 21 | Nazwy podstawowego Rome w `expanded_bi.txt`, używane m.in. nad komunikatem blokady. |
| Nazwy akcji i kategorii skrótów | 190/190 (100%) | 190/190 (100%) | `shortcut.txt`, 203 wpisy z uwzględnieniem powtórzonych kluczy. |
| Nazwy jednostek | 265/265 (100%) | 265/265 (100%) | Wszystkie klucze nazw jednostek i okrętów z `export_units.txt` |
| Opisy jednostek | 530/530 (100%) | 484/530 (91,32%) | Wszystkie klucze krótkich i pełnych opisów jednostek oraz okrętów z `export_units.txt`, w tym dwanaście znaczników braku pełnego opisu. |
| Budynki i ulepszenia | 0/3164 (0%) | 0/3164 (0%) | `export_buildings.txt` |
| Dyplomacja | 0/408 (0%) | 0/408 (0%) | `diplomacy.txt` |
| Regiony i osady kampanii imperialnej | 0/207 (0%) | 0/207 (0%) | `imperial_campaign_regions_and_settlement_names.txt` |
| Wydarzenia kampanii | — | — | `event_strings.txt`, `event_titles.txt`, `historic_events.txt`, `major_events.txt` |
| Postacie, cechy i świta | — | — | `names*.txt`, `export_vnvs.txt`, `export_ancillaries.txt` |
| Interfejs kampanii, bitew i ustawień | — | — | Pozostałe klucze Feral oraz m.in. `expanded*.txt`, `strat.txt`, `battle.txt` i `tooltips.txt` |
| Samouczki, porady i napisy | — | — | `export_prologue*.txt`, `export_advice*.txt` i pliki `*subtitles.txt` |

Liczymy unikalne klucze w ustalonym zakresie. Procenty liczymy względem wszystkich wpisów w danym zakresie. Przy niepełnym zakresie podajemy liczby bez procentu i poza sumą zbiorczą. Po zmianie tekstu lub jego wyświetlania sprawdź dany wpis ponownie, zanim zaliczysz go do drugiej kolumny. Kreska oznacza obszar, dla którego trzeba jeszcze ustalić komplet kluczy.

Liczby pochodzą z angielskich plików podstawowego Rome. Klucze nawigacji menu policzyliśmy osobno. Przy ekranach szczegółowych i oknach dialogowych nadal ustalamy pełną listę wpisów. Zakres Barbarian Invasion i Alexander ustalimy osobno na podstawie plików każdego dodatku, gdy rozpoczniemy prace nad jego tłumaczeniem.

### Zakres całego spolszczenia

Celem jest polski tekst widoczny dla gracza w podstawowym Rome na Steam, od okna startowego i menu po kampanię imperialną, samouczek, bitwy oraz napisy. Nazwy własne i terminy pozostawione świadomie w oryginale też należy przejrzeć. Barbarian Invasion i Alexander mają osobne zakresy.

#### Inwentaryzacja głównych tabel tekstu

Punkt odniesienia to angielska instalacja Steam, kompilacja `8081527`. W głównym katalogu `data/text` znaleźliśmy **23 896 kluczy liczonych osobno w każdym z 43 plików**. Po połączeniu powtarzających się kluczy zostaje **23 294**. Z grup `Rome.InGame`, `Rome.Override`, `Rome.Annotations` i `Rome.LoadingTips` w `Localizable_Game.strings` pochodzi kolejnych **7582** kluczy po odjęciu jawnie oznaczonych wpisów dodatków i wariantów konsolowych lub mobilnych. **2117** identyfikatorów występuje w obu źródłach, co daje **28 759** identyfikatorów w inwentaryzacji. W plikach moda znajdują się odpowiedniki **2556 z nich (8,89%)**. To pokrycie zebranych kluczy. Ustalenie, które wpisy są używane w grze i które wymagają przekładu, może zmienić mianownik.

| Obszar | Klucze w plikach `data/text` | Tabele źródłowe |
| --- | ---: | --- |
| Menu, sterowanie, interfejs bitwy i kampanii | 5580 | `menu_english_stm.txt`, `shortcut.txt`, `battle.txt`, `building_battle.txt`, `shared.txt`, `expanded.txt`, `expanded_bi.txt`, `strat.txt`, `cursor_action_tooltips.txt`, `tooltips.txt` |
| Jednostki i budynki | 3959 | `export_units.txt`, `export_buildings.txt` |
| Postacie, imiona, cechy i świta | 5923 | `names.txt`, `names_feral.txt`, `export_vnvs.txt`, `export_ancillaries.txt` |
| Dyplomacja i wydarzenia | 1983 | `diplomacy.txt`, `event_strings.txt`, `event_titles.txt`, `historic_events.txt`, `major_events.txt` |
| Kampanie, scenariusze bitew, regiony i zasoby | 802 | `campaign_descriptions.txt`, `battle_descriptions.txt`, `rebel_faction_descr.txt`, `climates.txt`, `landmarks.txt`, `resources.txt` i cztery tabele `*_regions_and_settlement_names.txt` |
| Samouczek i doradcy | 3191 | `export_advice.txt`, `export_advice_feral.txt`, `export_prologue.txt`, `export_prologue_feral.txt` |
| Napisy i cytaty | 2213 | `battle_event_subtitles.txt`, `factionintrosubtitles.txt`, `historic_battles_subtitles.txt`, `prebattle_speeches_subtitles.txt`, `quotes.txt` |
| Edytor bitew | 245 | `battle_ed.txt`, do potwierdzenia dostępność w zwykłej instalacji Steam |

Pozycje w tabeli liczą klucze osobno w każdym pliku. Dla powtórzeń w jednym pliku liczymy klucz raz. W połączonej inwentaryzacji klucz `{NAZWA}` z `data/text` odpowiada `Rome.Override.NAZWA`. Jeśli gra używa różnych wartości pod tym samym kluczem, oba konteksty wymagają sprawdzenia. Uwzględniamy angielski wariant menu Steam, czyli `menu_english_stm.txt`. Dane przypisań z `descr_shortcuts.txt`, nieużyty wariant `menu_english.txt` i stara tabela regionów `old_imperial_*` są poza inwentaryzacją. Format daty i prosty plik napisów końcowych wymagają oddzielnego sprawdzenia, bo nie mają kluczy w nawiasach klamrowych.

#### Co trzeba jeszcze przypisać do zakresu

- **Launcher i wspólny interfejs Feral.** Napisy okna startowego, menedżera modów, komunikatów i wyboru gry występują w `Rome.Startup` oraz w ogólnym `Localizable.strings`. Ten drugi zawiera 2016 kluczy, w tym współdzielone i platformowe. Do zakresu wchodzą te wyświetlane przez Steam przy uruchamianiu podstawowego Rome.
- **Współdzielone i archiwalne wpisy.** Trzeba przypisać teksty bez jednoznacznego oznaczenia do podstawowego Rome lub dodatków, sprawdzić dostępność edytora i kampanii pomocniczych, a także wyłapać aliasy, puste wpisy i nazwy pozostające bez zmian.
- **Napisy poza głównymi tabelami.** Przy testach okien i scenariuszy trzeba odnotować tekst wyświetlany z danych map, materiałów wideo lub innych źródeł. Taki wpis dopisujemy do zakresu po ustaleniu źródła i sposobu nadpisania.

## 📦 Instalacja

### Test lokalny na Windows

1. Skopiuj cały folder [`Rome-PL`](Rome-PL) do `%LOCALAPPDATA%\Feral Interactive\Total War ROME REMASTERED\Mods\My Mods\`. Plik `modinfo.json` powinien być bezpośrednio w folderze `My Mods\Rome-PL`.
2. Uruchom grę przez Steam. W oknie startowym otwórz **Mod Manager**, wybierz **ROME REMASTERED - Spolszczenie** i włącz mod. Do wygenerowania manifestu (`filelist.json`) użyj przycisku **Regenerate Manifest**. Powtórz ten krok po zmianie plików moda.
3. Uruchom podstawowe **Rome** z angielskim językiem gry. W menu głównym przycisk **Load Game** powinien wyświetlać **Wczytaj grę**.

## 🤝 Współpraca

Projekt jest otwarty na zgłaszanie błędów, sugestii tłumaczeń oraz propozycji ulepszeń.
