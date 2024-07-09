# Reagowanie na incydent typu Kompromitacja konta (Compromised Account)

## Opis ataku

   Atakujący uzyskują dostęp do jednego konta (za pomocą inżynierii społecznej lub innej metody).

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- logowania poza godzinami pracy
- logowanie się z nietypowych lokalizacji
- logowania próbujące omijać ustalone zasady (np. poza VPN-em)
- zmiany grupy/uprawnień konta
- nietypowo wysoki ruch sieciowy

## Miejsca do zbadania

- dzienniki usługi Active Directory
- logi systemu operacyjnego
- ruch sieciowy
- kontakt z użytkownikiem w celu uzyskania wyjaśnień

## Działania w przypadku potwierdzeniu ataku

- wyłącz konto
- zmiana hasła
- analiza mająca na celu ustalanie przyczyny kompromitacji
  - po stronie użytkownika np.:
    - słabe hasło
    - jedno hasło w różnych systemach
  - po stronie administracyjnej np.:
    - błędy konfiguracji
    - podatności systemu

## Zalecenia po odtworzeniu

zależne od przyczyny

- szkolenia personelu
- utwardzenie systemu
- udoskonalenie procesów ochrony konta
