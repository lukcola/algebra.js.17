1) QUEST_ID: 76088 Potrebno je HTML dokumentu dodijeliti naslov "My Portfolio". 
Sta je potrebno napisati unutar <head> oznake HTML dokumenta kako bi se to postiglo?
	
1.	<title>My Portfolio</title>     //// TOCNO
2.	<hl>My Portfolio</hl>
3.	<header>My Portfolio</hl>
4.	Zadatak nije moguce rijesiti u HTML

2) QUEST_ID: 76120 Koji element koristimo za oznacavanje sadrzaja koji predstavlja glavnu navigaciju?
	
1.	<navigation>
2.	<menu>
3.	<nav>  //// TOCNO
4.	Zadatak niie moquce riiesiti u HTML

3) QUEST ID: 76121 Sta je HTML?

HyperTextMarkupLanguage, prezentacijski jezik (jezik označavanja) za kreiranje web stranica,
sluzi za definiciju pojedinih komponenti od kojih se sastoji web stranica 

4) QUEST_ID: 76087 Zadan je sadrzaj: https://example.com/good-song.mp3 Koristeci HTML, oznacite sadrzaj kao audio zapis sa kontrolama za 
upravljanje reprodukcijom sadrzaja. Zadatak je potrebno rijesiti u dostupnom code editoru.

<audio controls> 

<source src="https://example.com/good-song.mp3" type="audio/mpeg"> 

</audio>

Ili

<audio src=" https://example.com/good-song.mp3" controls></audio>

5) QUEST_ID: 76432 Preuzmite upute za rjesavanje zadatka te vodeci se temom opisanom u pdf dokumentu izradite HTML dokument koji sadrzi strukturu 
korisnickog sucelja aplikacije s obrascem i dvije unaprijed pohranjene stavke. Zadatak rijesite u Visual Studio Codu. 
Rjesenje pohranite u obliku HTML dokumenta i prilozite u .zip formatu u polje
za upload datoteke u isoitnoi aolikaciii.

<!DOCTYPE html>
<html lang=""en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplikacija sa obrascem</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #50b3a2;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #2980b9 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        #main {
            padding: 30px;
            background: #fff;
            margin-top: 30px;
        }
        #items {
            margin: 20px 0;
        }
        .item {
            padding: 10px;
            border: #ccc 1px solid;
            background: #e4e4e4;
            margin-bottom: 5px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Aplikacija sa obrascem</h1>
            <nav>
                <ul>
                    <li><a href="#">Početna</a></li>
                    <li><a href="#">O nama</a></li>
                    <li><a href="#">Kontakt</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div id="main" class="container">
        <h2>Dodaj novu stavku</h2>
        <form id="itemForm">
            <div>
                <label for="item">Stavka:</label>
                <input type="text" id="item" name="item" required>
            </div>
            <div>
                <button type="submit">Dodaj</button>
            </div>
        </form>
        <div id="items">
            <h2>Stavke</h2>
            <div class="item">Stavka 1</div>
            <div class="item">Stavka 2</div>
        </div>
    </div>
    <script>
        document.getElementById('itemForm').addEventListener('submit', function(e) {
            e.preventDefault();
            var itemText = document.getElementById('item').value;
            var newItem = document.createElement('div');
            newItem.className = 'item';
            newItem.appendChild(document.createTextNode(itemText));
            document.getElementById('items').appendChild(newItem);
            document.getElementById('item').value = '';
        });
    </script>
</body>
</html>

6)  QUEST_ID: 76126 Kako HTML omogucuje izradu pristupacnih web stranica?

Pristupačnost internetskih stranica odnosi se na dizajn i razvoj web sadržaja koji omogućuje svim korisnicima, uključujući one s invaliditetom, 
da ih mogu koristiti. HTML igra ključnu ulogu u osiguravanju pristupačnosti web stranica

Mogućnost da se web rješenje koristi prema potrebama i mogućnostima korisnika.

Postiže se:
	
primjenom semantičkih HTML elemenata, pravilnom definicijom HTML atributa (npr. "alt" kao zamjenski tekst za grafike, "role" za davanje značenja elementima, 
"lang" kao oznaka jezika sadržaja itd.)
osiguranjem tekstualnog sadržaja kao alternative za ne-tekstualni sadržaj (npr. tekstualni transkript za audio sadržaj)
omogućavanjem korisnicima da prilagode vlastito sučelje (veličinu znakova, boje itd.)

7) QUEST_ID: 76127 Koji od navedenih elemenata je najprikladnije koristiti za oznacavanje sadrzaja koji nije direktno povezan sa sadrzajem koji ga okruzuje?
	
