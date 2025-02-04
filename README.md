# Automatizirano Testiranje Web Aplikacije

## Opis Projekta
Ovaj projekt služi za automatizirano testiranje web aplikacije koristeći Selenium WebDriver i TestNG. Testovi provjeravaju funkcionalnosti kao što su registracija korisnika, prijava, dodavanje proizvoda u košaricu, proces naplate i slanje kontakt forme.

## Tehnologije
- **Java** – programski jezik u kojem su napisani testovi
- **Selenium WebDriver** – za automatizaciju web preglednika
- **TestNG** – za upravljanje i organizaciju testova
- **Maven** – alat za upravljanje ovisnostima i build procesom
- **WebDriver Manager** – za automatsko upravljanje driverima preglednika

## Struktura Testova
Testovi su podijeljeni u pet cjelina:
1. **Registracija i prijava korisnika**
2. **Dodavanje proizvoda u košaricu**
3. **Slanje kontakt forme**
4. **Proces naplate**
5. **Odjava korisnika**

## Kako Pokrenuti Testove
1. Klonirajte repozitorij:  
   ```bash
   git clone <repo-url>
   ```
2. Otvorite projekt u omiljenom IDE-u (npr. IntelliJ IDEA, Eclipse)
3. Osigurajte da imate JDK 11 ili noviji instaliran
4. Pokrenite testove pomoću Maven-a:  
   ```bash
   mvn test
   ```

## Autor
Stefan Belić



