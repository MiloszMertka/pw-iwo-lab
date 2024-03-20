# Specyfikacja Wymagań Zamawiającego

1. [Wprowadzenie](#wprowadzenie)
    - [Definicja problemu](#definicja-problemu)
    - [Cel biznesowy](#cel-biznesowy)
2. [Wizja Systemu](#wizja-systemu)
    - [Opis procesów biznesowych](#opis-procesów-biznesowych)
    - [Cechy systemu](#cechy-systemu)
3. [Wymagania funkcjonalne](#wymagania-funkcjonalne)
4. [Wymagania jakościowe i ograniczenia](#wymagania-jakościowe-i-ograniczenia)
5. [Słownik dziedziny](#słownik-dziedziny)

Kierownik projektu: Miłosz Mertka  
Zredagował: Stanisław Maliński  
Sprawdził: Krzysztof Tadeusik  
Pozostali członkowie zespołu:  
Bernard Cesarz,  
Sebastian Grosfeld,  
Ulyana Petrashevich,  
Sebastian Pietrykowski,  
Sebastian Sekula,  
Maciej Sudol,  
Michał Szlązak  

## Wprowadzenie

### Definicja problemu

[*Michał Szlązak*]  
W dzisiejszym środowisku, gdzie wiele osób preferuje korzystać z usług cateringowych w celu oszczędzenia czasu i zachowania zdrowego trybu życia, istnieje wyraźna potrzeba efektywnego sposobu zamawiania posiłków od wielu dostawców cateringowych w jednym miejscu. 

Obecnie, brak takiego centralnego systemu prowadzi do rozproszenia zamówień i trudności zarówno dla klientów, którzy muszą składać zamówienia oddzielnie u różnych dostawców, jak i dla dostawców, którzy muszą radzić sobie z różnorodnością zamówień i wieloma wymaganiami klientów. 

Brak jednolitego systemu integracji i zarządzania zamówieniami utrudnia śledzenie, płatności i dostawy, co prowadzi do nieefektywności i frustracji zarówno u klientów, jak i u dostawców. Rozwiązanie tego problemu biznesowego wymaga stworzenia spójnego systemu, który umożliwi łatwe i wygodne zamawianie posiłków od wielu dostawców w obrębie jednego zamówienia.

Zwiększy to elastyczność składania zamówień dla klientów i ułatwi zarządzanie zamówieniami dla dostawców. Zmniejszy presję na dostawcach usług cateringowych, którzy nie będą musieli samodzielnie spełnić wszystkich wymagań i potrzeb klienta.

### Cel biznesowy
[*Maciej Sudol*]  
Celem projektu jest stworzenie kompleksowego systemu gromadzącego dostawców cateringowych, umożliwiającego efektywne i elastyczne zamawianie posiłków od różnych dostawców w jednej aplikacji.
System ma za zadanie:
- umożliwić klientom zamawianie dowolnych kombinacji różnych posiłków od różnych dostawców lub skorzystania z subskrypcji,
- dostarczyć klientom narzędzi do oceniania i rekomendowania usług poszczególnych dostawców,
- stworzyć system nagród dla stałych klientów,
- umożliwić klientom i dostawcom zarządzanie własnymi zamówieniami i płatnościami,
- umożliwić dostawcom gromadzenie i śledzenie statystyk swoich usług,
- umożliwić promocję usług dostawców w aplikacji,
- stworzyć sprawny i przejrzysty proces zarządzania kurierami,
- dostarczyć intuicyjny interfejs użytkownika w formie aplikacji webowej i mobilnej.

## Wizja Systemu

### Opis procesów biznesowych

#### 1. Rejestracja dostawcy w systemie
Firma cateringowa decyduje się na dołączenie do systemu. Następnie ta firma, zwana od teraz dostawcą, przekazuje w formie elektronicznej formularz z danymi niezbędnymi do funkcjonowania w systemie dla administratora systemu. Przesłany formularz jest następnie walidowany przez system pod względem poprawności. Jeżeli dane wprowadzone są niepoprawne to formularz jest zwracany do poprawienia. Jeżeli dostawca anuluje poprawianie formularza to zostanie on odrzucony. Następnie sprawdzany jest przez administratora systemu. Jeżeli dane są niezgodne to zwracany jest do poprawienia. Jeżeli dostawca anuluje poprawianie formularza to zostanie on odrzucony. Po weryfikacji administrator tworzy konto w systemie dla dostawcy. Następnie administrator przekazuje dane do pierwszego logowania w systemie dla dostawcy. Potem po pierwszym logowaniu w aplikacji mobilnej lub webowej dostawca zmienia pierwotne dane logowania na swoje prywatne. Od teraz dostawca jest widoczny w systemie i może prowadzić w ramach tego określone działania.
[*Sebastian Grosfeld*]   

#### 2. Rejestracja klienta w systemie
Użytkownik wchodzi na stronę logowania w aplikacji webowej lub mobilnej i wybiera opcję rejestracji. Użytkownik wypełnia formularz rejestracyjny który jest następnie walidowany pod względem poprawności przez system. Jeżeli dane wprowadzone są niepoprawne to formularz jest zwracany do poprawienia. Jeżeli użytkownik anuluje poprawianie formularza to zostanie on odrzucony. Po pomyślnym zakończeniu weryfikacji na adres poczty elektronicznej podanej przez użytkownika zostaje wysłany link potwierdzający utworzenie konta. Po wejściu w link użytkownik zostaje poinformowany w komunikacie o aktywacji konta. Od teraz użytkownik, zwany od teraz klientem, widoczny jest w systemie i może prowadzić w ramach tego określone działania.
[*Sebastian Grosfeld*]   

#### 3. Złożenie zamówienia przez klienta
Klient wybiera opcję w aplikacji mobilnej lub webowej dotyczącą złożenia zamównienia. Następnie wprowadza adres oraz datę dostawy w przeznaczone do tego pola w aplikacji. System wyświetla na podstawie wprowadzonych danych ofertę. Klient wybiera dostępne filtry dotyczące oferty, poprzez odpowiedni formularz. Klient może także zostawić ten formularz pusty. System wyświetla zaktualizowaną ofertę na podstawie wprowadzonych filtrów. Klient wybiera elementy zamówienia dostępne w ramach oferty. Alternatywnie klient może wybrać elementy zamówienia na podstawie swojej historii zamówień. Po skomponowaniu elementów zamówienia klient przechodzi do koszyka zakupowego. W ramach koszyka widoczne jest podsumowanie zamówienia z dobrze widocznymi informacjami o dacie. Następnie klient wybiera dostępną formę dostawy. Klient może wprowadzić kod rabatowy w przeznaczone do tego pole w aplikacji. Po tej czynności kwota zamówienia zaktualizuje się. Następnie klient wybiera jeden z dostępnych rodzajów płatności. Klient może zaznaczyć opcję wydania faktury. W przypadku zaznaczenia tej opcji system wyświetla formularz z danymi do faktury. Klient wprowadza dane do formularza. System waliduje wprowadzone dane. Jeżeli dane wprowadzone są niepoprawne to formularz jest zwracany do poprawienia. Jeżeli użytkownik anuluje poprawianie formularza to zostanie on odrzucony. Klient dokonuje płatności. Zamówienie zostaje zapisane w systemie. Odpowiedzialni dostawcy rozpoczynają realizację zamówienia.
[*Sebastian Grosfeld*]   

#### 4. Rozpoczęcie subskrypcji przez klienta
Klient wybiera opcję w aplikacji webowej lub mobilnej dotyczącą rozpoczęcia subskrypcji. Następnie wprowadza adres na który ma być realizowana subskrypcja w przeznaczone do tego pole w aplikacji. Na podstawie wprowadzonej danej system wyświetla ofertę subskrypcji. Klient wybiera dostępne filtry dotyczące oferty, poprzez odpowiedni formularz. Klient może także zostawić ten formularz pusty. System wyświetla zaktualizowaną ofertę subskrypcji na podstawie wprowadzonych filtrów. Klient wybiera jedną z dostępnych ofert i przechodzi do koszyka zakupowego. W koszyku widoczne jest podsumowanie wybranej subskrypcji. Następnie klient wybiera dostępną formę dostawy dla subskrypcji. Klient może wprowadzić kod rabatowy w przenaczone do tego pole w aplikacji. Po tej czynności kwota podsumowania subskrypcji zaktualizuje się. Następnie klient wybiera jeden z dostępnych rodzajów płatności. Klient może zaznaczyć opcję wydania faktury. W przypadku zaznaczenia tej opcji system wyświetla formularz z danymi do faktury. Klient wprowadza dane do formularza. System waliduje wprowadzone dane. Jeżeli dane wprowadzone są niepoprawne to formularz jest zwracany do poprawienia. Jeżeli użytkownik anuluje poprawianie formularza to zostanie on odrzucony. Klient dokonuje płatności. Subskrypcja zostaje zapisana w systemie. Odpowiedzialny dostawca rozpoczyna realizację subskrycji.
[*Sebastian Grosfeld*]   

#### 5. Rezygnacja z subskrypcji przez klienta
Klient wybiera zakładkę w aplikacji zawierającą aktywne subskrypcje u dostawców. Wybiera subskrypcje z której chce zrezygnować, a następnie wybiera opcję rezygnacji z subskrypcji. System wyświetla informacje na temat wybranej subskrypcji oraz od kiedy przestałaby obowiązywać. Następnie system wyświetla komunikat potwierdzający rezygnację z subskrypcji. W przypadku anulowania system z powrotem wyświetla aktywne subskrypcje. W przypadku potwierdzenia system wprowadza odpowiednie zmiany do systemu. Po upływie daty wygaśnięcia subskrypcji subskrypcja jest deaktywowana dla danego klienta. 
[*Sebastian Grosfeld*]   

#### 6. Wskazanie rekomendacji dla klienta
Klient przegląda dostępną ofertę. System pobiera infromacje o poprzednich zamówieniach klienta. Następnie na podstawie zebranych danych system wyznacza rekomendacje w ramach oferty z nastawieniem na zachęcenie do zamówienia nowych pozycji oraz na najlepiej oceniane pozycje. Następnie system w pierwszej kolejności wyświetla pozycje odpowiadające wystawionej wcześniej rekomendacji.
[*Sebastian Grosfeld*]   

#### 7. Wystawianie opinii przez klientów
Klient wybiera zakładkę w aplikacji zawierającą zrealizowane zamówienia. Wybiera jedne z wyświetlanych zamówień i wybiera opcję wystawienia opinii. System weryfikuje czy zamówienie zostało odebrane przez klienta. Jeśli nie, to wyświetla odpowiedni komunikat i wraca do zrealizowanych zamówień. Jeśli tak, to system wyświetla formularz wystawienia opinii w związku z zrealizowanym zamówieniem. Klient wypełnia formularz. System weryfikuje go pod względem poprawności. Jeżeli dane wprowadzone są nie poprawne to formularz jest zwracany do poprawienia. Jeżeli klient anuluje poprawianie formularza to zostanie on odrzucony. Jeśli dane są poprawne to system wyświetli komunikat z podziękowaniem i zapisze wystawioną opinię. 
[*Sebastian Grosfeld*]   

#### 8. Weryfikacja opinii klienta
Do systemu trafia informacja o zgłoszeniu wystawionej opinii przez klienta. System przekazuje tą informację zawierającą m.in powód zgłoszenia do wyznaczonego pracownika. Pracownik ten weryfikuje wystawioną opinię pod względem nieodpowiednich treści. Jeżeli pracownik stwierdzi że zgłoszenie jest słuszne to potwierdza zgłoszenie. Następnie opinia jest usuwana przez system. W przypadku gdy pracownik stwierdzi że zgłoszenie jest niesłuszne to odrzuca zgłoszenie, a system zachowuje opinię.
[*Sebastian Grosfeld*]   

#### 9. Realizacja rozliczeń z dostawcami usług caterinowych
System gromadzi informacje dotyczące zamówień złożonych przez klientów i wysyła je do dostawcy. Następnie oczekuje na otrzymanie faktur wystawionych przez dostawcę. Otrzymane faktury są weryfikowane co do zgodności danych identyfikacyjnych, produktów, cen i kwoty do zapłaty. Po dokonaniu weryfikacji, faktury są rejestrowane w systemie księgowym firmy i zatwierdzane do zapłaty. Jeśli wszystkie dane są poprawne, faktury są akceptowane do płatności. W przypadku jakichkolwiek nieprawidłowości, konieczne może być skontaktowanie się z dostawcą w celu wyjaśnienia sytuacji. Następnie firma dokonuje płatności dla dostawcy w formie przelewu bankowego. Do dostawcy wysyłane jest potwierdzenie przelewu.
[*Sebastian Pietrykowski*]   

#### 10. Zarządzanie zamówieniami posiłków
System przyjmuje zamówienia na posiłki od klientów. Po otrzymaniu zamównienia, system rejestruje je w bazie danych. System sprawdza dostępność zamówionych posiłków oraz możliwe terminy dostawy. Jeśli któryś z zamówionych posiłków jest niedostępny w danym terminie, system może zaproponować alternatywny posiłek lub inne dostępne terminy. Po weryfikacji dostępności, zamówienia są przygotowywane do realizacji. Posiłki są przygotowywane zgodnie z zamówieniem, pakowane i dostarczane do klientów. Gdy dostawa wyrusza do klienta dostaje on powiadomienie w aplikacji.
[*Sebastian Pietrykowski*]   

#### 11. Dodawanie posiłków przez dostawcę
Dostawca wybiera zakładkę w aplikacji zawierającą oferowane zamówienia. Z tej pozycji ma możliwość dodania nowego posiłku. W tym celu musi podać dane w formularzu dotyczące posiłu, w szczególności kaloryczność, informacje o wartościach odżywczych, rodzaj kuchni, opis, zdjęcie. Ponadto sprzedawca określa możliwy termin dostawy, obejmujący określenie dni tygodnia, godzin dostawy oraz minimalnej ilości zamówień dla danego posiłku. Następnie zatwierdza formnularz.
[*Sebastian Pietrykowski*]   

#### 12. Aktualizowanie oferowanych posiłków przez dostawcę
Dostawca wybiera zakładkę w aplikacji zawierającą oferowane zamówienia. Odnajduje interesujący go posiłek. Dostawca wybiera opcję edycji posiłku. Zostaje przekierowany do formularza zawierającego dane zapisane w systemie. Dostawca dokonuje niezbędnych zmian, następnie zatwierdza formularz. System dokonuje aktualizacji danych w swojej bazie danych.
[*Sebastian Pietrykowski*]   

#### 13. Zgłaszanie przez klienta skargi na dostawcę
Klient wchodzi w aplikacji w historię swoich zamówień, wybiera odpowiednie zamówienie. Klient wypełnia odpowiedni formularz, w którym opisuje swoją skargę. Podaje informację o typie problemu, opisuje zdarzenie. Skarga trafia do pracownika, który po zweryfikowaniu skargi kontaktuje się z dostawcą. W trakcie kontaktu pracownik dokładnie opisuje problem i oczekiwania wobec dostawcy w celu rozwiązania sytuacji. Dostawca podejmuje działania w celu rozwiązania problemu. Klient zostaje poinformowany o działaniach wobec dostawcy. W przypadku braku zadowolenia pracownik podejmuje dalsze działania wobec dostawcy. Jeżeli dostawca nie zgodzi się na proponowane rozwiązanie dostawca zostaje usunięty z listy dostawców.
[*Sebastian Pietrykowski*]   

#### 14. Pozyskiwanie statystyk biznesowych przez dostawcę
Dostawca wybiera w aplikacji zakładkę zawierającą statystyki. Dostawca ma możliwość przeglądania różnych rodzajów statystyk, takich jak liczba aktywnych klientów, przychody czy inne istotne wskaźniki biznesowe. Dostawcy są prezentowane odpowiednie wykresy i zestawienia danych. Może on sortować i filtrować przedstawione dane. Następnie dostawca analizuje zebrane dane, aby lepiej zrozumieć swoją działalność oraz identyfikować trendy i wzorce w zachowaniach klientów. Na podstawie analizy danych dostawca dokonuje interpretacji wyników i wyciąga wnioski.
[*Sebastian Pietrykowski*]   

#### 15. Aktualizacja danych dostawcy w systemie
Dostawca usług cateringowych kontaktuje się pracownikiem firmy. Otrzymuje formularz ze swoimi danymi, wprowadza niezbędne modyfikacje. Przesłany formularz jest następnie walidowany przez system pod względem poprawności. W przypadku błędów jest zwracany do ponownego uzupełnienia. Formularz jest sprawdzany przez administratora systemu. Jeżeli wykryje on błąd formularz jest zwracany. Po weryfikacji administrator wprowadza niezbędne zmiany w systemie i informuje dostawcę o wprowadzeniu zmian.
[*Sebastian Pietrykowski*]   

#### 16. Rezygnacja dostawcy z uczestniczenia w systemie
Dostawca usług cateringowych kontaktuje się pracownikiem firmy. Informuje o zamiarze rezygnacji współpracy. Pracownik przekonuje do kontynuacji współpracy. Pyta dostawcę o przyczyny decyzji i oferuje rozwiązanie zadowalające obie strony. W przypadku braku chęci kontynuacji współpracy ze strony dostawcy informuje o harmonogramie działań. Posiłki oferowane przez dostawcę przestają być oferowane klientom. Następuje rozlicznie z dostawcą. Dane dostawcy są usuwane z systemu.
[*Sebastian Pietrykowski*]   

#### 17. Promowanie usług dostawców
Dostawca wybiera zakładkę w aplikacji zawierającą zarządzanie promowaniem usług. Zostaje mu przedstawione oferta promowania, w ramach której usługi dostawcy będą wyróżnione na stronie. Dostawca może zaznaczyć interesującą go ofertę i wykupić odpowiedni pakiet. Po płatności zostaje poinformowany o rozpoczęciu promocji. Dostawca może monitorować efektywność promocji przez udostępnione w aplikacji statystyki. Na podstawie zebranych danych dostawca może wykupić inny pakiet promowania.
[*Sebastian Pietrykowski*]   

## Cechy systemu
### Wymagania funkcjonalne
> Notacja x.y.z.v:
> x - aktor
> y - kategoria
> z - numer wymagania
> v - potencjalnie wersja w przyszłości
#### 1. Jako użytkownik:
##### 1.1 Rejestracja/Logowanie 
1.1.1 chcę mieć możliwość zarejestrowania się w aplikacji, aby móc korzystać z jej funkcji. [*Sebastian Sekula*]   
1.1.2 chcę mieć możliwość zarejestrowania się w aplikacji za pomocą konta Microsoft, Google, Apple, aby nie musieć podawać dodatkowych danych. [*Sebastian Sekula*]   
1.1.3 chcę mieć możliwość zalogowania się do aplikacji, aby móc korzystać z jej funkcji. [*Sebastian Sekula*]   
1.1.4 chcę mieć możliwość zalogowania się do tej samej aplikacji na różnych urządzeniach, aby mieć dostęp do swoich danych zawsze i wszędzie. [*Sebastian Sekula*] 
##### 1.2 Oceny/Rekomendacje
1.2.1 chcę mieć możliwość oceniać i komentować dostawców usług cateringowych z których usług skorzystałem, aby pomóc innym użytkownikom w wyborze najlepszej oferty. [*Sebastian Sekula*]   
1.2.2 chcę mieć możliwość przeglądania ocen i opinii na temat dostawców usług cateringowych z google, uber eats, oferteo, dietly, cateromarket oraz używanej aplikacji aby wybrać najlepszą ofertę. [*Sebastian Sekula*] 
##### 1.3 Zamówienia 
1.3.1 chcę mieć możliwość zamówienia jedzenia z dostawą, aby nie musieć gotować. [*Sebastian Sekula*]   
1.3.2 chcę mieć możliwość filtrowania usług cateringowych na podstawie:    
  - adres
  - data
  - dostawców
  - kalorie
  - popularność
  - opinie
  - docelowy klient
  - pojedyńcze posiłki
  - cena
  - typy posiłków - obiad, lunch
  - rodzaj kuchni
  - diety  

, aby znaleźć najlepszą ofertę odpowiednią dla mnie. [*Sebastian Sekula*]   
1.3.3 chcę mieć możliwość dowolnie konfigurować posiłki, aby zamówić dokładnie to, na co mam ochotę. [*Sebastian Sekula*]   
1.3.4 chcę mieć możliwość dowolnie konfigurować dostawców usług cateringowych, aby zamówić dokładnie to, na co mam ochotę. [*Sebastian Sekula*]   
1.3.5 chcę mieć możliwość zasubskrybowania usług cateringowych, aby nie musieć zamawiać posiłków codziennie.  
##### 1.4. Ulubione/Preferencje

1.4.1 chciałbym, aby aplikacja zapamiętała moje ulubione posiłki, aby móc je zamówić ponownie w szybki sposób. [*Sebastian Sekula*]   
1.4.2 chciałbym, aby aplikacja wyświetlała mi nowe posiłki na podstawie moich preferencji, aby móc spróbować czegoś nowego. [*Sebastian Sekula*]   
1.4.3 chciałbym, aby aplikacja wysyłała mi powiadomienia mailowe oraz przez powiadomienia push w aplikacji mobilnej o nowych daniach, aby spróbować czegoś nowego. [*Sebastian Sekula*]  
##### 1.5 Nagrody
[*Sebastian Sekula*]  
1.5.1 chciałbym, aby aplikacja nagradzała mnie za zamawianie posiłków, aby zyskać rabaty na kolejne zamówienia.  
#### 2. Jako dostawca usług cateringowych:
##### 2.1. Oferta 
2.1.1 chcę dodawać nowe posiłki do oferty, aby zwiększyć liczbę posiłków dostępnych dla klientów [*Adam Smerdzyński*]   
2.1.2 chcę usuwać wybrane posiłki z oferty, aby klienci nie widzieli posiłków, których nie ma dostępnych do zakupu [*Adam Smerdzyński*]   
2.1.3 chcę edytować informacje o wybranych posiłkach z oferty, aby w przypadku pomyłki mieć możliwość szybkiej poprawy [*Adam Smerdzyński*]   
2.1.4 chcę dodawać nowe pakiety posiłków do oferty, aby zwiększyć liczbę pakietów posiłków dostępnych dla klientów [*Adam Smerdzyński*]   
2.1.5 chcę usuwać wybrane pakiety posiłków z oferty, aby klienci nie widzieli pakietów posiłków, których nie ma dostępnych do zakupu [*Adam Smerdzyński*]   
2.1.6 chcę edytować informacje o wybranych pakietach posiłków z oferty, aby w przypadku pomyłki mieć możliwość szybkiej poprawy [*Adam Smerdzyński*]   
2.1.7 chcę dodawać do każdego posiłku dodatkowe informacje takie jak zdjęcie, opis czy ilość kalorii, aby zwiększyć swiadomość klientów odnośnie posiłku, który zamawiają [*Adam Smerdzyński*]   
2.1.8 chcę przeglądać aktywne zamówienia klientów, aby wiedzieć ile osób czeka jeszcze na swoje zamówienia [*Adam Smerdzyński*] 
##### 2.2. Promowanie, oceny
2.2.1 chcę mieć możliwość promowania swoich ofert, aby zwiększyć ilość klientów, do których dociera oferta [*Adam Smerdzyński*]   
2.2.2 chcę móc przeglądać opinie klientów, aby poprawiać jakość swoich usług [*Adam Smerdzyński*]   
2.2.3 chcę móc zgłaszać opinie klientów, które uważam za nieprawdziwe, aby przeciwdziałać nieuczciwej konkurencji [*Adam Smerdzyński*]  
##### 2.3. Statystyki 
2.3.1 chcę przeglądać statystyki: liczby aktywnych klientów, przychodów itp., aby mieć świadomość aktualnej sytuacji i wyciągać wnioski ze statystyk [*Adam Smerdzyński*]  
#### 3. Jako zarządzający:
##### 3.1. Dostawcy
3.1.1 chcę dodawać nowych dostawców, aby zwiększyć liczbę dostępnych ofert dla klientów [*Adam Smerdzyński*]   
3.1.2 chcę usuwać wybranych dostawców, aby klienci nie widzieli ofert dostawców, z którymi już nie współpracuję [*Adam Smerdzyński*]    
##### 3.2. Opinie
3.2.1 chcę mieć możliwość rozpatrzenia zgłoszenia opinii, aby zweryfikować czy opinia klienta jest zgodna z prawdą [*Adam Smerdzyński*]  
##### 3.3. Promowanie/powiadomienia
3.3.1 chcę udostępniać możliwość zakupu promowania ofert dostawców, aby zwiększyć zyski [*Adam Smerdzyński*]   
3.3.2 chcę aby klienci otrzymywali powiadomienia mailowe oraz powiadomienia push w aplikacji mobilnej z rekomendacjami lub zachęcające do wystawienia opinii, aby zachęcić klientów do ponownych zakupów w aplikacji
[*Adam Smerdzyński*]
3.3.3 chcę mieć możliwość zablokowania wystawiania opinii użytkownikowi, aby uniemożliwić mu szerzenie nienawiści i ograniczać niepoprawne zachowania [*Sebastian Sekula*]

### Wymagania jakościowe i ograniczenia

#### Optymalizacja dla platform mobilnych
[*Mateusz Tkaczyk*]
- **Rodzaj**: Użyteczność
- **Opis**: Aplikacja mobilna musi być zoptymalizowana pod kątem szybkości i wygody użytkowania na urządzeniach mobilnych.
- **Sposób pomiaru**: Testy użyteczności przeprowadzone na różnych urządzeniach mobilnych.
- **Możliwy wynik pomiaru**: Czas wykonania typowych operacji w aplikacji.
- **Oczekiwane wartości**: Średni czas wykonania operacji poniżej 3 sekund.

#### Elastyczność regionu funkcjonowania
[*Mateusz Tkaczyk*]
- **Rodzaj**: Skalowalność
- **Opis**: System musi być dostosowany do obsługi dużej liczby użytkowników w Polsce.
- **Sposób pomiaru**: Testy obciążeniowe systemu.
- **Możliwy wynik pomiaru**: Liczba jednocześnie obsługiwanych użytkowników.
- **Oczekiwane wartości**: System obsługuje co najmniej podwojenie obecnej liczby użytkowników.

#### Niezawodność systemu
[*Mateusz Tkaczyk*]
- **Rodzaj**: Niezawodność
- **Opis**: System może mieć przerwy w działaniu tylko w nocy, minimalizując wpływ na użytkowników.
- **Sposób pomiaru**: Monitoring czasu działania systemu.
- **Możliwy wynik pomiaru**: Procent czasu, kiedy system jest dostępny.
- **Oczekiwane wartości**: Dostępność systemu na poziomie 99,8%.

#### Proces rejestracji użytkownika
[*Mateusz Tkaczyk*]
- **Rodzaj**: Użyteczność
- **Opis**: Proces rejestracji musi być prosty i intuicyjny, z możliwością logowania przez Microsoft, Google i Apple.
- **Sposób pomiaru**: Czas potrzebny na zarejestrowanie nowego użytkownika.
- **Możliwy wynik pomiaru**: Od 1 do 5 minut.
- **Oczekiwane wartości**: Średni czas rejestracji poniżej 2 minut.

#### Weryfikacja negatywnych opinii
[*Mateusz Tkaczyk*]
- **Rodzaj**: Funkcjonalność
- **Opis**: Musi istnieć system weryfikacji negatywnych opinii przez pracowników.
- **Sposób pomiaru**: Liczba weryfikacji negatywnych opinii w stosunku do ich ogólnej liczby.
- **Możliwy wynik pomiaru**: Procent zweryfikowanych opinii.
- **Oczekiwane wartości**: 100% negatywnych opinii zweryfikowanych.

#### Filtrowanie ofert
[*Mateusz Tkaczyk*]
- **Rodzaj**: Funkcjonalność
- **Opis**: System musi umożliwiać filtrowanie ofert na podstawie wielu kryteriów, w tym adresu, daty, kalorii, popularności, opinii, ceny i rodzaju kuchni.
- **Sposób pomiaru**: Liczba dostępnych filtrów i ich skuteczność.
- **Możliwy wynik pomiaru**: Procent użytkowników korzystających z filtrów.
- **Oczekiwane wartości**: Co najmniej 80% użytkowników korzysta z funkcji filtrowania.

#### Powiadomienia o zachęcie do oceny
[*Mateusz Tkaczyk*]
- **Rodzaj**: Użyteczność
- **Opis**: System powinien wysyłać powiadomienia zachęcające użytkowników do wystawienia opinii dzień po dostarczeniu zamówienia.
- **Sposób pomiaru**: Liczba wysłanych powiadomień i procent użytkowników, którzy wystawili opinię.
- **Możliwy wynik pomiaru**: Procent użytkowników, którzy wystawili opinię po otrzymaniu powiadomienia.
- **Oczekiwane wartości**: Co najmniej 50% użytkowników wystawia opinię po otrzymaniu powiadomienia.

#### Efektywność systemu nagród
[*Mateusz Tkaczyk*]
- **Rodzaj**: Użyteczność
- **Opis**: System nagród powinien być intuicyjny i motywować użytkowników do częstszego korzystania z usług.
- **Sposób pomiaru**: Liczba użytkowników korzystających z systemu nagród.
- **Możliwy wynik pomiaru**: Liczba użytkowników korzystających z systemu nagród w stosunku do ogólnej liczby użytkowników.
- **Oczekiwane wartości**: Co najmniej 50% aktywnych użytkowników korzysta z systemu nagród.

#### Integracja z zewnętrznymi systemami opinii
[*Mateusz Tkaczyk*]
- **Rodzaj**: Integracja
- **Opis**: System musi integrować oceny z zewnętrznych platform, takich jak Google, itp.
- **Sposób pomiaru**: Liczba zintegrowanych platform i dokładność wyświetlanych ocen.
- **Możliwy wynik pomiaru**: Procent poprawnie zintegrowanych ocen.
- **Oczekiwane wartości**: 100% poprawności.

### Ograniczenia
- **Platformy mobilne**: System musi być dostępny jako aplikacja mobilna, co oznacza, że musi być kompatybilny z różnymi systemami operacyjnymi mobilnymi.
[*Mateusz Tkaczyk*]  
- **Protokół Oauth Microsoft, Apple**: System musi obsługiwać protokół Oauth dla logowania przez Microsoft, Google i Apple.
[*Mateusz Tkaczyk*]  
- **Powiadomienia push**: System musi obsługiwać powiadomienia push, co oznacza, że musi być w stanie wysyłać powiadomienia do urządzeń użytkowników.
[*Mateusz Tkaczyk*]  
- **Region funkcjonowania - Polska**: System musi być dostosowany do obsługi klientów w Polsce, co może obejmować obsługę języka polskiego, waluty PLN itp.
[*Mateusz Tkaczyk*]  
- **Odpytywanie API systemu cateringowego**: System musi być w stanie komunikować się z API dostawców usług cateringowych w celu uzyskania informacji o dostępności i szczegółach ofert.
[*Mateusz Tkaczyk*]  
- **Niezawodność - przerwy działania mogą się odbywać w nocy**: System musi być niezawodny i dostępny przez większość czasu, ale może być niedostępny w nocy na konserwację.
[*Mateusz Tkaczyk*]  
- **Wyprzedzenie zamówień - zależy od dostawcy**: System musi umożliwiać dostawcom ustalanie okresu wyprzedzenia dla zamówień.
[*Mateusz Tkaczyk*]  

### Słownik dziedziny
1.	Dostawca \[usług\] – firma lub przedsiębiorstwo oferujące usługi cateringowe.  
[*Ulyana Petrashevich*]
2.	Posiłek – produkt spożywczy, dostarczany przez dostawcę, charakteryzujący się zdjęciem, opisem, typem posiłku, kuchnią, dietą i ceną.  
[*Ulyana Petrashevich*] 
3.	Opis posiłku – słowny opis zawierający informacje o posiłku.
[*Ulyana Petrashevich*]
4.	Typ posiłku – kategoria, nadawana posiłku, z ustalonej listy: śniadanie, lunch, obiad, kolacja, deser.
[*Ulyana Petrashevich*]
5.	Kuchnia – styl kulinarny przygotowania posiłku.
[*Ulyana Petrashevich*]
6.	Dieta – specjalne wymagania żywieniowe.
[*Ulyana Petrashevich*]
7.	Cena \[posiłku\] – kwota pieniężna wymagana za dany posiłek, określona przez dostawcę.
[*Ulyana Petrashevich*]
8.	Subskrypcja - zestaw posiłków, kompletowany i dostarczany przez dostawcę do klienta, przez ustalony okres czasu.
[*Ulyana Petrashevich*]
9.	Zamówienie – zestaw informacji dotyczący okazania żądanej usługi.
[*Ulyana Petrashevich*]
10.	Rozliczenie – zestaw informacji dotyczący finansowego zobowiązania lub rozliczenia między stronami klient – dostawca usług.
[*Ulyana Petrashevich*]
11.	Konto – indywidualne konto użytkownika w systemie, umożliwiające zarządzanie zamówieniami.
[*Ulyana Petrashevich*]
12.	Użytkownik – osoba, korzystająca z aplikacji lub systemu w celu uzyskania określonych informacji lub realizacji określonych zadań.
[*Ulyana Petrashevich*]
13.	Klient - użytkownik, posiadający konto w systemie, posiadający możliwość składania zamówienia.
[*Ulyana Petrashevich*]
14.	Aktywny klient - klient, składający zamówienia w systemie.
[*Ulyana Petrashevich*]
15. Klient stały - klient, korzystający z usług tego samego dostawcy.
[*Ulyana Petrashevich*]
16. Klient polecający - klient, zapraszający ludzi do skorzystania z systemu.
[*Ulyana Petrashevich*]
17. Przychód – łączna wartość sprzedaży usług w danym okresie rozliczeniowym.
[*Ulyana Petrashevich*]
18. Pakiet \[posiłków\] – zestawienie posiłków dostępnych do zamówienia w ramach określonego pakietu.
[*Ulyana Petrashevich*]
19. Program promowania – oferta promocyjna umożliwiająca dostawcom wyróżnienie swoich usług.
[*Ulyana Petrashevich*]
20. Ocena – stopień satysfakcji użytkowników z usług lub posiłków, wyliczany na podstawie zostawionych przez klientów opinii.
[*Ulyana Petrashevich*]
21. Opinia – wypowiedź użytkownika na temat satysfakcji z jakości realizowania usługi lub posiłku, w postaci oceny w skali 1-5 i tekstu opisowego.
[*Ulyana Petrashevich*]
22. Zła/negatywna opinia – opinia z oceną w zakresie 1-3.
[*Ulyana Petrashevich*]
23. Dobra/pozytywna opinia – opinia z oceną w zakresie 4-5.
[*Ulyana Petrashevich*]
24. Popularność \[usługi\] - liczba zamówień danej usługi w danym okresie czasu.
[*Ulyana Petrashevich*]
25. Pieczątka – nagroda przyznawana stałym klientom za każde zamówienie.
[*Ulyana Petrashevich*]
26. Rabat – obniżka ceny zamówienia dla klientów w ramach promocji.
[*Ulyana Petrashevich*]
27. Kod rabatowy – kod umożliwiający uzyskanie rabatu podczas składania zamówienia.
[*Ulyana Petrashevich*]
28. Przerwa działania – okres czasu, w którym system nie jest dostępny dla użytkowników.
[*Ulyana Petrashevich*]
29. Platforma mobilna - Aplikacja lub strona internetowa dostępna na urządzeniach mobilnych, umożliwiająca użytkownikom korzystanie z usług cateringowych.
[*Bernard Cesarz*]  
30. Integracja z zewnętrznymi systemami opinii - Proces połączenia systemu z zewnętrznymi platformami do gromadzenia i wyświetlania opinii użytkowników.
[*Bernard Cesarz*]  
31. Lista dostaw - Zestawienie dostępnych dostawców usług cateringowych, które mogą być wybrane przez użytkowników.
[*Bernard Cesarz*]  
32. Powiadomienia push - Wiadomości wysyłane do urządzeń użytkowników bez ich bezpośredniego zapytania, często w celu informowania o nowych ofertach, promocjach lub statusie zamówienia.
[*Bernard Cesarz*]  
33. Zgłaszanie opinii - Proces, w którym użytkownicy mogą zgłaszać swoje opinie na temat posiłków, które próbowali, w celu pomocy innym użytkownikom w podejmowaniu decyzji.
[*Bernard Cesarz*]  
34. Odpytywanie API systemu cateringowego - Proces wysyłania zapytań do zewnętrznego systemu (API) w celu pobrania aktualnych informacji, takich jak dostępność posiłków, ceny, itp.
[*Bernard Cesarz*]  
35. Niezawodność systemu - Właściwość systemu, która zapewnia jego ciągłe działanie bez przerwy, zwłaszcza w okresie, kiedy regularnie będzie występować większe obciążenie.
[*Bernard Cesarz*]  
36. Prometeusz - Narzędzie do zbierania i analizy statystyk dotyczących działania systemu, takich jak liczba zamówień w danym czasie.
[*Bernard Cesarz*]  
37. Subskrypcja - Usługa, w ramach której użytkownik otrzymuje regularne dostawy posiłków od wybranego dostawcy.
[*Bernard Cesarz*]  
38. Wycena ofert - Proces oceny ofert posiłków, uwzględniający prowizje za promocje oraz stałe prowizje.
[*Bernard Cesarz*]  
39. Zamówienie - Proces składania żądania na dostarczenie posiłków, w którym użytkownik podaje adres dostawy, datę dostawy, wybiera ofertę i przechodzi do koszyka zakupowego.
[*Bernard Cesarz*]  
40. Koszyk zakupowy - Sekcja w aplikacji lub stronie internetowej, w której użytkownik gromadzi wybrane posiłki do zamówienia.
[*Bernard Cesarz*]  
41. Zarządzanie kontem - Proces zarządzania użytkownikiem w systemie, w tym aktualizacji danych, zarządzania zamówieniami i preferencjami.
[*Bernard Cesarz*]  
42. Statystyki - Dane dotyczące działania systemu, takie jak liczba zarejestrowanych użytkowników, liczba zamówień, popularność posiłków, itp.
[*Bernard Cesarz*]  
43. Zarządzanie kodami rabatowymi - Proces tworzenia, aktualizacji i wygaśnięcia kodów rabatowych, które mogą być używane przez użytkowników podczas składania zamówień.
[*Bernard Cesarz*]  
44. Raportowanie opini przez zwykłych użytkowników - Proces, w którym użytkownicy mogą zgłaszać swoje opinie na temat posiłków, które próbowali, w celu pomocy innym użytkownikom w podejmowaniu decyzji.
[*Bernard Cesarz*]  
45. Filtrowanie - Funkcja pozwalająca użytkownikom na wyszukanie posiłków na podstawie różnych kryteriów, takich jak adres, data, dostawcy, kalorie, popularność, opinie, dieta, cena, typy posiłków, rodzaj kuchni, itp.
[*Bernard Cesarz*]  
46. Cenzura nieprzyzwoitych treści w opiniach - Proces moderacji opinii, w którym złe/negatywne opinie są filtrowane lub usuwane, aby zapewnić pozytywne doświadczenia dla użytkowników.
[*Bernard Cesarz*]  
47. Zgłaszanie zamówień - Proces składania zamówienia przez użytkowników, którzy są zarejestrowani w systemie.
[*Bernard Cesarz*]  
48. Rejestracja - Proces tworzenia konta użytkownika w systemie, umożliwiający korzystanie z usług.
[*Bernard Cesarz*]  
49. Dane do faktury - Informacje potrzebne do wystawienia faktury dla firm, takie jak nazwa firmy, adres, dane kontaktowe, itp.
[*Bernard Cesarz*]  
50. Zapamiętywanie preferencji - Funkcja, która pozwala systemowi zapamiętywać preferencje użytkownika, takie jak ulubione posiłki, dostawcy, itp., aby ułatwić składanie przyszłych zamówień.
[*Bernard Cesarz*]  
51. Historia zamówień - Zestawienie wszystkich zamówień, które użytkownik złożył, z możliwością dodawania nowych zamówień na ich podstawie.
[*Bernard Cesarz*]  
52. Zachęcanie użytkowników do zostawiania ocen - Strategia marketingowa, mająca na celu zwiększenie liczby opinii na temat posiłków, poprzez różne formy zachęcania, takie jak nagrody, promocje, itp.
[*Bernard Cesarz*]  
53. Powiadomienia dzień po dostarczeniu zamówienia - Funkcja wysyłania powiadomień do użytkowników po dostarczeniu ich zamówienia, w celu zebrania opinii lub potencjalnego złożenia kolejnego zamówienia.
[*Bernard Cesarz*]  
54. Region funkcjonowania - Geograficzny obszar, w którym system jest dostępny i funkcjonuje, w tym przypadku Polska.
[*Bernard Cesarz*]  
55. Elastyczność systemu - Właściwość systemu, która pozwala na łatwe skalowanie liczby użytkowników i dostosowywanie do zmieniających się potrzeb.
[*Bernard Cesarz*]  
