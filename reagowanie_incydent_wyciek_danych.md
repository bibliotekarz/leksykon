# Reagowanie na incydent typu Wyciek danych (Data Exfiltration)

## Opis ataku

Atakujący (często nieuczciwy pracownik) kradnie dane, kopiuje na zewnętrzne nośniki lub wysyła za pomoca sieci.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- nietypowo wysoki ruch sieciowy
- połączenia do rozwiązań przechowywania w chmurze (Dropbox, Google Cloud)
- uruchomienie programów typu p2p
- alerty o nowych/nieznanych nośnikach USB w tym z poza dopuszczonych do używania

## Miejsca do zbadania

- logi urządzeń sieciowych
- logi proxy
- logi systemu operacyjnego
- skontaktuj się z użytkownikiem na którego koncie nastąpił wyciek

## Działania w przypadku potwierdzeniu ataku

- jeśli pracownik: Skontaktuj się z kierownikiem, przeprowadź pełne śledztwo
- jeśli zagrożenie zewnętrzne:
  - izoluj maszynę, odłącz od sieci
  - zweryfikuj co i na jakim koncie/uprawnieniach zostało pobrane
  - określ sposób w jaki atakujący dostał się do danych i do maszyny z której wysyłał dane
- jeżeli wyciek dotyczy danych osobowych uruchomić procedury narzucone przez politykę ochrony danych osobowych 72 godziny na powiadomienie PUODO

## Zalecenia po odtworzeniu

- szkolenia personelu
- wprowadzenie systemu Data Loss Prevention (DLP)
- udoskonalenie procesów ochrony danych
