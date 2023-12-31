# Ściany murowe w ABC Płyta

[Zakup](#zakup) | [Instalacja](#instalacja) | [Wideo](#wideo) | [Instrukcja](#instrukcja) | [Kontakt](#kontakt)

Moduł do szybkiego projektowania ścian murowych zgodnie z Eurokodami w
programie **ABC Płyta** firmy [PRO-SOFT](https://www.pro-soft.gliwice.pl/).

W celu zapoznania się z możliwościami modułu można obejrzeć [wideo](#wideo)
lub go [zainstalować](#instalacja). Przed [zakupem](#zakup) działa w trybie DEMO,
gdzie nie można zmieniać parametrów elementu murowego.
Szczegółowy opis działania zawarty jest w [instrukcji](#instrukcja).

## Zakup

Cena **600,- zł** netto za licencję wieczystą, na fakturze kwota będzie powiększona
o podatek VAT w wysokości 23%.

Wymagana jest aktualizacja programu **ABC Płyta** do wersji minimum 6.24 zgodnie z
[cennikiem](https://www.pro-soft.gliwice.pl/cennik.html).
Do pobrania, aktualizacji oraz autoryzacji modułu wymagane jest połączenie z siecią.

Kupując więcej niż jedną licencję otrzymuje się upusty:
drugi i trzeci egzemplarz - 40%, czwarty i dalsze egzemplarze - 60%.

Zakupy w formie grupowej prowadzi firma [TINSERWIS](https://www.tinserwis.pl/),
gdzie można uzyskać maksymalnie 50% rabatu. Istnieje możliwość dzierżawy modułu razem
z programem **ABC Płyta**. W celu zakupu i dzierżawy prosimy o [kontakt](#kontakt).

```
Moduł podlega ochronie prawa autorskiego bez udzielania jakiejkolwiek gwarancji.
Jest sprzedawany jako narzędzie do wsparcia zarobkowego procesu projektowego.
Jest dostarczany "taki jaki jest" i nie ma gwarancji, że jest wolny od błędów pomimo
dołożenia wszelkich starań. Autor modułu nie ponosi odpowiedzialności za skutki powstałe
w wyniku nieumiejętnego posługiwania się oprogramowaniem, w tym związane z utratą
danych. Osoba kupująca dobrowolnie wyraża zgodę na powyższe warunki licencyjne oraz
na przetwarzanie swoich danych osobowych w celu obsługi zakupu licencji.
```

## Instalacja

Plik instalacyjny pobieramy w zależności od tego, jaki program **ABC** posiadamy na
kluczu USB.

Wybieramy jeden z poniższych linków, aby rozpocząć pobieranie:

- [Mam kilka programów **ABC** na kluczu USB](https://github.com/pkpkbud/mury/releases/download/0.2.0/Mury-ABC6-0.2.0-win32.msi)
- [Mam tylko **ABC Płyta** na kluczu USB](https://github.com/pkpkbud/mury/releases/download/0.2.0/Mury-ABC6p-0.2.0-win32.msi)

Moduł instalujemy w lokalizacji programu **ABC Płyta** w folderze *EXE*
(np. *C:\ABC6\EXE*).

Spis zmian oraz poprzednie wersje są dostępne w serwisie
[GitHub](https://github.com/pkpkbud/mury/releases).

## Wideo

<iframe width="560" height="315" src="https://www.youtube.com/embed/4C1No9RfA6Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Instrukcja

Podczas korzystania z modułu, można uzyskać wskazówki dotyczące danej funkcji po
najechaniu na opis kursorem myszy. Jednostki, w jakich podane są wartości są po
lewej stronie każdego pola. Wartości można zmieniać, wpisując na klawiaturze i
zatwierdzając klawiszem `Enter`, klikając na znaki `góra`-`dół` po prawej stronie
pola lub wciskając klawisze strzałek `↑`-`↓` na klawiaturze.

### Uruchomienie

Moduł można uruchomić samodzielnie w trybie kalkulatora. W tym celu należy uruchomić
skrót z pulpitu albo plik `sciana.exe` z lokalizacji instalacji (np. *C:\ABC6\EXE*).
Przy uruchamianiu można wybrać plik zadania z końcówką *.MUR* w celu wczytania wcześniej
zapisanych wyników. Przy zamykaniu można zapisać wyniki do pliku z końcówką *.MUR*.
Pierwsze uruchomienie należy wykonać z poziomu programu **ABC Płyta**.

W programie **ABC Płyta** dla podpór typu `Ściana` można zaprojektować ścianę murową.
W wynikach zadania w menu `Wymiar` dostępna jest opcja `Projektowanie ściany`.
W przypadku, gdy ta możliwość nie jest dostępna trzeba zaktualizować program
**ABC Płyta** do wersji 6.24, włączyć pełny zakres menu przyciskiem "M" lub wybrać
z menu opcję `Pokaż → Wybór wymiarowania`.

![image](https://github.com/pkpkbud/mury/assets/55211992/2ac5cf3e-1e1c-496f-bb2d-ea8a488f2fc2)

### Obciążenia

Po uruchomieniu pokaże się pytanie o obciążenia. W przypadku wariantu będzie można
zmienić mnożnik obciążenia, podpowiadany z opisu obciążeń przyjmowanych do obwiedni.
Obwiednia generalnie będzie obliczana jako `Automat EN`, chyba, że są zdefiniowane
własne kombinacje wg PN-EN, to wtedy będzie można je wybrać. Przycisk `Usuń` usuwa
wcześniej zadane miejsca.

![image](https://github.com/pkpkbud/mury/assets/55211992/dd0029d5-228f-4527-b12a-d4972d870869)

### Wybór miejsca

Po zatwierdzeniu obciążeń plansza zostanie zamknięta i pokaże się rysunek modelu.
Pojawią się podpory liniowe typu `Ściana`, należy wybrać dwa skrajne węzły
projektowanego miejsca.

### Usztywnienia

![image](https://github.com/pkpkbud/mury/assets/55211992/d6820d3e-6211-4e02-ac28-bbe952d335e3)

W oknie można wybrać dla każdego z węzłów czy jego krawędź pionowa jest `Podparta`
czy `Swobodna`. Wybór ten ma wpływ na wysokość efektywną ściany, wartości momentów
gnących (schemat statyczny belki w przypadku braku usztywnień lub płyty) oraz stan
graniczny użytkowalności (sprawdzenie ograniczenia wysokości i długości ściany
w zależności od jej grubości zgodnie z załącznikiem F normy *PN-EN 1996-1-1*).

### Projektowanie

![image](https://github.com/pkpkbud/mury/assets/55211992/3f6e9a11-43e2-4ecc-9b0f-1da854dc7517)

Po wprowadzeniu danych na pierwszej planszy można przyciskiem `OK` przejść do planszy
głównej modułu. Na niej przeprowadzane jest całe projektowanie. Składa się z opisanych
poniżej elementów.

**Ramki z danymi u góry**, gdzie podobnie jak na pierwszej planszy należy podać
wartości, tym razem dotyczące przyjętych założeń projektowych, materiałów, wymiarów
oraz obciążeń obliczeniowych. Opcja `Typowy` pozwala na wybór elementu murowego
z listy i automatyczne uzupełnienie parametrów elementu murowego oraz ciężaru.
`Opis` można dowolnie modyfikować, domyślnie wpisane są numery węzłów.
W celu policzenia ściany jako metrowego pasma należy odznaczyć opcję `Długość`.
Przycisk `Wiatr` otwiera okno, gdzie po wprowadzeniu danych dotyczących lokalizacji
oraz obiektu budowlanego, oddziaływanie wiatru według normy *PN-EN 1991-1-4*
zostaje wprowadzone jako obciążenie prostopadłe do powierzchni.
Jeżeli jest zadana długość ściany i nie ma zadanych usztywnień pionowych krawędzi,
możemy określić inne niż długość ściany pasmo zbierania obciążenia od wiatru.

![image](https://github.com/pkpkbud/mury/assets/55211992/e216c58e-a01b-46da-a9c1-68bf54de9eb4)

Po włączeniu opcji `Własne` wszystkie wartości obciążeń można dowolnie modyfikować
oraz można wybrać wariant z obwiedni sił. Przycisk `Zeruj` zeruje wszystkie obciążenia.
Ponowne wciśnięcie przywraca wartości przed zerowaniem. Wymiary ściany są pobierane
z opisu podpory lub są przyjmowane wartości domyślne.

![image](https://github.com/pkpkbud/mury/assets/55211992/66ef1b7e-589a-4f23-8f38-7a03d85e722b)

**Ramka z wynikami u dołu**, która aktualizuje się po zmianie wartości parametrów
lub po naciśnięciu przycisku `Oblicz`. Każda linijka zawiera opis sprawdzanego warunku,
wzór oraz stopień wytężenia podany w procentach. W przypadku, gdy któryś warunek nie
jest spełniony, kolor tekstu zmienia się na czerwony. Nie są również pokazywane
sprawdzenia wyników o zerowym wytężeniu. W przypadku wymiarowania na obwiednię sił,
na końcu każdego wzoru w nawiasie kwadratowym podany jest decydujący przypadek.
Po najechaniu na niego kursorem myszy wyświetlone zostaną wartości sił pobrane
z programu **ABC Płyta**. Nazwa przypadku oznacza wiodące obciążenie dla warunku.

Sprawdzane są następujące warunki nośności zgodnie z normą *PN-EN 1996-1-1*:
- Smukłość ściany murowej zgodnie z punktem 5.5.1.4.
- Ściana murowa niezbrojona obciążona głównie pionowo zgodnie z punktem 6.1.2
(obciążenia pionowe u góry, dołu lub w środku wysokości ściany).
- Ściana murowa niezbrojona obciążona prostopadle do swojej powierzchni zgodnie
z punktem 6.3.1 (zginanie równolegle lub prostopadle do spoin wspornych).

**Ramka przycisków po prawej** stronie zawierająca następujące funkcje: 
- Przycisk `Oblicz` aktualizuje część z wynikami dla zadanych wartości.
- Przycisk `Usztywnienia` otwiera ponownie wcześniej opisane okno
[Usztywnienia](#usztywnienia).
- Przycisk `Do schowka` kopiuje listę z notką obliczeniową do schowka. Po zamknięciu
modułu schowek zostaje wyczyszczony.
- Przycisk `Do Worda` otwiera nowy dokument zawierający notkę obliczeniową. Ponowne
naciśnięcie przycisku powoduje dopisanie wyników do otwartego dokumentu. W przypadku
posiadania innego pakietu niż *Microsoft Office*, jest tworzony i otwierany
nowy plik *Nazwa_zadania.MUR.DOCX* w lokalizacji zadania.
- Przycisk `Aktualizuj` sprawdza, czy jest uruchomiona aktualna wersja modułu oraz w
razie potrzeby umożliwia pobranie i aktualizację do najnowszej wersji. Plik instalacyjny
jest pobierany w tle, trzeba poczekać na jego pobranie. Następnie moduł jest wyłączany
i uruchamia się instalacja. Zaleca się zamknięcie programu **ABC Płyta** przed
instalacją.
- Przycisk `Zamknij` zapisuje wyniki i zamyka moduł, skąd można przejść do wyboru
kolejnego miejsca.
- Przełączanie opcji `Zawsze na wierzchu` powoduje przypięcie lub odpięcie modułu ponad
innymi oknami.
- Zaznaczenie opcji `Domyślne` powoduje, że po zamknięciu modułu bieżące ustawienia
zostają zapisane jako domyślne do wymiarowania kolejnych miejsc.

## Kontakt

Wszelkie sugestie i ewentualne błędy w programie można zgłaszać poprzez e-mail
lub serwis [GitHub](https://github.com/pkpkbud/mury/issues).

**PKPKBUD Paweł Kowalski Projektowanie Konstrukcji Budowlanych**\
NIP: 2220810920, REGON: 522155974

tel. 603 088 626\
e-mail: <pkpkbud@gmail.com>
