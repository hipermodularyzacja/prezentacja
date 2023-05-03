# prezentacja.hipermodularyzacja.pl

## Wprowadzenie [5 minut]

### Kim jestem?

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


### Cel prezentacji

Celem tej prezentacji jest przekazanie wiedzy na temat wieloletnich badań na temat hipermodularyzacji.



### Plan prezentacji:

##### 1. Geneza
##### 2. Słownictwo
##### 3. Teoria
##### 4. Galeria przykładów
##### 5. Jak (hiper)modularyzować?
##### 6. Dyskusja
 
każdy krok jest obliczony na ok. 5 minut


### Jak powstała ta prezentacja?

Ta prezentacja jest podsumowaniem wieloletnich prac badawaczych nad drogą dotarcia do automatyzacji.
Badałem specyfikę i naturę metod, które sprawdzają się w różnych branżach i zastosowaniach.



### Jakie książki polecam?

+ [Systems and Software Quality: The next step for industrialisation,  von Martin Wieczorek, Diederik Vos, Heinz Bons](https://www.amazon.de/Systems-Software-Quality-next-industrialisation/dp/3662514044)
+ [hipermodularyzacja -  w trakcie pisania]



### Nagroda

Nagrodą będzie ebook, dla każdego uczestnika, książki, która bedzie dostępna za 6 miesięcy w Listopadzie 2023.







# 1. Geneza

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

Modularyzacja to przyporządkowywanie na podstawie specyfiki.

Hipermodularyzacja to wytwarzanie ustandaryzowanych i wyspecjalizowanych modułów.

**Modularyzacja** zajmuje się tworzeniem sieci modułów, **Hiermodularyzacja** wchodzi istotę samych modułów, determinuje ich powstawanie, narzuca standardy.


Modularyzacja jest metodyką skupia się na samym zarządzaniu (systemem, architekturą)
Hipermodularyzacja narzuza metodykę tworzenia nowych modułów


### architektura modułowa

architektura modułowa odnosi się do projektowania systemu składającego się z niezależnych jednostek, które można łączyć w celu stworzenia większego i bardziej złożonego systemu.
Te niezależne jednostki nazywane są modułami i można je łatwo wymieniać lub modyfikować bez wpływu na cały system.


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





# 2. Słownictwo


Problem, Rozwiązanie, Hipoteza, Procedura, Proces, Technika, Dyrektywa, Metoda, Metodyka, Metodologia

Na podstawie [Uniwersalnego słownika języka polskiego](https://sjp.pwn.pl/poradnia/haslo/metoda-metodyka-metodologia;7632.html)
Metoda, technika, procedura badawcza


#### [Badania naukowe](https://pl.wikipedia.org/wiki/Badania_naukowe)

+ Służą osiągnięciu postępu wiedzy naukowej, ustaleniu nowych twierdzeń naukowych, tez, aksjomatów, uogólnień i definicji
+ Badanie naukowe rozpoczyna się od ustalenia tematu jako problemu naukowego. Na tym etapie ustalany jest problem naukowy i formułowany jako temat badania.


#### [Problem naukowy](https://pl.wikipedia.org/wiki/Problem_naukowy)

+ pytanie: **Co?**
+ Problem naukowy nie musi być w każdym przypadku sprecyzowany dokładnie i niewzruszony.


#### [Hipoteza](https://pl.wikipedia.org/wiki/Hipoteza)

+ pytanie: **Dlaczego?**
+ hipoteza to założenie, na podstawie którego zadajemy sobie pytanie: dlaczego zjawisko, fakt czy proces jest możliwe?
+ Hipoteza badawcza po przeprowadzeniu badania może zostać potwierdzona bądź obalona
+ Stawianie i testowanie hipotez to jeden z podstawowych procesów twórczego myślenia oraz fundamentalny element procesu tworzenia nauki. 


#### [Technika](https://pl.wikipedia.org/wiki/Technika)

to [sposób]() realizacji [metod]() przy respektowaniu [dyrektyw]() biorąc pod uwagę warunki środowiskowe


#### [Dyrektywa](https://pl.wikipedia.org/wiki/Dyrektywa), wytyczna, rozporządzenie

rozkaz, instrukcja lub norma postępowania nakazująca określone zasady działania; wytyczna, zalecenie, nakaz:

+ czego nie wolno?
+ co wolno?



#### [Metoda](https://pl.wikipedia.org/wiki/Metoda), forma rozwiązania [problemu]() 

+ To [sposób]() postępowania mający prowadzić do osiągnięcia zamierzonego celu. 
+ To powtarzalny [sposób]() rozwiązywania [problemu]().


##### Przykład:

+ Eksperyment
+ Monografia
+ Metoda indywidualnych przypadków
+ Metoda sondażu diagnostycznego



#### [Proces](https://pl.wikipedia.org/wiki/Proces)

Proces to seria zadań i czynności, które prowadzą do [celu](). 

+ pytanie: **Jakie procedury?**
+ Proces badawczy to świadoma, celowa zmierzona czynność
+ powinna kierować się określonymi regułami i wskazaniami

##### Przykład:



#### [Procedura](https://pl.wikipedia.org/wiki/Procedura)

+ pytanie: **Jakie czynności?**
+ Procedura to metod w organizacji
+ proces to [zbiór]() [procedur]()
+ Procedura to zbiór instrukcji dotyczących wykonania pojedynczego zadania lub czynności w ramach procesu.

Metoda zwykle jest ogólna, nie uwzględnia na przykład specyfiki organizacji i jej otoczenia.
Procedura natomiast jest bardziej szczegółowa, pokazuje sposób użycia danej metody z zachowaniem porządku i powtarzalności, przy uwzględnieniu aspektów otoczenia, w jakim metoda będzie stosowana. 
Pokazuje sekwencję czynności, jakie należy wykonać w odpowiedniej kolejności, by osiągnąć zamierzony rezultat, a także określa kto i co wykonuje.


Procedura może być [metodą]() rozwiązania [problemu]().

##### Przykład:

Przykładem niech będzie nieuprawniony dostęp do komputerów firmowych. 
Metodą na rozwiązanie takiego problemu jest tworzenie unikalnych kont użytkowników zabezpieczonych hasłami. 
W tym wypadku organizacje powinny wdrożyć procedurę tworzenia kont użytkowników i zarządzania nimi. 
O ile tworzenie kont jest sprawdzoną i powszechnie stosowaną metodą, procedura zostanie stworzona z uwzględnieniem specyfiki danej organizacji, w odniesieniu do dokumentów, regulaminu, czy wewnętrznych ustaleń firmy. 
Będzie ona jasno określać zakres odpowiedzialności osób realizujących działania w ramach procedury oraz kolejność wykonywanych zadań, procesów




#### Proces i Procedura

Rozważmy typowy proces zarządzania żądaniami. Kroki w procesie obejmują:

    Otrzymanie żądania
    Przekierowanie wniosku do odpowiedniego recenzenta
    Zatwierdzenie lub odrzucenie wniosku
    Powiadomienie wnioskodawcy o decyzji zatwierdzającej

Dla każdego z tych kroków istnieje odrębna procedura. 
Służy to jako zestaw instrukcji, który mówi pracownikowi dokładnie, jak ukończyć każdy etap procesu. 
Na przykład, podczas kierowania wniosku do odpowiedniego recenzenta, może być wymagana następująca procedura:

    Sprawdź typ żądania.
    Wybrać zatwierdzającego na podstawie typu.
    Utwórz bilet zatwierdzenia.
    Dodaj termin zatwierdzenia do biletu.
    Wyślij zgłoszenie do zatwierdzającego.



#### [Metodyka](https://pl.wikipedia.org/wiki/Metodyka) 

to [zbiór]() [metod]() i [technik]() dotyczących sposobów wykonywania pracy lub trybu postępowania prowadzącego do określonego [celu]().

+ pytanie: **Jak to należy robić?**
+ kieruje się ku praktyce wykonawczej, skupia się na metodach realizacji zadań
+ pojedyncza metodyka będzie gromadziła [metody]() lub [techniki]()
+ Metodyka abstrahuje od merytorycznego kontekstu danego obszaru,

+ Przykład:
  + Metodyki zarządzania projektami: PRINCE2 lub TenStep. 


#### [Metodologia](https://pl.wikipedia.org/wiki/Metodologia) 

to [nauka]() o metodach badań naukowych i o sposobach przeprowadzania analiz oraz oceniania wartości poznawczej poszczególnych [dyscyplin naukowych]().

+ pytanie: **Co należy robić?**
+ kieruje się ku teorii usprawniania
Przykłady: 
+ Agile - metodologia prowadzenia projektów zwinnych.



### Paradygmaty programowania

Programowanie imperatywne oraz deklaratywne

#### Paradygmat imperatywny
opisuje proces wykonywania jako sekwencję instrukcji zmieniających stan programu. 
Rozszerzeniem (w sensie wbudowanych funkcji) i rodzajem (w sensie paradygmatu) programowania imperatywnego jest programowanie proceduralne. 
+ jak coś zrobić, krok po kroku
+ Cel jest określony poprzez szczegółowe czynności
+ opis czynności procedur


Przykład paradygmat imperatywnego: programowanie strukturalne i proceduralne

+ W programowaniu strukturalnym chodzi o używanie struktur, które kontrolują flow programu w stylu for, switch, while, if, else
+ Podejście proceduralne polega na podzieleniu programu na procedury czyli funkcje w skład których wchodzi struktura, to wyższa forma abstrakcji, ale zachowuje cechy programu imperatywnego

Każdy program proceduralny jest też programem strukturalnym (ze względu na użycie wywołań funkcji, które są tymi "strukturami" sterującymi przebiegiem programu).
![image](https://user-images.githubusercontent.com/5669657/235690706-40450624-bf13-40ad-980a-dabbd985bfda.png)



#### Paradygmat deklaratywny

Peter Van Roy oraz Serif Haridi podają następujące warunki, jakie musi spełniać program, aby mógł być uznany za deklaratywny:

+ niezależny — wynik końcowy nie zależy od żadnego zewnętrznego stanu,
+ bezstanowy — nie posiada stanu wewnętrznego, który jest zachowywany między wywołaniami,
+ deterministyczny — dla takich samych argumentów wejściowych zawsze daje ten sam wynik.


Przykłady:
Istnieje kilka szczegółowych paradygmatów, które spełniają te warunki, różniących się sposobami ich osiągnięcia: programowanie funkcyjne, programowanie logiczne, programowanie ograniczeń. 

+ co ma dla nas zrobić, 
+ celem jest rezultat - proces, a nie same procedury
+ bez szczegółów implementacji, 
+ ważny jest dla nas wynik



#### Paradygmat modularny

Programowanie modularne, modular programming

paradygmat programowania zalecający stosowanie nadrzędności modułów w stosunku do procedur i bloków tworzących program. 
Moduł grupuje funkcjonalnie związane ze sobą dane oraz procedury i jest reprezentacją obiektu jednokrotnie występującego w programie. 
Programowanie takie wykorzystywane jest przez wyspecjalizowane języki programowania, np. Ada, Modula-2, Pascal, Fortran90.

Paradygmat programowania modularnego jest blisko związany z innymi paradygmatami, a mianowicie programowaniem strukturalnym i programowaniem zorientowanym obiektowo, gdzie jest często stosowany. 



#### Podsumowanie

W praktyce życiowej kierujemy się wyborem:

+ mniejszego zła []
+ zasady pareto skupiając się na rezultacie angażujemy tylko część czas, energii i zasobów, aby zmaksymalizowac efektywność, elastyczność, reużycie

O ile rezultatem powyższych wyborów jest zaangażowanie jednorazowe o tyle w modularyzacji rezultatem ma być wielokrotne użycie - reużycie, pozostałe cechy są mniej istotne, ale towarzyszą temu procesowi.

Rezultatem  modularyzacji rezultatem ma być lepsza specjalizacja.






# 3. Teoria [10 minut]

Zadawanie własicwych pytań 

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


## Summary
How to live in hyper modular world, how to manage the all modular elements?

Living in a hyper-modular world means that we are constantly surrounded by an increasing number of specialized modules that are interconnected to form complex systems. Here are some ways to manage the all modular elements in a hyper-modular world:

#### Develop a modular mindset
Adopt a modular mindset that allows you to break down complex problems into smaller, more manageable pieces. 
This will help you understand and manage the interconnected modules of a system.

#### Understand the interfaces 
In a hyper-modular world, it's important to understand how different modules interface with each other. 
Learn about the different types of interfaces, such as APIs or protocols, and how they work.

#### Use modular tools
Use modular tools to manage the different modules of a system. 
This includes tools for version control, testing, and deployment.

#### Practice modular design
Use modular design principles to create systems that are flexible and scalable. 
This means breaking down systems into smaller, specialized modules that can be easily replaced or updated.

#### Collaborate with others
Collaboration is key in a hyper-modular world. 
Work with others to share knowledge and expertise in managing the different modules of a system.

#### Continuously learn
A hyper-modular world is constantly evolving. 
Continuously learn about new technologies and techniques for managing modular systems.

By adopting a modular mindset, understanding the interfaces, using modular tools, practicing modular design, collaborating with others, and continuously learning, you can effectively manage the all modular elements in a hyper-modular world.


## How to do it?


Building the components using hyper-modular design principles means breaking down the components into smaller, specialized components that can be easily replaced or updated,

Here is a to-do list with explanations on how to build components using hyper-modular design principles for a non-technical person:
 
By following these steps, you can design and convert processes to hyper-modular components that are flexible, scalable, and efficient. 

Remember to focus on specialization, flexibility, and collaboration to create a system that can adapt to the process's changing needs.


#### Identify the process: 
Start by identifying the process that you want to convert into hyper-modular components. This could be any process, such as a manufacturing process, a customer service process, or a project management process.

#### Break down the process: 
Break down the process into smaller components or modules. 
Each module should be highly specialized and focused on one specific task. 
For example, a customer service process could be broken down into smaller modules such as answering calls, responding to emails, and handling complaints.

#### Define the interfaces: 
Define the interfaces between the different modules. 
This will help you understand how the different modules interact with each other. 
For example, the interface between the answering calls module and the responding to emails module could be the customer database.

#### Design the modules: 
Design each module to be highly specialized and flexible. 
This will allow them to be easily replaced or updated as the process evolves. 
For example, the answering calls module could be designed to handle different types of calls, such as sales calls, support calls, and billing calls.

#### Build the components: 
Build the components using hyper-modular design principles. 
This means breaking down the components into smaller, specialized components that can be easily replaced or updated. 
For example, the answering calls module could be broken down into smaller components such as call scripts, FAQs, and customer information forms.

#### Test and iterate: 
Test the components to ensure they are working effectively. 
Iterate and refine the design until you find a solution that works. 
For example, test the call scripts to ensure they are effective in handling different types of calls.

#### Integrate the components: 
Integrate the components back into the overall process. 
Ensure that the interfaces between the different modules are working effectively. 
For example, ensure that the customer information forms are being properly transferred to the responding to emails module.

#### Continuously improve: 
Continuously improve the process by monitoring its performance and making adjustments as necessary. 
For example, monitor the average call time for the answering calls module and adjust the call scripts to improve efficiency.

By following these steps, a non-technical person can build components using hyper-modular design principles, which can lead to a more efficient and effective process.





# 4. Galeria przykładów [5 minut]

Galeria Przykładów modularyzacji




### architektura modularna i monolityczna

+ [Modularyzacja: kolejny modny trend IT, czy jedyna słuszna droga? - Tech Blog ING Bank Śląski](https://techblog.ing.pl/blog/modularyzacja-kolejny-modny-trend-it-czy-jedyna-sluszna-droga)


systemy do pakowania przedmiotów
systemy układania 




# 5. Jak (hiper)modularyzować?

Jak budować system w oparciu o hiper-modularne komponenty?
Jakie są zasady projektowania hipermodułowego?

Budowanie komponentów przy użyciu hipermodułowych zasad projektowania oznacza rozbijanie komponentów na mniejsze, wyspecjalizowane komponenty, które można łatwo wymienić lub zaktualizować.
 
Wykonując te kroki, możesz projektować i przekształcać procesy w hipermodułowe komponenty.

Pamiętaj, aby skupić się na specjalizacji, reużyciu i współpracy łączonych hiper-modułów.
Dzięki temu całą sieć hipermodułów można dostosować do zmieniających się potrzeb procesu.


#### Identyfikuj:
Zacznij od zidentyfikowania procesu, który chcesz przekształcić w komponenty hipermodułowe. 
Może to być dowolny proces, taki jak proces produkcyjny, proces obsługi klienta lub proces zarządzania projektem.

#### Dziel:
Podziel proces na mniejsze komponenty lub moduły.
Każdy moduł powinien być wysoce wyspecjalizowany i skoncentrowany na jednym konkretnym zadaniu.
Na przykład proces obsługi klienta można podzielić na mniejsze moduły, takie jak odbieranie połączeń, odpowiadanie na e-maile i rozpatrywanie reklamacji.

#### Łącz:
Zdefiniuj interfejsy między różnymi modułami.
Pomoże Ci to zrozumieć, w jaki sposób poszczególne moduły współdziałają ze sobą.
Na przykład interfejsem pomiędzy modułem odbierania połączeń a modułem odpowiadania na e-maile może być baza danych klientów.

#### Twórz:
Zaprojektuj każdy moduł tak, aby był wysoce wyspecjalizowany i elastyczny.
Umożliwi to ich łatwą wymianę lub aktualizację w miarę rozwoju procesu.
Na przykład moduł odbierania połączeń może być zaprojektowany do obsługi różnych typów połączeń, takich jak połączenia sprzedażowe, połączenia wsparcia i połączenia rozliczeniowe.

#### Buduj:
Zbuduj komponenty, korzystając z hipermodułowych zasad projektowania.
Oznacza to podzielenie komponentów na mniejsze, wyspecjalizowane komponenty, które można łatwo wymienić lub zaktualizować.
Na przykład moduł odbierania połączeń można podzielić na mniejsze elementy, takie jak skrypty rozmów, często zadawane pytania i formularze informacyjne dla klientów.

#### Testuj:
Przetestuj komponenty, aby upewnić się, że działają efektywnie.
Powtarzaj i udoskonalaj projekt, aż znajdziesz rozwiązanie, które działa.
Na przykład przetestuj skrypty połączeń, aby upewnić się, że są skuteczne w obsłudze różnych typów połączeń.

#### Integruj:
Zintegruj komponenty z powrotem w cały proces.
Upewnij się, że interfejsy między różnymi modułami działają skutecznie.
Na przykład upewnij się, że formularze z informacjami o klientach są prawidłowo przesyłane do modułu odpowiadania na wiadomości e-mail.

#### Ulepszaj:
Stale ulepszaj proces, monitorując jego wydajność i dokonując niezbędnych korekt.
Na przykład monitoruj średni czas połączeń dla modułu odbierania połączeń i dostosuj skrypty połączeń, aby poprawić wydajność.

Postępując zgodnie z tymi krokami, osoba nietechniczna może budować komponenty przy użyciu zasad projektowania hipermodułowego, co może prowadzić do bardziej wydajnego i efektywnego procesu.




# 6. Dyskusja [15 Minut]





## Źródła


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
