# Scenariusze przypadków użycia

## Aktor główny - Administrator : PU1 - PU7

### PU1. Wysłanie powiadomienia do klienta [Sebastian Pietrykowski]

Test:
1. Administrator wchodzi w panel administracji i wybiera przycisk "Wyślij powiadomienie".
2. Administrator obiera i wypełnia formularz wysyłania powiadomień przykładowymi danymi.
3. Administrator klika "Wyślij".

Oczekiwany rezultat:
1. Jeśli dane były poprawne to klient odbiera powiadomienie. 

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/6e13f398-0366-4fa3-af68-76353db5b48d)


### PU2. Przejrzenie listy usługodawców [Sebastian Pietrykowski]

Test:
1. Administrator wchodzi w panel administracji i wybiera listę usługodawców.
2. Administrator wybiera kryteria filtrowania.

Oczekiwany rezultat:
1. Jeśli listę udało się pobrać to administrator widzi przefiltrowaną listę usługodawców.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/6fe4019c-74ba-48e6-9451-c7280ff81962)


### PU3.	Dodanie usługodawcy [Sebastian Pietrykowski]

Test:
1. Administrator wchodzi na stronę rejstracji dostawcy i wprowadza dane dostawcy.
2. Administrator zatwierdza profil dostawcy.
3. Rzecznik biznesowy przekazuje dane logowania dostawcy.

Oczekiwany rezultat:
1. Jeśli dane były poprawne to dostawca odbiera dane logowania.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/4a261667-0fd7-4454-a89c-d721822e5a25)


### PU4. Usunięcie usługodawcy [Sebastian Pietrykowski]

Test:
1. Administrator wchodzi w panel administracji i wybiera listę usługodawców.
2. Administrator klika przycisk usunięcia przy usługodawcy.

Oczekiwany rezultat:
1. Jeśli nie wystąpił błąd to administrator dostaje powiadomienie o usunięciu.
2. Usługodawca przstaje istnieć w systemie - nie widać go na liście usługodawców.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/78e9d8e5-3a87-467a-bbe3-abd1290e3201)


### PU5.	Rozliczenie usługodawcy [Sebastian Pietrykowski]

Test:
1. Administrator obiera powiadomienie i wchodzi na stronę faktur.
2. Administrator przegląda fakturę, wykonuje przelew i odznacza fakturę.

Oczekiwany rezultat:
1. Jeśli nie wystąpił błąd to system zapisał rozliczenie faktury.
2. Usługodawca dostał przelew.


![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/d83c5bd9-5624-40c5-b88b-f719e7b40748)


### PU6.	Przejrzenie listy zgłoszonych opinii [Sebastian Pietrykowski]

Test:
1. Administrator wchodzi na stronę zgłoszonych opinii.
2. Administrator przegląda listę zgłoszonych opinii.
3. Administrator stosuje filtry do listy.

Oczekiwany rezultat:
1. Jeśli nie wystąpił błąd to administrator widzi przefiltrowaną listę.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/c5ac2c36-144b-4a39-8caf-e72b2954ad05)


### PU7.	Zablokowanie użytkownikowi możliwości wystawiania opinii [Sebastian Pietrykowski]

Test:
1. Administrator wybiera panel do zarządzania użytkownikami.
2. Administrator wyszukuje użytkownika.
3. Administrator klika przycisk blokujący wystawianie opinii.

Oczekiwany rezultat:
1. Jeśli nie wystąpił błąd to wskazany użytkownik nie może wystawić opinii.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/ddd87f78-0108-404b-867f-14a70586328d)


-----------------------------------------------------

## Aktor główny - Usługodawca : PU8 - PU28

### PU8.	Rezygnacja ze współpracy z aplikacją [Sebastian Pietrykowski]

Test:
1. Usługodawca kontaktuje się z pracownikiem firmy w związku z rezygnacją.
2. Pracownikowi nie udaję się przekonać usługodawcy do pozostania.