1.	<aside> //// TOCNO
2.	<section>
3.	<div>
4.	Nista ad navedenoq

8) QUEST_ID: 76128 Koji ad navedenih elemenata je najprikladnije koristiti za oznacavanje uvodnog sadrzaja?
	
1.	<div>
2.	<head>
3.	<header> //// TOCNO
4.	Nista ad navedenoq

9) QUEST_ID: 76130 HTML dokument ne smije sadrzavati vise ad jednog <article> elementa.
 
1.	Tocno
2.	Netocno  //// TOCNO

10) QUEST_ID: 76183 Koji HTML atribut koristimo za primjenu linijskih stilskih pravila?
	
1.	css
2.	styles
3.	style //// TOCNO
4.	Zadatak nije moquce riiesiti u CSS

11) QUEST_ID: 76185 Koji selektor ce selektirati sve <a> elemente koji se nalaze pod pokazivacem misa?
	
1.	a#hover
2.	a.hover
3.	a:hover //// TOCNO
4.	Zadatak niie moquce riiesiti u CSS

12) QUEST_ID: 76187 Sta je potrebno napisati da bi se iskoristila CSS3 varijabla "color- primary" kao vrijednost za promjenu boje teksta?
	
1.	color: var(--color-primary);  //// TOCNO
2.	color: --color-primary;
3.	color: color-primary;
4.	Zadatak niie moquce riiesiti u css

13) QUEST_ID: 76171 Zadan je prazan <div> element. Koristeci CSS, selektirajte element i uredite ga tako da odgovara obliku na slici. 
    Pretpostavite velicine i boje, one ne moraju biti u potpunosti tocne. Zadatak je potrebno rijesiti u dostupnom code editoru.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stilizirani Div</title>
    <style>
        div {
            width: 200px;
            height: 100px;
            background-color: #3498db; 
            border: 2px solid #2980b9; 
            border-radius: 15px; 
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.3);
            margin: 20px;
        }
    </style>
</head>
<body>
    <div></div>
</body>
</html>

14) QUEST_ID: 76435 Preuzmite skicu dizajna korisnickog sucelja web aplikacije. Izradite CSS dokument koji ureduje projekt izraden u prethodnom koraku 
tako da raspored elemenata korisnickog sucelja odgovora rasporedu elemenata u skici dizajna. Dizajn za mobilne uredaje mora biti primijenjen na ekranima 
sirine do 768px ukljucivo, a dizajn za racunala mora biti primijenjen na ekranima sirine vece od 768px iskljucivo. css dokument
mora biti povezan s projektom kao vanjska lista stilskih pravila. Izbor boja, tipografije, i ostalih vizualnih elemenata koji se ne ticu rasporeda 
elemenata na sucelju je proizvoljan. Proiekt oohranite i orilozite u .ZIP arhivi.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplikacija sa obrascem</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Aplikacija sa obrascem</h1>
            <nav>
                <ul>
                    <li><a href="#">Početna</a></li>
                    <li><a href="#">O nama</a></li>
                    <li><a href="#">Kontakt</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div id="main" class="container">
        <h2>Dodaj novu stavku</h2>
        <form id="itemForm">
            <div>
                <label for="item">Stavka:</label>
                <input type="text" id="item" name="item" required>
            </div>
            <div>
                <button type="submit">Dodaj</button>
            </div>
        </form>
        <div id="items">
            <h2>Stavke</h2>
            <div class="item">Stavka 1</div>
            <div class="item">Stavka 2</div>
        </div>
    </div>
    <script>
        document.getElementById('itemForm').addEventListener('submit', function(e) {
            e.preventDefault();
            var itemText = document.getElementById('item').value;
            var newItem = document.createElement('div');
            newItem.className = 'item';
            newItem.appendChild(document.createTextNode(itemText));
            document.getElementById('items').appendChild(newItem);
            document.getElementById('item').value = '';
        });
    </script>
</body>
</html>

Css dio:

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

header {
    background: #50b3a2;
    color: #fff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #2980b9 3px solid;
}

header a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 16px;
}

header ul {
    padding: 0;
    list-style: none;
}

header li {
    display: inline;
    padding: 0 20px 0 20px;
}

#main {
    padding: 30px;
    background: #fff;
    margin-top: 30px;
}

#items {
    margin: 20px 0;
}

.item {
    padding: 10px;
    border: #ccc 1px solid;
    background: #e4e4e4;
    margin-bottom: 5px;
}

@media (max-width: 768px) {
    .container {
        width: 90%;
    }

    header ul {
        text-align: center;
    }

    header li {
        display: block;
        padding: 10px 0;
    }

    #main {
        padding: 20px;
    }

    .item {
        font-size: 14px;
    }
}

