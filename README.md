# JavaScript Design Patterns

Dizajn paterni su napredna objektno orijentisana rešenja za softverske probleme koji se često pojavljuju. Paterne ne treba gledati nešto kao vrlo striktno, svako može da napravi patern za svoj problem i da ga podeli. Takođe paterni ne zavise od bilo kog programskog jezika. Paterni se odnose na dizajn za višekratnu upotrebu i interakciju objekata. Svaki patern ima naziv i postaje deo vokabulara kada se raspravlja o složenim dizajnerskim rješenjima.

Knjiga **[The 23 Gang of Four (GoF)](https://springframework.guru/gang-of-four-design-patterns/)** je objavljena 1994, napisali su je Erich Gamma, Richard Helm, Ralph Johnson, i John Vlissides. Ova knjiga se smatra temeljom za sve ostale paterne takođe na osnovu nje oni se kategorizuju u tri grupe: **kreaciski**, **strukturalni** i **bihevioralni**.


## Kreaciski Paterni
  
| Naziv | Opis |
| --- | --- |
| [Singleton](https://github.com/milospantelinac/JavaScript_Singleton_Design_Pattern) | Klasa od koje može postojati samo jedna instanca |
| Builder | Odvaja konstrukciju objekta od njegove reprezentacije |
| Abstract Factory | Omogućuje proizvodnju **families of related** objekata bez navođenja njihovih konkretnih klasa. |
| Factory Method | Stvara instancu nekoliko izvedenih klasa |
| Prototype | Potpuno inicijalizirana instanca koju treba kopirati ili klonirati |

## Strukturalni Paterni

| Naziv | Opis |
| --- | --- |
| Adapter | Spajanje interfejsa različitih klasa |
| Bridge | Odvaja interfejs objekta od njegove implementacije |
| Composite | Struktura stabla jednostavnih i složenih objekata |
| Decorator | Dinamički dodavanje responsibilities objektima |
| [Facade](https://github.com/milospantelinac/JavaScript_Facade_Design_Pattern/blob/main/README.md) | Jedna klasa koja predstavlja celi podsistem |
| Flyweight | Omogućuje da se smesti više objekata u dostupnu količinu RAM-a deljenjem zajedničkih delova stanja. |
| Proxy | Objekat koji reprezentuje drugi objekat |

## Bihevioralni Paterni

| Naziv | Opis |
| --- | --- |
| Chain of Resp | Način prosleđivanja zahteva između lanca objekata |
| Command | Enkapsulacija zahteva naredbe kao objekat |
| Interpreter | Način uključivanja jezičnih elemenata u program |
| Iterator | Sekvencijalni pristup elementima kolekcije |
| Mediator | Definiše pojednostavljenu komunikaciju između klasa |
| Memento | Snimite i vratite unutrašnje stanje objekta |
| Observer | Način obaveštavanja o promenama određenom broju klasa |
| State | Promenite ponašanje objekta kada se promeni njegovo stanje |
| Strategy | Enkapsulira algoritam unutar klase |
| Template Method | Odložite tačne korake algoritma na podklasu |
| Visitor | Definiše novu operaciju u klasi bez promene |
