# Reagowanie na incydent typu Ataki na System Nazw Domenowych (DNS)

## Opis ataku

Ataki na DNS są ukierunkowane na infrastrukturę systemu nazw domen, zakłócając lub manipulując procesami rozpoznawania DNS w celu przekierowania użytkowników na złośliwe strony internetowe lub przechwycenia ruchu.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- niewyjaśnione awarie lub opóźnienia rozpoznawania DNS
- nieoczekiwane zmiany w konfiguracjach lub rekordach DNS

## Miejsca do zbadania

- logi serwera DNS i ruch zapytań
- przechwytywanie i analiza pakietów sieciowych pod kątem anomalii związanych z DNS

## Działania w przypadku potwierdzeniu ataku

- analiza przebiegu ataku celem załatania podatności czy uszczelnienia systemu
- weryfikacja poprawności konfiguracji głównego serwera nazw w sieci (master) i serwerów wspomagających (slave)
- weryfikacja konfiguracji urządzeń pośredniczących pod kontem zatruwania ich cache

## Zalecenia po odtworzeniu

- wdrożenie DNSSEC w celu zabezpieczenia transakcji DNS
- monitorowanie ruchu DNS pod kątem oznak tunelowania DNS lub zatruwania DNS
- wykorzystanie filtrowania DNS i usług opartych na reputacji do blokowania złośliwych domen