Oczekiwany rezultat:
1. Jeśli nie wystąpił błąd to usługodawca odbiera informacje o harmonogramie.
2. Dane i oferty dostawcy zostają usunięte z systemu.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/f51a5b97-f0d1-439d-af8d-f52f0a4f1f23)


### PU9.	Rozliczenie z aplikacją [Sebastian Pietrykowski]

Test:
1. Usługodawca żąda i odbiera informacje o zamówieniach.
2. Usługodawca wystawia i wysyła fakturę.

Oczekiwany rezultat:
1. Jeśli nie wystąpił błąd to usługodawca odbiera potwierdzenie opłacenia faktury.


![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/f186db11-3bb6-42f0-832b-41211305ab56)


### PU10.	Zarejestrowanie się w systemie [Sebastian Pietrykowski]

Test:
1. Administrator wchodzi na stronę rejstracji dostawcy i wprowadza dane dostawcy.
2. Administrator zatwierdza profil dostawcy.
3. Rzecznik biznesowy przekazuje dane logowania dostawcy.

Oczekiwany rezultat:
1. Jeśli dane były poprawne to dostawca odbiera dane logowania.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/6fe4fb55-9479-4683-a5ae-f193b217ff05)


### PU11.	Zalogowanie się do systemu [Sebastian Pietrykowski]

Test:
1. Usługodawca wchodzi na stronę logowania.
2. Usługodawca wpisuje dane logowania i klika "Zaloguj się".

Oczekiwany rezultat:
1. Jeśli dane były poprawne to usługodawca zostaje zalogowany do systemu.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/ddb37b91-f218-4233-9d86-e50ec5fb528a)


### PU12.	Zarejestrowanie się w systemie za pomocą konta Microsoft, Google lub Apple [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi na stronę rejestracji i wybiera opcje "Firma".
2. Usługodawca wybiera zewnętrzny system i zostaje przekierowany.
3. Usługodawca wprowadza dane i potwierdza formularz.

Oczekiwany rezultat:
1. Jeśli dane były poprawne to usługodawca zostaje zarejestrowany do systemu.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/1de1284f-e8f3-4fac-9c25-3fa896e1df04)


### PU13.	Zalogowanie się do systemu za pomocą konta Microsoft, Google lub Apple [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi na stronę rejstracji i wybiera opcje "Firma".
2. Usługodawca wybiera zewnętrzny system logowania i zostaje przekierowany.
3. Usługodawca wprowadza dane i potwierdza formularz logowania.

Oczekiwany rezultat:
1. Jeśli dane były poprawne to usługodawca zostaje zalogowany do systemu.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/4cc1dc25-015b-493c-8674-0a54bf6ce6a0)


### PU14.	Przejrzenie oferty posiłków [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi na stronę "Moje oferty".

Oczekiwany rezultat:
1. Jeśli nie wystąpiły błędy to usługodawca widzi listę posiłków.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/b9d6e363-272a-4496-9d98-42ca8af3b767)


### PU15.	Dodanie posiłku do oferty [Ulyana Petrashevich]

Test:
1. Usługodawca klika przycisk "Dodaj" na stronie "Moje oferty".
2. Usługodawca wypełnia formularz dodania posiłku i go wysyła.

Oczekiwany rezultat:
1. Jeśli nie wystąpiły błędy i dane były poprawne to usługodawca dostaje powiadomienie.
2. Posiłek zostaje dodany do systemu - jest widoczny w ofercie posiłków.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/7f433698-24d9-43a1-8b9f-37a4b72560a8)


### PU16.	Zedytowanie posiłku z oferty [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi w tryb edycji i wybiera opcję edycji posiłku na stronie "Moje oferty".
2. Usługodawca wypełnia formularz edycji posiłku i go wysyła.

