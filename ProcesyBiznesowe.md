# Procesy Biznesowe

## Opis procesów biznesowych:

### 1. Rejestracja dostawcy w systemie
Firma cateringowa decyduje się na dołączenie do systemu. Następnie ta firma, zwana od teraz dostawcą, przekazuje w formie elektronicznej formularz z danymi niezbędnymi do funkcjonowania w systemie dla administratora systemu. Przesłany formularz jest następnie walidowany przez system pod względem poprawności. Jeżeli dane wprowadzone są niepoprawne to formularz jest zwracany do poprawienia. Jeżeli dostawca anuluje poprawianie formularza to zostanie on odrzucony. Następnie sprawdzany jest przez administratora systemu. Jeżeli dane są niezgodne to zwracany jest do poprawienia. Jeżeli dostawca anuluje poprawianie formularza to zostanie on odrzucony. Po weryfikacji administrator tworzy konto w systemie dla dostawcy. Następnie administrator przekazuje dane do pierwszego logowania w systemie dla dostawcy. Potem po pierwszym logowaniu w aplikacji mobilnej lub webowej dostawca zmienia pierwotne dane logowania na swoje prywatne. Od teraz dostawca jest widoczny w systemie i może prowadzić w ramach tego określone działania.
![](images/Rejestracja_dostawcy_w_systemie.png "Rejestracja dostawcy w systemie")  
*Diag. 1. Twórca: Mateusz Tkaczyk, Właściciel procesu: Bernard Cesarz*

### 2. Rejestracja klienta w systemie
Użytkownik wchodzi na stronę logowania w aplikacji webowej lub mobilnej i wybiera opcję rejestracji. Użytkownik wypełnia formularz rejestracyjny który jest następnie walidowany pod względem poprawności przez system. Jeżeli dane wprowadzone są niepoprawne to formularz jest zwracany do poprawienia. Jeżeli użytkownik anuluje poprawianie formularza to zostanie on odrzucony. Po pomyślnym zakończeniu weryfikacji na adres poczty elektronicznej podanej przez użytkownika zostaje wysłany link potwierdzający utworzenie konta. Po wejściu w link użytkownik zostaje poinformowany w komunikacie o aktywacji konta. Od teraz użytkownik, zwany od teraz klientem, widoczny jest w systemie i może prowadzić w ramach tego określone działania.
![](images/Rejestracja_klienta_w_systemie.png "Rejestracja klienta w systemie")  
*Diag. 2. Twórca: Mateusz Tkaczyk, Właściciel procesu: Mateusz Tkaczyk*

### 3. Złożenie zamówienia przez klienta
Klient wybiera opcję w aplikacji mobilnej lub webowej dotyczącą złożenia zamównienia. Następnie wprowadza adres oraz datę dostawy w przeznaczone do tego pola w aplikacji. System wyświetla na podstawie wprowadzonych danych ofertę. Klient wybiera dostępne filtry dotyczące oferty, poprzez odpowiedni formularz. Klient może także zostawić ten formularz pusty. System wyświetla zaktualizowaną ofertę na podstawie wprowadzonych filtrów. Klient wybiera elementy zamówienia dostępne w ramach oferty. Alternatywnie klient może wybrać elementy zamówienia na podstawie swojej historii zamówień. Po skomponowaniu elementów zamówienia klient przechodzi do koszyka zakupowego. W ramach koszyka widoczne jest podsumowanie zamówienia z dobrze widocznymi informacjami o dacie. Następnie klient wybiera dostępną formę dostawy. Klient może wprowadzić kod rabatowy w przeznaczone do tego pole w aplikacji. Po tej czynności kwota zamówienia zaktualizuje się. Następnie klient wybiera jeden z dostępnych rodzajów płatności. Klient może zaznaczyć opcję wydania faktury. W przypadku zaznaczenia tej opcji system wyświetla formularz z danymi do faktury. Klient wprowadza dane do formularza. System waliduje wprowadzone dane. Jeżeli dane wprowadzone są niepoprawne to formularz jest zwracany do poprawienia. Jeżeli użytkownik anuluje poprawianie formularza to zostanie on odrzucony. Klient dokonuje płatności. Zamówienie zostaje zapisane w systemie. Odpowiedzialni dostawcy rozpoczynają realizację zamówienia.
![](images/Złożenie_zamówienia_przez_klienta.png "Złożenie zamówienia przez klienta")  
*Diag. 3. Twórca: Mateusz Tkaczyk, Właściciel procesu: Mateusz Tkaczyk*

