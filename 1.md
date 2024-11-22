Java Script #1

Wyswitlanie tekstu 	

    1. Wyświetlenie tekstu w konsoli 
    `console.log("Hello World")`
    Wyświetla napis "Hello World" w konsoli.

    2. Wyświetlanie struktury dokumentu
	` console.dir(document)`
    Pokazuje szczegółową strukturę obiektu document, który reprezentuje całą stronę internetową.
	
	3. Wyświetlanie danych w tabeli w konsoli
    `console.table([1, 2, 3, 4, 5])`
    Wyświetla tablicę [1, 2, 3, 4, 5] w postaci tabeli, co ułatwia analizowanie danych.

    4. Wyświetlanie tekstu z zastosowaniem stylu CSS
    `console.log("%ctekst", "color: red")`
    5. Wyświetla tekst "tekst" w konsoli z zastosowaniem czerwonego koloru.

    6. Wyświetlanie ostrzeżenia w konsoli
    `console.warn("tekst1")`
    Wyświetla komunikat "tekst1" jako ostrzeżenie, zazwyczaj wyróżnione żółtym kolorem.
	
	7.	Wyswietlanie tekstu bezposrednio na stronie
	`document.write("tekst do wyswietlenia")
	Wyswietla tekst bezposrednio na stronie o tresci "tekst do wyswietlenia

Operatory porównania:

    == (czy są równe)
    Sprawdza, czy dwie wartości są równe, ale nie sprawdza typu. Jeśli porównywane wartości mają różne typy, JavaScript stara się je skonwertować do tego samego typu przed porównaniem.
    Przykład:
    `5 == "5" // true (bo JavaScript konwertuje string "5" na liczbę 5)`

    != (czy są różne)
    Sprawdza, czy dwie wartości są różne, ale nie sprawdza typu.
    Przykład:
    `5 != "5" // false (bo JavaScript konwertuje string "5" na liczbę 5)`

    === (czy są równe i mają ten sam typ)
    Sprawdza, czy dwie wartości są dokładnie równe i mają ten sam typ. Jest to bardziej restrykcyjne porównanie niż ==.
    Przykład:
    `5 === "5" // false (bo różnią się typem: liczba i string)`

    !== (czy są różne i mają różny typ)
    Sprawdza, czy dwie wartości są różne lub mają różny typ.
    Przykład:
   ` 5 !== "5" // true (bo różnią się typem)`

    > (większe niż)
    Sprawdza, czy pierwsza wartość jest większa od drugiej.
    Przykład:
    `10 > 5 // true`

    >= (większe lub równe)
    Sprawdza, czy pierwsza wartość jest większa lub równa drugiej.
    Przykład:
    `10 >= 5 // true`

    < (mniejsze niż)
    Sprawdza, czy pierwsza wartość jest mniejsza od drugiej.
    Przykład:
    `5 < 10 // true`
	
    <= (mniejsze lub równe)
    Sprawdza, czy pierwsza wartość jest mniejsza lub równa drugiej.
    Przykład:
    `5 <= 10 // true`