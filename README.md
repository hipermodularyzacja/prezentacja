
# prezentacja [prezentacja.hipermodularyzacja.pl](https://prezentacja.hipermodularyzacja.pl/)

### Informacje:

+ Temat: **Hipermodularyzacja** w praktyce hardware & software development

+ Opis: Na dzisiejszym spotkaniu omówimy, jak modułowa architektura i hipermodularność stanowią ważne koncepcje dla DevOps, twórców sprzętu i oprogramowania. 
Omówimy korzyści związane z decentralizacją, w tym elastyczność, skalowalność, łatwość w utrzymaniu, bezpieczeństwo, łatwość w rozwijaniu i lepszą dostępność systemu. 
Podyskutujemy o wpływie decentralizacji, modularyzacji i hipermodularyzacji na procesy doskonalenia sieci.

+ Keywords: Modularyzacja, hipermodularność, decentralizacja, elastyczność, skalowalność, reużywalność, konserwacja, odporność, dostosowywanie, kooperacja, zwinność, odporność, dostępność.

+ Czas: Czwartek, 11 maja 2023 17:00

+ Miejsce: Meetup, [Hipermodularyzacja w praktyce hardware & software development](https://www.meetup.com/pl-PL/devops-institute-skilup-poland/events/293100939/)

+ Prelegent: Tom Sapletta



### Plan:


#### Prezentacja
###### 1. Prelegent
###### 2. Cel prezentacji
###### 3. Problem - dlaczego?
###### 4. Zastosowanie - gdzie?

#### Hipermodularyzacja
###### 5. Geneza 
###### 6. Badanie - w jaki sposób?
###### 7. Korzyści z hipermodularności

####  Przykłady
###### 8. Co wie chatGPT?
###### 9. Galeria przykładów


####  Praktyka
###### 10. Jak hiperm odularyzować?
###### 11. Metoda hiper modularyzacji
###### 12. Przykład użycia

##### Dyskusja
 
*Każdy punkt jest obliczony na ok. 3 minuty


### Prezentacja w formie mapy myśli

![image](https://user-images.githubusercontent.com/5669657/237053890-9b67b4bc-f92a-4ff1-bb31-7d0ce2ff2426.png)

```mermaid
mindmap
  root((hiper modularyzacja))
    Prezentacja
      Prelegent<br>kto?      
      Cel prezentacji
        Problem<br>dlaczego?
        Zastosowanie<br>gdzie?      
        
    Modularyzacja
      Geneza      
      Badanie<br>w jaki sposób?      
      Korzyści z hipermodularności
      
    Przykłady
      Co wie chatGPT?
      Galeria przykładów                
      
    Praktyka
      Technika
      Jak hiper modularyzować?
      Przykład użycia                    
```



+ [Online FlowChart & Diagrams Editor](https://mermaid.live/edit#pako:eNpdUsFuwjAM_RUrJ5D4AjQNaZuEtAkJaZxQLyYxbWgaV2mqqkFcdtlH7DO47sb4r7VAy9ac7Gc_O372XkhWJKYi01ZlmEcWwDH70SjROTnIWJUGXR1Q7nA8bsMAS0eBrG-hK3CBDMUN-LBxj6nn2RXuws9kIO9ZuoNbHm8MZS1LGZSBYp7do2ssPBdcodXUpsQqaBqU7qzF3592wTlZCvif8ISqq1fBDlMNRc7F6bgZFH5jF-rzl9QQ4CLGTQvLLdhldYqEOj1_oKr7iRkqTSAT9PPlqp9pjoacxkaMG-F0rGDwhqUx9XXaj7QimVh9918xhcGuGsF-Pmf31dxaQXn-rqXGYT8xEVkzHWrV3MG-pUXCJ5RRJKaNaan0Dk0kIntoUrH0_F5bKaZbNAVNRJkr9PSiMXaY9WiOds1890lpz25xPTbJdqtjcfgFi97JiQ)


---

# 1. Prelegent

Kim jestem?

### Co robię?

+ [github](https://github.com/tom-sapletta-com)/tom-sapletta-com
   + ponad 200 projektów, kilka tysięcy repozytoriów z otwartymi źródłami
   
+ [linkedIn](https://www.linkedin.com/in/tom-sapletta-com/)/tom-sapletta-com 
  + [makerslab](http://discord.makerslab.pl) - społeczność, kooperacja
  + [softreck](http://www.softreck.pl) - opensource: dialogware 

### Role:

+ [entuzjasta](http://www.entuzjasta.pl) technologii, metodologii, socjologii, cybernetyki
+ Badacz, [researcher](http://www.researcher.pl)
+ Programista, DevOps, [platform engineer](http://www.platformengineer.pl)

### Tematy:

+ [modularyzacja](http://www.entuzjasta.pl)
+ [automatyzacja](http://www..pl)
+ [bezpieczeństwo](http://www..pl)

### Ślad węglowy:

+ do 2013 Polska
+ do 2023 Niemcy
+ ...


![image](https://user-images.githubusercontent.com/5669657/236694792-17bb2ba3-0236-4bbf-a58f-43312847a33b.png)
+ [Żródło: github/tom-sapletta-com - Tom Sapletta](https://github.com/tom-sapletta-com)








# 2. Cel prezentacji

![image](https://user-images.githubusercontent.com/5669657/236607475-39851935-19e4-4bf7-a1ac-9035587e0d4b.png)
[żródło: Film pt. Rejs, youtube](https://www.youtube.com/watch?v=ylfdoWEyYXQ)


### Temat

Temat Hipermodularyzacji jest niezależny od branży, interdyscyplinarny, mimo wszystko jest tak niszowy, że w Polsce tylko dwie osoby o tym napisały w ciągu ostatnich lat.
Wg Google w Polsce osoby, które poruszyły temat: hipermodularyzacja to Tomasz Jakut i ja. 
+ Czy wobec tego pisanie książki i tworzenie prezentacji o hipermodularyzacji jest pozbawione sensu? 


### Cel

Celem tej prezentacji jest przekazanie wiedzy na temat moich wieloletnich badań na temat hipermodularyzacji.
Dobrze udokumentowana wiedza, sprawdzona, powtarzalna jest lepszym podłożem do zwiększenia ilościowego całej sieci, zwielokrotnieniem jej wiązań oraz zmniejszenie kosztu utrzymania.
To oznacza, że jako ludzie stosujący modularne myślenie możemy zajmować się dziesiątkami, setkami projektów w ciągu roku i tysiącami w ciągu kilku lat.



### Korzyści

+ Posiadanie i zarządzanie tylko tym co jest nam niezbędne
+ Inwestowanie energi, czasu i środków tylko w to co jest nam niezbędne a nie w dedykowaną infrastrukturę
+ Eksperymentowanie, ciągłą edukację przez praktykę
+ Optymalizanie drogi dojścia do rezultatu, poprzez bazowanie na już wypracowanych rezultatach


### Dlaczego?

Dlaczego warto uczyć się i stosować hipermodularyzację?
Wielu z nas ceni sobie minimalizm, ale nie możemy go narzucić innym, starając się respektować to, że świat jest złożony.
Hipermodularyzacja pomaga utrzymać w porządku magazyn z tysiącami pudełek, które czy chcemy czy nie musimy umieć w odpowiednim momencie znaleźć, otworzyć i użyć.
Każda odnajdywalna i nazywalna rzecz w naszym meta świecie jest wartością, każda niepotrzebna, nienazywalna rzecz jest przeszkodą, tworzącą bałagan.

### Niezależność - wolność od ograniczeń

Bezludna wyspa:
+ Co zabierzesz ze sobą na bezludną wyspę?
Dlaczego czegoś nie zabierzesz?
Jakbyś mógł zabrać wszystko co możesz, gdybyś mógł wysłać posłańca, jakbyś mu przekazał, nie mogąc samemu tego przywieźć?
Każda rzecz, której nie zabierzesz ze sobą na bezludną wyspę, bo nie będzie tam mebli, nie ułatwi Tobie życiażycie Tobie i bliskim niezależnie od lokalizacji.


### Minimalizm

Minimalizm pozwala na higienę, skupiając się na tym co jest dla nas ważne.
W świecie rzeczy potrzebne są metody aranżacji przestrzeni, do nas potrzeb z minimalnym nakładaem energii.
Hipermodularyzacja pozwala na realizację potrzeb, do których przygotowujemy się długofalowo, ułatwiając przewartościowanie, poznanie każdego elementu, dostosowanie go pod nasze potrzeby.


### Edukacja

To wiąże się z ciągłą edukacją, hipermodularyzacja to proces wymagający czasu, pracy i cierpliwości. 
Jednak nauka i stosowanie tej umiejętności może przynieść wiele korzyści i poprawić jakość naszego życ

Celem badania hipermodularyzacji jest zwiększenie jakości systemów, wzmocnienie wiązań modułów i przez to ciągły wzrost struktury systemu i ekspansja.

![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/a03e04d9-58b4-4c10-9386-3cec61dfc52d)

```mermaid
flowchart LR
  B[ponowne użycie zasobów] --> C[oszczędność zasobów] --> D[lepsze zarządzanie]  
```




![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/d36f1871-72b2-4807-822e-a11330a0f302)


```mermaid
flowchart LR
  E[więcej wyspecjalizowanych modułów] --> F[szybsza reakcja na wyzwania] --> G[lepsza adaptacja i jakość]
```

### Zastosowanie

W stale zmieniającym się świecie przy dźwigni technologicznej trudno zajmować się wieloma aspektami rzeczywistości i zarządzać optymalnie posiadanymi zasobami oraz energią.
O dziwo w analogowym świecie (dla uproszczenia) sprzedaje się nam wizję binarną, dwubiegunową, jednak rzeczywistość oferuje więcej opcji:

W kontekście ograniczeń to minimalizm i maksymalizm.
Wypracowywanie wolnej przestrzeni można uzyskać poprzez redukcję lub poprzez zhierarchizowanie, ale wtedy na skutek nieprzemyślanej modularyzacji mogą przyjść podwyższone koszta zarządzania.

Umiejscowienie tego w kontekście naszego życia rodzinnego, zawodowego rodzi wyboru, które często są kompromisem i kwestią, którą pomaga rozstrzygnąć **hipermodularyzacja** to 
ograniczyć koszty energetyczne, finansowe, czasowe **w dłuższej perspektywie**



### Dla kogo

Hipermodularyzacja jest dla tych, którzy:
+ lubią eksperymentować i doświadczać,
+ lubią uczyć się w praktyce,
+ poszukują, są głodni lepszej jakości,
+ biorą odpowiedzialność za skutki aktualnych działań,
+ szukają długofalowych konstruktywnych rozwiązań,
+ budują organicznie


### Forma prezentacji

W prezentacji będę posługiwał się przykładami z różnych dziedziń, gdyż modularyzacja jest interdyscyplinarna.

Dla uproszczenia przekazu posługuję się przykładami, z życia wielu z nas, abyśmy mogli na koniec w dyskusji rozmawiać na temat łatwych do wyjaśnienia przykładów.



### Jak powstała ta prezentacja?

Ta prezentacja jest podsumowaniem wieloletnich prac badawaczych nad drogą dotarcia do automatyzacji.
Badałem specyfikę i naturę metod, które sprawdzają się w różnych branżach i zastosowaniach.

Wiele  z tych doświadczeń była o wiele trudniejsza i kosztowniejsza 20 lat temu, gdy dopiero starałem się adaptować świat do swoich potrzeb i możliwości.
Dziś jest to możliwe znacznie szybciej.



### Jakie książki polecam?

+ [Systems and Software Quality: The next step for industrialisation,  von Martin Wieczorek, Diederik Vos, Heinz Bons](https://www.amazon.de/Systems-Software-Quality-next-industrialisation/dp/3662514044)
+ [hipermodularyzacja -  w trakcie pisania](http://hipermodularyzacja.pl)



### Nagroda

Nagrodą będzie ebook, dla każdego uczestnika, książki, która bedzie dostępna za 6 miesięcy w Listopadzie 2023.
+ prosze o kontakt na linkedin









# 3. Problem - dlaczego?

### Bałagan

+ Bytu: polityka, środowisko, kultura
+ Pojęć: definicje, semantyka, 
+ Danych: format, interfejs, dostęp
+ Rzeczy: magazyn, forma, transport, wymiana
+ Narzędzi: sposób użycia, doświadczenie, re-użycie


![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/1aced43c-f61b-458d-aa63-742099cb4fdd)


```mermaid
mindmap
  root((Bałagan))
    Bytu
        polityka
        środowisko
        kultura
    Pojęć
        definicje
        semantyka
    Danych
        format
        interfejs
        dostęp
    Rzeczy
        magazyn
        forma
        transport
        wymiana
    Narzędzi
        sposób użycia
        doświadczenie
        re użycie      
```


### Forma i treść

![image](https://user-images.githubusercontent.com/5669657/236606256-ec0d72e5-8c50-4b4e-ab91-45c629c41f50.png)
[żródło: Film pt. Rejs, youtube](https://www.youtube.com/watch?v=ylfdoWEyYXQ)

„Nie mogę być jednocześnie twórcą i tworzywem” – mówił filozof (Andrzej Dobosz) w klasyku polskiego kina, w filmie „Rejs”.
Dotyczy to często każdego z nas na styku teorii i praktyki...

W praktyce życiowej kierujemy się wyborem:

+ mniejszego zła 
+ zasady pareto 

skupiając się na rezultacie angażujemy tylko część czas, energii i zasobów, aby zmaksymalizowac efektywność, elastyczność, reużycie

O ile rezultatem powyższych wyborów jest zaangażowanie jednorazowe o tyle w modularyzacji rezultatem ma być wielokrotne użycie - reużycie, pozostałe cechy są mniej istotne, ale towarzyszą temu procesowi.









# 4. Zastosowanie - gdzie?


+ Rozwój oprogramowania
+ Architektura
+ Infrastruktura
+ Projektowanie produktów
+ Zarządzanie projektami
+ Magazynowanie

![image](https://user-images.githubusercontent.com/5669657/236698180-57d81a58-cc26-44ce-99bd-a9d0acd002be.png)
+ [Źródło: SDU Robotics](https://www.sdu.dk/en/forskning/sdurobotics)


### Rozwój oprogramowania

W rozwoju oprogramowania modułowość jest często używana do tworzenia komponentów wielokrotnego użytku, które można łatwo zintegrować z różnymi aplikacjami. 
Z drugiej strony, hipermodularność jest często używana do rozbijania złożonych aplikacji na mniejsze, wyspecjalizowane mikroserwisy, które mogą być rozwijane i wdrażane niezależnie.


W systemach, gdzie tworzy się równolegle rozwiązania specjalizowane: technologia + marketplace


#### Architektura

+ Wzorce: Enterprise Integration Patterns
+ DSL: Jenkins, Camel, APIDSL 
+ Systemy, frameworki, biblioteki, klasy, funkcje
+ API, SDK, SCHEMA


#### Infrastruktura

+ hosting: cPanel, direct admin, plesk
+ docker, swarm, kubernetes
+ proxmox, openstack, 
+ SDR, O-RAN, 
+ Automaty, Roboty, Cyfrowe Bliźniaki, Digital Twin


### Projektowanie produktów

W projektowaniu produktów modularność jest często wykorzystywana do tworzenia produktów z wymiennymi częściami, które można łatwo wymienić lub uaktualnić. 
Z drugiej strony, hipermodularność jest często używana do tworzenia produktów z wysoce konfigurowalnymi funkcjami i opcjami.


### Zarządzanie projektami

W zarządzaniu projektami modułowość jest często wykorzystywana do rozbijania projektu na mniejsze, łatwe do zarządzania zadania, które można przypisać różnym członkom zespołu. 
Z drugiej strony, hipermodułowość jest często używana do tworzenia wysoce zwinnych i adaptowalnych przepływów pracy w projekcie, które mogą być łatwo dostosowane i skorygowane w oparciu o zmieniające się wymagania.


### Magazynowanie

Codzienne problemy są związane nie tylko z tworzeniem ale też zarządzaniem, które pozwala m.in. na zamianie dużego bałaganu w mniejsze lokalne bałagany
Kontekst powstania tego małego bałaganu pozwala na specjalizacje procesu uporządkowania.


Pokój dziecka:

+ ograniczona ilość miejsca
+ nieporządek
+ forma: meble, pojemniki, miejsca
+ tworzywo: zabawki, urządzenia, przedmioty


Porządek dziś, Porządek jutro

Jak tego dokonać, odpowiedź na koniec przentacji!


![image](https://user-images.githubusercontent.com/5669657/236608538-0e99b3fc-49e2-498e-9e6c-a6a5bf7ffffc.png)
+ źródło: [Jak zaprowadzić porządek w pokoju dziecka? » Brykacze.pl - blog. Wszystko o zabawkach.](http://blog.brykacze.pl/zaprowadzic-porzadek-pokoju-dziecka/rodzic/)








# 5. Geneza

+ Tło
+ Cel Hipermodularyzacji 
+ Różnice między Modularyzacją i Hipermodularyzacją
+ Architektura modułowa

![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/66553873-5a35-402e-8dac-87712167c839)

```mermaid
mindmap
  root((Bałagan))
    Tło    
    Cel
    Różnice   
    Architektura
```

Wprowadzenie do hipermodularyzacji 

+ Muzyka, [www/tekst.md](https://github.com/hipermodularyzacja/www/blob/main/tekst.md)

## Podsumowanie
1. Modularyzacja polega na tworzeniu sieci modułów, natomiast hipermodularyzacja polega na rozbijaniu istniejących modułów na mniejsze i bardziej wyspecjalizowane moduły.
2. Modularyzacja skupia się na zarządzaniu architekturą, natomiast hipermodularyzacja skupia się na samych modułach.
3. Modularyzacja ma na celu ułatwienie tworzenia lepszych systemów, przez tworzenie ustandaryzowanych i wyspecjalizowanych modułów.
4. Problemy związane z modularyzacją to głównie brak granic, które można odwzorować na klocki, czyli trudność w dopasowaniu rzeczywistości do wzorca.
5. Modularyzacja ma na celu zmienianie rzeczywistości poprzez zawężenie pola oddziaływania modularyzacji, tworzenie nowych modułów i wymianę tych istniejących.


## Tło

Automatyzacja wymusza modularyzację, standaryzację i specjalizację.

Droga do automatyzacji zaczyna się od modularyzacji, ponieważ, zanim będziemy wiedzieli jaki standard użyć, możemy wcześniej na podstawie minimalnych danych o cechach procesu poznać jaka jest jego specyfika i przez to przyporzadkować go do określonego zbioru.


### Cel Hipermodularyzacji

+ **Hipermodularyzacja** przenosi architekturę modułową na wyższy poziom.
+ Wykracza poza tradycyjne podejście modułowe i obejmuje podział systemu na mniejsze, bardziej wyspecjalizowane moduły.
+ **Hipermodularyzacja** zajmuje się nie tyle zarządzaniem architekturą, co skupieniem się na najmniejszych elementach, by projektować moduły, które będą ułatwiały tworzenie lepszych systemów.


### Różnice między Modularyzacją i Hipermodularyzacją


##### W prostych słowach:

+ **Modularyzacja** to budowanie systemu poprzez wykorzystanie gotowych modułów.
+ **Hipermodularyzacja** to rozbijanie istniejących modułów na mniejsze, by stworzyć więcej prostych, re-używalnych modułów.


##### Modularyzacja w budowaniu systemów

**Modularyzacja** zajmuje się tworzeniem sieci modułów, **Hiermodularyzacja** wchodzi istotę samych modułów, determinuje ich powstawanie, narzuca standardy.

Modularyzacja to tworzenie sieci modułów. (Ilościowe)

**Hipermodularyzacja** to tworzenie ustandaryzowanych i wyspecjalizowanych modułów. (Jakościowe)



### Architektura modułowa

Architektura modułowa odnosi się do projektowania systemu składającego się z niezależnych jednostek, które można łączyć w celu stworzenia większego i bardziej złożonego systemu.
Te niezależne jednostki nazywane są modułami i można je łatwo wymieniać lub modyfikować bez wpływu na cały system.

Modularyzacja jest metodyką skupia się na samym zarządzaniu (systemem, architekturą)
**Hipermodularyzacja** narzuza metodykę tworzenia nowych modułów




### Problemy związane z modularyzacją, jak rozeznać granice?
+ [156. Wrocław JUG - Problemy wynikające z modularyzacji. - Łukasz Szydło - YouTube](https://www.youtube.com/watch?v=JJXmgCx_wh0)


#### Odwzorowanie

W tej prezentacji przeznaczonej dla programistów można zaobserwować jak jest pojmowana modularyzacja w IT.
Częstą praktyką jest wykorzystywanie dostępnych i znanych programiście wzorców, dopasowwywanie rzeczywistości pod wrzozec.
Niestety taka praktyka w naturalny sposób prowadzi do tworzenia implementecji, kosztownych w utrzymaniu.

Można tę sytuację porównać do klocków, gdzie chcąc odwzorować obiekt, np pojazd, używamy tylko dostępnym klocków.




#### Kierunek oddziaływania modularyzacji na rzeczywistość

W modularyzacji gdy braknie klocków to dostarczamy nowe, lepiej dopasowane poprzez hipermodularyzację.

+ staramy się zmieniać rzeczywistość prowadząc zmiany w ograniczonym miejscu i czasie.
+ Staramy się zawężać pole oddziaływania modularyzacji na rzeczywistość prowadząc do uszlachetnienia tylko części w danej chwili
+ oddziałujemy tam gdzie jest to łatwiejsze, gdzie ingerencja nie jest znacząca, nie jest wymagany duży koszt

UWAGA
+ nie prowadzimy działań na całym systemie, gdyż interesuje nas elastyczność i sprężystość, odporność na wpływ z zewnątrz, chcemy uniknąć braku dostępu do zasobów
+ korzystamy z tego co mamy, nie zmieniamy połączeń, które prowadzą do ryzyka
















# 6. Badanie - w jaki sposób?

Jako badacz (researcher) poszukujący lepszych rozwiązań warto znać podstawowe zagadnienia, by podczas poszukiwań lepszych modułów w drodze hipermodularyzacji klarownie udokumentować rezultaty:

## Słownictwo 

+ Problem
+ Rozwiązanie
+ Hipoteza
+ Procedura
+ Proces
+ Technika
+ Dyrektywa
+ Metoda
+ Metodyka
+ Metodologia


[Badanie](badanie.md)

![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/ae0a7d54-91e6-4b83-a11a-2f2e3f74a46d)

```mermaid
mindmap
  root((Badanie))
    Problem
    Rozwiązanie
    Hipoteza
    Procedura
    Proces
    Technika
    Dyrektywa
    Metoda
    Metodyka
    Metodologia
```

![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/a9e20f0a-c478-473f-8825-34780278a9a1)


```mermaid
stateDiagram
     state Cel {        
        Problem --> Rozwiązanie        
    }
    state Hipoteza {        
        Stawianie --> Testowanie        
    }
    state Problem {        
        Hipoteza
    }
    state Technika {        
        Metoda --> Środowisko        
    }
    state Proces {
        Procedura        
    }
    state Dyrektywa {
        norma        
        zakaz
    }
    state Procedura {        
        Zadanie --> Czynność        
    }
    state Środowisko {
        Dyrektywa        
    }
    state Rozwiązanie {        
        Technika
    }
    state Metoda {
        Proces
    }
```












# 7. Korzyści z hipermodularności

## Podsumowanie

Modularyzacja to droga do solidnych, elastycznych i wydajnych systemów.
Modułowa architektura i hipermodularność to ważne koncepcje dla DevOps, twórców sprzętu i oprogramowania, które oferują wiele korzyści w zakresie elastyczności, skalowalności, reużywalności, konserwacji, odporności, dostosowywania i współpracy. Decentralizacja może przynieść wiele korzyści, w tym elastyczność, skalowalność, łatwość w utrzymaniu, bezpieczeństwo, łatwość w rozwijaniu i lepszą dostępność systemu.


### Korzyści:

Korzyści systemu opartego o hipermodularne elementy łączy te wszystkie korzyści jednocześnie:

+ Zwinność, Agility
+ Odporność, Resilience
+ Dostosowalność, Customization
+ Kooperacja
+ Elastyczność, Flexibility
+ Skalowalność, Scalability
+ Reużywalność, Reusability
+ Konserwacja
+ Decentralizacja
 


![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/3b9c36e8-2a01-4384-a37a-d77b27647236)

```mermaid
mindmap
  root((Badanie))
    Zwinność
    Odporność
    Dostosowywanie
    Współpraca
    Elastyczność    
    Skalowalność
    Reużywalność    
    Konserwacja
    Decentralizacja    
```



#### Zwinność
Hipermodularność pozwala na szybki rozwój i wdrażanie nowych funkcji i usług. Deweloperzy mogą pracować nad poszczególnymi modułami bez wpływu na cały system, co pozwala na szybszą iterację i dostarczanie.


#### Odporność

Systemy hipermodularne są bardziej odporne na awarie. Jeśli jeden moduł ulegnie awarii, można go łatwo wymienić na zapasowy lub nowy moduł, bez wpływu na resztę systemu.


#### Dostosowywanie

Hipermodularność pozwala na większą personalizację systemu. Moduły można dodawać, usuwać lub wymieniać, aby spełnić określone wymagania lub potrzeby biznesowe.


#### Kooperacja

Moduły mogą być tworzone i wdrażane osobno, a następnie łatwo wprowadzane do głównego systemu. 
Moduły można łatwo rozpowszechniać i udostępniać innym użytkownikom, co pozwala na bezproblemową współpracę, wymianę i wspólną pracę nad aplikacją. 
Hipermodularność zachęca do współpracy między programistami. Różne zespoły mogą pracować nad różnymi modułami, co ułatwia zarządzanie procesem rozwoju.


#### Elastyczność

Modułowa architektura pozwala na łatwą modyfikację i dostosowanie systemu. Dodawanie nowych funkcji, aktualizacja komponentów i naprawianie błędów może odbywać się bez zakłócania pracy całego systemu.


#### Skalowalność

Modułowa architektura wspiera skalowalność.
Pozwala na dodawanie nowych modułów do systemu, czyniąc go zdolnym do obsługi zwiększonego obciążenia.


#### Reużywalność

+ ile z zasobów, które mamy, możemy ponownie użyć?
+ Co w przypadku potrzeby naprawy, czy musimy wymieniać całość?
Możliwość ponownego użycia, Moduły mogą być używane w różnych systemach lub aplikacjach, oszczędzając czas i zasoby w procesie rozwoju.


#### Konserwacja

Modułowa architektura upraszcza konserwację.
System można łatwo konserwować, wymieniając lub aktualizując moduł, którego dotyczy problem, bez wpływu na cały system.


#### Decentralizacja

Decentralizacja zwiększa modułowość aplikacji, co oznacza, że można je łatwiej dostosować do potrzeb i zadań. 
Decentralizacja także wpływa na bezpieczeństwo systemu, ponieważ moduły są oddzielone i izolowane, dzięki czemu zagrożenia są ograniczone do jednostkowych modułów.






## Decentralizacja a Modularyzacja
+ Czy decentralizacja jest zawsze modularna?
+ Co jeśli decentrazliacja nie jest przeprowadzona w modularny sposób?
+ Jak przebiega doskonalenie sieci zdecentralizowanej?
Decentralizacja w kontekście modularyzacji przynosi wiele korzyści, w tym większą elastyczność, skalowalność, łatwość w utrzymaniu, bezpieczeństwo, łatwość w rozwijaniu i lepszą dostępność systemu.

+ Elastyczność
+ Skalowalność
+ Łatwość w utrzymaniu
+ Bezpieczeństwo
+ Łatwość w rozwijaniu
+ Dostępność

![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/5d6dd301-3486-431b-bb5c-880b5212a381)


```mermaid
mindmap
  root((Decentralizacja))    
    Elastyczność
    Skalowalność
    Łatwość w utrzymaniu
    Bezpieczeństwo
    Łatwość w rozwijaniu
    Dostępność
```

Decentralizacja może przynieść wiele korzyści w kontekście modularyzacji, w tym:

### Elastyczność: 
Decentralizacja umożliwia łatwe dodawanie lub usuwanie modułów bez wpływu na cały system. Każdy moduł może działać niezależnie, co daje większą elastyczność w zarządzaniu projektem.


### Skalowalność: 
Modułowa architektura ułatwia skalowanie systemu. Dzięki temu możemy łatwo rozbudować system o dodatkowe moduły, gdy jest to potrzebne.


### Łatwość w utrzymaniu: 
W przypadku awarii lub problemów z jednym modułem, łatwo można go wyłączyć i naprawić. Nie ma potrzeby zatrzymywania całego systemu.


### Bezpieczeństwo: 
Decentralizacja może zwiększyć bezpieczeństwo systemu, ponieważ każdy moduł jest odpowiedzialny tylko za swoją własną funkcjonalność. W przypadku ataku lub naruszenia bezpieczeństwa jednego modułu, reszta systemu będzie nadal działać.


### Łatwość w rozwijaniu: 
Decentralizacja ułatwia rozwijanie systemu poprzez dodawanie nowych modułów. Każdy moduł może być rozwijany przez różnych programistów, co przyspiesza proces rozwoju.


### Dostępność: 
Decentralizacja umożliwia lepszą dostępność systemu. Jeśli jeden moduł przestanie działać, pozostałe moduły będą nadal dostępne dla użytkowników.










# 8. Co wie chatGPT?

Zadawanie właściwych pytań 

Właściwe zadawanie pytań jest konieczne do poznania prawdy na temat, który nas interesuje,
zwłaszcza w kontekście ostatniego roku dostępności sztucznej inteligencji do masowego użycia. 
Część tej prezentacji (teoretyczna) powstała w ostatnim tygodniu, przy pomocy chatGPT 3.5, właśnie dzięki zadawaniu odpowiednich pytań


+ Modularity and hypermodularity in the daily routine of a person working with people
+ Modularity and hypermodularity in preparing a presentation
+ Examples of usage between modularity and hypermodularity
+ How to learn the Modular thinking approach?
+ How to learn the hypermodular thinking approach?
+ How to live in hyper modular world, how to manage the all modular elements?



## Modularity and hypermodularity in the daily routine of a person working with people

#### Modularity:

+ A personal trainer who uses modular programming to create tailored workout plans for each client, based on their individual fitness goals and abilities.

+ A teacher who uses modular lesson plans to create customized learning experiences for each student, based on their individual learning style and level of understanding.

+ A therapist who uses modular therapy techniques to create personalized treatment plans for each client, based on their individual needs and goals.

#### Hypermodularity:

+ A life coach who uses hypermodularity to break down the coaching process into smaller, specialized components such as goal setting, time management, and personal development, allowing for greater flexibility and customization.

+ A social worker who uses hypermodularity to break down the case management process into smaller, specialized components such as housing, education, and healthcare, allowing for greater collaboration and coordination with other service providers.

+ A mentor who uses hypermodularity to break down the mentoring process into smaller, specialized components such as career development, skill building, and personal growth, allowing for greater customization and scalability.



## Modularity and hypermodularity in preparing a presentation

#### Modularity:

+ A presenter who uses modular slide templates to create a consistent visual style throughout the presentation, including headers, bullet points, and images.

+ A presenter who uses modular content modules to create a presentation with customized information for each audience, including data, graphics, and case studies.

+ A presenter who uses modular presentation software to create a presentation that can be easily customized and reused for multiple presentations, including themes, layouts, and transitions.

#### Hypermodularity:

+ A presenter who uses hypermodularity to break down the presentation into smaller, specialized components such as introduction, main points, and conclusion, allowing for greater flexibility in adjusting the order or adding/removing components.

+ A presenter who uses hypermodularity to break down the presentation into smaller, specialized content modules such as videos, animations, and interactive elements, allowing for greater customization and engagement.

+ A presenter who uses hypermodularity to break down the presentation into smaller, specialized versions for different audiences, allowing for greater customization of the content and delivery style based on the audience's needs and preferences.



## How to learn the Modular thinking approach?

Modular thinking is a way of approaching problems by breaking them down into smaller, more manageable pieces. Here are some steps you can take to learn modular thinking:

#### Start with small problems: 
Begin by breaking down small problems into smaller, more manageable pieces. This will help you develop your modular thinking skills and build confidence.

#### Identify the components: 
Once you have identified the problem, start identifying the different components or modules that make up the problem. Try to understand how these components work together to create the problem.

#### Define the interfaces: 
Next, define the interfaces between the different components. This will help you understand how the different modules interact with each other.

#### Develop a modular design: 
Once you have identified the components and interfaces, start developing a modular design. This should include how the different modules will work together to solve the problem.

#### Test and iterate: 
Test your modular design to see if it solves the problem. If it does not, iterate and refine your design until you find a solution that works.

#### Practice, practice, practice: 
Keep practicing modular thinking by breaking down larger problems into smaller, more manageable pieces. This will help you build your skills and become more comfortable with the approach.

#### Learn from others: 
Seek out resources, books, and mentors who can help you learn more about modular thinking. You can also learn from others by studying their designs and solutions.

By following these steps, you can develop your modular thinking skills and become better equipped to tackle complex problems in a more efficient and effective way.


#### How to learn the hypermodular thinking approach?

Hypermodular thinking is an advanced approach to problem-solving that involves breaking down complex systems or problems into smaller, highly specialized components or microservices. Here are some steps you can take to learn hypermodular thinking approach:

#### Understand modularity: 
Before you can understand hypermodularity, it's important to understand modularity. Learn about modular design principles, practices, and tools.

#### Study hypermodular systems: 
Study and analyze existing hypermodular systems, such as microservices architecture or modular product design. This will help you understand how different modules can work together to create a more flexible and scalable system.

#### Learn to break down problems: 
Develop your ability to break down complex problems into smaller, more specialized components. This requires a deep understanding of the problem and the ability to identify the different components of the problem.

#### Focus on interfaces: 
In hypermodularity, interfaces between different components are critical. Learn how to design effective interfaces that allow modules to work together seamlessly.

#### Develop a modular mindset: 
Hypermodular thinking requires a mindset that is focused on breaking down problems into smaller pieces. Practice this mindset by breaking down problems in your daily life, such as organizing your workday or planning a trip.

#### Experiment with hypermodularity:
Start experimenting with hypermodular design in your own work. Start with small projects and build your way up. This will help you gain experience and build your skills.

#### Learn from others: 
Seek out resources, books, and mentors who can help you learn more about hypermodular thinking. You can also learn from others by studying their designs and solutions.

By following these steps, you can develop your hypermodular thinking skills and become better equipped to tackle complex problems in a more flexible and scalable way. Remember to start small, focus on interfaces, and keep experimenting to build your skills.











# 9. Galeria przykładów

Galeria Przykładów **hipermodularyzacji**

+ Oprogramowanie, Software
+ Sprzęt, Hardware
+ Przeprowadzka
+ Magazynowanie


![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/0992ee1e-9d98-4b10-ad65-5dcae5497cd8)


```mermaid
mindmap
  root((Przykłady))    
    Software
    Hardware
    Przeprowadzka
    Magazynowanie
```


#### Oprogramowanie:

Moje projekty:
+ Dialogware: text2software - zmodularyzowane budowanie aplikacji
+ Metamoduły bazujące na tym:  [docs.metamodule.org](https://docs.metamodule.org/)




### architektura modularna i monolityczna

+ [Modularyzacja: kolejny modny trend IT, czy jedyna słuszna droga? - Tech Blog ING Bank Śląski](https://techblog.ing.pl/blog/modularyzacja-kolejny-modny-trend-it-czy-jedyna-sluszna-droga)


systemy do pakowania przedmiotów
systemy układania 






### Przeprowadzka:

+ oddziaływanie forma <-> treść

przenosimy w kartonach wszystkie rzeczy i nie mając starych mebli albo tylko część dodajemy nowe.
Mamy możliwość poukładania wszystkich rzeczy w zależnośći od przeznaczenia lub/oraz właściciela:

Tam gdzie jest własność wspólna, np. ręczniki, określamy miejsce w przestrzeni dostępne dla każdego
Tam gdzie jest własność prywatna, odzież codzienna, określamy pokoje, które są używane przez konkretne osoby.
Tam gdzie jest własność prywatna, ale używana w przestrzeni wspólnej, np buty, parasolki określamy ograniczone miejsce wspólne, korytarz.

Stosowanie hipermodularyzacji pozwala na ułatwienie wielu procesów, związanych z umeblowaniem, re-nżacją, zmianą przeznaczenia.



### Magazynowanie

Modularne, mobilne skrzynki z materiałami do pracy

+ Regał ivar z firmy ikea
+ Systemowe skrzynki macpac firmy makita
![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/0d2fd0d6-3cbb-4a94-97c4-0c3226ce052a)

+ możliwość szybiego i łatwego transportu oraz korzystania z zawartości w terenie
![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/541cb8f0-4b20-420c-b8a5-4cce2f68ad80)




### Modularny hardware

[Mobilna serwerownia – militarity](https://militarity.com/index.php/2023/04/18/mobilna-serwerownia/)

##### Dlaczego?
+ minipc - niski koszt w porównaniu do dedykowanych serwerów i podzespołów
+ systemowe skrzynki - uniwersalność w porówaniu do dedykowanych rozwiązań
+ mobilna infrastruktura - łatwość dostosowania

![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/be33655e-45eb-4dcb-aae5-d460de742d38)


##### Jedna warstwa zawiera:
+ switch sieci lokalnej
+ 3 x minipc do wirtualizacji i programowania
+ przegrodę z aktywnym chłodzeniem
+ listwę zasilającą

![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/2fa7d7a4-9d26-4b56-ba4e-9378302faffb)












# 10. Jak (hiper)modularyzować?



## Metodyka w IT

Życie w hiper-modułowym świecie oznacza, że nieustannie otacza nas coraz większa liczba wyspecjalizowanych modułów, które są ze sobą połączone, tworząc złożone systemy. 
Oto kilka sposobów zarządzania wszystkimi modułowymi elementami w hipermodułowym świecie:


#### Rozwijaj modułowy sposób myślenia

Rozbijaj złożone problemy na mniejsze, łatwiejsze i bardziej ekonomiczne w zarządzaniu elementy.
Pomoże Ci to zrozumieć i zarządzać połączonymi ze sobą modułami systemu.

#### Zapoznaj się z interfejsami

W hiper-modułowym świecie ważne jest, aby zrozumieć, w jaki sposób różne moduły wchodzą ze sobą w interakcję.
Dowiedz się o różnych typach interfejsów, takich jak interfejsy API lub protokoły, oraz o tym, jak działają.


#### Korzystaj z narzędzi modułowych

Używaj narzędzi modułowych do zarządzania różnymi modułami systemu.
Obejmuje to narzędzia do kontroli wersji, testowania i wdrażania.


#### Ćwicz projektowanie modułowe

Korzystaj z zasad projektowania modułowego, aby tworzyć elastyczne i skalowalne systemy.
Oznacza to podzielenie systemów na mniejsze, wyspecjalizowane moduły, które można łatwo wymienić lub zaktualizować.


#### Współpracuj z innymi

Współpraca jest kluczem w hiper-modułowym świecie.
Współpracuj z innymi, aby dzielić się wiedzą i doświadczeniem w zarządzaniu różnymi modułami systemu.


#### Nieustannie się ucz

Hipermodułowy świat nieustannie ewoluuje.
Stale poznawaj nowe technologie i techniki zarządzania systemami modułowymi.



#### Różnicowanie

porównuj i wyciągaj wnioski z różnic
działa w dwóch obszarach na tych samych narzędziach i formach
testuj stale monitorując sposób oddziaływania 



#### Przechodzenie pomiędzy poziomami

Wchodzenie z poziomu treści na formę a nie pozostanie w jednym obszarze
1. zmiana treści
2. zmiana formy
3. zmiana treści


Przyjmując modułowy sposób myślenia, rozumiejąc interfejsy, używając modułowych narzędzi, ćwicząc modułowe projektowanie, współpracując z innymi i stale się ucząc, możesz skutecznie zarządzać wszystkimi modułowymi elementami w hipermodułowym świecie.








# 11. Metoda hipermodularyzacji


```
Sieć
 Ogranicz
 Ulepsz
 Powiel

Gałąź
 Identyfikuj
 Dziel
 Łącz
  
Moduł
 Projektuj
 Buduj
 Testuj
 Integruj
```
 


![image](https://github.com/hipermodularyzacja/prezentacja/assets/5669657/fa537680-61db-46fd-881e-d42af998bbf6)

```mermaid
stateDiagram    
    [*] --> Sieć
   
    Rozdziel --> Gałąź   
    Sieć --> Rozdziel
    
    Gałąź --> Powiel
    Powiel --> Sieć
        
    Gałąź --> Dodaj
    Dodaj --> Moduł

    Re_użyj --> Gałąź
    Moduł --> Re_użyj
                    
    Dane --> Wyodrębnij
    Wyodrębnij --> Moduł

    Moduł --> klasyfikuj
    klasyfikuj --> Dane


    state Sieć {
        [*] --> Optymalizacja
        Optymalizacja --> Monitorowanie
        Monitorowanie --> [*]
    }

    state Gałąź {
        [*] --> Identyfikacja
        Identyfikacja --> Rekonfiguracja   
        Rekonfiguracja --> [*]
    }

    state Moduł {
        [*] --> Standaryzowanie
        Standaryzowanie --> Specjalizowanie
        Specjalizowanie --> [*]        
    }

    state Dane {
        [*] --> [*]
    }     
```


+ Jak budować system w oparciu o hiper-modularne komponenty?
+ Jakie są zasady projektowania hiper-modularnego?

Budowanie komponentów przy użyciu hipermodularnych zasad projektowania oznacza rozbijanie komponentów na mniejsze, wyspecjalizowane komponenty, które można łatwo wymienić lub zaktualizować.
 
+ Jak przekształcać procesy w hiper-modularne komponenty?

Pamiętaj, aby skupić się na specjalizacji, reużyciu i współpracy łączonych hiper-modułów.
Dzięki temu całą sieć hipermodułów można dostosować do zmieniających się potrzeb.

## Podsumowanie


1. Buduj systemy w oparciu o hipermodularne komponenty.
2. Rozbij złożone problemy na mniejsze, łatwiejsze i bardziej ekonomiczne w zarządzaniu elementy.
3. Zdefiniuj interfejsy między różnymi modułami.
4. Zaprojektuj moduły tak, aby były wysoce wyspecjalizowane i elastyczne.
5. Zbuduj komponenty, korzystając z hipermodułowych zasad projektowania.
6. Przetestuj komponenty, aby upewnić się, że działają efektywnie.
7. Zintegruj komponenty z powrotem w cały proces.
8. Korzystaj z narzędzi modułowych do zarządzania różnymi modułami systemu.
9. Korzystaj z zasad projektowania modułowego, aby tworzyć elastyczne i skalowalne systemy.
10. Współpracuj z innymi, aby dzielić się wiedzą i doświadczeniem w zarządzaniu różnymi modułami systemu.
11. Stale poznawaj nowe technologie i techniki zarządzania systemami modułowymi.
12. Porównuj i wyciągaj wnioski z różnic działa w dwóch obszarach na tych samych narzędziach i formach testuj stale monitorując sposób oddziaływania.


## Sieć

+ Optymalizacja
+ Monitorowanie

+ Ograniczaj -> Ulepszaj -> Powielaj

```
Sieć
 Ograniczaj
 Ulepszaj
 Powielaj
```

```mermaid
stateDiagram
    [*] --> Ogranicz
    Ogranicz --> Ulepsz
    Ulepsz --> Powiel    
    Powiel --> [*]
```


#### Ograniczaj

Określ kontekst w którym chcesz usprawnić system połączeń, lub chcesz dopiero go zaimplementować.
W modularyzacji staramy się  ograniczać pole widzenia, analizy i działania, aby ograniczyć jej koszty.
Prześledć gdzie jest największy ruch w sieci połączeń organizacji, gdzie korzyści z modularyzacji mogą przynieść najwięcej korzyści, gdzie specjalizacja czyli podniesienie jakości będzie docenione?
**Na przykład** Przy obsłudze klienta są dwa przypadki dzwoniących, reklamacje i zapytania ofertowe, odbierającym może być być sekretarka, która krok po kroku poprowadzi dzwoniącego a następnie bot, ta sama implementacja może dotyczcyć chatbota na stronie www lub wiadomości email, ale najpierw trzeba ograniczyć ją do telefonujących.



#### Ulepszaj:

Stale ulepszaj proces, monitorując jego wydajność i dokonując niezbędnych korekt.
**Na przykład** monitoruj średni czas połączeń dla modułu odbierania połączeń i dostosuj skrypty połączeń, aby poprawić wydajność.

Postępując zgodnie z tymi krokami, osoba nietechniczna może budować komponenty przy użyciu zasad projektowania hipermodułowego, co może prowadzić do bardziej wydajnego i efektywnego procesu.



#### Powielaj

Jeśli zmiana przynosi dobre rezultaty powiel je również w innym środowisku, by poprzez porównanie edukować się
+ Tworzenie kilku na raz
+ Porównanie modułów





## Galąź (Proces)


+ Identyfikacja
+ Rekonfiguracja

+ Identyfikuj -> Dziel -> Łącz



```
Gałąź
 Identyfikuj
 Dziel
 Łącz
```

```mermaid
stateDiagram
  [*] --> Identyfikuj
  Identyfikuj --> Dziel
  Dziel --> Łącz    
  Łącz --> [*]
```




#### Identyfikuj:

Zacznij od zidentyfikowania procesu, który chcesz przekształcić w komponenty hipermodułowe. 
Może to być dowolny proces, taki jak proces produkcyjny, proces obsługi klienta lub proces zarządzania projektem.


#### Dziel:

Podziel proces na mniejsze komponenty lub moduły.
Każdy moduł powinien być wysoce wyspecjalizowany i skoncentrowany na jednym konkretnym zadaniu.
**Na przykład** proces obsługi klienta można podzielić na mniejsze moduły, takie jak odbieranie połączeń, odpowiadanie na e-maile i rozpatrywanie reklamacji.


#### Łącz:

Zdefiniuj interfejsy między różnymi modułami.
Pomoże Ci to zrozumieć, w jaki sposób poszczególne moduły współdziałają ze sobą.
**Na przykład** interfejsem pomiędzy modułem odbierania połączeń a modułem odpowiadania na e-maile może być baza danych klientów.





## Moduł (Hipermodularyzacja)

+ Projektuj -> Buduj -> Testuj -> Integruj



```
Moduł
 Projektuj
 Buduj
 Testuj
 Integruj
```

```mermaid
stateDiagram
    [*] --> Buduj
    Buduj --> Testuj    
    Testuj --> [*]
```


#### Projektuj:

Zaprojektuj moduł tak, aby był wysoce wyspecjalizowany i elastyczny.
Umożliwi to łatwą wymianę lub aktualizację w miarę rozwoju procesu.
**Na przykład** moduł odbierania połączeń może być zaprojektowany do obsługi różnych typów połączeń, takich jak połączenia sprzedażowe, połączenia wsparcia i połączenia rozliczeniowe.


#### Buduj:

Zbuduj komponenty, korzystając z hipermodułowych zasad projektowania.
Oznacza to podzielenie komponentów na mniejsze, wyspecjalizowane komponenty, które można łatwo wymienić lub zaktualizować.
**Na przykład** moduł odbierania połączeń można podzielić na mniejsze elementy, takie jak skrypty rozmów, często zadawane pytania i formularze informacyjne dla klientów.


#### Testuj:

Przetestuj komponenty, aby upewnić się, że działają efektywnie.
Powtarzaj i udoskonalaj projekt, aż znajdziesz rozwiązanie, które działa.
**Na przykład** przetestuj skrypty połączeń, aby upewnić się, że są skuteczne w obsłudze różnych typów połączeń.


#### Integruj:

Zintegruj komponenty z powrotem w cały proces.
Upewnij się, że interfejsy między różnymi modułami działają skutecznie.
**Na przykład** upewnij się, że formularze z informacjami o klientach są prawidłowo przesyłane do modułu odpowiadania na wiadomości e-mail.






















# 12. Przykład użycia


### Programowanie
Sieć: infrastruktura, Architektura, DevOps
Gałąź: biblioteka, aplikacja 
Moduł: klasa, program, funkcja
Dane: formaty danych json, html, txt


### Edycja tekstu

+ zamiast kasowania przenoszenie do innego folderu/projektu
+ zamiast tworzeni długich tekstów, krótkie notki w plikach z załączeniem do innych projektów

[flatedit.com](https://www.flatedit.com/)



### Pokój dziecka:


#### Etap 1

+ jeśli zabawki będą schowane do szafek, szuflad czy skrzynek to zawsze będzie to wyglądało na porządek.
+  chodziło jedynie o wrzucenie zabawek do pudełek. Oczywiście to nie jest tak, że dzięki temu w pokojach dzieci panuje idealny porządek, ale jest im po prostu łatwiej go utrzymać, a ja jak wchodzę, to nie widzę tego, że w pudełku z klockami są też samochody, więc się tym nie denerwuję :)
+ pojemnik na zabawki w salonie. Dziecku będzie łatwiej po skończonej zabawie w salonie wrzucić zabawki do jednego pudła, a nie odnosić po kolei do swojego pokoju. 
+ Oczywiście te zabawki będą sobie rotowały między pokojem dziecka a pokojem dziennym, ale rodzice będą musieli raz na jakiś czas zorganizować przegląd pudełka w salonie i poprosić dziecko o przeniesienie części zabawek z powrotem do salonu. 

[Jak utrzymać porządek w pokoju dziecka? - Mamy Gadżety](https://mamygadzety.pl/porzadek-pokoju-dziecka/)

![image](https://user-images.githubusercontent.com/5669657/236608428-2e022a4b-224d-4c66-9d33-25efb200f8df.png)



#### Etap 2


##### rozmiary:
duże - wszystko w jednym,
dedykowane 1:1

##### forma: 
ogólne,
dedykowane,

#### kolory
dopasowane do koloru przedmiotów,
transparentne

##### ograniczenia zasobów
różne pokoje


![image](https://user-images.githubusercontent.com/5669657/236608605-8405fca3-2ff3-4af9-b76b-3099f1f0817b.png)

+ źródło: [Jak zaprowadzić porządek w pokoju dziecka? » Brykacze.pl - blog. Wszystko o zabawkach.](http://blog.brykacze.pl/zaprowadzic-porzadek-pokoju-dziecka/rodzic/)


#### Etap 3


+ Małe, transparentne pudełka, 
+ Duży niekontrolowany bałagan przeniesiony do małego kontrolowanego pudełka,
+ Bezpieczny i łatwy transport przez dziecko
+ Możliwość zarządzania zawartością na kolejnych etapach.
+ Duże obiekty i już zapakowane mogą być układane obok siebie, nie ma potrzeby pakowania wszystkiego do dedykowanych większych skrzyni, gdyż to utrudnia dostępność i zarządzanie


Proza codzienności:

![image](https://user-images.githubusercontent.com/5669657/236609574-ebc44829-ff78-44f4-81e8-e988379276be.png)

Transparentne pojemniki:

![image](https://user-images.githubusercontent.com/5669657/236608899-70078ba3-2ab5-4e73-81cd-2d2403df9d28.png)


Wnioski:
+ Zmniejszenie barier, ciężaru, dopasowanie do wzrostu i możliwości operatora
+ Wyłączenie szuflad, dużych kartonów i szafek
+ otwarte, transparentne przestrzenie ułatwiają dotarcie i odłożnie przedmiotu


----




### koniec:
klask, klask, klask
![image](https://user-images.githubusercontent.com/5669657/236607603-e6a4a61c-8381-4bca-bb6f-bf5c066b6667.png)
















# Dyskusja [15 Minut]

Co na to jury?
![image](https://user-images.githubusercontent.com/5669657/236607373-38586979-bf9e-4dd3-997c-3379ca95cdb1.png)



+ pytania
+ rozwiązania
+ doświadczenia











---

## Narzędzia

+ [GitHub](https://github.com/)
+ [Include diagrams in your Markdown files with Mermaid - The GitHub Blog](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)
+ [WebStorm: The Smartest JavaScript IDE, by JetBrains](https://www.jetbrains.com/webstorm/)


## Źródła


+ [Modularyzacja przy wytwarzaniu oprogramowania](https://www.hipermodularyzacja.pl/)

+ Polskie wydanie, Wersja Polska: HiperModularyzacja.pl [książka: Hiper Modularyzacja](https://book.hipermodularyzacja.pl/)

+ Polskie wydanie, Wersja Polska: HiperModularyzacja.pl [Blog: blog.HiperModularyzacja.pl](https://blog.hipermodularyzacja.pl/)

+ W trakcie jest też wersja angielska: HyperModularity.com  [www. Hyper Modularity .com](http://www.hypermodularity.com/)

+ [muzyka: Hiper Modularyzacja](https://www.hipermodularyzacja.pl/tekst.html)

+ Artykuł [Hipermodularyzacja, czyli Rzym płonie](https://blog.comandeer.pl/hipermodularyzacja-czyli-rzym-plonie.html)

+ Metamoduły bazujące na tym:  [docs.metamodule.org](https://docs.metamodule.org/)

+ [Systems and Software Quality: The next step for industrialisation,  von Martin Wieczorek, Diederik Vos, Heinz Bons](https://www.amazon.de/Systems-Software-Quality-next-industrialisation/dp/3662514044)

+ [Modularyzacja: kolejny modny trend IT, czy jedyna słuszna droga? - Tech Blog ING Bank Śląski](https://techblog.ing.pl/blog/modularyzacja-kolejny-modny-trend-it-czy-jedyna-sluszna-droga)

+ [Uniwersalnego słownika języka polskiego](https://sjp.pwn.pl/poradnia/haslo/metoda-metodyka-metodologia;7632.html)

+ [programowanie deklaratywne i imperatywne](https://codenga.pl/artykuly/poradniki/programowanie-imperatywne-oraz-deklaratywne)

+ [Programowanie deklaratywne – Wikipedia, wolna encyklopedia](https://pl.wikipedia.org/wiki/Programowanie_deklaratywne)

+ [IMMUSEC Metodologia, metodyka, metoda, sposób, procedura – wyjaśnienie zawiłości językowych](https://www.immusec.com/metodologia-metodyka-metoda-sposob-procedura-wyjasnienie-zawilosci-jezykowych/)

+ [Metodologia – Słownik języka polskiego](http://sjp.pwn.pl/slownik/2567697/metodologia)

+ [Metodyka – Słownik języka polskiego](http://sjp.pwn.pl/slownik/2567700/metodyka)

+ [Metoda – Słownik języka polskiego](http://sjp.pwn.pl/slownik/2482575/metoda)

+ [Sposób – Słownik SJP](http://sjp.pl/spos%F3b)

+ [What is the difference between a method and a procedure?](http://wiki.answers.com/Q/What_is_the_difference_between_a_method_and_a_procedure)




---
+ [edit](https://github.com/hipermodularyzacja/prezentacja/edit/main/README.md)