Oczekiwany rezultat:
1. Jeśli nie wystąpiły błędy i dane były poprawne to usługodawca dostaje powiadomienie.
2. Posiłek zostaje zaktualizowany w systemie - jest widoczny w ofercie posiłków.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/e28d1591-9674-4e77-94b7-9efbe725f6d0)


### PU17.	Usunięcie posiłku z oferty [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi w tryb edycji i wybiera opcję usunięcia posiłku na stronie "Moje oferty".
2. Usługodawca potwierdza usunięcie.

Oczekiwany rezultat:
1. Jeśli nie wystąpiły błędy i dane były poprawne to usługodawca dostaje komunikat o usunięciu.
2. Posiłek zostaje usunięty z systemu - nie jest widoczny w ofercie posiłków.


![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/fe01395e-dbd7-4ee6-9ad2-f390fe5e86f8)


### PU18.	Dodanie pakietu posiłków do oferty [Ulyana Petrashevich]

Test:
1. Usługodawca klika przycisk "Dodaj" na stronie "Moje oferty" w zakładce pakietów.
2. Usługodawca wypełnia formularz dodania pakietu i go wysyła.

Oczekiwany rezultat:
1. Jeśli nie wystąpiły błędy i dane były poprawne to usługodawca dostaje komunikat o dodaniu pakietu.
2. Pakiet zostaje dodany do systemu - jest widoczny w ofercie.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/ed383525-9a3d-4f69-af30-e2df240f881d)


### PU19.	Zedytowanie pakietu posiłków [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi w tryb edycji i wybiera opcję edycji pakietu na stronie "Moje oferty" w zakładce z pakietami.
2. Usługodawca wypełnia formularz edycji i go potwierdza.

Oczekiwany rezultat:
1. Jeśli nie wystąpiły błędy i dane były poprawne to usługodawca dostaje komunikat o zaktualizowaniu.
2. Pakiet zostaje zaktualizowany systemie - jest widoczny w ofercie posiłków.


![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/a10ffdce-021b-4067-9d66-30641b1e31d1)


### PU20.	Usunięcie pakietu posiłków z oferty [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi w tryb edycji i wybiera opcję usunięcia pakietu na stronie "Moje oferty" w zakładce pakietów.
2. Usługodawca potwierdza usunięcie.

Oczekiwany rezultat:
1. Jeśli nie wystąpiły błędy i dane były poprawne to usługodawca dostaje komunikat o usunięciu.
2. Pakiet zostaje usunięty z systemu - nie jest widoczny w ofercie.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/9b001cdc-643f-48a3-9a85-35490b4cce8e)


### PU21.	Przejrzenie oferty pakietów [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi w zakładkę "Oferta pakietów".

Oczekiwany rezultat:
1. Usługodawca widzi listę pakietów.


![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/a02b6155-d89a-4baa-b521-580e2728f14a)

### PU22.	Promowanie oferty [Ulyana Petrashevich]

Test:
1. Usługodawca wchodzi na stronę "Promowanie ofert".
2. Usługodawca wybiera program promowania.
3. Usługodawca opłaca program.

Oczekiwany rezultat:
1. Program promowania staje się aktywny dla usługodawcy.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/3440b911-72d2-460c-bb1d-95c2c520d779)


### PU23.	Dokonanie płatności za usługę promowania [Michał Szlązak]

Test:
1. Usługodawca wybiera ofertę promowania i metodę płatności.

Oczekiwany rezultat:
1. Program promowania zostaje opłacony.
2. Usługodawca otrzymuje powiadomienie.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/4dd59d4f-9c21-4e51-8d0f-7ff916ed4e3d)


### PU24.	Przejrzenie statystyk [Michał Szlązak]

Test:
1. Usługodawca wchodzi na stronę statystyk.

Oczekiwany rezultat:
1. Usługodawca widzi pobrane statystyki.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/08c41491-cf9c-43ce-bc8a-6651e7d15760)


