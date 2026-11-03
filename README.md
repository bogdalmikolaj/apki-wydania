# apki-wydania

Gotowe APK apek Mikołaja (kod w prywatnym repo `apki`). Podpisane wspólnym kluczem, SHA-256 `4C:79:75:6E:…:54:3B:3C`.

Apki same sprawdzają `wydania.json` (przycisk aktualizacji w górnym pasku, w tle co 6 h) i instalują nowszą wersję.
Ręcznie: pobierz plik na telefon i otwórz.

| Apka | Pakiet | Wersja | Plik |
|---|---|---|---|
| Kantor Kapitana | `pl.mikolaj.kantor` | 1.4 (5) | [kantor-v1.4.apk](kantor-v1.4.apk) |
| Kalkulatory | `pl.kapitan.kalkulatory` | 1.13 (14) | [kalkulatory-v1.13.apk](kalkulatory-v1.13.apk) |
| Pogodynka | `pl.mikolaj.pogodynka` | 3.2 (16) | [pogodynka-v3.2.apk](pogodynka-v3.2.apk) |

Nowe wydanie: dodaj plik `<apka>-v<wersja>.apk` (starych nie usuwaj) i podbij wpis w `wydania.json` (`versionCode` musi rosnąć).
