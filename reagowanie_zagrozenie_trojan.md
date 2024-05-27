# Reagowanie na zagrożenie Trojan

## Opis ataku

Trojany to złośliwe programy podszywające się pod legalne oprogramowanie, umożliwiające atakującym uzyskanie nieautoryzowanego dostępu do systemów oraz kradzież poufnych informacji i eskalację ataku.

## Wskaźniki skompromitowania (IOC - Indicators of Compromise)

- niewyjaśnione awarie, zawieszanie się systemu, spowolnienie działań komputera
- nieautoryzowane instalacje (w tym próby) lub zmiany oprogramowania, konfiguracji

## Miejsca do zbadania

- logi systemowe i aplikacji
- zmiany w systemie plików i rejestrze
- logi połączeń sieciowych

## Działania w przypadku potwierdzeniu ataku

- uruchomienie skanowania antywirusowego i narzędzi do usuwania złośliwego oprogramowania
- edukacja użytkowników w zakresie postępowania z podejrzanymi plikami do pobrania i załącznikami

## Zalecenia po odtworzeniu

- analiza w jaki sposób został trojan zainstalowany w systemie i podjecie kroków eliminujących tę lukę
