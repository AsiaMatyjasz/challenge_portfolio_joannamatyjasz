 challenge_portfolio_joannamatyjasz 
# Task 1
## Subtask 1
9/10 :sunglasses: 
## Subtask 3
Hejka! Nazywam się Asia i wzięłam udział w projekcie aby sprawdzić na czym polega praca testera w praktyce. Skończyłam właśnie kurs na testera manualnego z dobrekursy.it. Posiadam 8 letnie doświadczenie w dziale zapewnienia jakości w branży spożywczej. Od wyzwania oczekuję, że dowiem się czy ta praca sprawia mi satysfakcję oraz czy mogłabym to robić w celach zarobkowych :wink:
## Subtask 4
* Aplikacja służy do przeglądania dokonań zawodników/ graczy. Można przeglądać ich dane personalne, w jakich meczach grali, jakie zdobyli punkty, sprawdzać raporty. 
* Funkcje w aplikacji:
  *  pierwszym krokiem jest logowanie do serwisu poprzez podanie loginu oraz hasła, można wybrać "przypomnij hasło";
  * można dodać nowego zawodnika, profil uzupełnić o różne informacje tj. podstawowe: imię, nazwisko, telefon, e-mail, waga, wzrost, data urodzenia, dominująca noga, klub, poziom rozgrywek, główna pozycja, pozycja alternatywna, województwo i osiąginięcia. Można dodać też profil fb oraz link do youtuba;
  * w zakładce zawodnicy jest możliwość ściągnięcia listy w formacie csv, wydrukowania listy, wyboru kolumn do wyświetlania oraz filtrowania;
  * w zakładce zawodnicy jest możliwość wyszukania zawodnika poprzez wyszukiwarkę "search";
  * po wybraniu zawodnika jest opcja dodania meczu w którym zawodnik brał udział, edytowania poprzednich, wygenerowania raportu lub rozpoczęcia meczu;
  * stronę można przeglądać w języku polskim oraz angielskim.
  
 Strona nie jest intuicyjna np. dodając gracza nie do końca wiadomo jakie dane wpisać np. w polu "łączy nas piłka" lub "90 minut". W zakładce mecze, po kliknięciu rozpocznij mecz, nie wiadomo co się dzieje, wyświetla się boisko, żaden przycisk nie jest opisany co ozacza i co należy tam zrobić.
 * Interfejs aplikacji mógłby być bardziej czytelny. Strona główna jest niewykorzystana, jest dużo pustego pola, logo oraz informacja do czego służy strona nie jest umieszczona w odpowienim miejscu i nie przyciąga uwagi użytkowników. Wszystkie tabele są nieczytelne a ich szerokość nieokreślona, dlatego często się rozciągają w nieskończoność np. wyszukując zawodnika "aaa"- znajdujemy zawodnika o bardzo długim imieniu, więc tabela jest mocno rozciągnięta- bardzo nieczytelna.
 * Cała aplikacja jest nie intuicyjna.
 * Błędy:
   * podczas operacji przypomnij hasło, po wpisaniu adresu mailowego, którego nie ma w bazie aplikacji- strona wysyła komunikat "wysyłano wiadomość na podany adres e-mail"- kod błędu 400;
   * podczas edycji pozycji zawodnik lub mecz nie działa przycisk "clear";
   * nie ma ograniczeń ilości wpisywanych znaków w poszczególnych rubrykach- problem ze zbyt długimi imionami, nazwiskami oraz nazwami klubów- źle się wyswietlają później tabele;
   * można wpisać ujemne wartości: waga, wzrost, wiek;
   * w rubryce telefon można wpisać litery zamiast cyfr;
   * w wersji polskiej dalej pozostały przyciski po angielsku " submit" oraz "clear";
   * aby utworzyć raport z meczu, w którym wybrany gracz grał, musi mieć w swoim profilu uzupełnione województwo- chociaż nie jest to dana wymagana oraz nie było o tym wcześniej informacji.
   
## Subtask 5 
Jira jest, zespół jest, co dalej? :information_desk_person:

# Task 2
## Subtask 1
[subtask 1](https://docs.google.com/spreadsheets/d/1jssZ19mPhnLEkQjJ5264AYv4nxqdRPZ5/edit?usp=share_link&ouid=117261196751924266035&rtpof=true&sd=true)
## Subtask 2
[subtask 2](https://docs.google.com/spreadsheets/d/1cI-SRuJM7iyTg2ph4tk40krZENQ8k5gO/edit?usp=share_link&ouid=117261196751924266035&rtpof=true&sd=true)
## Subtask 3
Aby opisać dokładnie jak dana aplikacja ma działać i aby łatwo móc przeprowadzać testy regresji.
## Subtask 4
Będzie jutro bo brakło czasu :see_no_evil:

# Task 3
# Task 4
## Subtask 2
[subtask 1 i 2](https://docs.google.com/spreadsheets/d/1FDgeId1QS5ENXrZeQNMKK7LMUMQ4Rtbc/edit?usp=share_link&ouid=117261196751924266035&rtpof=true&sd=true)
## Subtask 3
#### 1.	Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?

Aplikacja jest serwisem ogłoszeniowym, można sprzedawać oraz kupować. Funkcje:
* przeglądanie ogłoszeń,
*	dodawanie ogłoszeń,
*	wyróżnienie ogłoszeń,
*	wymiana wiadomości,
*	wysyłanie CV za pośrednictwem formularza w kat. praca,
*	obserwowanie wybranych ogłoszeń lub wyników wyszukiwania.
*	system bezpiecznych płatności olx

Można przeglądać w wersji desktopowej w przeglądarce, bezpośrednio przez aplikację pobraną ze sklepu na urządzeniu mobilnym lub przez przeglądarkę internetową na urządzeniu mobilnym.

#### 2.	Kto ma być użytkownikiem końcowym aplikacji?
Wszyscy użytkownicy, którzy chcą coś sprzedać/ kupić bądź tylko przeglądać ogłoszenia

#### 3.	Czy według Ciebie aplikacja jest user friendly?
Tak, uważam, że aplikacja jest user friendly. Ma prosty interfejs, jest intuicyjna, wiadomo w co kliknąć aby coś zrobić. Przyciski nawigujące znajdują się na dole aplikacji, wyszukiwarka na górze.

#### 4.	Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? 

Zmiana wyświetlania języka na angielski i ukraiński( ze względu na kategorię dla ukrainy)

#### 5.	Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?
Aplikacja natywna:
*	dostęp do sprzętu urządzenia (geolokalizacja, kamera, mikrofon,  kalendarz, powiadomienia push) 
*	tworzona bezpośrednio pod oprogramowanie android. IOS
*	do interakcji z użytkownikiem, posiada złożone mechanizmy i funkcje, zazwyczaj wymaga uwierzytelnienia personalnego.

Aplikacja internetowa:
*	skupia się na przekazie informacji dla osoby odwiedzającej, proste funkcjonalności, zazwyczaj nie wymaga uwierzytelniania personalnego
*	jedna wersja, która może być obsługiwana przez wszystkie systemy


### Subtask 4
 [Jira](https://challangedareit.atlassian.net/jira/software/projects/CHAL/boards/1)