### 4. Rozpoczęcie subskrypcji przez klienta (model - Sebastian Pietrykowski, opis - Sebastian Grosfeld)
Klient wybiera opcję w aplikacji webowej lub mobilnej dotyczącą rozpoczęcia subskrypcji. Następnie wprowadza adres na który ma być realizowana subskrypcja w przeznaczone do tego pole w aplikacji. Na podstawie wprowadzonej danej system wyświetla ofertę subskrypcji. Klient wybiera dostępne filtry dotyczące oferty, poprzez odpowiedni formularz. Klient może także zostawić ten formularz pusty. System wyświetla zaktualizowaną ofertę subskrypcji na podstawie wprowadzonych filtrów. Klient wybiera jedną z dostępnych ofert i przechodzi do koszyka zakupowego. W koszyku widoczne jest podsumowanie wybranej subskrypcji. Następnie klient wybiera dostępną formę dostawy dla subskrypcji. Klient może wprowadzić kod rabatowy w przenaczone do tego pole w aplikacji. Po tej czynności kwota podsumowania subskrypcji zaktualizuje się. Następnie klient wybiera jeden z dostępnych rodzajów płatności. Klient może zaznaczyć opcję wydania faktury. W przypadku zaznaczenia tej opcji system wyświetla formularz z danymi do faktury. Klient wprowadza dane do formularza. System waliduje wprowadzone dane. Jeżeli dane wprowadzone są niepoprawne to formularz jest zwracany do poprawienia. Jeżeli użytkownik anuluje poprawianie formularza to zostanie on odrzucony. Klient dokonuje płatności. Subskrypcja zostaje zapisana w systemie. Odpowiedzialny dostawca rozpoczyna realizację subskrycji.
![](images/Rozpoczęcie_subskrypcji_przez_klienta.png "Rozpoczęcie subskrypcji przez klienta")  
*Diag. 4.1. Twórca: Sebastian Pietrykowski, Właściciel procesu: Stanisław Maliński*
![](images/Wprowadzenie_kodu_rabatowego.png "Wprowadzenie kodu rabatowego")  
*Diag. 4.2. Twórca: Sebastian Pietrykowski, Właściciel procesu: Stanisław Maliński*
![](images/Wystawienie_faktury.png "Wystawienie faktury")  
*Diag. 4.3. Twórca: Sebastian Pietrykowski, Właściciel procesu: Stanisław Maliński*

### 5. Rezygnacja z subskrypcji przez klienta (model - Sebastian Pietrykowski, opis - Sebastian Grosfeld)
Klient wybiera zakładkę w aplikacji zawierającą aktywne subskrypcje u dostawców. Wybiera subskrypcje z której chce zrezygnować, a następnie wybiera opcję rezygnacji z subskrypcji. System wyświetla informacje na temat wybranej subskrypcji oraz od kiedy przestałaby obowiązywać. Następnie system wyświetla komunikat potwierdzający rezygnację z subskrypcji. W przypadku anulowania system z powrotem wyświetla aktywne subskrypcje. W przypadku potwierdzenia system wprowadza odpowiednie zmiany do systemu. Po upływie daty wygaśnięcia subskrypcji subskrypcja jest deaktywowana dla danego klienta. 
![](images/Rezygnacja_z_subskrypcji_przez_klienta.png "Rezygnacja z subskrypcji przez klienta")  
*Diag. 5. Twórca: Sebastian Pietrykowski, Właściciel procesu: Sebastian Pietrykowski*

### 6. Wskazanie rekomendacji dla klienta (model - Sebastian Pietrykowski, opis - Sebastian Grosfeld)
Klient przegląda dostępną ofertę. System pobiera infromacje o poprzednich zamówieniach klienta. Następnie na podstawie zebranych danych system wyznacza rekomendacje w ramach oferty z nastawieniem na zachęcenie do zamówienia nowych pozycji oraz na najlepiej oceniane pozycje. Następnie system w pierwszej kolejności wyświetla pozycje odpowiadające wystawionej wcześniej rekomendacji.
![](images/Wskazanie_rekomendacji_dla_klienta.png "Wskazanie rekomendacji dla klienta")  
*Diag. 6. Twórca: Sebastian Pietrykowski, Właściciel procesu: Sebastian Pietrykowski*

### 7. Wystawianie opinii przez klientów
Klient wybiera zakładkę w aplikacji zawierającą zrealizowane zamówienia. Wybiera jedne z wyświetlanych zamówień i wybiera opcję wystawienia opinii. System weryfikuje czy zamówienie zostało odebrane przez klienta. Jeśli nie, to wyświetla odpowiedni komunikat i wraca do zrealizowanych zamówień. Jeśli tak, to system wyświetla formularz wystawienia opinii w związku z zrealizowanym zamówieniem. Klient wypełnia formularz. System weryfikuje go pod względem poprawności. Jeżeli dane wprowadzone są nie poprawne to formularz jest zwracany do poprawienia. Jeżeli klient anuluje poprawianie formularza to zostanie on odrzucony. Jeśli dane są poprawne to system wyświetli komunikat z podziękowaniem i zapisze wystawioną opinię. 
![Michał Szlązak](images/Wystawienie_Opinii.png "Wystawianie opinii przez klientów")
*Diag. 7. Twórca: Michał Szlązak, Właściciel procesu: Wiktor Nasierowski*

