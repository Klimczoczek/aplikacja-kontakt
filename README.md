# Aplikacja kontakty - dokumentacja


W tytule aplikacji w nawiasie jest podana liczba kontaktów

###Menu###

Menu składa się z 3 zakładek:
- Kontakty
- Sortowanie
- Opcje

Po kliknięciu zakładki "Kontakty" pokazują nam się podzakładki:
- Wyczyść => ten przycisk czyści całą liste kontaktów razem z zapisanymi. Przed usunięciem użytkownik musi potwierdzić tą akcje
- Zapisz => zapisuje wszystkie kontakty w pliku "baza.json". Message Box potwierdza zakończenie zapisu do pliku
- Koniec => przycisk ten wyłącza aplikacje

Po kliknięciu zakładki "Sortowanie" pokazuje nam się wybór sortowania istniejących kontaktów po Imieniu i Nazwisku

Po kliknięciu zakładki "Opcje" pokazują nam się podzakładki:
- Pomoc => Pokazuje w przeglądarce ten właśnie dokument :D
- O Autorze => Pokazuje autora tej pracy

###Szukanie###

Aby wyszukać w bazie kontaktów należy napisać daną frazę w polu tekstowym pod menu z napisem "Szukaj". Szukanie działa na zasadzie znajdowania jednej z wartości "imię", "nazwisko" lub "numer telefonu". Aplikacja po wpisaniu litery lub ciągu znaków szuka ich również w środku zdania.

###Dodawanie###

Aby dodać kontakt do bazy należy kliknąć w "+" w prawym górnym rogu. Pojawia się wtedy okno pozwalające napisać Imię, Nazwisko, Numer Telefonu i Datę Urodzenia w polach tekstowych. Po kliknięciu kontakt zostanie dodany do listy. Po wpisaniu istniejącego już numeru telefonu pokaże się komunikat mówiący o tym, że taki kontakt już istnieje.

###Lista Kontaktów###

Lista kontaktów pokazuje tylko imię i nazwisko danej osoby. Aby zobaczyć więcej informacji należy kliknąć w wybrany kontakt. Po kliknięciu pokazują nam się dodatkowe informacje takie jak numer telefon i datę urodzin oraz przyciski Edycja i Usuń. 

###Edytuj###

Po kliknięciu przycisku "Edytuj" pokazuje menu takie samo jak w przypadku dodawania jednak są tam już informacje danego kontaktu. Po wpisaniu wartości i kliknięciu przycisku edytuj kontakt zostanie edytowany.

###Usuń###

Po kliknięciu przycisku "Usuń" pokazuje nam się komunikat potwierdzenia czy użytkownik chce wykonać tą akcje, po potwierdzeniu kontakt zostaje usunięty.

###Ważne###
Użytkownik musi zawsze podawać poprawne dane.

