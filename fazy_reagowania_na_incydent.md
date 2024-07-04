# Fazy reagowania na incydent

## Przygotowanie
  
Ustal zasady i procedury reagowania na incydenty:

* Kto zleca
* Kto, co robi
* Kto zatwierdza i odpowiada
* Kto weryfikuje i rozlicza
* Jakie terminy, jaka kolejność postępowania

## Identyfikacja

Wykrywanie potencjalnych zdarzeń związanych z bezpieczeństwem:

* Testy (cykliczne i ad hoc)
* Monitoring zdarzeń logicznych (IDS, SIEM, antywirusy, IPS, DLP) jak i fizycznych (CCTV, SSWIN, KD, systemy p.poż)
* Informacje własne (hepldesk, pracownicy)
* Informacje od stron trzecich (SCIRT, kontrachenci, klienci)
  
## Ograniczanie rozprzestrzeniania się zagrożenia (mityngacja)

Ogranicz zakres i skalę incydentu:

* odseparuj sieci fizycznie lub logicznie
* odłącz od sieci zainfekowane urządzenia
* wyłącz urządzenia które moga stanowić cele a nie są zainfekowane
* wyłacz urzadzenia które nie będa potrzebne przy dokumentowaniu ataku i analizie incydentu
* powiadom potencjalne cele o zagrożeniu niech podejmą stosowne działania
* zmniejsz/zmień uprawnienia, blokuj konta

## Eliminacja

Usuń pierwotną przyczynę i wszelkie efekty incydentu:

* Zabezpiecz materiały i dowody do analizy śledczej
* Określ które zasoby nie zostały naruszone a które wymagaja interwencji
* Przeprowadź analizę źródła i przebiegu incydentu
* Określ sposób postępowania ze skopromitowanymi zasobami

## Odzyskiwanie

Przywróć i zweryfikuj funkcjonalność systemu:

* Odtwórz środowisko sprzętowe, jeśli jest taka potrzeba dokonaj jego niezbędnego upgrejdu czy modyfikacji
* Dokonaj odtworzenia środowiska logicznego w sposób wykluczający przywrócenie problemu np. poprzez backdory ulokowane w backupach czy snapshotach
* Dokonuj instalacji tylko z pewnych nośników
* Przeprowadź niezbędne aktualizacje
* Wdroż dostępne zabezpieczenia
* Dokonaj utwardzenia systemu
* Przywróć dane z kopii zapasowych lub na podstawie dostępnych materiałów
* Zleć sprawdzenie poprawności danych i działania systemu właścicelom procesów i zasobów
* Wykonaj testy bezpieczeństwa obejmujące również metodę ataku który wywołał incydent
  
## Wyciąganie wniosków i udoskonalenie systemu

Udokumentuj incydent i usprawnij przyszłe działania i reacje:

* Uzupełnij dokumentację o wnioski wyciągnięte z incydentu
* Zabezpiecz system przed możliwoscią powtórzenia się incydentu
* Zweryfikuj czy procedury nie zawiodły
* Zweryfikuj czy postępowano zgodnie z procedurami
* Sprawdź czy nie zawiodło planowanie procesów (np. niedostępność redbooka, niewłaściwa kolejność działań, brak jakiegoś etapu/decyzyjności)
* Sprawdź czy nie są potrzebne szkolenia kadry z realizacji procedur w sytuacji incydentu

## Komunikacja

Czas przekazywania informacji dobierany w zależnosci od komunikatu, jego celu i odbiorcy. Przykładowo informacje/wytyczne o podjęciu działań w sytuacji zagrożenia przekazujemy niezwłocznie, powiadomienia o wycieku danych osobowych czy mającymi w pływ na infrastrukturę Państwa zgodnie z przepisami prawa, komunikaty prasowe zgodnie z terminami okreslanymi przez "biznes".

* Komunikacja wewnętrzna o sytuacji 
* Komunikacja zewnętrzna w zależności od potrzeb (Służby, CSIRT, UODO, osoby których dane wyciekły)