### 8. Weryfikacja opinii klienta
Do systemu trafia informacja o zgłoszeniu wystawionej opinii przez klienta. System przekazuje tą informację zawierającą m.in powód zgłoszenia do wyznaczonego pracownika. Pracownik ten weryfikuje wystawioną opinię pod względem nieodpowiednich treści. Jeżeli pracownik stwierdzi że zgłoszenie jest słuszne to potwierdza zgłoszenie. Następnie opinia jest usuwana przez system. W przypadku gdy pracownik stwierdzi że zgłoszenie jest niesłuszne to odrzuca zgłoszenie, a system zachowuje opinię.
![](images/Weryfikacja_Opinii.png "Weryfikacja opinii klienta")  
*Diag. 8. Twórca: Michał Szlązak, Właściciel procesu: Michał Szlązak*

### 9. Realizacja rozliczeń z dostawcami usług caterinowych
System gromadzi informacje dotyczące zamówień złożonych przez klientów i wysyła je do dostawcy. Następnie oczekuje na otrzymanie faktur wystawionych przez dostawcę. Otrzymane faktury są weryfikowane co do zgodności danych identyfikacyjnych, produktów, cen i kwoty do zapłaty. Po dokonaniu weryfikacji, faktury są rejestrowane w systemie księgowym firmy i zatwierdzane do zapłaty. Jeśli wszystkie dane są poprawne, faktury są akceptowane do płatności. W przypadku jakichkolwiek nieprawidłowości, konieczne może być skontaktowanie się z dostawcą w celu wyjaśnienia sytuacji. Następnie firma dokonuje płatności dla dostawcy w formie przelewu bankowego. Do dostawcy wysyłane jest potwierdzenie przelewu.
![](images/Realizacja_rozliczeń_z_dostawcami_usług_cateringowych.png "Realizacja rozliczeń z dostawcami usług caterinowych")  
*Diag. 9. Twórca: Michał Szlązak, Właściciel procesu: Michał Szlązak*

### 10. Zarządzanie zamówieniami posiłków
System przyjmuje zamówienia na posiłki od klientów. Po otrzymaniu zamównienia, system rejestruje je w bazie danych. System sprawdza dostępność zamówionych posiłków oraz możliwe terminy dostawy. Jeśli któryś z zamówionych posiłków jest niedostępny w danym terminie, system może zaproponować alternatywny posiłek lub inne dostępne terminy. Po weryfikacji dostępności, zamówienia są przygotowywane do realizacji. Posiłki są przygotowywane zgodnie z zamówieniem, pakowane i dostarczane do klientów. Gdy dostawa wyrusza do klienta dostaje on powiadomienie w aplikacji.
![](images/Zarządzanie_zamówieniami_posiłków.png "Zarządzanie zamówieniami posiłków")  
*Diag. 10. Twórca: Michał Szlązak, Właściciel procesu: Krzysztof Tadeusik*

### 11. Dodawanie posiłków przez dostawcę
Dostawca wybiera zakładkę w aplikacji zawierającą oferowane zamówienia. Z tej pozycji ma możliwość dodania nowego posiłku. W tym celu musi podać dane w formularzu dotyczące posiłu, w szczególności kaloryczność, informacje o wartościach odżywczych, rodzaj kuchni, opis, zdjęcie. Ponadto sprzedawca określa możliwy termin dostawy, obejmujący określenie dni tygodnia, godzin dostawy oraz minimalnej ilości zamówień dla danego posiłku. Następnie zatwierdza formnularz.
![](./images/Dodawanie_posiłków_przez_dostawcę.png "Dodawanie posiłków przez dostawcę")  
*Diag. 11. Twórca: Ulyana Petrashevich, Właściciel procesu: Adam Smerdzyński*

### 12. Aktualizowanie oferowanych posiłków przez dostawcę
Dostawca wybiera zakładkę w aplikacji zawierającą oferowane zamówienia. Odnajduje interesujący go posiłek. Dostawca wybiera opcję edycji posiłku. Zostaje przekierowany do formularza zawierającego dane zapisane w systemie. Dostawca dokonuje niezbędnych zmian, następnie zatwierdza formularz. System dokonuje aktualizacji danych w swojej bazie danych.
![](./images/Aktualizowanie_oferowanych_posiłków_przez_dostawcę.png "Aktualizowanie oferowanych posiłków przez dostawcę")  
*Diag. 12. Twórca: Ulyana Petrashevich, Właściciel procesu: Ulyana Petrashevich*