### PU25.	Przejrzenie recenzji [Michał Szlązak]

Test:
1. Usługodawca wchodzi na stronę recenzji.

Oczekiwany rezultat:
1. Usługodawca widzi pobraną recenzje.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/464ce319-1426-4bcd-8a26-c599b14b2bda)


### PU26.	Zgłoszenie opinii [Michał Szlązak]

Test:
1. Usługodawca przegląda listę opinii.
2. Usługodawca składa zgłoszenie opinii.

Oczekiwany rezultat:
1. Jeśli zgłoszenie uzasadnione to opinia zostaje usunięta z systemu.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/7e1f6e10-950e-4ccd-bdab-927d3647e79d)


### PU27.	Przejrzenie obecnie aktywnych zamówień klientów [Michał Szlązak]

Test:
1. Usługodawca wchodzi na stronę aktywnych zamówień.

Oczekiwany rezultat:
1. Usługodawca widzi listę aktywnych zamówień.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/2c9a1002-0bd2-4d56-bd0b-54d47f96e659)


### PU28.	Oznaczenie zamówienia jako "w drodze" [Michał Szlązak]

Test:
1. Usługodawca przegląda listę aktywnych zamówień.
2. Oznacza zamówienie jako "w drodze".

Oczekiwany rezultat:
1. Stan zamówienia zostaje zmieniony w systemie.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/e04950ef-c906-46f1-8b10-7e3db36413eb)


-----------------------------------------------------

## Aktor główny - Klient : PU29 - PU54

### PU29.	Przejrzenie koszyka [Michał Szlązak]

Test:
1. Klient wchodzi na stronę koszyka.

Oczekiwany rezultat:
1. Klient widzi swój koszyk.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/d865bbd8-089b-4871-b8c8-319dca028fd6)


### PU30.	Rezygnacja z subskrypcji [Michał Szlązak]

Test:
1. Klient wchodzi na stronę koszyka.
2. Klient wybiera przycisk rezygnacji z subskrypcji.

Oczekiwany rezultat:
1. Subskrypcja zostaje usunięta dla tego klienta.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/e6738604-6556-40b9-b349-4674b8fffc1b)


### PU31.	Usunięcie posiłku [Michał Szlązak]

Test:
1. Klient wchodzi na stronę koszyka.
2. Klient wybiera przycisk usunięcia posiłku.

Oczekiwany rezultat:
1. Posiłek zostaje usunięty z koszyka dla tego klienta.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/8892bda5-6387-4f0e-9052-cfcdde02daa5)


### PU32.	Wybranie innego terminu dostawy [Michał Szlązak]

Test:
1. Klient wchodzi na stronę koszyka.
2. Klient wybiera zmianę daty dostawy.

Oczekiwany rezultat:
1. Termin dostawy zostaje zmieniony dla tego klienta.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/8a691943-d053-4f2a-a2a2-98ffa9e222f5)


### PU33.	Wybranie innego posiłku [Michał Szlązak]

Test:
1. Klient wchodzi na stronę koszyka.
2. Klient wybiera inny posiłek zamiast wczśniej wybranego.

Oczekiwany rezultat:
1. Koszyk zostaje zaktualizowany dla tego klienta.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/3f36ed45-f3dd-4f5d-bc79-c904f5a3872e)


### PU34.	Zarejestrowanie się w systemie [Stanisław Maliński]

Test:
1. Klient wchodzi na stronę główną i wybiera opcje dołączenia jako "Klient".
2. Klient wprowadza dane rejetracyjne.
3. Klient wchodzi w link wysłany w wiadomości.

Oczekiwany rezultat:
1. Konto klienta zostaje aktywowane i dodane do bazy.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/529040a2-6183-4a93-8f98-a2cb82991985)


### PU35.	Zalogowanie się do systemu [Stanisław Maliński

Test:
1. Klient wchodzi na stronę główną i wybiera opcje zalogowania jako "Klient".
2. Klient wprowadza dane logowania.

