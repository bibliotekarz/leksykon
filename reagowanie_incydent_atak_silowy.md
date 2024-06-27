# Reagowanie na incydent typu Atak siłowy (Brute Forcing)

## Opis ataku

Atakujący próbuje odgadnąć hasło, testując wiele różnych kombinacji.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- wiele nieudanych prób logowania w krótkim czasie

## Miejsca do zbadania

- dzienniki usługi Active Directory
- logi aplikacji
- logi systemu operacyjnego
- skontaktuj się z użytkownikiem

## Działania w przypadku potwierdzeniu ataku

- wyłącz atakowane konto jeśli wektor ataku wskazuje na konkretne
- zablokuj adres/adresy atakującego.

## Zalecenia po odtworzeniu

- wdrożenie dwuetapowej autoryzacji 2FA
- wdrożenie polityk blokowania konta (czasowego lub permanentnego) po podaniu x złych haseł
- wdrożenie narzędzi limitujących próby logowania jak Fail2ban
