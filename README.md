# Interaktív vizsga jegyzet
Jegyzet az interaktív vizsgához
<br><br>


### Csoportmunkaeszközök, Git

- **init**: Új Git tárolót inicializál az aktuális könyvtárban a verziókövetés megkezdéséhez.  

- **clone**: Letölt egy távoli tárolót a helyi gépre az összes fájllal és előzménnyel.  

- **add <file>**: A megadott fájlok változtatásait előkészíti a következő commit számára.  

- **commit -m "<message>"**: Az előkészített változtatásokat commitként menti egy leíró üzenettel.  

- **status**: Megmutatja a módosított, előkészített vagy követetlen fájlok aktuális állapotát.  

- **push <remote> <branch>**: Feltölti a helyi commitokat a megadott távoli ágra.  

- **pull <remote> <branch>**: Letölti és egyesíti a távoli ág frissítéseit a helyi ágba.  

- **branch**: Listázza az ágakat vagy új párhuzamos ágat hoz létre a `git branch <név>` paranccsal.  

- **checkout <branch>**: Átvált a megadott ágra vagy visszaállítja a fájlokat.  

- **merge <branch>**: A megadott ág változtatásait egyesíti az aktuális ágba.  

- **log**: Megjeleníti a commit előzményeket azonosítókkal, szerzőkkel, dátumokkal és üzenetekkel.  

- **diff**: Megmutatja a különbségeket a munkakönyvtár, előkészített fájlok vagy commitok között.  

- **stash**: Ideiglenesen menti a nem commitolt változtatásokat ágváltáshoz vagy más feladathoz.  

- **pull request**: Kérelem a kód átnézésére és beolvasztására a távoli repozitóriumban.

- **git remote add <name> <url>**: Távoli tárolót kapcsol a helyi Git konfigurációhoz.  

- **git fetch <remote>**: Letölti a távoli tároló frissítéseit anélkül, hogy egyesítené őket helyben.

- **fork** - Egy repozitórium másolatának készítése saját fiókban.

- **rebase** - Az ág történetének átírása a változtatások új alapra helyezésével.

- **verzió kezelés** - Szoftver, amely nyomon követi és kezeli a kód változásait.

## HTML5, CSS3

- **HTML5** - Weboldalak struktúrájának létrehozására szolgáló jelölőnyelv legújabb verziója.
  
- **CSS3** - Weboldalak stílusának és elrendezésének meghatározására szolgáló nyelv.
  
- **szemantikus elemek** - HTML-elemek, amelyek világosan leírják tartalmuk jelentését.
  
- **media queries** - CSS technika különböző képernyőméretekhez való alkalmazkodáshoz.
  
- **pseudo-class** - CSS szelektorok, amelyek elemek állapotát célozzák meg.

- **\<hr\>** - HTML elem vízszintes vonal beszúrására a weboldalon.
   
- **\<ol\>** - HTML elem sorszámozott lista létrehozására.

- **shorthand property** - CSS tulajdonság, amely több tulajdonságot egyetlen deklarációban egyesít.  

- **box model** - CSS koncepció, amely az elemek elrendezését és méretezését írja le.
  
## JavaScript, ECMAScript
- **ECMAScript** - A JavaScript szabványosított specifikációja.
  
- **async/await** - Szintaxis aszinkron műveletek kezelésére Promise-okkal.

- **$.ajax** - jQuery metódus aszinkron HTTP kérések küldésére.
  
- **DOM** - Document Object Model, a weboldal elemeinek programozható reprezentációja.
  
- **event listener** - Függvény, amely egy eseményre reagál.
  
- **closure** - Függvény, amely hozzáfér a külső hatókör változóhoz.
  
- **Promise** - Aszinkron műveletek eredményének reprezentálása.
  
- **arrow function** - Rövidített szintaxisú függvénykifejezés.
  
- **module** - Kódszervezési egység JavaScriptben az importáláshoz/exportáláshoz.

- **null** - JavaScript érték, amely szándékos üres értéket jelöl.

- **undefined** - JavaScript érték, amely egy nem definiált változóra utal.

## Tiszta kód alapelvek
- **DRY** - Don’t Repeat Yourself, az ismétlődő kód minimalizálása.
  
