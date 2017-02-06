### Co to jest algorytm -- cechy i właściwości
Skończony ciąg jednoznacznie zdefiniowanych kroków koniecznych do wykonania pewnego zadania.
Cechy: 
- poprawność
- jednoznaczność
- dokładność
- uniwersalność

Właściwości:
- złożoność obliczeniowa

### Porównać pojęcia program, algorytm, procedura, funkcja, agent programowy
1. Program to zaimplementowany algorytm w sposób zrozumiały dla komputera/maszyny go wykonującej.
2. Procedura/funkcja to część składowa programu. Funkcja zwraca wartość, procedura tylko wykonuje operacje.
3. Agent programowy to program charakteryzujący się autonomicznością, komunikatywnością (komunikacja z innymi agentami, użytkownikiem) i percepcją (zdolność do postrzegania środowiska).

### Rodzaje zabezpieczeń systemów komputerowych
1. Fizyczne/sprzętowe (hardware)
2. Techniczne/programowe (software)
3. Organizacyjne

### Urządzenia wejścia wyjścia
Urządzenia służące do wydobywania/przekazywania informacji z/do komputera, na przykład: mysz komputerowa, klawiatura, monitor, dysk twardy.

### Scharakteryzować architekturę klient-serwer oraz klient-broker-serwer
1. Klient-serwer: program klienta wysyła żądania do serwera, który te zapytania przetwarza i dostarcza odpowiednią usługę. Z reguły serwer jest jeden i może obsługiwać wiele klientów.
2. Klient-broker-serwer: pomiędzy klientem a serwerem jest pośrednik (broker), który tłumaczy żądania klienta na język zrozumiały dla serwera. Pozwala to na odseparowanie implementacji klienta i serwera.

