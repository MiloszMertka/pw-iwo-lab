
2. Klient (Uzytkownik)
    2.1. Zarejestrowanie się w systemie.
        2.1.1. Uzytkownik wchodzi na stronę powitalną.
        2.1.2. Uzytkownik klika przycisk `Zarejestruj się`.
        2.1.3. System wyświetla formularz rejestracji.
        2.1.3.1.1. Uzytkownik wybiera opcję rejestracji za pomocą konta Microsoft, Google lub Apple.
        2.1.3.2.1. Uzytkownik wprowadza dane do formularza tj:
            - imię
            - nazwisko
            - adres e-mail
            - numer telefonu 
            - hasło
            - potwierdzenie hasła
        2.1.3.2.2. Uzytkownik klika przycisk `Zarejestruj się`.
        2.1.3.2.3. System weryfikuje poprawność wprowadzonych danych.
        2.1.3.2.4. System wyświetla komunikat o błędzie w przypadku niepoprawnych danych oraz wskazuje błędne pole wraz z wyjaśnieniem.
        2.1.3.2.5 Powrót do punktu 2.1.3. jednak z zachowaniem wprowadzonych danych.
        2.1.4. System zapisuje dane w bazie danych.
        2.1.6. System wyświetla komunikat o pomyślnej rejestracji.
        2.1.7. System przesyła e-mail z linkiem aktywacyjnym konto uzytkownika.
        2.1.8. Uzytkownik uzywa linku aktywacyjnego do autoryzacji swojego email'u.
        2.1.9. Po naciśnięciu linku następuje przekierowanie na stronę systemu juz jako zalogowany uzytkownik.
    2.2. Zalogowanie się do systemu.
        2.2.1. Uzytkownik wchodzi na stronę powitalną.
        2.2.2. Uzytkownik klika przycisk `Zaloguj się`.
        2.2.3. System wyświetla formularz logowania.
        2.2.3.1.1. Uzytkownik wybiera opcję logowania za pomocą konta Microsoft, Google lub Apple.
        2.2.3.2.1. Uzytkownik wprowadza dane do formularza tj:
            - adres e-mail
            - hasło
        2.2.3.2.2. Uzytkownik klika przycisk `Zaloguj się`.
        2.2.3.2.3. System weryfikuje poprawność wprowadzonych danych.
        2.2.3.2.4. System wyświetla komunikat o błędzie w przypadku niepoprawnych danych.
        2.2.3.2.5. Powrót do punktu 2.2.3. z zachowaniem wprowadzonych danych.
        2.2.4. System wyświetla komunikat o pomyślnym zalogowaniu.
    2.3. Zarejestrowanie się w systemie za pomocą konta Microsoft, Google lub Apple.
        2.3.1. Uzwględnione w 2.1.3.1.1.
    2.4. Zalogowanie się do systemu za pomocą konta Microsoft, Google lub Apple.
        2.4.1. Uzwględnione w 2.2.3.1.1.
    2.5. Uzupełnienie danych adresowych. # KOMENTARZ: to nie jest do końca use-case. Uzupełnienie danych adresowych do czego? W jakim celu?
        2.5.1. System prosi o uzupełnienie danych adresowych.
        2.5.3. System wyświetla formularz uzupełnienia danych adresowych.
        2.5.4.1. Uzytkownik wybiera jeden ze wcześniej wprowadzonych adresów.
        2.5.4.2. Uzytkownik wprowadza dane do formularza tj:
            - miejscowość
            - ulica
            - numer domu
            - numer mieszkania (opcjonalnie)
            - kod pocztowy
        2.5.4.2.1. Uzytkownik zaznacza opcję 'Zapamiętaj ten adres'.
        2.5.5. Uzytkownik klika przycisk `Dalej`.
        2.5.6. System weryfikuje poprawność wprowadzonych danych.
        2.5.6.1. System wyświetla komunikat o błędzie w przypadku niepoprawnych danych oraz wskazuje błędne pole wraz z wyjaśnieniem.
        2.5.7. System zapisuje dane w bazie danych.
    2.6. Przejrzenie listy zrealizowanych zamówień.
        2.6.1. Uzytkownik otwiera stronę główną systemu.
        2.6.2. Uzytkownik klika przycisk `Zamówienia`.
        2.6.3. System wyświetla listę zamówień.
        2.6.4. Uzytkownik klika na zakładkę `Zrealizowane`.
        2.6.5. System wyświetla listę zrealizowanych zamówień.
        2.6.6. Uzytkownik przegląda listę zrealizowanych zamówień.
    2.7. Ocenienie usługi.
        2.7.1. System wyświetla ządanie o wystawienia opinii.
        2.7.2. Uzytkownik udostępnia swoją opinię w postaci gwiazdek oraz ewentualnego komentarza.
        2.7.3. Uzytkownik klika przycisk `Wyślij`.
    2.8. Zgłoszenie skargi na dostawce.
        2.7.2. Uzytkownik otwiera stronę główną systemu.
        2.7.3. Uzytkownik nawiguje do strony poświęconej danemu dostawcy.
        2.7.4. Uzytkownik klika przycisk `Zgłoś skargę`.
        2.7.4.1. Jezeli uzytkownik nigdy nie korzystał z usług danego dostawcy, system wyświetla komunikat o braku możliwości zgłoszenia skargi.
        2.7.5. Uzytkownik wprowadza treść skargi.
        2.7.6. Uzytkownik klika przycisk `Wyślij`.
    2.9. Wystawienie opinii na temat usługi.
        2.9.1. Pokrywa 2.7.
    2.10. Przejrzenie powiadomienia.
        2.10.1 Uzytkownik otwiera stronę główną systemu.
        2.10.2 Uzytkownik klika przycisk `Powiadomienia`.
        2.10.3 System wyświetla listę powiadomień.
        2.10.4 Uzytkownik klika na powiadomienie.
        2.10.5 System wyświetla szczegóły powiadomienia.
    2.11. Wyłączenie zbędnych powiadomień.
        2.11.1 Uzytkownik otwiera stronę główną systemu.
        2.11.2 Uzytkownik klika przycisk `Ustawienia` symbolizowany przez ikonę zębatki.
        2.11.3 System wyświetla listę ustawień.
        2.11.4 Uzytkownik przechodzi do sekcji `Powiadomienia`.
        2.11.5 Uzytkownik wybiera powiadomienia, które chce wyłączyć.
        2.11.5.1 W szczególności uzytkownik wybiera opcje `Wyłącz wszystkie powiadomienia`.
        2.11.6 Uzytkownik klika przycisk `Zapisz`.