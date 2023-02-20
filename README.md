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


## Subtask 4
 [Jira](https://challangedareit.atlassian.net/jira/software/projects/CHAL/boards/1)
 
![image](https://user-images.githubusercontent.com/122390450/217335479-56619465-fc47-444a-8139-ef7444d77b91.png)
![image](https://user-images.githubusercontent.com/122390450/217335357-cf03fe48-d0e7-474c-a10b-1c0c07c86ab5.png)


# Task 5
## Subtask 1
SELECT, FROM, WHERE, ORDER BY, ORDER BY DESC, BETWEEN, IN, OR, IS NULL, LIKE

## Subtask 3
#### 1.Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
![image](https://user-images.githubusercontent.com/122390450/218279093-f51d9810-99b6-4f87-b462-309ed244157e.png)

![image](https://user-images.githubusercontent.com/122390450/218279134-420e655c-5b28-4601-998a-4aea8b04a342.png)

#### 2.Wyświetl film, który powstał w 2019 roku.
![image](https://user-images.githubusercontent.com/122390450/218279257-fe7efcd5-5594-4d28-8a02-f87f68285380.png)

![image](https://user-images.githubusercontent.com/122390450/218279277-be5ddcb2-47c8-4a97-9943-2dbe1a9e0632.png)

#### 3.Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
![image](https://user-images.githubusercontent.com/122390450/218279391-c5f766f5-41f5-49a9-ab6a-f51e5cbae0e3.png)

![image](https://user-images.githubusercontent.com/122390450/218279364-3c812882-1d9e-4cc0-b49d-b69149949e0e.png)

#### 4.Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$
![image](https://user-images.githubusercontent.com/122390450/218279620-8ccce8f5-c493-460d-993b-1a3a926f30f6.png)

![image](https://user-images.githubusercontent.com/122390450/218279628-74647dc9-99ff-498f-97a1-757757489e99.png)

#### 5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
![image](https://user-images.githubusercontent.com/122390450/218280177-819bd9f7-d9a4-4a36-8e72-8990c0e686c0.png)

![image](https://user-images.githubusercontent.com/122390450/218280187-2e251a56-07b8-402e-b9c9-cfd763405b92.png)

#### 6.Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.
![image](https://user-images.githubusercontent.com/122390450/218280329-3cad991c-e749-4b62-b72a-f7e90ac87ff7.png)

![image](https://user-images.githubusercontent.com/122390450/218280340-d3e2666c-0c12-45a5-859b-cab118860a14.png)

#### 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN
![image](https://user-images.githubusercontent.com/122390450/218280477-383ac88f-9314-4a31-886e-42c4cb8c6710.png)

![image](https://user-images.githubusercontent.com/122390450/218280485-358bf7a1-1300-4126-ab2c-9a43db32273c.png)

#### 8.Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
![image](https://user-images.githubusercontent.com/122390450/218280589-82d7b18e-2b61-4b01-8b27-7465baec775a.png)

![image](https://user-images.githubusercontent.com/122390450/218280599-a086a0d3-8941-4b7f-80d7-c52da593d2ff.png)

#### 9.Wyświetl dane klienta, który nie ma podanego adresu email.
![image](https://user-images.githubusercontent.com/122390450/218280674-f52cde2f-0c97-4302-b574-fd34c158212d.png)

![image](https://user-images.githubusercontent.com/122390450/218280681-4d685e47-8403-4694-b8c8-891546d76920.png)

#### 10.Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
![image](https://user-images.githubusercontent.com/122390450/218280763-84e3986d-f82c-4716-ab25-40a7fe9cd16b.png)

![image](https://user-images.githubusercontent.com/122390450/218280784-df359576-9bea-4e7e-beda-5a62e2cc4b17.png)


# Task 6
## Subtask 1

#### 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 

![image](https://user-images.githubusercontent.com/122390450/220185655-4662ab98-e3b2-4557-ad7b-52ad0786e561.png)

![image](https://user-images.githubusercontent.com/122390450/220185593-9ce9eecb-8eae-405c-a329-87b1c1246387.png)

#### 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

![image](https://user-images.githubusercontent.com/122390450/220186630-75348dc1-fb72-4cc9-b435-5f703dbad40d.png)

![image](https://user-images.githubusercontent.com/122390450/220186669-41c69d30-78d4-4a4f-a714-bf9b5cd85698.png)


#### 13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com

![image](https://user-images.githubusercontent.com/122390450/220188583-b3994607-f519-4dc7-97e4-63c9d1ee0173.png)

![image](https://user-images.githubusercontent.com/122390450/220188548-2679c924-5b1f-431e-baaa-b6dd3bb3b8ec.png)

#### 14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

![image](https://user-images.githubusercontent.com/122390450/220190074-6ca3abe1-86fe-4f10-b251-c32bbaeac72f.png)

![image](https://user-images.githubusercontent.com/122390450/220190136-5d747876-bfd2-4ba2-864e-f496c805552b.png)

#### 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

![image](https://user-images.githubusercontent.com/122390450/220190628-6c775ad6-c8c3-45f4-ac39-30d73037a557.png)

![image](https://user-images.githubusercontent.com/122390450/220190588-731fe04c-12d3-4e18-bda4-f2e82fd18ee0.png)

#### 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

![image](https://user-images.githubusercontent.com/122390450/220190987-a89e066b-9b28-4c68-9c99-287400db6cf9.png)

![image](https://user-images.githubusercontent.com/122390450/220190961-357ad822-a3e2-4ced-80e2-796afc4261f9.png)

#### 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

![image](https://user-images.githubusercontent.com/122390450/220191164-9c807fab-d2a5-4bf8-9863-f96466ea98ae.png)

![image](https://user-images.githubusercontent.com/122390450/220191135-db52b39c-9ac2-4e1e-9775-26b3fc93949b.png)

#### 18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

![image](https://user-images.githubusercontent.com/122390450/220191508-211c5f8e-211a-4c7b-8e51-638354e6ac38.png)

![image](https://user-images.githubusercontent.com/122390450/220191260-6c56816a-5aaf-4c1b-b2f6-ab76805080f4.png)

![image](https://user-images.githubusercontent.com/122390450/220191469-b3105893-3894-4dc3-9335-387cd0707618.png)

#### 19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

![image](https://user-images.githubusercontent.com/122390450/220191880-743e6a44-8ede-46e1-9134-78c79a5a9c91.png)

![image](https://user-images.githubusercontent.com/122390450/220191849-417b7e77-c308-4891-9e52-a56e2df1d2bd.png)

#### 20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

![image](https://user-images.githubusercontent.com/122390450/220192060-243a5e22-144c-4096-a21b-7ad1fe28c06c.png)

![image](https://user-images.githubusercontent.com/122390450/220192016-91e7baec-be3e-4868-8b0a-8e8e4498c0da.png)

## Subtask 2

![image](https://user-images.githubusercontent.com/122390450/220202096-6fc3361a-d0cf-4c35-93fe-e3b1a1881a63.png)

## Subtask 3