### 13. Zgłaszanie przez klienta skargi na dostawcę
Klient wchodzi w aplikacji w historię swoich zamówień, wybiera odpowiednie zamówienie. Klient wypełnia odpowiedni formularz, w którym opisuje swoją skargę. Podaje informację o typie problemu, opisuje zdarzenie. Skarga trafia do pracownika, który po zweryfikowaniu skargi kontaktuje się z dostawcą. W trakcie kontaktu pracownik dokładnie opisuje problem i oczekiwania wobec dostawcy w celu rozwiązania sytuacji. Dostawca podejmuje działania w celu rozwiązania problemu. Klient zostaje poinformowany o działaniach wobec dostawcy. W przypadku braku zadowolenia pracownik podejmuje dalsze działania wobec dostawcy. Jeżeli dostawca nie zgodzi się na proponowane rozwiązanie dostawca zostaje usunięty z listy dostawców.
![](./images/Zgłaszanie_przez_klienta_skargi_na_dostawcę.png "Zgłaszanie przez klienta skargi na dostawcę")  
*Diag. 13. Twórca: Ulyana Petrashevich, Właściciel procesu: Ulyana Petrashevich*

### 14. Pozyskiwanie statystyk biznesowych przez dostawcę
Dostawca wybiera w aplikacji zakładkę zawierającą statystyki. Dostawca ma możliwość przeglądania różnych rodzajów statystyk, takich jak liczba aktywnych klientów, przychody czy inne istotne wskaźniki biznesowe. Dostawcy są prezentowane odpowiednie wykresy i zestawienia danych. Może on sortować i filtrować przedstawione dane. Następnie dostawca analizuje zebrane dane, aby lepiej zrozumieć swoją działalność oraz identyfikować trendy i wzorce w zachowaniach klientów. Na podstawie analizy danych dostawca dokonuje interpretacji wyników i wyciąga wnioski.
![](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/d5c20749-e22c-4a60-bd9c-200b35acaaea "Pozyskiwanie statystyk biznesowych przez dostawcę")  
*Diag. 14. Twórca: Sebastian Grosfeld, Właściciel procesu: Sebastian Grosfeld*

### 15. Aktualizacja danych dostawcy w systemie
Dostawca usług cateringowych kontaktuje się pracownikiem firmy. Otrzymuje formularz ze swoimi danymi, wprowadza niezbędne modyfikacje. Przesłany formularz jest następnie walidowany przez system pod względem poprawności. W przypadku błędów jest zwracany do ponownego uzupełnienia. Formularz jest sprawdzany przez administratora systemu. Jeżeli wykryje on błąd formularz jest zwracany. Po weryfikacji administrator wprowadza niezbędne zmiany w systemie i informuje dostawcę o wprowadzeniu zmian.
![](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/d9acce9e-18f1-4f4d-a85d-184761420b73 "Aktualizacja danych dostawcy w systemie")  
*Diag. 15. Twórca: Sebastian Grosfeld, Właściciel procesu: Sebastian Sekuła*

### 16. Rezygnacja dostawcy z uczestniczenia w systemie
Dostawca usług cateringowych kontaktuje się pracownikiem firmy. Informuje o zamiarze rezygnacji współpracy. Pracownik przekonuje do kontynuacji współpracy. Pyta dostawcę o przyczyny decyzji i oferuje rozwiązanie zadowalające obie strony. W przypadku braku chęci kontynuacji współpracy ze strony dostawcy informuje o harmonogramie działań. Posiłki oferowane przez dostawcę przestają być oferowane klientom. Następuje rozlicznie z dostawcą. Dane dostawcy są usuwane z systemu.
![](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/eb0462df-7f15-4b6b-b744-051b09fe309d "Rezygnacja dostawcy z uczestnictwa w systemie")  
*Diag. 16. Twórca: Sebastian Grosfeld, Właściciel procesu: Maciej Sudoł*

### 17. Promowanie usług dostawców
Dostawca wybiera zakładkę w aplikacji zawierającą zarządzanie promowaniem usług. Zostaje mu przedstawione oferta promowania, w ramach której usługi dostawcy będą wyróżnione na stronie. Dostawca może zaznaczyć interesującą go ofertę i wykupić odpowiedni pakiet. Po płatności zostaje poinformowany o rozpoczęciu promocji. Dostawca może monitorować efektywność promocji przez udostępnione w aplikacji statystyki. Na podstawie zebranych danych dostawca może wykupić inny pakiet promowania.
![](https://github.com/MiloszMertka/pw-iwo-lab/assets/95347931/36fb2a61-07eb-4764-8891-6813c07aaa50 "Promowanie usług dostawców")  
*Diag. 17. Twórca: Sebastian Grosfeld, Właściciel procesu: Sebastian Grosfeld*
