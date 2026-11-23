# Stos technologiczny

Projekt zostanie wykonany jako aplikacja webowa. Frontend będzie działał
w przeglądarce, a backend będzie odpowiadał za logikę systemu, uprawnienia
oraz zapis danych.

## Wybrane technologie

| Technologia | Zastosowanie | Krótkie uzasadnienie |
| --- | --- | --- |
| **C#** | Główny język backendu | Jest czytelny, popularny i dobrze współpracuje z platformą .NET. |
| **.NET / ASP.NET Core Web API** | Backend aplikacji | Pozwala przygotować REST API, logikę systemu i kontrolę dostępu w jednym projekcie. |
| **HTML5** | Struktura stron | Jest podstawowym standardem tworzenia interfejsów aplikacji internetowych. |
| **CSS3 i Bootstrap** | Wygląd oraz responsywność | Ułatwiają przygotowanie czytelnej strony działającej na komputerze i telefonie. |
| **JavaScript** | Obsługa frontendu | Pozwala pobierać dane z API, obsługiwać formularze i aktualizować stronę bez jej pełnego przeładowania. |
| **Entity Framework Core** | Dostęp do danych | Pozwala pracować z bazą za pomocą klas C# i ogranicza potrzebę ręcznego pisania zapytań SQL. |
| **SQLite** | Baza danych | Nie wymaga osobnego serwera, a cała baza znajduje się w jednym pliku. Jest wystarczająca dla projektu studenckiego. |
| **ASP.NET Core Identity** | Konta, hasła i role | Zapewnia gotową obsługę logowania, bezpiecznego przechowywania haseł oraz uprawnień użytkowników. |
| **BackgroundService** | Timer i zadania w tle | Umożliwia automatyczne tworzenie przypomnień o zbliżających się wizytach. |
| **xUnit** | Testy automatyczne | Jest popularnym narzędziem do testowania aplikacji napisanych w .NET. |
| **Git i GitHub** | Wersjonowanie i współpraca | Pozwalają pracować na branchach, przeglądać zmiany i tworzyć pull requesty. |

## Dodatkowe założenia

- Frontend komunikuje się z backendem przez REST API i dane w formacie JSON.
- Komunikacja z aplikacją odbywa się przez HTTPS.
- Zdjęcia zwierząt i dokumenty są przechowywane poza bazą danych.
- Powiadomienia są zapisywane w systemie i widoczne po zalogowaniu.
- Baza SQLite jest kopiowana raz dziennie do katalogu kopii zapasowych.
- W przyszłości SQLite można zastąpić PostgreSQL bez zmiany całej aplikacji.

Wybrany stos jest stosunkowo prosty do uruchomienia przez wszystkich członków
zespołu i nie wymaga konfigurowania osobnego serwera bazy danych ani serwera
pocztowego.