- **KISS** - Keep It Simple, Stupid, az egyszerű kód előnyben részesítése.
  
- **YAGNI** - You Aren’t Gonna Need It, csak a szükséges funkciók implementálása.
  
- **SOLID** - Objektumorientált tervezési elvek gyűjteménye.
  
- **refactoring / újraszervezés** - Kód átdolgozása a funkcionalitás megváltoztatása nélkül.
  
- **technikai adósság** - Gyors, de nem optimális kódolásból eredő jövőbeli költségek.

- **kódszag** - Olyan kódstruktúra, amely potenciális problémára utal.

- **elnevezési konvenció** - Szabályok a változók és függvények elnevezésére az olvashatóságért.

- **egyetlen felelősség elve** - Egy osztály/függvény csak egy feladatot végezzen.


## Adatbázis-tervezés, adatbázis-kezelés, SQL
- **SQL** - Structured Query Language adatbázisok lekérdezésére és kezelésére.
  
- **normalizálás** - Adatbázis redundanciájának csökkentése és konzisztenciájának biztosítása.
  
- **PRIMARY KEY** - Egyedi azonosító egy tábla rekordjaihoz.
  
- **FOREIGN KEY** - Egy tábla oszlopa, amely egy másik tábla primary key-ére hivatkozik.
  
- **INDEX** - Adatbázis-struktúra a lekérdezések sebességének növelésére.

- **JOIN** - Több tábla adatainak összekapcsolása lekérdezésekhez.

- **JOIN fajtái:**
  1. CROSS JOIN (Minden sort összekapcsol minden sorral a másik táblából, így a két tábla sorainak szorzatát adja)
  2. LEFT/RIGHT JOIN (bal/jobb oldali tábla összes sora + egyező jobb/bal oldali sorok)
  3. INNER JOIN (Csak azokat a sorokat adja vissza, amelyek mindkét táblában megfelelnek a megadott feltételnek)
  
- **MongoDB** - NoSQL dokumentumalapú adatbázis, JSON-szerű adatok tárolására. Rugalmas sémával működik, alkalmas nagy adathalmazokhoz és skálázható alkalmazásokhoz.
  
- **MySQL** - Relációs adatbázis-kezelő rendszer, SQL-t használ táblázatos adatstruktúrákhoz. Strukturált, nagy teljesítményű, alkalmas hagyományos alkalmazásokhoz.

- **MariaDB** - Nyílt forráskódú relációs adatbázis-kezelő, MySQL-kompatibilis.  
  
- **NoSQL** - Nem relációs adatbázisok, amelyek rugalmas adatmodelleket támogatnak.

- **Relációs adatmodell** - MySQL, PostgreSQL, MariaDB, Oracle Database használja

- **Hierarchikus adatmodell** - fa-szerű struktúra (szervezeti struktúrák, fájlrendszerek)

- **Hálós adatmodell** - adatok gráf-szerű struktúrában vannak, lehetővé téve összetettebb, (N:N) kapcsolatokat, a rekordok csomópontok, amelyeket élek kötnek össze.

- **Objektumorientált adatmodell** - Az adatokat objektumokként tárolja, amelyek attribútumokat és metódusokat tartalmaznak

- **schema** - Az adatbázis struktúrájának és szabályainak leírása.

## Mobil alkalmazásfejlesztés
- **native app** - Egy adott platformra (iOS, Android) fejlesztett alkalmazás.
  
- **hybrid app** - Webes technológiákkal készült, de natív alkalmazásként működő app.
  
- **cross-platform** - Több platformon futtatható alkalmazások fejlesztése.
  
- **Flutter** - Google keretrendszer cross-platform mobilalkalmazásokhoz.
  
- **React Native** - JavaScript alapú keretrendszer natív mobilalkalmazásokhoz.

- **Java/Kotlin** - Programozási nyelvek Android natív alkalmazásfejlesztéshez.  

- **Objective-C/Swift** - Nyelvek iOS natív alkalmazásfejlesztéshez.  


## Frontend készítésre szolgáló JavaScript keretrendszerek
- **React** - JavaScript könyvtár felhasználói felületek készítéséhez.

- **MVVM** - Model-View-ViewModel, frontend tervezési minta adat és UI szétválasztására.  
  
