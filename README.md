
# prezentacja.hipermodularyzacja.pl


## Plan prezentacji:

##### 1. Prelegent
##### 2. Cel prezentacji
##### 3. Problem - dlaczego?
##### 4. Zastosowanie - gdzie?
##### 4. Geneza 
##### 6. Badanie - w jaki sposób?
##### 7. Teoria
##### 8. Galeria przykładów
##### 9. Jak (hiper)modularyzować?
##### 10. Dyskusja
 
każdy krok jest obliczony na ok. 5 minut



---

# 1. Prelegent

+ Kim jestem?

### Role:
+ [entuzjasta](http://www.entuzjasta.pl) technologii, metodologii, socjologii, cybernetyki
+ badacz, [researcher](http://www.researcher.pl)
+ programista, administrator, DevOps, [platform engineer](http://www.platformengineer.pl)

### Tematy:
+ [modularyzacja](http://www.entuzjasta.pl)
+ [automatyzacja](http://www..pl)
+ [bezpieczeństwo](http://www..pl)

### Ślad węglowy:
+ do 2013 Polska
+ do 2023 Niemcy
+ ...







# 2. Cel prezentacji

![image](https://user-images.githubusercontent.com/5669657/236607475-39851935-19e4-4bf7-a1ac-9035587e0d4b.png)


Celem tej prezentacji jest przekazanie wiedzy na temat wieloletnich badań na temat hipermodularyzacji.

Celem badania tematu hipermodularyzacji jest zwiększenie jakości wiązań modułów, co wpływa w sferach informacyjnych i fizycznych wzmacnia strukturę umożliwiając zwiększenie jej możliwości.

Dobrze udokumentowana wiedza, sprawdzona, powtarzalna jest lepszym podłożem do zwiększenia ilościowego całej sieci, zwielokrotnieniem jej wiązań oraz zmniejszenie kosztu utrzymania.

To oznacza, że jako ludzie stosujący modularne myślenie możemy zajmować się tysiącami projektów w ciągu roku.

Moga zaoszczędzić zasoby i tworzyć lepsze organizacje.




### Forma prezentacji

W prezentacji będę posługiwał się przykładami z różnych dziedziń, gdyż modularyzacja jest interdyscyplinarna.

Dla uproszczenia przekazu posługuję się przykładami, z życia wielu z nas, abyśmy mogli na koniec w dyskusji rozmawiać na temat łatwych do wyjaśnienia przykładów.





### Jak powstała ta prezentacja?

Ta prezentacja jest podsumowaniem wieloletnich prac badawaczych nad drogą dotarcia do automatyzacji.
Badałem specyfikę i naturę metod, które sprawdzają się w różnych branżach i zastosowaniach.




### Jakie książki polecam?

+ [Systems and Software Quality: The next step for industrialisation,  von Martin Wieczorek, Diederik Vos, Heinz Bons](https://www.amazon.de/Systems-Software-Quality-next-industrialisation/dp/3662514044)
+ [hipermodularyzacja -  w trakcie pisania]



### Nagroda

Nagrodą będzie ebook, dla każdego uczestnika, książki, która bedzie dostępna za 6 miesięcy w Listopadzie 2023.







# 3. Problem - dlaczego?


### Bałagan

+ pojęciowy, definicje, sposób rozumienia przez otoczenie
+ danych, bazy danych, formaty, sposoby transmisji, udostępniania, autoryzacji
+ przedmiotów, magazyn, formy, sposób przenoszenia, 
+ narzędzi, sposób użycia, 


### Re-użycie

+ ile z zasobów, które mamy, możemy ponownie użyć?
+ CO w przypadku potrzeby naprawy, czy musimy wymieniać całość?




### Forma i treść

nie mogę być jednocześnie formą i tworzywem - Andrzej Dobosz (Filozof w "Rejsie"):
„Nie mogę być jednocześnie twórcą i tworzywem” – mówił filozof w klasyku polskiego kina, w filmie „Rejs”.

Dotyczy to często każdego z nas na styku teorii i praktyki.
![image](https://user-images.githubusercontent.com/5669657/236606256-ec0d72e5-8c50-4b4e-ab91-45c629c41f50.png)
żródło: https://www.youtube.com/watch?v=ylfdoWEyYXQ



Problemyu związane z modularyzacją, jak rozeznać granice?
+ [156. Wrocław JUG - Problemy wynikające z modularyzacji. - Łukasz Szydło - YouTube](https://www.youtube.com/watch?v=JJXmgCx_wh0)


### Odwzorowanie

W tej prezentacji przeznaczonej dla programistów można zaobserwować jak jest pojmowana modularyzacja w IT.
Częstą praktyką jest wykorzystywanie dostępnych i znanych programiście wzorców, dopasowwywanie rzeczywistości pod wrzozec.
Niestety taka praktyka w naturalny sposób prowadzi do tworzenia implementecji, kosztownych w utrzymaniu.

Można tę sytuację porównać do klocków, gdzie chcąc odwzorować obiekt, np pojazd, używamy tylko dostępnym klocków.


### Kierunek oddziaływania modularyzacji na rzeczywistość

W modularyzacji gdy braknie klocków to dostarczamy nowe, lepiej dopasowane poprzez hipermodularyzację.

+ staramy się zmieniać rzeczywistość prowadząc zmiany w ograniczonym miejscu i czasie.
+ Staramy się zawężać pole oddziaływania modularyzacji na rzeczywistość prowadząc do uszlachetnienia tylko części w danej chwili
+ oddziałujemy tam gdzie jest to łatwiejsze, gdzie ingerencja nie jest znacząca, nie jest wymagany duży koszt

UWAGA
+ nie prowadzimy działań na całym systemie, gdyż interesuje nas elastyczność i sprężystość, odporność na wpływ z zewnątrz, chcemy uniknąć braku dostępu do zasobów
+ korzystamy z tego co mamy, nie zmieniamy połączeń, które prowadzą do ryzyka




# 4. Zastosowanie - gdzie?




### Modularyzacja a zarządzanie

Codzienne problemy są związane nie tylko z tworzeniem ale też zarządzaniem, które pozwala m.in. na zamianie dużego bałaganu w mniejsze lokalne bałagany
Kontekst powstania tego małego bałaganu pozwala na specjalizacje procesu uporządkowania.





###  Modularyzacja a magazynowanie

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

Wprowadzenie do hipermodularyzacji 

+ Muzyka, [www/tekst.md](https://github.com/hipermodularyzacja/www/blob/main/tekst.md)


## Automatyzacja

Automatyzacja to droga w której modularyzujemy, standaryzujemy i specjalizujemy procesy.

Droga do automatyzacji zaczyna się od modularyzacji, ponieważ, zanim będziemy wiedzieli jaki standard użyć, możemy wcześniej na podstawie minimalnych danych o cechach procesu poznać jaka jest jego specyfika i przez to przyporzadkować go do określonego zbioru.


### Hipermodularyzacja

+ Hipermodularyzacja przenosi architekturę modułową na wyższy poziom.
+ Wykracza poza tradycyjne podejście modułowe i obejmuje podział systemu na mniejsze, bardziej wyspecjalizowane moduły.
+ Hipermodularyzacja zajmuje się nie tyle zarządzaniem architekturą, co skupieniem się na najmniejszych elementach, by projektować moduły, które będą ułatwiały tworzenie lepszych systemów.


### Modularyzacja i Hipermodularyzacja


#### W prostych słowach:

Modularyzacja to budowanie systemu poprzez wykorzystanie gotowych modułów.

Hipermodularyzacja to rozbijanie istniejących modułów na mniejsze by stworzyć więcej prostych, reużywalnych modułów.


#### Modualryzacja w budowaniu systemów

**Modularyzacja** zajmuje się tworzeniem sieci modułów, **Hiermodularyzacja** wchodzi istotę samych modułów, determinuje ich powstawanie, narzuca standardy.

Modularyzacja to tworzenie sieci modułów. (Ilościowe)

Hipermodularyzacja to tworzenie ustandaryzowanych i wyspecjalizowanych modułów. (Jakościowe)




### architektura modułowa

architektura modułowa odnosi się do projektowania systemu składającego się z niezależnych jednostek, które można łączyć w celu stworzenia większego i bardziej złożonego systemu.
Te niezależne jednostki nazywane są modułami i można je łatwo wymieniać lub modyfikować bez wpływu na cały system.

Modularyzacja jest metodyką skupia się na samym zarządzaniu (systemem, architekturą)
Hipermodularyzacja narzuza metodykę tworzenia nowych modułów



### Korzyści z hipermodularności

Modułowa architektura i hipermodularność to ważne koncepcje dla DevOps, twórców sprzętu i oprogramowania. 
Oferują znaczące korzyści w zakresie elastyczności, skalowalności, możliwości ponownego użycia, konserwacji, sprawności, odporności, dostosowywania i współpracy. 

Modularyzacja to droga do solidnych, elastycznych i wydajnych systemy.

Korzyści systemu opartego o hipermodularne elementy łączy te wszystkie korzyści jednocześnie:

+ Elastyczność, Flexibility
+ Reużywalność, Reusability
+ Skalowalność, Scalability
+ Zwinność, Agility
+ Odporność, Resilience
+ Dostosowalność, Customization




#### Zwinność
Hipermodularność pozwala na szybki rozwój i wdrażanie nowych funkcji i usług. Deweloperzy mogą pracować nad poszczególnymi modułami bez wpływu na cały system, co pozwala na szybszą iterację i dostarczanie.

#### Odporność
Systemy hipermodularne są bardziej odporne na awarie. Jeśli jeden moduł ulegnie awarii, można go łatwo wymienić na zapasowy lub nowy moduł, bez wpływu na resztę systemu.

#### Dostosowywanie
Hipermodularność pozwala na większą personalizację systemu. Moduły można dodawać, usuwać lub wymieniać, aby spełnić określone wymagania lub potrzeby biznesowe.

#### Współpraca
Hipermodularność zachęca do współpracy między programistami. Różne zespoły mogą pracować nad różnymi modułami, co ułatwia zarządzanie procesem rozwoju.


#### Elastyczność:
Modułowa architektura pozwala na łatwą modyfikację i dostosowanie systemu. Dodawanie nowych funkcji, aktualizacja komponentów i naprawianie błędów może odbywać się bez zakłócania pracy całego systemu.

#### Skalowalność:
Modułowa architektura wspiera skalowalność.
Pozwala na dodawanie nowych modułów do systemu, czyniąc go zdolnym do obsługi zwiększonego obciążenia.

#### Możliwość ponownego użycia:
Moduły mogą być używane w różnych systemach lub aplikacjach, oszczędzając czas i zasoby w procesie rozwoju.

#### Konserwacja:
Modułowa architektura upraszcza konserwację.
System można łatwo konserwować, wymieniając lub aktualizując moduł, którego dotyczy problem, bez wpływu na cały system.







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


#### Podsumowanie

W praktyce życiowej kierujemy się wyborem:

+ mniejszego zła []
+ zasady pareto skupiając się na rezultacie angażujemy tylko część czas, energii i zasobów, aby zmaksymalizowac efektywność, elastyczność, reużycie

O ile rezultatem powyższych wyborów jest zaangażowanie jednorazowe o tyle w modularyzacji rezultatem ma być wielokrotne użycie - reużycie, pozostałe cechy są mniej istotne, ale towarzyszą temu procesowi.

Rezultatem  modularyzacji rezultatem ma być lepsza specjalizacja.









# 7. Teoria

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



## Examples of usage between modularity and hypermodularity

#### In software development

In software development, modularity is often used for creating reusable components that can be easily integrated into different applications. 
Hypermodularity, on the other hand, is often used for breaking down complex applications into smaller, specialized microservices that can be developed and deployed independently.

#### Product design

In product design, modularity is often used for creating products with interchangeable parts that can be easily replaced or upgraded. 
Hypermodularity, on the other hand, is often used for creating products with highly customizable features and options.

#### project management

In project management, modularity is often used for breaking down a project into smaller, manageable tasks that can be assigned to different team members. 
Hypermodularity, on the other hand, is often used for creating highly agile and adaptable project workflows that can be easily customized and adjusted based on changing requirements.




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








# 8. Galeria przykładów

Galeria Przykładów modularyzacji




### Przeprowadzka:

przenosimy w kartonach wszystkie rzeczy i nie mając starych mebli albo tylko część dodajemy nowe.
Mamy możliwość poukładania wszystkich rzeczy w zależnośći od przeznaczenia lub/oraz właściciela:

Tam gdzie jest własność wspólna, np. ręczniki, określamy miejsce w przestrzeni dostępne dla każdego
Tam gdzie jest własność prywatna, odzież codzienna, określamy pokoje, które są używane przez konkretne osoby.
Tam gdzie jest własność prywatna, ale używana w przestrzeni wspólnej, np buty, parasolki określamy ograniczone miejsce wspólne, korytarz.


### Utrzymanie porządku


duże -> małe



### Magazynowanie


+ regały, skrzynki, pudełka


### Programowanie


+ Enterprise Integration Patterns
+ Camel
+ Wzorce
+ Biblioteki
+ Digital Twin


### Infrastruktura
+ plesk
+ proxmox
+ openstack


### Modularny hardware
+ minipc
+ systemowe skrzynki


5. ...


### architektura modularna i monolityczna

+ [Modularyzacja: kolejny modny trend IT, czy jedyna słuszna droga? - Tech Blog ING Bank Śląski](https://techblog.ing.pl/blog/modularyzacja-kolejny-modny-trend-it-czy-jedyna-sluszna-droga)


systemy do pakowania przedmiotów
systemy układania 








# 9. Jak (hiper)modularyzować?



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


Przyjmując modułowy sposób myślenia, rozumiejąc interfejsy, używając modułowych narzędzi, ćwicząc modułowe projektowanie, współpracując z innymi i stale się ucząc, możesz skutecznie zarządzać wszystkimi modułowymi elementami w hipermodułowym świecie.



## Technika


Jak budować system w oparciu o hiper-modularne komponenty?

Jakie są zasady projektowania hipermodułowego?

Budowanie komponentów przy użyciu hipermodułowych zasad projektowania oznacza rozbijanie komponentów na mniejsze, wyspecjalizowane komponenty, które można łatwo wymienić lub zaktualizować.
 
Wykonując te kroki, możesz projektować i przekształcać procesy w hipermodułowe komponenty.

Pamiętaj, aby skupić się na specjalizacji, reużyciu i współpracy łączonych hiper-modułów.
Dzięki temu całą sieć hipermodułów można dostosować do zmieniających się potrzeb procesu.

### Ogranicz

Określ kontekst w którym chcesz usprawnić system połączeń, lub chcesz dopiero go zaimplementować.
W modularyzacji staramy się  ograniczać pole widzenia, analizy i działania, aby ograniczyć jej koszty.
Prześledć gdzie jest największy ruch w sieci połączeń organizacji, gdzie korzyści z modularyzacji mogą przynieść najwięcej korzyści, gdzie specjalizacja czyli podniesienie jakości będzie docenione?
**Na przykład** Przy obsłudze klienta są dwa przypadki dzwoniących, reklamacje i zapytania ofertowe, odbierającym może być być sekretarka, która krok po kroku poprowadzi dzwoniącego a następnie bot, ta sama implementacja może dotyczcyć chatbota na stronie www lub wiadomości email, ale najpierw trzeba ograniczyć ją do telefonujących.

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

#### Twórz:

Zaprojektuj każdy moduł tak, aby był wysoce wyspecjalizowany i elastyczny.
Umożliwi to ich łatwą wymianę lub aktualizację w miarę rozwoju procesu.
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

#### Ulepszaj:

Stale ulepszaj proces, monitorując jego wydajność i dokonując niezbędnych korekt.
**Na przykład** monitoruj średni czas połączeń dla modułu odbierania połączeń i dostosuj skrypty połączeń, aby poprawić wydajność.

Postępując zgodnie z tymi krokami, osoba nietechniczna może budować komponenty przy użyciu zasad projektowania hipermodułowego, co może prowadzić do bardziej wydajnego i efektywnego procesu.


#### Powiel i porównaj

Jeśli zmiana przynosi dobre rezultaty powiel je również w innym środowisku, by poprzez porównanie edukować się
+ Tworzenie kilku na raz
+ Porównanie modułów




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

Proza codzienności:
![image](https://user-images.githubusercontent.com/5669657/236609574-ebc44829-ff78-44f4-81e8-e988379276be.png)

Transparentne pojemniki:
![image](https://user-images.githubusercontent.com/5669657/236608899-70078ba3-2ab5-4e73-81cd-2d2403df9d28.png)



----



### koniec:
klask, klask, klask
![image](https://user-images.githubusercontent.com/5669657/236607603-e6a4a61c-8381-4bca-bb6f-bf5c066b6667.png)








# 10. Dyskusja [15 Minut]

Co na to jury?
![image](https://user-images.githubusercontent.com/5669657/236607373-38586979-bf9e-4dd3-997c-3379ca95cdb1.png)



+ pytania
+ rozwiązania
+ doświadczenia











---

## Źródła


+ [Modularyzacja przy wytwarzaniu oprogramowania](https://www.hipermodularyzacja.pl/)

+ Polskie wydanie, Wersja Polska: HiperModularyzacja.pl [książka: Hiper Modularyzacja](https://book.hipermodularyzacja.pl/)

+ Polskie wydanie, Wersja Polska: HiperModularyzacja.pl [Blog: blog.HiperModularyzacja.pl](https://blog.hipermodularyzacja.pl/)

+ W trakcie jest też wersja angielska: HyperModularity.com  [www. Hyper Modularity .com](http://www.hypermodularity.com/)

+ [muzyka: Hiper Modularyzacja](https://www.hipermodularyzacja.pl/tekst.html)

+ Metamoduły bazujące na tym:  [docs.metamodule.org](https://docs.metamodule.org/)


+ [Systems and Software Quality: The next step for industrialisation,  von Martin Wieczorek, Diederik Vos, Heinz Bons](https://www.amazon.de/Systems-Software-Quality-next-industrialisation/dp/3662514044)

+ [Modularyzacja: kolejny modny trend IT, czy jedyna słuszna droga? - Tech Blog ING Bank Śląski](https://techblog.ing.pl/blog/modularyzacja-kolejny-modny-trend-it-czy-jedyna-sluszna-droga)

+ [Uniwersalnego słownika języka polskiego](https://sjp.pwn.pl/poradnia/haslo/metoda-metodyka-metodologia;7632.html)

+ [programowanie deklaratywne i imperatywne](https://codenga.pl/artykuly/poradniki/programowanie-imperatywne-oraz-deklaratywne)

+ [Programowanie deklaratywne – Wikipedia, wolna encyklopedia](https://pl.wikipedia.org/wiki/Programowanie_deklaratywne)

+ [IMMUSEC Metodologia, metodyka, metoda, sposób, procedura – wyjaśnienie zawiłości językowych](https://www.immusec.com/metodologia-metodyka-metoda-sposob-procedura-wyjasnienie-zawilosci-jezykowych/)

+ Metodologia – Słownik języka polskiego, http://sjp.pwn.pl/slownik/2567697/metodologia

+ Metodyka – Słownik języka polskiego, http://sjp.pwn.pl/slownik/2567700/metodyka

+ Metoda – Słownik języka polskiego http://sjp.pwn.pl/slownik/2482575/metoda

+ Sposób – Słownik SJP, http://sjp.pl/spos%F3b

+ What is the difference between a method and a procedure? http://wiki.answers.com/Q/What_is_the_difference_between_a_method_and_a_procedure

+ What is the difference between a method and a procedure? http://wiki.answers.com/Q/What_is_the_difference_between_a_method_and_a_procedure
