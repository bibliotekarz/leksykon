
# Przykładowe wskaźniki (IOC - Indicator of Compromise)

## Sieć

+ Spowolnienie systemu/sieci
+ Zwiększona liczba procesów zapisu/odczytu zarówno na dyskach jak i w sieci
+ Dziwne wielkości ramek i pakietów
+ Ruch sieciowy z/do adresów gdzie nie ma/nie powinno być urządzeń
+ Ruch sieciowy sugerujący że źródłem mogą być boty czy inne sztuczne formy jego pochodzenia

## Sprzęt

+ Aktualizacje z nietypowych źródeł/sposobów wgrania
+ Zmiany w ustawieniach urządzeń sieciowych, drukarek, komputerów stacjonarnych czy urządzeń mobilnych
+ Anomalie geolokacyjne
+ Zapytania do DNS obiegające od standardu sieci, kierujące do darknetu czy inne podejrzane lokalizacje
+ Problemy z usługami

## Oprogramowanie

+ Działanie nieznanych aplikacji PUA - (Potentially Unwanted Application)
+ Nadmiar zapytań do baz danych
+ Atak DDoS
+ Błędnie podpisane/przypisane dokumenty
+ Pliki wykonywalne (ale nie tylko) ulokowane poza typową strukturą np. w katalogu TMP
+ Usługi wystawione na nietypowych portach lub wręcz nieznane usługi

## Użytkownicy

+ Nietypowe aktywności logowania
  + godziny logowania poza czasem pracy
  + różne dziwne lokalizacje
  + drastyczne zmiany lokalizacji np. z krakowa na gdańsk w ciągu kilku minut
+ Wiele nieudanych prób logowania mających na celu np. złamanie haseł. Zwłaszcza wskazuje na ataków typu brute force.
+ Zmiany w profilach zwłaszcza podnoszenie uprawnień
+ Pojawiające się nowe profile użytkowników
+ Nietypowa aktywność kont uprzywilejowanych

## Logi

+ Logi systemowe wskazujące na atak
+ Uszkodzone/zmanipulowane logi systemowe
+ Skasowane zmanipulowane pliki przechowujące historię działań jak .bash_history czy .sqlite_history