### Wymienić i omówić metody wdrażania systemów informatycznych
_Odpowiedź niepewna (źr. https://pl.wikipedia.org/wiki/Wdro%C5%BCenie_systemu )._

1. Całościowa: stary system jest porzucany i wdrażany jest nowy (wysokie ryzyko, niskie koszty).
2. Cząstkowa: stopniowe wdrażanie modułów systemu (średnie ryzyko, średnie koszty).
3. Równoległa: wdrażanie nowego systemu, przy jednoczesnym podtrzymaniu starego (niskie ryzyko, wysokie koszty).

### Scharakteryzować podstawowe modele baz danych
1. Hierarchiczny: rekordy przyjmują strukturę drzewa (np. struktura katalogów w systemie plików).
2. Sieciowy: uogólniony model hierarchiczny, rekordy mogą przyjmować strukturę dowolnego grafu.
3. Relacyjny: rekordy są grupowane w relacje (tabele). Dla każdej relacji musi zostać wybrany klucz główny, jednoznacznie identyfikujący dany rekord. Klucz obcy pozwala na powiązanie relacji między sobą (_skrót myślowy_). Większość relacyjnych baz danych korzysta z języka zapytań SQL.
4. Obiektowy: dane przyjmują postać obiektów. W przeciwieństwie do modelu relacyjnego, obiekty i relacje między nimi przechowywane są bezpośrednio, bez podziału na wiersze i kolumny.

### Czym wyróżnia się rozproszony system informatyczny od innych
Obliczenia wykonywane są na wielu komputerach w potencjalnie różnych lokalizacjach.

### Porównaj metody analizy obiektowej i strukturalnej w projektowaniu systemów informatycznych
_Odpowiedź niepewna_

W analizie obiektowej dane i operujące na nich funkcje rozważane są łącznie (diagram klas), w analizie strukturalnej -- osobno (diagram przepływu danych).

### Scharakteryzować standardowy język zapytań do baz danych
SQL: język deklaratywny, pozwala na obsługę baz danych w RDBMS, m.in. tworzenie i usuwanie tabel, dodawanie i usuwanie rekordów, wykonywanie zapytań w celu uzyskania danych spełniających określone warunki.

### Na czym polega polimorfizm metod w programowaniu obiektowym i po co się go stosuje?
Polega na przedefiniowaniu metod klasy nadrzędnej w klasie pochodnej. Wywołanie tej metody nie wymaga znajomości typu klasy pochodnej. Pozwala to na odseparowanie implementacji od interfejsu, co z kolei ułatwia rozszerzanie funkcjonalności.

### Wymienić i scharakteryzować metody testowania oprogramowania
Ze względu na poziom szczegółowości:

1. Testy jednostkowe: testowaniu podlegają najmniejsze elementy programu (np. pojedyncze funkcje).
2. Testy integracyjne: testowaniu podlega komunikacja między komponentami systemu, w celu sprawdzenia poprawności interakcji między nimi.
3. Testy systemowe: testowaniu podlega cały zintegrowany system w celu sprawdzenia, czy spełnia postawione mu wymagania.
4. Testy akceptacyjne: sprawdzana jest gotowość systemu do wypuszczenia na rynek.

Ze względu na szczegóły implementacyjne:

1. Testy funkcjonalne (czarnej skrzynki): implementacja nie jest znana, testowana jest funkcjonalność i warstwa interfejsu systemu.
2. Testy strukturalne (białej skrzynki): implementacja jest znana, testowane są ścieżki przepływu sterowania (np. warunki).

### Wymienić metody ochrony danych w systemach baz danych
1. Kontrola dostępu,
2. audyt wykonywanych operacji,
3. uwierzytelnianie,
4. szyfrowanie danych,
5. kontrola integralności danych,
6. kopie zapasowe,
7. ochrona w warstwie aplikacji.

### Rola sterowników w dostępie do baz danych
Sterownik tłumaczy zapytania zadane przez użytkownika na język zrozumiały dla danego DBMS. Pozwala to na ujednolicenie interfejsu programistycznego komunikacji z systemami bazodanowymi.

### Zarządzanie procesami w systemach operacyjnych
Procesami zarządza planista (scheduler), który jest odpowiedzialny za rozpoczynanie, wznawianie i kończenie procesów oraz przełączanie kontekstu pomiędzy procesami. System operacyjny dostarcza mechanizmy umożliwiające komunikację między procesami oraz synchronizację.

### Co to jest system komputerowy, informacyjny, informatyczny
System komputerowy: sprzęt i oprogramowanie do przetwarzania danych.
System informacyjny: system, który przetwarza dane w informacje, gromadzi je i przesyła.
System informatyczny: część systemu informacyjnego, wykorzystująca system komputerowy.

### Powody tworzenia systemów rozproszonych
- większa wydajność,
- większa niezawodność,
- skalowalność

### Środowiska programistyczne stosowane do obliczeń inżynierskich
- MathWorks MATLAB,
- StatSoft Statistica,
- Wolfram Mathematica,
- język i środowisko R

### Rodzaje systemów operacyjnych (klasyfikacja i charakterystyka)
- Jedno- i wielozadaniowe: systemy wielozadaniowe mogą wykonywać wiele procesów jednocześnie, jednozadaniowe -- nie.
- Obsługujące jednego i wielu użytkowników: systemy operacyjne mogą rozpoznawać użytkowników i dzielić lub izolować przestrzeń dyskową itp.
- Rozproszone: system zarządza wieloma komputerami i sprawia wrażenie obsługi pojedynczego komputera (_ehh wiadomo o co chodzi_).
- Wbudowane: systemy operacyjne zaprojektowane na systemy wbudowane (wydajne, małe).
- Czasu rzeczywistego: system gwarantuje obsługę zdarzeń w czasie rzeczywistym, bez opóźnień.

### Podać klasyfikację języków programowania
Ze względu na generację:

1. 1GL: język maszynowy,
2. 2GL: język assembly,
3. 3,4,5GL: języki o wyższym stopniu abstrakcji.

Ze względu na paradygmat:

1. deklaratywne, w tym
	- logiczne
	- funkcyjne
2. imperatywne, w tym
	- proceduralne
3. strukturalne, w tym
	- obiektowe

### Paradygmaty programowania obiektowego
- Enkapsulacja: połączenie danych (pola) z operacjami na tych danych (metody) oraz ukrywanie informacji.
- Kompozycja, dziedziczenie: relacje między obiektami mogą przybierać postać: jest (dziedziczenie), ma (kompozycja). Klasa dziedzicząca przejmuje atrybuty i metody klasy nadrzędnej.
- Polimorfizm: kod wywołujący metody na danym obiekcie nie musi znać jego konkretnej klasy -- wystarczy znajomość jednej z klas nadrzędnych.

### Zadania systemu zarządzania bazami danych (DBMS)
- realizacja zapytań,
- dodawanie, usuwanie i modyfikacja danych,
- kontrola redundancji danych,
- kontrola użytkowników i autoryzacja,
- zarządzanie transakcjami,

### Topologie sieci komputerowych
- liniowa: elementy połączone z dwoma sąsiadującymi,
- magistrala: elementy połączone do jednej magistrali,
- pierścienia: elementy połączone z dwoma sąsiadującymi tworząc zamknięty pierścień.
- gwiazdy: elementy połączone do jednego punktu centralnego
- hierarchiczna: kombinacja gwiazdy i magistrali
- siatki: zawiera połączenia nadmiarowe

### Podstawowe składniki sprzętowe w sieciach komputerowych
1. Terminal,
2. karta sieciowa,
3. modem,
4. switch,
5. router,
6. hub,
7. most

### Zastosowania mikroprocesorów
Komputery, telefony, alarmy, pralki...

### Metody kompresji danych
Kompresja bezstratna, np. kodowanie Huffmana: bajty występujące częściej mają krótszą reprezentację niż te występujące rzadziej.
Kompresja stratna, może dotyczyć różnych sygnałów (np. dzwięk, obraz), np. transformata falkowa, transformata Fouriera, splot, zmiana rozdzielczości

### Sprzętowe środki przyspieszania obliczeń
- wykorzystanie wielu rdzeni procesora,
- wykorzystanie obliczeń na karcie graficznej GPGPU,
- wykorzystanie układów FPGA, ASIC.

### Klasyfikacja usług internetowych
- pocztowe (POP3, SMTP),
- transferu plików (FTP),
- terminalowe (SSH),
- serwisów informacyjnych (HTTP)

### Budowa procesora
- ALU (jednostka arytmetyczno-logiczna)
- akumulatory
- rejestry
- licznik programu
- rejestr instrukcji
- inne (np. FPU, pamięć cache)

### Technologie tworzenia stron internetowych
HTML, XHTML, CSS, JavaScript, PHP...

### Czym się różnią portal i wortal internetowy
portal jest wielotematyczny, wortal skupia się na jednym konkretnym temacie

### Przetwarzanie rozproszone -- charakterystyka
Przetwarzanie danych równolegle przez wiele komputerów o możliwie różnej lokalizacji. Informacje między komputerami wymieniane są sporadycznie. Charakteryzuje się dużą wydajnością, skalowalnością i niezawodnością. Szczególny przypadek przetwarzania równoległego.

### Przetwarzanie równoległe -- charakterystyka
Przetwarzanie danych równolegle przez jeden lub więcej komputerów. Procesy wykonywane są równocześnie. W przypadku wykonywania zadania na jednym komputerze, konieczna jest utylizacja wielu procesorów.

### Grafika rastrowa a grafika wektorowa
- rastrowa: obraz przedstawiony jest jako macierz pikseli,
- wektorowa: obraz zdefiniowany jest jako zbiór opisanych matematycznie figur geometrycznych.

### Porównanie modeli odniesienia: ISO/OSI oraz TCP/IP
ISO/OSI -- 7 warstw:

1. Fizyczna
2. Łącza danych
3. Sieciowa
4. Transportowa
5. Sesji
6. Prezentacji
7. Aplikacji

TCP/IP -- 4 warstwy:

1. Host-sieć (OSI 1, 2)
2. Internetowa (OSI 3)
3. Transportowa (OSI 4)
4. Aplikacji (OSI 5, 6, 7)

### Zadania warstwy transportowej
- adresowanie
- ustanawianie/zwalnianie połączenia
- buforowanie i sterowanie przepływem
- multipleksowanie
- odtwarzanie po awarii

### Charakterystyka warstwy fizycznej
Określa składniki sieci niezbędne do obsługi elektrycznego/optycznego/radiowego wysyłania i odbierania sygnałów.

### Charakterystyka warstwy łącza danych
Kontroluje warstwę fizyczną, zapewnia mechanizmy detekcji i korekcji błędów.

### Do czego służy protokół TCP, a do czego IP?
IP określa w jaki sposób dane są przesyłane (adres, trasa, pakiety).
TCP zapewnia niezmienioną (zachowana kolejność) i pełną (wszystkie pakiety dostarczone w całości bez duplikatów) sekwencję pakietów.

### Rodzaje światłowodów
_Odpowiedź niepewna_
- plastikowy: tani, małe prędkości, małe odległości
- krzemiankowy: nieco lepszy niż plastikowy
- jednomodowy: bardzo drogi, duże odległości, trudny w obsłudze
- wielomodoy: drogi, średnie odległości

### Scharakteryzować sieciowe systemy plików
Umożliwia dostęp do danych komputerom zdalnym. Dane znajdują się na jednym lub wielu serwerach.
Charakteryzuje je m.in.
- przeźroczystość dostępu: dostęp do plików jest taki sam jak dla plików lokalnych
- przeźroczystość lokacji: pliki zdalne i lokalne łączy jedna przestrzeń -- nazwa pliku nie określa jego lokacji
- przeźroczystość współbieżności: stan systemu plików jest taki sam dla wszystkich klientów

### Wymień i opisz warstwy modelu OSI
1. Fizyczna: wysyłanie i odbiór strumieni bitów, rozmieszczenie złącz
2. Łącza danych: kontrola jakości transmisji, podział pakietów na ramki
3. Sieciowa: sterowanie działaniem podsieci, algorytmy przesyłania danych
4. Transportowa: segmentowanie oraz składanie danych
5. Sesji: synchronizacja danych i zarządzanie dialogiem
6. Prezentacji: kontrola składni i semantyki przesyłanych informacji
7. Aplikacji: protokoły aplikacji, interfejs pomiędzy oprogramowaniem a warstwami niżej

### Podstawowe cechy standardów sieci bezprzewodowych WiFi
- 802.11a - do 54mbps, 5ghz,
- 802.11b - 11mbps, 2.4ghz, zasięg 30-120m,
- 802.11g - 54mbps, 2.4ghz, najpopulardniejszy standard, wymaga silnego i stabilnego sygnału względem 802.11b,
- 802.11n - 300mpbs, 5ghz lub 150mbps, 2.4ghz, wymaga silnego i stabilnego sygnału.

### Przedstawić budowę światłowodu
rdzeń (włókno szklane), wokół płaszcz (materiał o niższym współczynniku załamania światła), dalej powłoka lakierowana (chroni płaszcz), dalej powłoka wzmacniająca (ochrona przed wpływem środowiska).

### Cechy charakterystyczne cyfrowych sieci ISDN
ISDN to sieć cyfrowa ze zintegrowanymi usługami. W sieciach ISDN nie występują pośredniczące
urządzenia analogowe. Połączenia w ISDN są komutowane (zestawiane).
Cechy to:
- przekaz cyfrowy
- gwarantowana przepływnosc, bez wzgledu na odległosc
- szybkie zestawianie połaczen
- można likwidowac połaczenia zaraz po realizacji sesji
- szeroki zakres usług wideotelefonii

### Rodzaje i zastosowania macierzy dyskowych
- RAID 0: bez redundancji danych, szybki odczyt i zapis, duża pojemność
- RAID 1: dane powielane na wszystkich dodatkowych dyskach, mała pojemność, zwiększona niezawodność, szybki odczyt
- RAID 3: wszystkie poza jednym jak w RAID 0; ostatni dysk przechowuje sumy kontrolne -- łączy zalety RAID 0 ze zwiększoną niezawodnością.
- RAID 5: jak w RAID 0, suma kontrolna rozproszona po wszystkich dyskach, zwiększona niezawodność, szybki odczyt, wolny zapis
- RAID 6: jak w RAID 5, dodatkowa suma kontrolna, zwiększona niezawodność

### Zasada działania systemów klastrowych
Każdy węzeł klastra dostaje własne zadanie bądź cały klaster pracuje nad tym samym zadaniem. W przypadku awarii jednego węzła, wykonywane przez niego zadanie jest przejmowane przez inny węzeł.

### Zasada działania systemów ekspertowych
Oparte o bazy wiedzy (zasady jeżeli-to); wspomagają podejmowanie decyzji. Mogą wspomagać interpretację danych oraz przeprowadzać prognozę i diagnozę na ich podstawie.

### Omów zasadę działania monitora (CRT lub LCD)
LCD: zbudowany z macierzy komórek zawierających ciekły kryształ o kolorowych filtrach. Elektrody wytwarzają pole elektryczne, które wywołuje zmianę cząsteczek ciekłego kryształu, co z kolei powoduje zmianę polaryzacji światła przez nie przechodzącego, a co za tym idzie, ilości przepuszczanego światła. Z tyłu ekranu montowane jest dodatkowe podświetlenie, które ten efekt podkreśla.

### Wymienić i scharakteryzować rodzaje pamięci półprzewodnikowych
- RAM: pamięć ulotna, szybka
- ROM: pamięć nieulotna (dane pozostają pod odłączeniu zasilania), tylko do odczytu -- zapis jest niemożliwy lub odbywa się poprzez dodatkowe procedury lub z wykorzystaniem innego sprzętu.

### Przedstaw tablice prawdy AND, OR, XOR, zilustruj oznaczenie bramki, wymień przykładowe zastosowanie
za proste

### Wątki a procesy -- na podstawie wybranego systemu. Wymienić wady, zalety
Proces to program w trakcie wykonywania. Posiada własną przestrzeń adresów w pamięci, własny stos oraz tablicę deskryptorów. W systemie Unix tworzenie procesów może się odbyć poprzez wywołanie funkcji systemowych UNIX _fork_ i _exec_.

Wątek działa w obrębie procesu. Posiada oddzielny stos, jednak część danych jest współdzielona. Tworzenie nowych wątków może przebiegać wywołując funkcje _pthread\_create_. Wątek jest "lżejszy" od procesu.

### Budowa typowego układu FPGA
Zbudowany jest z programowalnych bloków logicznych oraz programowalnej macierzy połączeń. Bloki mogą być skomplikowanymi układami lub pojedynczymi bramkami logicznymi. Bloki zawierają również elementy pamięciowe (np. przerzutniki).

### Podstawowe tryby adresowania systemów mikroprocesorowych
- natychmiastowe: nie ma odniesienia do pamięci w celu pobrania argumentu (instrukcja zawiera dane)
- bezpośrednie: jedno odniesienie do pamięci (operand jako adres lokacji argumentu)
- pośrednie: wiele odniesień do pamięci (operand jako adres na wskaźnik)

### Hierarchia pamięci w systemie komputerowym, stronicowanie oraz koncepcja pamięci wirtualnej
Hierarchia:

1. rejestry procesora
2. pamięć podręczna procesora
3. pamięć RAM
4. pamięć flash
5. pamięć dyskowa
6. np. dysk optyczny

Stronicowanie to metoda implementacji pamięci wirtualnej. Pamięć fizyczna dzielona jest na bloki (strony) o równych wielkościach. Adresy logiczne następnie mapowane są na odpowiednie strony oraz fizyczne adresy.

Pamięć wirtualna pozwala na traktowanie pamięci komputera w jednolity sposób. Jeżeli program wymaga większej pamięci niż tej dostępnej, system operacyjny może wykorzystać pamięć dyskową, jednak postępowanie pozostaje bez zmian.

### Omówić strukturę i funkcjonowanie systemu transmisyjnego
Źródło wiadomośći -> przetwornik analogowo-cyfrowy -> koder źródła -> koder kanału -> modulator -> układ wysokiej częstotliwości -> medium transmisyjne -> układ wysokiej częstotliwości -> demodulator -> dekoder kanału -> dekoder źródła -> przetwornik cyfrowo-analogowy -> odbiorca wiadomości

### Różnice pomiędzy pamięcią statyczną i dynamiczną
SRAM: bez zegara, bez konieczności odświeżania, niskie zużycie mocy, każda komórka składa się z 6 tranzystorów -- pamięć szybka, wysoka cena, wykorzystywana w małych ilościach (cache procesora).
DRAM: wymagane cykliczne odświeżanie, każda komórka składa się z 1 tranzystora -- pamięć wolniejsza, niska cena (pamięć RAM).

### Problem synchronizacji przy transmisji danych i transmisja asynchroniczna
Urządzenie może się zdesynchronizować podczas odbioru sygnału. Problem ten może być częściowo rozwiązany poprzez zastosowanie kodowania, które umożliwiałoby ponowną synchronizację w takiej sytuacji.

Transmisja asynchroniczna - bez sygnału zegarowego, rozpoczęcie i zakończenie sygnału oznaczane są specjalną sekwencją bitów.

### Uprawnienia plików na przykładzie systemu operacyjnego Unix/Linux
Uprawnienia plików dotyczą trzech grup:
- właściciela pliku,
- grupy, do której należy właściciel,
- pozostałych, niespełniających poprzednich warunków.

Uprawnienia dotyczą
- odczytu,
- zapisu,
- wykonania plików.

Nadawanie plików odbywa się poprzez komendę _chmod_.

### Scharakteryzować sieciowe systemy plików
p. 41.

### Co to jest cykl życia oprogramowania i z jakich faz się składa
Ciąg działań projektowo-programowych, obejmujący zakres od powstania zapotrzebowania na oprogramowanie aż do jego wycofania z eksploatacji. Wyróżnić można 4 fazy:
- określenie wymagań,
- wytworzenie systemu,
- wdrożenie,
- eksploatacja i konserwacja.

### Wymienić rodzaje diagramów w UML
- diagram klas
- diagram przypadków użycia
- diagram stanów
- diagram aktywności
- diagram komponentów

### Co oznaczają skróty ERD oraz DFD? Do czego się ich używa?
ERD to diagram związków encji, wykorzystywany do projektowania baz danych.
DFD to diagram przepływu danych, wykorzystywany do projektowania sposobu przetwarzania danych.

### Przeciążanie funkcji i operatorów w języku C++
Przeciążanie funkcji polega na definicji funkcji o takiej samej nazwie co już istniejąca, o innych parametrach wejściowych lub wyjściowych (ale nie wyłącznie wyjściem). Przy wywołaniu funkcji, wybierana jest ta, o odpowiedniej liczbie i typach argumentów.

Przeciążanie operatorów polega na określeniu funkcji o specjalnej nazwie `operator @` dla pewnego operatora `@` i typu lub typów. Niektórych operatorów nie można przeciążać, należą do nich m.in. operator `':?'` oraz `'.'`.

### Scharakteryzować instrukcje iteracyjne w przykładowym języku programowania
Język C

`for (wyrażenie początkowe; wyrażenie logiczne; wyrażenie wykonywane co iterację) { ciało pętli }`

pętla wykonuje się do momentu, gdy wyrażenie logiczne zwróci fałsz (wartość 0).

`while (wyrażenie logiczne) { ciało pętli }`

pętla wykonuje się dopóki wyrażenie logiczne zwraca prawdę (wartość różną od 0).

`do { ciało pętli } while (wyrażenie logiczne);`

pętla wykona się co najmniej raz, warunek sprawdzany jest pod koniec pętli.
Jeżeli ciało pętli zawierają tylko jedno wyrażenie, nawiasy klamrowe mogą zostać opuszczone.

### Omówić na czym polega przeciążanie funkcji i operatorów w języku C++
p. 64.

### Scharakteryzować mechanizmy dostępu do składowych klasy tworzonych statycznie i dynamicznie
Zakładając język C++, do składowych statycznych odwołanie następuje wg schematu nazwa-klasy::nazwa-składowej lub nazwa-obiektu.nazwa-składowej lub nazwa-wskaźnika->nazwa-składowej. Dla składowych klasy tworzonych dynamicznie tak jak wyżej z pominięciem przypadku z operatorem `::`.

### Omów pojęcia agregacji i zawierania w diagramach UML
_Odpowiedź niepewna_

Agregacja oznacza, że obiekty klasy posiadają potencjalnie dzieloną referencję do innego obiektu
Zawieranie oznacza, że obiekty klasy posiadają na własność inne obiekty, tj. odpowiadają za jego cykl życia.

### Budowa i zasady działania wybranego urządzenia (drukarka laserowa, dysk twardy, pamięć USB, streamer, etc.)
p. 49.

### Metody komunikacji człowiek-komputer
- język poleceń
- formularze
- menu
- manipulacja bezpośrednia
- komunikacja w języku naturalnym
- interfejsy multimedialne
- sprzęgi rzeczywistości wirtualnej

### Wymienić metody ekstrakcji wiedzy z danych
- streszczanie
- poszukiwanie asocjacji
- analiza jakościowa danych
- analiza ilościowa danych
- klasyfikacja
- grupowanie

### Co to są drzewa decyzyjne i do czego służą
Przedstawienie procesu decyzyjnego za pomocą grafu (drzewa), gdzie wierzchołki określają aktualny stan a krawędzie pewne decyzje.

### Rekurencja i jej implementacja w językach wysokiego poziomu
Rekurencja to wywołanie funkcji wewnątrz tej samej funkcji.
Implementacja nie różni się od zwykłego wywołania funkcji.

### Co to są algorytmy zachłanne -- podać przykład takiego algorytmu
Są to algorytmy, które w każdym kroku podejmują najkorzystniejszą w danym momencie akcję.
Przykład: ciągły problem plecakowy (znajduje rozwiązanie optymalne), dyskretny problem plecakowy (nie gwarantuje optymalnego rozwiązania).

### Na czym polega haszowanie i gdzie ma ono zastosowanie?
Haszowanie to transformacja pewnego obiektu na indeks, w celu umieszczenia go w mapie lub zbiorze haszującym lub w celu szybkiej identyfikacji obiektu.

### Co to są problemy obliczeniowo trudne -- podać przykład takiego problemu
Są to problemy, dla których nie jest znane rozwiązanie o złożoności wielomianowej lub niższej dla rozmiaru danych wejściowych. Przykładem tego problemu jest problem komiwojażera.

### Maszynowa reprezentacja danych
Ciąg bitów, często o rozmiarze 8 * 2^n bitów. Może reprezentować liczby całkowite bez znaku (bezpośrednia reprezentacja lub kod BCD lub kod Graya), liczby całkowite ze znakiem (np. kod uzupełnień do 2 U2), liczby stałoprzecinkowe (np. bezpośrednia reprezentacja, z separatorem ustalonym na danej pozycji), liczby zmiennoprzecinkowe (np. standard IEEE 754 -- bit znaku, bity cechy i mantysy), znaki (7-bitowa reprezentacja ASCII lub inne kodowanie, np. UTF-8 mapowane na znaki Unicode).

### Assembler, interpreter, kompilator -- porównać i wyjaśnić pojęcia
- assembler: program zamieniający kod w języku assembly na kod maszynowy,
- interpreter: program interpretujący kod pewnego języka programowania w trakcie jego wykonywania,
- kompilator: program zamieniający kod pewnego języka programowania na postać pośrednią (np. bytecode) lub kod maszynowy przed jego wykonaniem.

### Zarządzanie pamięcią w Unix/Linux
Podsystem zarządzania pamięcią zapewnia:
- dużą przestrzeń adresową: wykorzystując pamięć wirtualną, system operacyjny sprawia wrażenie posiadania znacznie większej ilości pamięci,
- ochronę pamięci: każdy proces ma do dyspozycji własną wirtualną przestrzeń adresową. Przestrzenie te są odseparowane i jedna aplikacja nie może wpłynąć na inną. Pamięć może także być oznaczona jako chroniona przed zapisem.
- mapowanie pamięci: zawartość pliku może być bezpośrednio włączona w przestrzeń adresową procesu
- alokację pamięci fizycznej: każdy może posiadać dostateczny kawałek pamięci fizycznej
- dzieloną pamięć wirtualną: możliwość dzielenia pamięci pomiędzy procesami.

### Zasady korzystanie z kluczy i pakietów kryptograficznych PGP (Pretty Good Privacy)
Program PGP może generować klucze asymetryczne -- generowana jest para kluczy. Jeden z nich stosowany jest do szyfrowania i autoryzacji (publiczny), drugi do podpisywania i deszyfrowania wiadomości (prywatny). PGP jest stosowany do podpisywania, szyfrowania i deszyfrowania wiadomości oraz całych partycji dyskowych. Poszczególne podmioty podpisują sobie nawzajem klucze, przez co progresywnie formuje się sieć indywidualnych kluczy publicznych połączonych ze sobą łączami stworzonymi przez podpisy (web of trust).

### Metody reprezentacji wiedzy i wnioskowanie
- rachunek zdań, rachunek predykatów,
- zapis stwierdzeń
- systemy regułowe
- sieci semantyczne
- oparte na ramach
- używające modeli obliczeniowych

Wnioskowanie -- ustalenie opisu obiektu na podstawie przesłanek.

### Zasady przetwarzanie transakcji w DBMS
ACID:
- Atomicity: atomowość, transakcja odbywa się w całości albo w ogóle,
- Consistency: spójność, transakcje nie naruszają integralności danych,
- Isolation: transakcje odbywają się bez wiedzy o innych,
- Durability: trwałość, wyniki zatwierdzonych transakcji nie mogą zostać utracone.

### Narzędzia i środowiska wytwarzania oprogramowania
Narzędzia i środowiska wytwarzania oprogramowania:
- Eclipse
- Visual Studio
- Qt Creator

### Wzorce projektowe i programowe
Określają pewne schematy postępowania przy projektowaniu systemów bazowanych na obiektach. Podział na wzorce
- kreacyjne (np. abstrakcyjna fabryka)
- strukturalne (np. most)
- behawioralne (np. strategia)

### Metody podnoszenie niezawodności systemów wbudowanych
Testowanie, ograniczenie złożoności zadań, rozdzielanie zadań na mniejsze systemy.

### Ryzyko i odpowiedzialność związana z systemami informatycznymi
Ryzyko to miara zagrożenia wynikającego z prawdopodobieństwa wystąpienia pewnych niekorzystnych zdarzeń. Za ocenę ryzyka i identyfikację zagrożeń dla projektu odpowiedzialny jest menedżer projektu.

### Klasyfikacja systemów oprogramowania użytkowego
- akcesoria (słowniki, kompresory),
- bezpieczeństwo (antywirusy),
- biuro (edytory),
- grafika (edytory),
- internet (przeglądarki),
- multimedia (odtwarzacze).

### Systemy wspomagające wytwarzanie oprogramowania -- klasyfikacja, przykłady, funkcje
Systemy CASE (computer aided software engineering).
Klasyfikacja:
- narzędzia wspierające poszczególne zadania w cyklu życia oprogramowania, w tym
	- Upper CASE: modelowanie logiki biznesowej, analiza,
	- Lower CASE: testowanie, integracja komponentów, 
- narzędzia wspierające dwa lub więcej zadań w cyklu życia oprogramowania,
- środowiska wspierające cały cykl życia oprogramowania.

Przykłady:
- Enterprise Architect
- Visual Paradigm
- Rose
- Oracle Designer

Funkcje:
- modelowanie logiki biznesowej (graficzne narzędzia),
- projektowanie i konstrukcja,
- weryfikacja i walidacja,
- metryka i miara (np. postępu),
- zarządzanie projektem.

### Wymienić i scharakteryzować podstawowe techniki w grafice komputerowej
- antyaliasing,
- oświetlenie, cieniowanie, raytracing, HDR,
- teksturowanie, filtracja tekstur,
- postprocessing,

### Wymienić i scharakteryzować metody przetwarzania obrazów
- operacje na histogramie,
- operacje geometryczne,
- operacje arytmetyczne/logiczne,
- normalizacja,
- filtracje,
- wektoryzacja, rasteryzacja,
- transformacja (na przykład dft).

### Zasady i metody tworzenia indeksów w bazach danych
??

### Rodzaje i sposób działania przerzutników
_Odpowiedź niepełna_
- typu D: wyzwalane zboczem, wystawia stan wejścia D na wyjście Q w czasie zbocza narastającego, na zboczu opadającym wartość jest zapamiętywana
- typu RS: asynchroniczny, wejścia Set (S) i Reset (R) -- R na 0 wymusza 0 na wyjściu, R na 1 wymusza S na wyjściu.
- typu T: wyzwolenie zboczem zegara.

### Różnica pomiędzy automatem Mealy'ego a automatem Moore'a
Wyjścia w automacie Mealy'ego zależą od stanu wewnętrznego i sygnałów wejściowych, w automacie Moore'a wyjścia zależą wyłącznie od stanu wewnętrznego. Automaty te są równoważne -- jeden można zamienić bezstratnie w drugi.

### Różnica pomiędzy układami typu PLA a układami PAL
PAL:
- programowalna matryca OR i AND,
- wejścia i wyjścia są jednokierunkowe,
- możliwe współdzielenie termów przez funkcje wyjściowe.
PLA:
- programowalna matryca AND, matryca OR stała,
- dwukierunkowe wejścia i wyjścia,
- brak współdzielenia termów przez funkcje wyjściowe,
- szybsze i o mniejszym poborze mocy.

### Wymienić i omówić znanych światowych wynalazców w dziedzinie informatyki i telekomunikacji
Michael Faraday - wprowadził do fizyki pojęcia takie jak: linie siły pola magnetycznego i elektrycznego. Odkrył, że płaszczyzna polaryzacji światła ulega zmianie po przejściu przez pole magnetyczne (wskazuje to na związek m-dzy światłem a elektromagnetyzmem).

James Clerk Maxwell - na podstawie rozważań teoretycznych wyciągnął wniosek, że światło jest falą elektromagnetyczną.

Thomas Alva Edison - wynalazca, stworzył m.in. żarówkę, fonograf, akumulator. Udoskonalił telefon Alexandra Bella.

Heinrich Rudolf Hertz - na podstawie teorii Maxwella przeprowadził eksperyment potwierdzający jego teoretyczne rozważania. Pionier radiokomunikacji.

Samuel Morse - malarz i wynalazca, skonstruował telegraf elektromagnetyczny i opracował dla niego specjalny alfabet złożony z kombinacji kresek i kropek.

Alexandr Stiepanowicz Popow - na podstawie badań H. Hertza stworzył radiotelegraf.

Marconi Guglielmo (??) - rozpoczął nawiązywanie łączności radiowej.

Nikola Tesla - stworzył podstawy teoretyczne konstrukcji radia, był m.in twórcą pierwszych urządzeń bezprzewodowych.

Alexander Graham Bell - wynalazca, opracował telefon. Podstawowe dzieło to praca dotycząca sposobu zapisywania i odtwarzania mowy.

Jean Baudot - skonstruował aparat telegraficzny bodot. Od jego nazwiska pochodzi jednostka szybkości modulacji bod.

Agner Krarup Erlang - opracował wzór (znany dziś jako wzór Erlanga) do obliczenia natężenia ruchu sieci telefonicznej. Pierwsza osoba, która zajęła się problemem sieci telefonicznych.

### Omówić sposoby prezentacji informacji oraz pojęcia informacji analogowej i cyfrowej sygnału analogowego oraz cyfrowego
Informacja analogowa i cyfrowa:
- Analogowe - informacje w tej postaci mogą  być:
	- Proste - mocno wyróżniona jedna częstotliwość i niewielki zestaw harmonicznych (np. dzwięk jednego klawisza pianina)
	- Złożone - składają się z wielu częstotliwości o różnym natężeniu (np. głos ludzki).
- Cyfrowe - informacja z postaci impulsów elektrycznych (wartości binarnych), dyskretna.

Sygnały analogowe oraz cyfrowe:
- Analogowy - jest ciągły w czasie. Jest to sinusoidalna fala o określonej częstotliwości amplitudzie i fazie. Musi być dodatkowo wzmacniany przy przesyle na większą odległość.
- Cyfrowy - zapisany jako zakodowane skwantyzowane wartości w pewnych odstępach czasu. Transmisje sygnału cyfrowego cechują się większym stopniem niezawodności niż analogowe zwłaszcza na dłuższych dystansach. Jeżeli nastąpi potrzeba wzmocnienia, sygnał jest regenerowany cyfrowo, co nie zwiększa mocy szumu ani zniekształceń.

### Zdefiniować pojęcie widma sygnału oraz omówić numeryczne metody jego obliczania
Widmo sygnału przedstawia sygnał w dziedzinie częstotliwości.

Do numerycznych metod obliczania należą: naiwna implementacja dyskretnej transformaty Fouriera (złożoność O(n^2)), szybka transformata Fouriera (złożoność O(nlogn)) -- obliczają widmo na podstawie spróbkowanego sygnału (wynik taki sam niezależnie od metody). Wartości zwracane to liczby zespolone, (po normalizacji) moduł przedstawia amplitudę danej częstotliwości, argument określa fazę danej częstotliwości.

### Omówić skalę decybelową
Służy do porównywania mocy/amplitud dwóch sygnałów.
Wyrażana wzorem P = 10log10(P/P0), gdzie P i P0 to wielkości mocy.

### Co to jest szerokości pasma oraz przepływności kanału transmisyjnego
Szerokość pasma -- różnica między górną a dolną częstotliwością pasma, które kanał jest zdolny przenieść z nierównomiernością nie gorszą niż 3dB.
Przepływność kanału -- zdolność kanału do przenoszenia informacji (ilość przesłanych bitów na sekundę). Do obliczania przepływności stosuje się wzór 2B*log2(M), gdzie B to szerokość pasma, M to liczba dyskretnych poziomów (jezeli M = 2, każdy sygnał zawiera bit). Maksymalna teoretyczna przepływność kanału jest ograniczona prawem Shannona P = B*log2(1+S/N), gdzie S/N to stosunek mocy sygnału do szumu.

### Omówić zagadnienie modulacji ze szczególnym uwzględnieniem modulacji cyfrowych. Omówić znane media transmisyjne
Modulacja to proces zmiany cech pewnego sygnału (zwanego sygnałem nośnym) innym sygnałem (zwanym sygnałem modulującym) w celu zawarcia informacji w sygnale nośnym.

Do modulacji cyfrowych należą ASK (amplituda fali nośnej jest modulowana kwadratowym sygnałem modulującym), PSK (to samo dla fazy), FSK (to samo dla częstotliwości), QAM (kodowanie amplitudą i fazą w celu zawarcia większej ilości informacji, często prezentowane przez diagramy konstelacyjne).

Do mediów transmisyjnych należą:
- przewodowe:
	- kable symetryczne,
	- kable współosiowe,
	- kable światłowodowe,
	- kable energetyczne,
- bezprzewodowe:
	- fale radiowe,
	- fale świetlne

### Omówić problem uwierzytelniania na przykładach: uwierzytelniania SYK, uwierzytelniania SYH, uwierzytelniania SYA oraz pojęcia hasła, karty magnetycznej, karta elektronicznej, karty identyfikacyjnej SIM oraz omówić techniki biometryczne.
Metody uwierzytelniania:
- SYK (something you know): na podstawie tego, co użytkownik zna (np. hasło),
- SYH (something you have): na podstawie tego, co użytkownik ma (np. token, karta),
- SYA (something you are): na podstawie tego, kim użytkownik jest (np. odcisk palca).

Hasło to ciąg znaków.

Karta magnetyczna -- karta z paskiem magnetycznym, na podstawie którego przebiega autoryzacja.

Karta elektroniczna -- bezpieczniejsza niż magnetyczna, zawiera układ elektroniczny, który pozwala na lepszą autoryzację.

Karta identyfikacyjna SIM -- karty z możliwością zapisu haseł dostępu, adresacji numerów, algorytmów szyfrowania, książki telefonicznej, pamięci komunikatów SMS, wielu stopni uprawnień.

Techniki biometryczne:
- rozpoznawanie odcisku palca,
- skanowanie siatkówki oka,
- rozpoznawanie cech twarzy,
- rozpoznawanie geometrii ręki/palca,
- rozpoznawanie głosu,
- rozpoznawanie podpisu.

### Formaty danych liczbowych
Liczby całkowite bez znaku/ze znakiem (kod U2), liczby stałoprzecinkowe, liczby zmiennoprzecinkowe.

### Omówić zasady wykonania operacji arytmetycznych w kodzie U2
Dodawanie i odejmowanie -- bezpośrednio, bitowe.
Mnożenie -- liczby są rozszerzane do do dwukrotnie większej reprezentacji (nie zawsze konieczne), następnie przeprowadzone jest bitowe mnożenie.
Dzielenie -- liczby są zamieniane na reprezentację bezznakową, po podzieleniu następuje przywrócenie znaku.

### Omówić zasady wykonania operacji na liczbach zmiennopozycyjnych
Według standardu IEEE, dodawanie, odejmowanie, mnożenie i dzielenie wykonywane jest dokładnie a następnie jest zaokrąglane do najbliższej lub parzystej cyfry -- w praktyce jest to nieefektywne; ten sam efekt można uzyskać wykorzystując dodatkowe bity kontrolne (guard, round, sticky). Po zaokrągleniu wynik jest normalizowany. Przy dodawaniu i odejmowaniu, liczby sprowadzane są do tego samego wykładnika. Przy mnożeniu/dzieleniu wykładnik jest dodawany/odejmowany. Operacja jest dalej przeprowadzana na wartościach mantysy. Operacje dodawania i mnożenia są przemienne ale nie koniecznie łączne ani rozdzielne, tj. `a + b = b + a` ale  `a + (b + c) != (a + b) + c`, i `a * (b + c) != a * b + a * c` (równość tylko w pewnych przypadkach).

### Wymienić standardowe postacie wyrażeń boolowskich
- DNF (disjunctive normal form) -- suma iloczynów logicznych,
- FDNF (full DNF) -- suma iloczynów logicznych, gdzie w każdej sumie znajduje się każda zmienna dokładnie raz,
- CNF (conjunctive normal form) -- iloczyn sum logicznych,
- FCNF -- analogicznie do FDNF.
Jedyne operacje dozwolone w tych postaciach to AND, OR i NOT.

### Omówić kombinacyjne i sekwencyjne układy logiczne
Kombinacyjne układy logiczne to takie, których wyjście zależy jedynie od wartości na wejściach.

Sekwencyjne układy logiczne zależą dodatkowo od stanu poprzedniego.

### Scharakteryzować poszczególne etapy procesu konwersji analogowo-cyfrowej
1. Filtrowanie (szumów itp.),
2. Próbkowanie (pobieranie wartości co pewien okres czasu),
3. Kwantyzacja (zaokrąglanie wartości do skończonych reprezentacji),
4. Kodowanie (zamiana sygnału w kod zrozumiały dla urządzenia).

### Omówić ogólną charakterystykę filtrów cyfrowych
Filtr cyfrowy to system, który przeprowadza operacje na spróbkowanym sygnale prowadzące do redukcji lub uwydatnienia pewnych elementów tego sygnału. Filtrowanie może przebiegać w dziedzinie czasu lub częstotliwości. W dziedzinie częstotliwości właściwości filtru opisuje transmitancja.

### Opisać proces akwizycji i kodowania danych multimedialnych w kontekście zastosowania ich w systemach transmisji strumieniowej.
Akwizycja danych – w informatyce i analizie sygnałów pierwszy etap przetwarzania danych polegający
na ich przygotowaniu do dalszej obróbki czy interpretacji; obejmuje on m.in. przechwytywanie,
próbkowanie, czy kwantowanie danych w dowolnej postaci, często różnorakich sygnałów, np. w
postaci falowej.

Dane multimedialne maja zazwyczaj duży rozmiar. W aplikacji multimedialnej dane te sa
kompresowane, transmitowane i prezentowane użytkownikowi. Akwizycja i kodowanie (w tym
kompresja) sa potrzebne do efektywnej transmisji strumieniowej.

### Wymienić i omówić podstawowe parametry stosowane przy definiowaniu jakości usług
_jakich usług... odpowiedź do weryfikacji_
- utrata pakietów,
- opóźnienie,
- fluktuacja opóźnień,
- zmiana kolejności pakietów.

### Wymienić i omówić podstawowe metody szeregowania pakietów
- kolejki FIFO: w przypadku przeciążenia, nowe pakiety mogą zostać odrzucone,
- kolejki priorytetowe: jest kilka (4?) kolejek o różnych priorytetach, kolejki opróżniane są w kolejności od najwyższego priorytetu,
- kolejki cykliczne i ważone WFQ: zapewnia sprawiedliwy przydział łącza wszystkim rodzajom ruchu, stosowany w przypadkach, gdy w sieci znajdują się źródła o dużym zróżnicowaniu natężeń,
- kolejkowanie custom queuing: gwarantuje, że żaden typ ruchu nie przekroczy skonfigurowanego procenta przydzielonej mu przepustowości,
- round-robin: każdy użytkownik obsługiwany jest cyklicznie.

### Różnica między standardami JPEG i JPEG2000, rodzaje transformacji obrazu
Standard JPEG oparty jest o dyskretną transformatę kosinusową, JPEG2000 wykorzystuje dyskretną transformatę falkową i może przeprowadzić kompresję bezstratną. JPEG2000 jest nowszym standardem i daje w wyniku lepszą jakość obrazu.

Rodzaje transformacji:
- dyskretna transformacja kosinusowa,
- dyskretna transformacja falkowa,
- dyskretna transformacja Fouriera,
- transformacja Hougha.

### Scharakteryzować kod Graya jako przykład elementu wchodzącego w skład metod cyfrowej modulacji sygnału
Kod Graya charakteryzuje się tym, że dwa kolejne słowa kodowe różnią się jednym bitem. Stosowane są w modulacjach, ponieważ niwelowane są stany niepożądane wynikające z potrzeby zmiany kilku bitów. Wykorzystywane np. w modulacji QAM.

### Różnica między kodami detekcyjnymi i korekcyjnymi -- przykłady zastosowań
Kody detekcyjne przekazują dodatkowe informacje pozwalające na wykrycie błędu (może być następnie zażądane ponowne wysłanie informacji). Stosowane w transmisjach w Internecie, komunikacji radiowej.
Informacje w kodach korekcyjnych pozwalają dodatkowo na jego korekcje (dane mogą zostać odtworzone). Stosowane np. w macierzach dyskowych RAID.
