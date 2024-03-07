## Wymagania

### Optymalizacja dla platform mobilnych
- **Rodzaj**: Użyteczność
- **Opis**: Aplikacja mobilna musi być zoptymalizowana pod kątem szybkości i wygody użytkowania na urządzeniach mobilnych.
- **Sposób pomiaru**: Testy użyteczności przeprowadzone na różnych urządzeniach mobilnych.
- **Możliwy wynik pomiaru**: Czas wykonania typowych operacji w aplikacji.
- **Oczekiwane wartości**: Średni czas wykonania operacji poniżej 3 sekund.

### Elastyczność regionu funkcjonowania
- **Rodzaj**: Skalowalność
- **Opis**: System musi być dostosowany do obsługi dużej liczby użytkowników w Polsce.
- **Sposób pomiaru**: Testy obciążeniowe systemu.
- **Możliwy wynik pomiaru**: Liczba jednocześnie obsługiwanych użytkowników.
- **Oczekiwane wartości**: System obsługuje co najmniej podwojenie obecnej liczby użytkowników.

### Niezawodność systemu
- **Rodzaj**: Niezawodność
- **Opis**: System może mieć przerwy w działaniu tylko w nocy, minimalizując wpływ na użytkowników.
- **Sposób pomiaru**: Monitoring czasu działania systemu.
- **Możliwy wynik pomiaru**: Procent czasu, kiedy system jest dostępny.
- **Oczekiwane wartości**: Dostępność systemu na poziomie 99,8%.

### Proces rejestracji użytkownika
- **Rodzaj**: Użyteczność
- **Opis**: Proces rejestracji musi być prosty i intuicyjny, z możliwością logowania przez Microsoft, Google i Apple.
- **Sposób pomiaru**: Czas potrzebny na zarejestrowanie nowego użytkownika.
- **Możliwy wynik pomiaru**: Od 1 do 5 minut.
- **Oczekiwane wartości**: Średni czas rejestracji poniżej 2 minut.

### Weryfikacja negatywnych opinii
- **Rodzaj**: Funkcjonalność
- **Opis**: Musi istnieć system weryfikacji negatywnych opinii przez pracowników.
- **Sposób pomiaru**: Liczba weryfikacji negatywnych opinii w stosunku do ich ogólnej liczby.
- **Możliwy wynik pomiaru**: Procent zweryfikowanych opinii.
- **Oczekiwane wartości**: 100% negatywnych opinii zweryfikowanych.

### Filtrowanie ofert
- **Rodzaj**: Funkcjonalność
- **Opis**: System musi umożliwiać filtrowanie ofert na podstawie wielu kryteriów, w tym adresu, daty, kalorii, popularności, opinii, ceny i rodzaju kuchni.
- **Sposób pomiaru**: Liczba dostępnych filtrów i ich skuteczność.
- **Możliwy wynik pomiaru**: Procent użytkowników korzystających z filtrów.
- **Oczekiwane wartości**: Co najmniej 80% użytkowników korzysta z funkcji filtrowania.

### Powiadomienia o zachęcie do oceny
- **Rodzaj**: Użyteczność
- **Opis**: System powinien wysyłać powiadomienia zachęcające użytkowników do wystawienia opinii dzień po dostarczeniu zamówienia.
- **Sposób pomiaru**: Liczba wysłanych powiadomień i procent użytkowników, którzy wystawili opinię.
- **Możliwy wynik pomiaru**: Procent użytkowników, którzy wystawili opinię po otrzymaniu powiadomienia.
- **Oczekiwane wartości**: Co najmniej 50% użytkowników wystawia opinię po otrzymaniu powiadomienia.

### Efektywność systemu nagród
- **Rodzaj**: Użyteczność
- **Opis**: System nagród powinien być intuicyjny i motywować użytkowników do częstszego korzystania z usług.
- **Sposób pomiaru**: Liczba użytkowników korzystających z systemu nagród.
- **Możliwy wynik pomiaru**: Liczba użytkowników korzystających z systemu nagród w stosunku do ogólnej liczby użytkowników.
- **Oczekiwane wartości**: Co najmniej 50% aktywnych użytkowników korzysta z systemu nagród.

### Integracja z zewnętrznymi systemami opinii
- **Rodzaj**: Integracja
- **Opis**: System musi integrować oceny z zewnętrznych platform, takich jak Google, itp.
- **Sposób pomiaru**: Liczba zintegrowanych platform i dokładność wyświetlanych ocen.
- **Możliwy wynik pomiaru**: Procent poprawnie zintegrowanych ocen.
- **Oczekiwane wartości**: 100% poprawności.

## Ograniczenia

- **Platformy mobilne**: System musi być dostępny jako aplikacja mobilna, co oznacza, że musi być kompatybilny z różnymi systemami operacyjnymi mobilnymi.
- **Protokół Oauth Microsoft, Apple**: System musi obsługiwać protokół Oauth dla logowania przez Microsoft, Google i Apple.
- **Powiadomienia push**: System musi obsługiwać powiadomienia push, co oznacza, że musi być w stanie wysyłać powiadomienia do urządzeń użytkowników.
- **Region funkcjonowania - Polska**: System musi być dostosowany do obsługi klientów w Polsce, co może obejmować obsługę języka polskiego, waluty PLN itp.
- **Odpytywanie API systemu cateringowego**: System musi być w stanie komunikować się z API dostawców usług cateringowych w celu uzyskania informacji o dostępności i szczegółach ofert.
- **Niezawodność - przerwy działania mogą się odbywać w nocy**: System musi być niezawodny i dostępny przez większość czasu, ale może być niedostępny w nocy na konserwację.
- **Wyprzedzenie zamówień - zależy od dostawcy**: System musi umożliwiać dostawcom ustalanie okresu wyprzedzenia dla zamówień.