Oczekiwany rezultat:
1. Jeśli dane poprawne to klient zostaje zalogowany  i wyświetlona zostaje strona główna.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/ca267aae-e53e-4123-b6f1-e6b95cad6596)


### PU36.	Zarejestrowanie się w systemie za pomocą konta Microsoft, Google lub Apple [Stanisław Maliński]

Test:
1. Klient wchodzi na stronę główną i wybiera opcje dołączenia jako "Klient".
2. Klient wybiera opcję rejestracji przez zewnętrzny system.

Oczekiwany rezultat:
1. Konto klienta zostaje aktywowane i dodane do bazy.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/88570de0-15f3-4231-b803-5d2a968cd9c0)


### PU37.	Zalogowanie się do systemu za pomocą konta Microsoft, Google lub Apple [Stanisław Maliński]

Test:
1. Klient wchodzi na stronę główną i wybiera opcje zalogowania jako "Klient".
2. Klient wybiera opcję logowaniai przez zewnętrzny system.

Oczekiwany rezultat:
1. Jeśli dane poprawne to klient zostaje zalogowany  i wyświetlona zostaje strona główna.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/4be20b2f-39f4-4873-9bb3-54b8ed618c7d)


### PU38.	Uzupełnienie danych adresowych [Stanisław Maliński]

Test:
1. Klient wypełnia formularz wprowadzania danych adresowych.
2. Klient zaznacza zapamiętanie adresu.

Oczekiwany rezultat:
1. Jeśli dane poprawne to adres zostaje zapamiętany w systemie.


![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/a9b04dc3-817c-406d-a605-00a5531c9d7a)


### PU39.	Przejrzenie listy zrealizowanych zamówień [Stanisław Maliński]

Test:
1. Klient naciska przycisk "Zamówienia".
2. Klient otwiera zakładkę "Zrealizowane".

Oczekiwany rezultat:
1. Klient widzi listę zrealizowanych zamówień.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/37200b24-8c6c-4828-97e1-8ce32bd88867)


### PU40.	Ocenienie usługi [Stanisław Maliński]

Test:
1. System wyświetla żądanie o ocenę.
2. Klient potwierdza, wypełnia i wysyła ocenę.

Oczekiwany rezultat:
1. Ocena zostaje zapisana w systemie.
2. Wyśietlone zostaje podziękowanie.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/62eb150b-e02a-4832-80f9-8e23e750446a)


### PU41.	Zgłoszenie skargi na dostawce [Stanisław Maliński]

Test:
1. Klient wchodzi w profil usługodwacy i wybiera przycisk "Zgłoś skargę".
2. Klient wypełnia i wysyła formularz skargi.

Oczekiwany rezultat:
1. Skarga zostaje złożona w systemie.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/e1a44ee6-4681-43c7-89b3-67b5910c7997)


### PU42.	Wystawienie opinii na temat usługi [Stanisław Maliński]

Test:
1. System wyświetla żądanie o ocenę.
2. Klient potwierdza, wypełnia i wysyła ocenę.

Oczekiwany rezultat:
1. Ocena zostaje zapisana w systemie.
2. Wyświetlone zostaje podziękowanie.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/d7baf94f-9b7e-4c61-b454-b0f259f42c76)


### PU43.	Przejrzenie powiadomienia [Stanisław Maliński]

Test:
1. Klient przechodzi do zakładki "Powiadomienia".
2. Klient naciska na powiadomienie.

Oczekiwany rezultat:
1. Klient widzi szczegóły wybranego powiadomienia.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/42f6d9e4-133f-48f3-80c3-848c08e9348e)


### PU44.	Wyłączenie zbędnych powiadomień [Stanisław Maliński]

Test:
1. Klient przechodzi do zakładki ustawień.
2. Klient wyłacza wybrane powiadomienia.

