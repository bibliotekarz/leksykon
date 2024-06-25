# Reagowanie na incydent typu atak Ransomwar

## Opis ataku

Złośliwe oprogramowanie przeprowadzające atak polegający na zaszyfrowaniu plików i danych. Po zakończonym procesie żąda okupu (często w kryptowalutach) od użytkownika w zamian za odszyfrowanie plików.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- alerty antywirusowe
- połączenia do podejrzanych adresów IP (C&C)
- utrata dostępu do maszyn, danych
- wyświetlenie ransomware note

## Miejsca do zbadania

- logi programu antywirusowego
- dzienniki systemu operacyjnego
- logi kont użytkowników
- ruch sieciowy

## Działania w przypadku potwierdzeniu ataku

- zleć sprawdzenie przez program antywirusowy
- izoluj maszynę
- zbadaj sposób rozprzestrzeniania się ransomware
- odizoluj backup

## Zalecenia po odtworzeniu

- przegląd uprawnień i możliwości ich eskalacji
- dokonanie analizy incydentu:
  - którędy atakujący dostał sie do systemu
  - czego czy podatność została załatana
  - czy poprawiono procedury z naciskiem na weryfikacją ich realizacji
