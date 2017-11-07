2. W nowym projekcie wykonaj poniższe czynności:
* Stwórz klasę `Osoba`
* Stwórz interfejsy `Sport` i `Muzyka`, dodaj w nich deklarację metody `Gra()` zwracającej typ `string`
* Oba interejsy podepnij pod klasę `Osoba`, dodaj implementację interfejsu tak by metoda zwracała string `"gra"`.
* w klasie `Main` i metodzie `Main` stwórz trzy obiekty za pomocą poniższego kodu:

```Java
            Osoba osoba1 = new Osoba();
            Muzyka osoba2 = new Osoba();
            Sport osoba3 = new Osoba();
```
* Na powyższych obiektach wywołaj metodę `Gra()` i sprawdź na konsoli co zwraca.
* (zaawansowane) Czy jest możliwe zaimplementowanie metody `Gra()` tak, aby `osoba1`, `osoba2` i `osoba3` zwracały po wywowłaniu tej metody coś innego? Podpowiedź: tzw. anonimowa implementacja https://stackoverflow.com/questions/573621/is-the-c-sharp-explicit-implementation-of-the-interface-present-in-java
