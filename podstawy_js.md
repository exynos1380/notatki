### JavaScript #1

1. ## Wyświetlanie tekstu

    1. **Wyświetlenie tekstu w konsoli**
    ```javascript
    console.log("Hello World")
    ```
    Wyświetla napis "Hello World" w konsoli.

    2. **Wyświetlanie struktury dokumentu**
    ```javascript
    console.dir(document)
    ```
    Pokazuje szczegółową strukturę obiektu `document`, który reprezentuje całą stronę internetową.

    3. **Wyświetlanie danych w tabeli w konsoli**
    ```javascript
    console.table([1, 2, 3, 4, 5])
    ```
    Wyświetla tablicę `[1, 2, 3, 4, 5]` w postaci tabeli, co ułatwia analizowanie danych.

    4. **Wyświetlanie tekstu z zastosowaniem stylu CSS**
    ```javascript
    console.log("%ctekst", "color: red")
    ```
    Wyświetla tekst **"tekst"** w konsoli z zastosowaniem **czerwonego koloru**.

    5. **Wyświetlanie ostrzeżenia w konsoli**
    ```javascript
    console.warn("tekst1")
    ```
    Wyświetla komunikat **"tekst1"** jako ostrzeżenie, zazwyczaj wyróżnione **żółtym kolorem**.

    6. **Wyświetlanie tekstu bezpośrednio na stronie**
    ```javascript
    document.write("tekst do wyswietlenia")
    ```
    Wyświetla tekst **"tekst do wyswietlenia"** bezpośrednio na stronie.

---

# Operatory porównania:

1. **`==` (czy są równe)**
    Sprawdza, czy dwie wartości są **równe**, ale nie sprawdza typu. Jeśli porównywane wartości mają różne typy, JavaScript stara się je skonwertować do tego samego typu przed porównaniem.
    Przykład:
    ```javascript
    5 == "5" // true (bo JavaScript konwertuje string "5" na liczbę 5)
    ```

2. **`!=` (czy są różne)**
    Sprawdza, czy dwie wartości są **różne**, ale nie sprawdza typu.
    Przykład:
    ```javascript
    5 != "5" // false (bo JavaScript konwertuje string "5" na liczbę 5)
    ```

3. **`===` (czy są równe i mają ten sam typ)**
    Sprawdza, czy dwie wartości są **dokładnie równe** i mają **ten sam typ**. Jest to bardziej restrykcyjne porównanie niż `==`.
    Przykład:
    ```javascript
    5 === "5" // false (bo różnią się typem: liczba i string)
    ```

4. **`!==` (czy są różne i mają różny typ)**
    Sprawdza, czy dwie wartości są **różne** lub mają **różny typ**.
    Przykład:
    ```javascript
    5 !== "5" // true (bo różnią się typem)
    ```

5. **`>` (większe niż)**
    Sprawdza, czy pierwsza wartość jest **większa** od drugiej.
    Przykład:
    ```javascript
    10 > 5 // true
    ```

6. **`>=` (większe lub równe)**
    Sprawdza, czy pierwsza wartość jest **większa lub równa** drugiej.
    Przykład:
    ```javascript
    10 >= 5 // true
    ```

7. **`<` (mniejsze niż)**
    Sprawdza, czy pierwsza wartość jest **mniejsza** od drugiej.
    Przykład:
    ```javascript
    5 < 10 // true
    ```

8. **`<=` (mniejsze lub równe)**
    Sprawdza, czy pierwsza wartość jest **mniejsza lub równa** drugiej.
    Przykład:
    ```javascript
    5 <= 10 // true
    ```

