# Reagowanie na zagrożenie oprogramowanie szpiegujące (Spyware)

## Opis ataku

Spyware to złośliwe oprogramowanie, które potajemnie monitoruje i gromadzi informacje o użytkowniku bez jego wiedzy lub zgody.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- niewyjaśnione spowolnienia wydajności systemu
- podejrzane zmiany w ustawieniach przeglądarki lub na stronach internetowych
- wycieki haseł z przeglądarek i menedżerów haseł

## Miejsca do zbadania

- logi bezpieczeństwa punktów końcowych
- logi programu antywirusowego
- historia przeglądarki internetowej i zainstalowane do niej motywy rozszerzenia
- uruchomione procesy na badanej maszynie

## Działania w przypadku potwierdzeniu ataku

- uruchomienie skanowania antywirusowego i narzędzia do usuwania oprogramowania szpiegującego
- przegląd zainstalowanych rozszeżeń i motywów do przeglądarek
- przegląd oprogramowania pod kontem pozornych "ulepszaczy" wydajności czy predkości systemu itd.
- przegląd obecnego w systemie oprogramowania nie wymagającego instalacji (portable)

## Zalecenia po odtworzeniu

- edukacja użytkowników na temat bezpiecznych nawyków przeglądania internetu i unikania podejrzanych plików do pobrania czy instalacji clickbajtowego oprogramowania.
