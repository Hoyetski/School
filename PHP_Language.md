
![logo](https://github.com/Hoyetski/School/blob/main/PHP_Alternative_logo_by_Levi_Morrison.png)

*Alternatywne Logo PHP*

# Struktura języka PHP

**PHP - Hypertext Preprocessor**, jest obiektowym językiem programowania wykonywanym po stronie serwera, przeznaczonym do tworzenia i generowania aplikacji internetowych.

**PHP** Jako język skryptowy stosuje prostą składnie, kod umieszcza się w plikach w domyślnym rozszerzeniu `.php` a następnie umieszcza się na serwerze posiadającym 
**interpreter PHP**, jeśli zwykłemu plikowi **HTML** nadamy rozszerznie **PHP** to zostanie on prawidłowo pomimo, że nie jest to skrypt **PHP** dzieje się tak dlatego, 
że **Parser PHP** podczas przetwarzania strony ma **2** tryby pracy: 
1. **HTML**, w którym bez przetwarzania jest wyświetlana cała treść.
2.  **PHP**, w którym treść jest traktowana jako skrypt to przetworzenia.

Język **PHP** umożliwia przetwarzanie danych z formularzy, dynamiczne generowanie zawartości stron internetowych, wysyłanie i odbieranie ***cookies*** a 
także wykonywanie operacji na bazie danych, pozwala również na dynamiczne tworzenie obrazów, dokumentów oraz animacji. 

Wyróżnia się **3** główne obszary, w których stosuje się **PHP**:
- Skrypty po stronie serwera.
- Skrypty wywołane z wiersza poleceń.
- Aplikacje po stronie klienta- czyli zaawansowane funkcje **PHP** umożliwiające tworzenie aplikacji desktopowych.

Skrypty **PHP** są plikami tekstowymi dlatego do ich tworzenia można wykorzystać dowolny edytor tekstu, umieszczając kod **PHP** w dokumencie **HTML** należy użyć znacznika `<?php` do otwarcia i `?>` do zamknięcia kodu **PHP**, `<>` to ***angle brackets***.

**Sekcje PHP** mogą być umieszczane w dowolnym miejscu dokumentu **HTML** a ich liczba jest nie ograniczona.

# Systemy baz danych

**Bazy danych** to uporządkowany zgodnie z ustalonymi założeniami, zbiór danych.

Wszelkie istotne dla systemu informacje są zapisane w postaci **cyfrowej** i stanowią dane.

**System zarządzania bazą danych**, to zbiór programów i narzędzi, może występować jako jedna aplikacja pozwalająca na tworzenie, przechowywanie i przetwarzanie **baz danych**, oraz zarządanie nimi. 

**System baz danych** składa się z zbioru danych *bazy danych* i obsługującego go systemu zarządzania **bazą danych**. 

Obecnie standardem jest tworzenie dynamicznych witryn i aplikacji internetowych, korzystających ze zbioru danych zlokalizowanych na serwerach, dlatego organizacja danych na potrzeby systemów informatycznych lokalnych i internetowych jest istotnym procesem.

W ujęciu fizycznym, wyróżniamy lokalne systemy **baz danych**, aplikacyjne lub desktopowe i sieciowe **systemy baz danych**, serwery **baz danych** stanowią najczęściej usługę w architekturze *klient - serwer*. 

**Baza danych** stoi po stronie *serwera*, udostępniającą użytkownikowi obsługę sieciowych **systemów baz danych** wraz z narzędziami niezbędnymi do udostępniania zasobów, aplikacji i komunikacji z **bazą danych**.

Do najpopularniejszych **systemów zarządzania bazą danych** w architekturze *klient - serwer* zaliczamy:
 - Microsoft SQL server.
 - MySQL.
 - Oracle.
 - PostgreSQL.

Istnieją również **systemy baz danych** pracujące jako lokalne aplikacje, nazywamy je lokalnymi lub desktopowymi **systemami baz danych**.

Systemy te umożliwiają tworzenie nowych samodzielnych aplikacji ***bazodanowych*** oraz współdzielenie danych w sieci lokalnej.

# Cechy systemów bazy danych

Każdy **system bazy danych** powinnien charakteryzować się następującymi cechami:
 - Określoną strukturą **systemu bazy danych**.
 - Trwałością **danych**, czyli możliwością przechowywanią **danych** w pamięci masowej przez długi okres.
 - Możliwością przeprowadzenia określonych operacji na **danych**, dotyczy to wprowadzenia zapytań oraz usuwania **danych**.
 - Niezależnością **danych**, czyli oddzielenie struktury przechowywania **danych** od systemów zarządzania **danymi** oraz platformy sprzętowej.
 - Bezpieczeństwem **danych**, czyli zapewnianie mechanizmów kontroli dostępu do **danych**.
 - Integralnością **danych** przez zapewnianie zgodności **danych** z rzeczywistością.
 - Spójnością **danych**, określaną poprzez poprawność **danych** oraz odporność na anomalie.

# Modele baz danych 
 
**Model bazy danych** można określić jako logiczny sposób organizacji **danych** złożony ze zbioru reguł, opisujących **dane**, wzajemne zależności między nimi, dozwolone operacje na **danych** oraz zasady dostępu do systemu **bazy danych**.

Wyróżniamy **6** modeli baz danych:
 1. Model jednorodny- czyli proste **bazy danych** oparte na jednej tabeli, może się charakteryzować nadmiarowością **danych** oraz trudnością wyszukiwania informacji.
 2. Model hierarchiczny, który jest oparty na struktuże odwróconego drzewa, charakterystyczna dla tego modelu jest zależność typu: *podrzędny-nadrzędny*

# Relacyjne bazy danych
W systemach opartych na bazach danych, najbardziej rozpowszechnił się model relacyjny bazy danych.

Podstawę relacyjnych baz danych stanowi teoria, która opublikował Edgar Frank (Ted Codd), według niej cały model relacyjny jest oparty na matematycznym pojęciu relacji.

Relają nazywamy dowolny podzbiór iloczynu kardeziańskiego, najczęściej relacje będą reprezentowane przez tabele, jeżeli tabela typową relacją to jej kolumny są atrybutami a wiersze krotkami.

Krotka to nie powtażalny zbiór wartości o określonych typach danych, umieszczonych w polach, opisujący pojedyńczy element tabeli bazy danych.

Wyłączony jest z tej definicji pierwszy wiersz tabeli, będący wierszem nagłówkowym, zawierającym nazwy kolumn (atrybutów).

Krotki nazywamy też rekordami tabeli bazy danych.

Atrybut to kolumna tabeli, mająca określoną nazwe, atrybuty określają zbiór cech elementu bazy danych póżniej opisywanych wartościami.

Zbiór wartości atrybutu nazywamy dziedziną lub typem danych.

W projektowaniu relacyjnych baz danych stosujemy dodatkowo pojęcie encji, encja to reprezentacja obiektu zarówno materialnej i nie materialnego (rzecz, osoba, miejsce, zdarzenie, pojęcia), będącego elementem odróżnialnym przez określane cechy.

Encje o podobnych cechach mogą być grupowane w zbiory encji, encje są opisane atrybutami, między encjami mogą zachodzić związki zwane relacjami, dopiero na podstawie projektu zdefiniowanych encji lub grup encji tworzymy tabele relacyjnej bazy danych.

Atrybuty encji są podstawą do tworzenia kolumn tych tabel, każda poprawnie zdefiniowana tabela powinna spełniać określone wymagania:
- tabela musi posiadać jednoznaczną nazwe.
- każda kolumna (atrybut) musi posiadać jednoznaczną nazwe opisującą ceche elementu bazy oraz określony typ danych do opisu wartości tej cechy
- każde pole tabeli musi zawierać tak zwaną wartośc atomową, czyli wartość niepodzielną zgodną z ustolnym typem danych
- nie może się powtarzać opis tego samego elementu bazy danych w postaci zdublowanego rekordu
- nie powinny pojawiać się pola tabeli opisujące cechy nieużyteczne z punktu widzenia funcjonalności bazy danych
- każda tabela musi posiadać przynajmniej jeden atrybut lub zbiór atrybutów, który będzie jednoznacznie identyfikować każdy rekord bazy danych, taki atrybut nazywamy kluczem.

Każda tabela musi posiadać atrybut lub zbiór atrybutów jednoznacznie indetyfikujący każdy rekord tabeli bazy danycyh, taki atrybut nosi nazwę klucza głównego (podstawowego).

Klucz głowny następujące warunki:
- musi być unikatowy
- powinnien mieć nie podzielną wartość
- nie może przyjmować wartości null
- wartość klucza nie może się zmieniać

W bazach danych możemy spotkać 5 rodzajów kluczy
- klucz prosty- jest to klucz jednoelementowy
- klucz złożony- klucz kilko elementowy
- klucz stuczny- dodatkowa kolumna indentyfukująca każdy rekord, utworzona w sposób stuczny, z klucza stucznego korzysta się w tedy, gdy z cech opisujących obiekt nie można wyodrębnić takiej cechy, która spełnia warunki dla klucza głównego
- klucz obcy- klucz główny jednej tabeli, wykorzystywany do tworzenia związków pomiędzy tabelami
- klucz kandydujący 	