- **Vue.js** - Nyílt forráskódú progresszív JavaScript MVVM keretrendszer frontend fejlesztéshez.
  
- **Angular** - TypeScript alapú keretrendszer komplex webalkalmazásokhoz.

- **Ember.js** - JavaScript keretrendszer strukturált webalkalmazásokhoz.

- **Backbone** - JavaScript frontend keretrendszer.

- **state management** - Az alkalmazás állapotának kezelése frontend keretrendszerekben.
  
- **component** - Újrafelhasználható UI elem egy frontend keretrendszerben.
  
- **state** - A komponens aktuális állapotát tároló adatstruktúra.
  
- **props** - Adatok átadása komponensek között Reactben vagy Vue-ban


## Backend készítésre szolgáló nyelvek és keretrendszerek, ORM
- **Node.js** - JavaScript futtatókörnyezet szerveroldali fejlesztéshez.
  
- **Django** - Python alapú backend keretrendszer webalkalmazásokhoz.
  
- **Spring** - Java alapú keretrendszer vállalati alkalmazásokhoz.

- **Laravel** - PHP keretrendszer webalkalmazások gyors fejlesztéséhez.
  
- **Symfony** - PHP keretrendszer skálázható webalkalmazásokhoz.
  
- **Zend Framework** - PHP keretrendszer vállalati szintű alkalmazásokhoz.
   
- **HTTP method** - Protokollparancsok, mint GET, POST, PUT a szerverrel való kommunikációhoz.
  
- **ORM** - Object-Relational Mapping, objektumok és adatbázisok közötti leképezés.
  
- **REST API** - Webes API, amely HTTP kérésekkel kommunikál.
  
- **Express** - Node.js alapú könnyű keretrendszer API-k készítéséhez.
  
- **middleware** - Kód, amely a kérés és válasz között fut a backendben.

## Objektum Orientált Programozás (OOP)
- **class** - Objektumok létrehozására szolgáló sablon.
  
- **object** - Egy osztály példánya, amely adatokat és viselkedést tartalmaz.
  
- **öröklődés** - Egy osztály tulajdonságainak és metódusainak átvétele.

- **zártság/encapsulation** - Adatok és metódusok elrejtése egy osztályon belül (public, private, protected).
  
- **poliformizmus (toString())** - Objektumok különböző formákban való használata.
  
- **absztrakt osztály** - NEM példányosítható (adattag, metódusa, ...).

- **interface** - üres metódusok

- Liskov-helyettesítési elv – Egy osztály bármelyik leszármazottja helyettesítheti az alaposztályt anélkül, hogy a program működése megváltozna vagy hibás lenne.

- Lekérdező metódus (getter) – Olyan metódus, amely egy osztály egy tulajdonságának értékét olvassa ki.

- Beállító metódus (setter) – Olyan metódus, amely egy osztály egy tulajdonságának értékét állítja be.

- Tulajdonság (property) – Olyan osztályelem, amely kívülről változóként viselkedik, de belül lekérdező és beállító metódusok szabályozzák.

- Példa:
```csharp
// Interfész a viselkedés egységesítéséhez
public interface ISzemély
{
    string Részletek();
}

// Alaposztály öröklődéshez
public abstract class Entitás
{
    public static int PéldánySzámláló { get; private set; } // Statikus számláló

    public Entitás()
    {
        PéldánySzámláló++;
    }

    public abstract string Típus(); // Absztrakt metódus
}

// Eseménykezelő delegált
public delegate void ÁtlagVáltozottEseményKezelő(object küldő, double újÁtlag);

public class Személy : Entitás, ISzemély
{
    // Privát mezők a kapszulázáshoz
    private int _azonosító;
    private double _átlag;
    private string _név;
    private DateTime _dátum;

    // Nyilvános tulajdonságok validációval
    public int Azonosító
    {
        get => _azonosító;
        set => _azonosító = value >= 0 ? value : throw new ArgumentException("Az azonosító nem lehet negatív.");
    }

    public double Átlag
    {
        get => _átlag;
        set
        {
            if (value < 0 || value > 100) throw new ArgumentException("Az átlag 0 és 100 között legyen.");
            _átlag = value;
            ÁtlagVáltozott?.Invoke(this, value); // Esemény kiváltása
        }
    }

    public string Név
    {
        get => _név;
        set => _név = string.IsNullOrEmpty(value) ? throw new ArgumentException("A név nem lehet üres.") : value;
    }

    public DateTime Dátum
    {
        get => _dátum;
        set => _dátum = value;
    }

    // Csak olvasható tulajdonság
    public string Leírás => $"{Név} (ID: {Azonosító}, Átlag: {Átlag})";

    // Statikus tulajdonság
    public static string AlapNév { get; } = "Ismeretlen";

    // Esemény
    public event ÁtlagVáltozottEseményKezelő ÁtlagVáltozott;

    // Konstruktorok
    public Személy(int azonosító, double átlag, string név, DateTime dátum)
    {
        Azonosító = azonosító;
        Átlag = átlag;
        Név = név;
        Dátum = dátum;
    }

    public Személy() : this(0, 0.0, AlapNév, DateTime.Now) { }

    // Virtuális metódus
    public virtual string Összegzés() => $"Személy: {Név}";

    // Interfész metódus
    public string Részletek() => Leírás;

    // Absztrakt metódus felülírása
    public override string Típus() => "Személy";

    // ToString felülírása
    public override string ToString() => Leírás;
}
```

