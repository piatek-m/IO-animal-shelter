# Kontekst projektu

## Wizja
System jest aplikacją webową wspierającą pracę schroniska dla zwierząt.
Zastępuje papierową/rozproszoną ewidencję jednym miejscem, w którym:
- pracownicy prowadzą ewidencję zwierząt i ich dokumentację medyczną,
- odwiedzający i potencjalni adoptujący mogą przeglądać zwierzęta dostępne do adopcji,
- schronisko obsługuje proces adopcji od zgłoszenia do przekazania zwierzęcia.

### Poza zakresem
Płatności i darowizny, księgowość, integracje z rejestrami zewnętrznymi.

## Aktorzy
| Aktor | Opis | Główne interakcje z systemem |
|---|---|---|
| Adoptujący | Osoba zainteresowana adopcją konkretnego zwierzęcia | Umawianie wizyt, śledzenie jego statusu |
| Wolontariusz | Osoba pomagająca w schronisku, ograniczone uprawnienia | Podgląd zadań, np. spacery, karmienie |
| Pracownik schroniska | Osoba zarządzająca zwierzętami i adopcjami | Ewidencja, dokumentacja medyczna, decyzje o adopcji |
| Administrator | Osoba zarządzająca kontami pracowników, wolontariuszy | Tworzenie i dodawanie kont, zmiany uprawnień |
| Weterynarz | Osoba badająca zwierzęta | Badanie, szczepienie, chipowanie zwierząt |
| Timer | Aktor systemowy reprezentujący upływ czasu | Inicjuje wysyłanie przypomnienia o wizycie |
