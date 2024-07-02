# Reagowanie na zagrożenie Podszywanie się (Spoofing)

## Opis ataku

Spoofing polega na fałszowaniu informacji w celu podszycia się pod zaufany podmiot. Atakujący podszywają się pod różne elementy/obiekty/usługi jak adres IP, adres e-mail, strona internetowa, serwer DNS w celu oszukania użytkowników lub ominięcia środków bezpieczeństwa.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- nietypowe próby logowania z nieznanych adresów IP
- nieoczekiwane wiadomości e-mail od znanych kontaktów z prośbą o poufne informacje bądź przesłanie danych

## Miejsca do zbadania

- nagłówki e-maili i kod źródłowy korespondencji
- logi ruchu sieciowego
- analiza nagłówków ruchu sieciowego w czasie rzeczywistym

## Działania w przypadku potwierdzeniu ataku

- wyeliminowanie dostępu atakujących do bronionych zasobów (np. filtrowanie poczty)
- skonfigurowanie zapór sieciowych, systemów wykrywania i reagowania na końcówkach (EDR), systemów wykrywania włamań (IDS) w celu wykrywania i blokowania sfałszowanego ruchu

## Zalecenia po odtworzeniu

- cykliczne przeglądy aktualizacje konfiguracji urządzeń sieciowych typu UTM, SIG/SWG, IDS/IPS, firewall
- wdrożenie protokołów uwierzytelniania wiadomości e-mail, takich jak SPF, DKIM i DMARC
- wdrożenie podpisów kryptograficznych
