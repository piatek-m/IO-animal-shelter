| ID | Kategoria | Wymaganie (mierzalne) | Priorytet (MoSCoW) |
| :---- | :---- | :---- | :---- |
| **NFR-01** | Wydajność | Strony katalogu i karty zwierzęcia ładują się w ≤ 2 s (95. percentyl) przy 50 jednoczesnych użytkownikach. | Must |
| **NFR-02** | Wydajność | Wyszukiwanie i filtrowanie zwraca wyniki w ≤ 1 s dla do 1000 zwierząt. | Should |
| **NFR-03** | Bezpieczeństwo | Hasła są przechowywane jako hash; transmisja tylko przez HTTPS. | Must |
| **NFR-04** | Bezpieczeństwo | Kontrola dostępu oparta na rolach (RBAC) egzekwowana po stronie serwera, a nie tylko w interfejsie. | Must |
| **NFR-05** | Bezpieczeństwo | Ochrona przed OWASP Top 10: SQL injection, XSS, CSRF; walidacja danych wejściowych po stronie serwera. | Must |
| **NFR-06** | Ochrona danych (RODO) | Dane osobowe adoptujących są zbierane za zgodą, na żądanie można je wyeksportować i usunąć, a dostęp do nich ma tylko uprawniony personel. | Must |
| **NFR-07** | Niezawodność | Dostępność systemu ≥ 99% w godzinach pracy schroniska (7:00–19:00). | Should |
| **NFR-08** | Niezawodność | Automatyczna kopia zapasowa bazy raz dziennie, przechowywana co najmniej 14 dni; odtworzenie przetestowane. | Must |
| **NFR-09** | Użyteczność | Dodanie zwierzęcia lub umówienie wizyty zajmuje nowemu użytkownikowi ≤ 5 min bez instrukcji. | Should |
| **NFR-10** | Skalowalność | Architektura pozwala na wzrost do 5000 rekordów zwierząt i 500 kont bez zmiany projektu. | Could |
| **NFR-11** | Lokalizacja | Interfejs w języku polskim, daty w formacie DD.MM.RRRR, strefa czasowa Europe/Warsaw. | Must |