Oczekiwany rezultat:
1. Klient nie otrzymuje wybranych powiadomień.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/6cf4e7fd-dcc8-4a7a-8e40-852ce87e3892)


### PU45.	Przejrzenie ofert [Mateusz Tkaczyk]

Test:
1. Klient przechodzi do strony głównej.

Oczekiwany rezultat:
1. Klient widzi ofertę zgodnie z preferencjami.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/a0215355-d0d8-4ece-811d-401ccdf6b4b3)


### PU46.	Przefiltrowanie dostawców usług cateringowych [Mateusz Tkaczyk]

Test:
1. Klient przechodzi do strony głównej.
2. Klient stosuje filtry do dostawców.

Oczekiwany rezultat:
1. Klient widzi przefiltrowaną ofertę zgodnie z preferencjami.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/367671d5-acc3-4ca7-9723-faf9d7ab2cf6)


### PU47.	Przejrzenie konkretnej oferty [Mateusz Tkaczyk]

Test:
1. Klient przechodzi do strony "Przejdź do oferty" przy wybranej ofercie.

Oczekiwany rezultat:
1. Klient widzi szczegóły oferty.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/70b5215f-1d62-4afa-bb5a-31351f89d07b)


### PU48.	Przejrzenie ocen i komentarzy o usługodawcy [Mateusz Tkaczyk]

Test:
1. Klient przechodzi do strony ocen usługodawcy.

Oczekiwany rezultat:
1. Klient widzi oceny wybranego usługodawcy.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/e1c8e4e7-1868-4665-82f9-c789f165dd9f)


### PU49.	Zgłoszenie opinii [Mateusz Tkaczyk]

Test:
1. Klient naciska przycisk "Zgłoś" przy wybranej opinii.
2. Klient wypełnia zgłoszenie i je przesyła.

Oczekiwany rezultat:
1. Zgłoszona opinia zostaje usunięta z systemu.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/b2df4e98-83c0-4f69-a9e4-a50b87af4b28)


### PU50.	Skonfigurowanie posiłku [Mateusz Tkaczyk]

Test:
1. Klient wybiera opcje konfiguracji.
2. Klient konfiguruje posiłek.

Oczekiwany rezultat:
1. Skonfigurowany posiłęk zostaje zapisany.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/52faed77-6c40-4334-815d-316671a8a8f3)


### PU51.	Zasubskrybowanie usługi cateringowej [Mateusz Tkaczyk]

Test:
1. Klient klika przycisk "Zasubskrybuj" przy wybranej subskrybcji.
2. Klient dokonuje konfiguracji posiłku.

Oczekiwany rezultat:
1. Klient zostaje przekierowany na stronę składania zamównienia.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/7eb8f4e2-ac10-45a3-ae31-5fdb22e00f83)


### PU52.	Złożenie zamówienia na jedzenie [Mateusz Tkaczyk]

Test:
1. Klient przechodzi na stronę składania zamównienia.
2. Klient wprowadza dane dostawcy.
3. Klient opłaca zamówienie online.

Oczekiwany rezultat:
1. Zamówienie zostaje przekazane do realizacji.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/496b9016-a6e1-42dc-8d52-ac0c3d8b0f84)


### PU53.	Zrealizowanie kodu rabatowego [Mateusz Tkaczyk]

Test:
1. Klient podaje kod rabatowy.

Oczekiwany rezultat:
1. System przypisuje klientowi zniżkę.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/0c938f55-e36c-4f33-ba0a-8cb7ce295e85)


### PU54.	Opłacenie zamówienia online [Mateusz Tkaczyk]

Test:
1. Klient wybiera metodę płatności.
2. Klient podaje dane płatności.

Oczekiwany rezultat:
1. Płatność została zrealizawana.
2. System zamówień dostaje powiadomienie o udanej transakcji.

![image](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/d7782fa8-b77c-4073-bd31-e8a5e542d07d)


