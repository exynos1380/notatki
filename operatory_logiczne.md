# JavaScript #1:

Wyswietlanie tekstu

1. **Wyświetlenie tekstu w konsoli**
   ```javascript
   console.log("Hello World")

Wyświetla napis "Hello World" w konsoli.

    Wyświetlanie struktury dokumentu

`console.dir(document)`

Pokazuje szczegółową strukturę obiektu document, który reprezentuje całą stronę internetową.

Wyświetlanie danych w tabeli w konsoli

`console.table([1, 2, 3, 4, 5])`

Wyświetla tablicę [1, 2, 3, 4, 5] w postaci tabeli, co ułatwia analizowanie danych.

Wyświetlanie tekstu z zastosowaniem stylu CSS

`console.log("%ctekst", "color: red")`

Wyświetla tekst "tekst" w konsoli z zastosowaniem czerwonego koloru.

Wyświetlanie ostrzeżenia w konsoli

`console.warn("tekst1")`

Wyświetla komunikat "tekst1" jako ostrzeżenie, zazwyczaj wyróżnione żółtym kolorem.

Wyświetlanie tekstu bezpośrednio na stronie

    document.write("tekst do wyswietlenia")

    Bezpośrednio na stronie pojawi się tekst "tekst do wyswietlenia".

Operatory porównania:

  == (czy są równe)

5 == "5" // true (bo JavaScript konwertuje string "5" na liczbę 5)

Sprawdza, czy dwie wartości są równe, ale nie sprawdza typu. JavaScript konwertuje wartości przed porównaniem.

!= (czy są różne)

5 != "5" // false (bo JavaScript konwertuje string "5" na liczbę 5)

Sprawdza, czy dwie wartości są różne, ale nie sprawdza typu.

=== (czy są równe i mają ten sam typ)

5 === "5" // false (bo różnią się typem: liczba i string)

Sprawdza, czy dwie wartości są dokładnie równe i mają ten sam typ.

!== (czy są różne i mają różny typ)

5 !== "5" // true (bo różnią się typem: liczba i string)

Sprawdza, czy dwie wartości są różne lub mają różny typ.

> (większe niż)

10 > 5 // true

Sprawdza, czy pierwsza wartość jest większa od drugiej.

>= (większe lub równe)

10 >= 5 // true

Sprawdza, czy pierwsza wartość jest większa lub równa drugiej.

< (mniejsze niż)

5 < 10 // true

Sprawdza, czy pierwsza wartość jest mniejsza od drugiej.

<= (mniejsze lub równe)

5 <= 10 // true

Sprawdza, czy pierwsza wartość jest mniejsza lub równa drugiej.