# AplikacjaBazodanowa2019

# System ułatwiający współdziałanie dwóch różnych silników bazodanowych – PostgreSQL oraz ClickHouse.


### Spis treści:
  1.	Cel i funkcje systemu; 
  2.	Dane gromadzone przez system;
  3.	Autorzy aplikacji;
  4.	Terminarz;
  5.	Podział prac między członków zespołu;
  6.	Schematy UML.
  

### 1. Cel i funkcje systemu:
System ma spełniać podstawowe założenia jako menadżer plików dla  dwóch różnych środowisk bazodanowych – PostgreSQL oraz ClickHouse. 
- Aplikacja ta, będzie umożliwiać użytkownikowi m.in. CRUD (tworzenie / dodawanie, odczytywanie / wyświetlanie, aktualizowanie, usuwanie) oraz kopiowanie danych z jednej bazy do drugiej. 
- Użytkownik będzie mógł poznać czas wykonywania poszczególnych operacji.


### 2.	Dane gromadzone przez system:
Obie bazy będą posiadać takie same dane i struktury, ponieważ aplikacja ma za główne zadanie sprawne kopiowanie plików ze środowiska PostgreSQL do ClickHouse i odwrotnie. 
System bedzie zapisywał czasy poszczególnych operacji, w celu porównawczym.


### 3.	Autorzy aplikacji:
  •	Jednacz Bartosz
  •	Nędza Patrycja
  •	Sobkowicz Mateusz
  •	Wojdyła Marek
  
  
### 4.	Termiarz pracy:
  •	Opracowanie założeń i wymagań: *28.10.2019*
  •	Opracowanie wstępnej dokumentacji: *04.11.2019*
  •	Implementacja: *18.11.2019*
  •	Testy: *25.11.2019*
  •	Przygotowanie całkowitej dokumentacji: *02.12.2019*
  •	Prezentacja projektu, rozliczenie, zaliczenie: *16.12.2019*
  
  
### 5. Podział prac między członków zespołu:
  •	Jednacz Bartosz:
    - programowanie back-endu aplikacji w języku PHP.

  •	Nędza Patrycja:
    - baza danych: PostgreSQL
    - zapytania dotyczące wybranej wyżej bazy
    - dokumentacja aplikacji

  •	Sobkowicz Mateusz:
    - baza danych: ClickHouse
    - zapytania dotyczące wybranej wyżej bazy
    - testy

  •	Wojdyła Marek:
    - programowanie front-endu aplikacji w języku PHP.


### 6. Schematy UML:
  •	Diagram użycia: 
  
  ![Błąd]( "Opcjonalny tytul")
  
  
  •	Diagram aktywności:
  
  ![Błąd]( "Opcjonalny tytul")
  
  
  •	Diagram sekwencji:
  
  ![Błąd]( "Opcjonalny tytul")
  
  
  
  
  
  
  
