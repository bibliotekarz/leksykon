# Reagowanie na incydent typu Odmowa usługi (Denial Of Service, DoS/DDoS)

## Opis ataku

Atakujący zakłóca działanie systemu poprzez wykorzystanie podatności DoS lub generowanie dużej ilości ruchu.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- nietypowo wysoki ruch sieciowy na serwerach publicznie dostępnych
- brak dostępu do usług sieciowych z powodu braku odpowiedzi lub timeoutów

## Miejsca do zbadania

- analiza ruchu sieciowego
- logi firewalla, urządzenia brzegowego
- logi systemu operacyjnego

## Działania w przypadku potwierdzeniu ataku

- jeśli atak prowadzony jest na podatną usługę/urządzenie: uruchom działania naprawcze zespołu odpowiedzialnego za aktualizację i opiekę nad sprzętem/aplikacjami
- jeśli atak spowodowany jest typu flood: kontakt z zespołem wsparcia sieciowego lub dostawcą usług internetowych (ISP) żeby zablokowali na infrastrukturze przed adresem docelowym ataku

## Zalecenia po odtworzeniu

- analiza możliwości wprowadzenia technik obrony przed takimi atakami (i wdrożenie jeśli możliwe)
- analiza i optymalizacja konfiguracji urzadzeń sieciowych, wzbogacenia ich przepustowości itp.
- jeśli możliwe załatanie lub wyłączenie podatnych na atak usług
- poprawa bądź dopisanie procedur działania w przypadku ataku DDoS np. poprzez spisanienie/aktualizacja listy kontaktowej operatorów dostawcy łącza mogacych pomóc w przypadku powtórzenia ataku