@media (min-width: 769px) {
    .container {
        width: 70%;
    }

    header ul {
        float: right;
    }

    header li {
        display: inline;
    }

    #main {
        padding: 40px;
    }

    .item {
        font-size: 16px;
    }
}


15) QUEST_ID: 76221 Potrebno je pozvati SCSS funkciju "lighten". Kaja od navedenih linija koda je ispravna?

1.	@import lighten(red, 30%); //// TOCNO
2.	lighten(red, 30%);
3.	@mixin lighten(red, 30%);
4.	@use lighten(red, 30%);

16) QUEST_ID: 76217 Potrebno je iskoristiti SCSS mixin "square". Kaja od navedenih linija koda je ispravna?

1.      @use square;
2.	@mixin square; //// TOCNO
3.	square();
4.	@include square·

17) QUEST_ID: 76219 Sto je to minifikacija (minimizacija)? Zasto koristiti minifikaciju?

Minifikacija je proces uklanjanja svih nepotrebnih znakova iz izvornog koda bez promjene njegove funkcionalnosti. 
To uključuje uklanjanje razmaka, komentara, novih linija i povremenih nepotrebnih znakova koji se koriste za čitljivost koda. 
Minifikacija se najčešće primjenjuje na HTML, CSS i JavaScript datoteke.

18) QUEST_ID: 76229 Sto se od navedenog ne koristi za petlju?

1.	for
2.	do-while
3.	while
4.	while-do //// TOCNO

19) QUEST_ID: 76231 Stood navedenog nije ispravan identifikator varijable?

1.	numberl
2.	number-1 //// TOCNO
3.	$numberl
4.	number 1

20) QUEST_ID: 76232 Koja je razlika izmedu deklariranja varijable pomocu kljucne rijeci "let" i "const"?

Razlika izmedju cont i let je ta da je vrijednost const varijable nepromjenjiva. 
let varijabla nije jednako striktna i ona ce prihvatiti drugu vrijednost ako joj je dodijelimo, kao i var varijabla.

ili

let: varijabla može da mjenjati vrjednost tokom izvršavanja programa, kao što su brojači u petljama ili privremene promenljive.
const: koristi se kada želimo da vrjednost varijable ostane nepromenjiva (konstantna) tokom izvršavanja programa, 
što je često korisno za definiranje vrjednosti koje se ne trebaju mjenjati, kao što su konstante, 
fiksne vrednosti ili reference na objekte koji se ne menjaju.

21) QUEST_ID: 76233 Potrebno je definirati funkciju "max" koja ce vratiti veci od dva broja. 
Ako su brojevi jednaki, funkcija vraca prvi broj. Funkcija prima dva broja preko parametara. 
Pretpostavite da ce parametri uvijek biti brojevi. 
Primjer: max(l, 2) - funkcija vraca 2 max(l, 1) - funkcija vraca 1 Zadatak je potrebno rijesiti u dostupnom code editoru.


function max(num1, num2) {
    if (num1 >= num2) {
        return num1;
    } else {
        return num2;
    }
}

// Primjer poziva funkcije
console.log(max(5, 2)); // Output: 5
console.log(max(1, 3)); // Output: 3
console.log(max(4, 4)); // Output: 4

ili 

function veciOdDva(broj1, broj2) {
    if (broj1 === broj2) {
        return broj1;
    } else if (broj1 > broj2) {
        return broj1;
    } else {
        return broj2;
    }
}

// Primjer poziva funkcije
console.log(veciOdDva(5, 10)); // Output: 10
console.log(veciOdDva(10, 5)); // Output: 10
console.log(veciOdDva(7, 7));  // Output: 7

22) QUEST_ID: 76436	Izradite JavaScript dokument koji omogucuje funkcionalnosti web aplikacije i korisnickog sucelja, 
a koje su opisane u kriterijima zadatka. Kriteriji zadatka nalaze se u dokumentu s temom koji ste ranije preuzeli. 

?

23) QUEST_ID: 76267 JavaScript je objektno-orijentirani programski jezik.
	
1.	Tocno //// TOCNO
2.	Netocno

24) QUEST_ID: 76268 JavaScript je funkcijski programski jezik.
	
1.	Tocno //// TOCNO
2.	Netocno

25) QUEST_ID: 76269 Sta je ECMAScript?

ECMAScript je ključni standard koji definira jezične karakteristike i specifikaciju JavaScripta, čime se omogućava interoperabilnost i 
unapređenje jezika kroz redovno ažuriranje standarda.