## Tartalomkezelő rendszerek (CMS)
- **CMS** - Tartalomkezelő rendszer weboldalak tartalmának kezelésére.
  
- **WordPress** - Népszerű CMS weboldalak és blogok készítéséhez.
  
- **plugin** - CMS funkcionalitását bővítő kiegészítő.
  
- **theme** - A CMS weboldal megjelenését meghatározó sablon.

- **content management** - Weboldalak tartalmának létrehozása, szerkesztése és publikálása.  

- **headless CMS** - Tartalomkezelő rendszer, amely API-n keresztül biztosít tartalmat.

## Tesztelés

- **fekete dobozos teszt** - A rendszer működését csak a bemenetek és kimenetek alapján vizsgálja, anélkül hogy ismerné a belső működést.

- **fehér dobozos teszt** - A tesztelő ismeri a szoftver belső kódját és logikáját, és ezek alapján tervezi a teszteket.
  
- **szürke dobozos tesztelés** - ahol a tesztelő részleges ismerettel rendelkezik a szoftver belső működéséről, kombinálva a külső funkcionalitás tesztelését.

- **integrációs teszt** -  Több modul vagy komponens közötti együttműködés helyességét ellenőrzi, például adatfolyamokat vagy függőségeket tesztelve.

- **egységteszt** -  Egyéni kódegységek (pl. függvények, osztályok) tesztelése elszigetelten, függetlenül más rendszerelemektől.

- **end-to-end test** -  A teljes rendszer működését teszteli a felhasználói felülettől az adatbázisig, valós felhasználói forgatókönyvek alapján.
  
- **TDD (tesztvezérelt fejlesztés)** – Olyan fejlesztési módszertan, ahol előbb a teszteseteket írjuk meg, majd ez alapján fejlesztjük le a működő kódot.
  
- **mockolás** - Külső függőségek szimulálása teszteléshez.
  
- **kód lefedettség** - A tesztelt kód aránya a teljes kódbázishoz képest.

- **rendszer teszt** - A teljes szoftverrendszer működésének átfogó tesztelése, beleértve a funkcionális és nem-funkcionális követelményeket is.

- **tesztpiramis:**
1. GUI / UI tesztek
2. Elfogadási / integrációs tesztek
3. Egység / komponens tesztek

- **elfogadási teszt** – A végfelhasználó vagy megrendelő által jóváhagyott tesztek, amelyek igazolják, hogy a rendszer megfelel az üzleti elvárásoknak.
  
- **Jest** - JavaScript teszt-keretrendszer unit és integrációs tesztekhez.  

- **Jasmine** - JavaScript teszt-keretrendszer viselkedésvezérelt(BDD) fejlesztéshez.  

- **Mocha** - Rugalmas JavaScript teszt-keretrendszer aszinkron tesztekhez.  


## Egyebek
- **Java/Swing** - Java könyvtár asztali GUI alkalmazásokhoz.
- Figyelj arra, hogy a válaszok között van olyan megoldás, ami nem is létezik pl: "Bingo", ami egy nem létező "JavaScript teszt-keretrendszer".
