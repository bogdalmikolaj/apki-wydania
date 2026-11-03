# apki-wydania

Gotowe APK apek Mikołaja (kod w prywatnym repo `apki`). Podpisane wspólnym kluczem, SHA-256 `4C:79:75:6E:…:54:3B:3C`.

Apki same sprawdzają `wydania.json` (przycisk aktualizacji w górnym pasku, w tle co 6 h) i instalują nowszą wersję.
Ręcznie: pobierz plik na telefon i otwórz.

| Apka | Pakiet | Wersja | Plik |
|---|---|---|---|
| Kantor Kapitana | `pl.mikolaj.kantor` | 1.3 (4) | [kantor-v1.3.apk](kantor-v1.3.apk) |
| Kalkulatory | `pl.kapitan.kalkulatory` | 1.12 (13) | [kalkulatory-v1.12.apk](kalkulatory-v1.12.apk) |
| Pogodynka | `pl.mikolaj.pogodynka` | 3.1 (15) | [pogodynka-v3.1.apk](pogodynka-v3.1.apk) |

Nowe wydanie: dodaj plik `<apka>-v<wersja>.apk` (starych nie usuwaj) i podbij wpis w `wydania.json` (`versionCode` musi rosnąć).