ECMAScript je skriptni programski jezik koji čini osnovu za JavaScript, JScript i ActionScript. 
Definiran je standardom ECMA-262, koji je razvio Ecma International. ECMAScript pruža osnovne funkcionalnosti jezika koje se koriste za izradu web aplikacija 
i web stranica. Njegova najpoznatija implementacija je JavaScript, koji se koristi za izradu dinamičkih i interaktivnih web stranica.

26) QUEST_ID: 76305 Sta HTML DOM ne definira?
	
1.	HTML elemente kao objekte
2.	Metode pristupa i manipulacije s HTML elementima
3.	Metode pristupa i manipulacije s prozorom preglednika  //// TOCNO
4.	Svoistva svih HTML elemenata

27) QUEST_ID: 76306 Kaja od navedenih metoda koje postoje nad "document" objektom nije ispravna?
	
1.	document.getElementByld()  
2.	document.querySelector()
3.	document.querySelectorAII()
4.	document.qetElementByClassName() //// TOCNO

28) QUEST_ID: 76307 Na stranici se nalazi copyright element i unutar njega element s ID-jem "copyright-year". 
Zeljeno ponasanje je da se unutar elementa s ID-jem "copyright-year" ispise trenutna godina. 
Koristeci JavaScript, napisite kod koji ce realizirati zeljeno ponasanje. (zadatak rijesiti u dostupnom code editoru)


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Copyright Year Example</title>
</head>
<body>
    <div id="copyright">
        &copy; <span id="copyright-year"></span>
    </div>

    <script>
        // Dohvatite element sa ID-jem "copyright-year"
        var yearElement = document.getElementById('copyright-year');

        // Postavite sadržaj elementa na trenutnu godinu
        yearElement.textContent = new Date().getFullYear();
    </script>
</body>
</html>

29) QUEST_ID: 76341 Git je distribuirani sustav za verzioniranje koda.
	
1.	Tocno //// TOCNO
2.	Netocno

30) QUEST_ID: 76342 Sta je to repozitorij?

Repozitorij (ili skraćeno "repo") je mjesto gdje se pohranjuju podaci i datoteke koji čine verzionirani projekt ili softverski sustav. 
U kontekstu Git-a, repozitorij je osnovna jedinica za pohranu izvornog koda i povijesti promjena.

ili 

je mjesto nakojem se pohranjuju sve datoteke jednog projekta
Repozitoriji mogu biti lokalni ili na nekom posluzitelju (ovisno o sustavu za verzioniranje koji koristimo)
Na jednom repozitoriju moze raditi jedna ili vise osoba. Neki od popularnih repozitorija: GitHub, GitLab, Bitbucket

31) QUEST_ID: 76343 Kako se inicijalizira Git repozitorij?

git init	

32) QUEST_ID: 76378 Sta je task runner?

Task runner je alat koji omogućuje automatizaciju ponavljajućih zadataka koji se tipično rade ručno tijekom razvoja projekta.grunt, gulp

Ili

Task runner je alat koji automatizira ponavljajuće zadatke u procesu razvoja softvera, posebno web aplikacija. 
Pomaže u upravljanju i izvršavanju zadataka kao što su: Minifikacija datoteka, Sastavljanje (kompiliranje) CSS ili JavaScript koda, Optimizacija slika, 
pokretanje testova. 
Task runneri su važni jer pojednostavljuju i ubrzavaju proces razvoja, čineći ga efikasnijim i manje sklonim greškama.

33) QUEST_ID: 76377 Kako se instalira paket s nazivom algebra-library tako da se zapise u package.json datoteku?
	
npm install algebra-library --save
 
34) QUEST_ID: 76412 Child komponenta moze i smije mijenjati props objekt koji je primila od parent komponente.

1.	Tocno
2.	Netocno //// TOCNO

35) QUEST_ID: 76413 Stood navedenog nije jedna od faza zivotnog ciklusa React komponente?

1.	Inicijalizacija
2.	Postavljanje na DOM
3.	Resetiranje  //// TOCNO
4.	Brisanje iz DOM-a

36) QUEST_ID: 76421 Potrebno je u komponentu <User> postaviti prop "firstName". Odaberite ispravnu liniju koda.
1.	<User prop.firstName="John" />
2.	<User props.firstName="John" />
3.	<User firstName="John" />  //// TOCNO
4.	<User>{firstame: "John"}</User>
 

......

1a. bio je zadatak s kojim u css-u treba napraviti element s proizvoljnim vrijednostima. Izgleda ovako

div {
border: none;
padding: 50px;
height: 200px;
width: 200px;
background-color: red;
border-top-right-radius: 100%;
border-bottom-left-radius: 100%;
}
