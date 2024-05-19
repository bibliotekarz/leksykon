# Reagowanie na incydent typu Ataki na Internet Rzeczy (IoT)

## Opis ataku

Ataki na Internet Rzeczy (IoT) skierowane są na urządzenia podłączone do internetu, wykorzystując podatności w celu uzyskania nad nimi kontroli w celach złośliwych, takich jak inwigilacja, stworzenie "pacjenta zero", dołączenia do botnetu, itp.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- niewyjaśnione zmiany w zachowaniu lub wydajności urządzenia
- nieautoryzowany dostęp do ustawień lub konfiguracji urządzenia
- połączenia (próby połączeń) z nietypowymi adresami

## Miejsca do zbadania

- logi urządzeń IoT
- historie zdarzeń
- logi urządzeń monitorujących zarządzających siecią IoT
- analiza ruchu sieciowego pod kątem nietypowej komunikacji urządzeń IoT

## Działania w przypadku potwierdzeniu ataku

- przywrócenie firmware
- aktualizacja oprogramowania urzadzeń
- aktualizacja oprogramowania gromadzacego dane/zarządzającego urządzeniami IoT
- wymuszenie szyfrowania połączeń (jeśli możliwe)

## Zalecenia po odtworzeniu

- regularna aktualizacja firmware i oprogramowania urządzeń IoT
- odseparowanie sieci dla IoT od sieci użytkowej i właściwa konfiguracja firewalli ograniczająca publiczny dostęp do urządzeń IoT ze świata
- segmentowanie urządzeń IoT w oddzielnych segmentach sieci
- wdrożenie silnych haseł i szyfrowania dostępu do urządzeń IoT
