console.log("Hello World")
console.dir(document)
console.table([1, 2, 3, 4, 5])
console.log("%cmetro", "color: red")
console.warn("UWAGA S.T.A.L.K.E.R FANBOY!")

//document.write("java script <br>")
    //okno informacyjne
    //alert("Masz bana")
    //okno decyzyjne
    //console.log(confirm("Czy lubisz Metro?"))
    //okno tekstowe
    //console.log(prompt("Czy lubisz Metro", "TAK!"))

//zmienne
var i = 1.44
let a = 2
const b = 20
let bardzoDlugaZmienna = "camelCase"

// Tworzymy zmienne opisujace telefon, kozystamy z camelCase, zmienne powinny uzwierciedlac jego zawartosc


let markaTel = "Samsung"
let modelTel = "A52"
let kolor = "czarny"
let rokProd = 2021;
let pojBaterii = 4500;
console.log("Marka:", markaTel)
console.log("Model:", modelTel)
console.log("Kolor:", kolor)
console.log("Rok produkcji:", rokProd)
console.log("Pojemnosc baterii:", pojBaterii)

let koltel = "czarny";
console.log(`Kolor telefonu: ${koltel}`)
console.log(`Suma 1 i 3: ${1+3}`)

//operatory arytmetyczne
//+, -, *, /

console.log(`Potegowanie: ${2**3}`)
console.log(`Potegowanie: ${Math.pow(2,3)}`)
console.log(`Pierwiastkowanie: ${Math.sqrt(16,2)}`)

//operatory przypisania
let o = 5;
o = o + 2;
o += 2;
console.log(o)

let p = 6;
p++;
console.log(p++)
console.log(p)


//operatory porównania:
// == (czy są równe)
// !=(czy są różne)
// === (czy są równe i mają ten sam typ)
// !== (czy są różne i mają różny typ)
// >,>=,<,<=

//operatory logiczne:
// && - AND
// || - OR
// ! - NOT

//instrukcje warunkowe:
/*let c1 = 6;
if (c1 > 0) {
    document.write("Liczba jest dodatnia")
} else if (c1 = 0) {
    document.write("Liczba jest równa zero")
} else
    document.write("Liczba jest ujemna")

if (c1 > 10 && c1 < 30) {
    document.write(" Liczba należy do przedziału 10-30")
} else {
    document.write(" Liczba nie należy do przedziału 10-30")
}*/

//instrukcje switch
/*let liczba_ = parseInt(prompt("Podaj liczbę: "))
switch (liczba_) {
    case 1:
        console.log("Jeden")
        break
    case 2:
        console.log("Dwa")
        break
    case 3:
        console.log("Trzy")
        break
    case 4:
        console.log("Cztery")
        break
    default:
        console.log("Podana liczba nie nalezy do przedziału 1-4")
}*/

/*let liczba1 = parseFloat(prompt("Podaj pierwszą liczbę: "))
let znak = prompt("Podaj operator arytmetyczny: ")
let liczba2 = parseFloat(prompt("Podaj drugą liczbę: "))

switch (znak) {
    case "+":
        document.write(liczba1 + liczba2)
        break
    case "-":
        document.write(liczba1 - liczba2)
        break
    case "/":
        document.write(liczba1 / liczba2)
        break
    case "*":
        document.write(liczba1 * liczba2)
        break
    default:
        document.write(" Błędne dane")
}*/

//https://www.onlinegdb.com/SCYU1SKR8B

//1
/*let a1 = parseFloat(prompt("Wpisz pierwsza liczbe: "))
let b1 = parseFloat(prompt("Wpisz druga liczbe: "))
let x1 = "";

if (b1 === 0) {
    document.write("Nie można dzielic przez 0! <br>")
}
else if (isNaN(a1) || isNaN(b1)){
    document.write("Podano błędne dane! <br>") 
}
else {
    x1=a1/b1;
    document.write("Wynik dzielenia: " + x1  + "<br>")
}
*/

//2 
/*let a2 = parseFloat(prompt("Wpisz pierwsza liczbe: "))
let b2 = parseFloat(prompt("Wpisz druga liczbe: "))
let c2 = parseFloat(prompt("Wpisz trzecia liczbe: "))
let d2 = parseFloat(prompt("Wpisz czwarta liczbe: "))
let x2 = "";

if (b2 === 0 || d2 === 0) {
    document.write("Nie można dzielic przez 0! <br>")
}
else if (isNaN(a2) || isNaN(b2) || isNaN(c2) || isNaN(d2)){
    document.write("Podano błędne dane! <br>") 
}
else {
    x2=a2/b2 + c2/d2;
    document.write("Wynik dzialania: " + x2  + "<br>")
}*/

//3
/*let a3 = parseFloat(prompt("Wpisz pierwsza liczbe: "))
let b3 = parseFloat(prompt("Wpisz druga liczbe: "))
let x3 = "";

if (b3 === 4) {
    document.write("Nie można dzielic przez 0! <br>")
}
else if (isNaN(a3) || isNaN(b3)){
    document.write("Podano błędne dane! <br>") 
}
else {
    x3= (a3+6)/(b3-4);
    document.write("Wynik działania: " + x3  + "<br>")
}*/

//4 

/*x4 = parseFloat(prompt("Podaj liczbe: "))

if (isNaN(x4)){
    document.write("Podano bledne dane!")
}
else {switch (true) {
    case x4 % 8 === 0:
        document.write(`Liczba ${x4} dzieli się przez 8`)
        break
    case x4 % 4 === 0:
        document.write(`Liczba ${x4} dzieli się przez 4`)
        break
    case x4 % 2 === 0:
        document.write(`Liczba ${x4} dzieli się przez 2`)
        break
    default:
        document.write(`Liczba ${x4} nie dzieli się ani przez 8 ani przez 4 ani nawet przez 2`)
}}*/

//5 

/*function ocena(){
const form = document.getElementById("formularz");

    
    let x5 = parseInt(document.getElementById("numberInput").value);

    if (x5 >= 0 && x5 <= 100) {
        document.write("Liczba z przedziału 0..100");
    } else if (x5 >= 101 && x5 <= 200) {
        document.write("Liczba z przedziału 101..200");
    } else if (x5 >= 201 && x5 <= 300) {
        document.write("Liczba z przedziału 201..300");
    } else if (x5 >= 301 && x5 <= 400) {
        document.write("Liczba z przedziału 301..400");
    } else if (x5 >= 401 && x5 <= 500) {
        document.write("Liczba z przedziału 401..500");
    } else if (x5 > 500) {
        document.write("Liczba większa od 500");
    } else {
        document.write("Podana liczba jest nieprawidłowa");
    }
}*/

//7 
/*let miesiac = parseFloat(prompt("Podaj nazwe miesiaca: "));

switch(miesiac){
    case 1:
        document.write("Styczeń")
    break
    case 2:
        document.write("Luty")
    break
    case 3:
        document.write("Marzec")
    break
    case 4:
        document.write("Kwiecień")
    break
    case 5:
        document.write("Maj")
    break
    case 6:
        document.write("Czerwiec")
    break
    case 7:
        document.write("Lipiec")
    break
    case 8:
        document.write("Sierpień")
    break
    case 9:
        document.write("Wrzesień")
    break
    case 10:
        document.write("Październik")
    break
    case 11:
        document.write("Listopad")
    break
    case 12:
        document.write("Grudzień")
    break
    default:
        document.write("Podano błędne dane!")
}*/

//8 
/*function ocena(){
    const form = document.getElementById("formularz");
    
        
        let x5 = parseInt(document.getElementById("numberInput").value);
        let wynik = document.getElementById("wynik");
        switch(x5){
            case 1:
                wynik.innerHTML="Brak promocji do następnej klasy";
                
                break
            case 2:
            case 3:
            case 4:
            case 5:
                wynik.innerHTML="Promocja do następnej klasy";
                break
            case 6:
                wynik.innerHTML="Promocja z oceną celującą";
                break
            default:
                wynik.innerHTML="Podano błędne dane!";
        }
    }*/
//6
/*const form = document.getElementById("formularz6");


function liczby(){
let liczba1 = parseFloat(document.getElementById("liczba1").value);
let liczba2 = parseFloat(document.getElementById("liczba2").value);
let liczba3 = parseFloat(document.getElementById("liczba3").value);

let wynik = document.getElementById("wynik6");

    if(liczba1 >= liczba2){
        if(liczba1 >= liczba3){
            wynik.innerHTML=`Liczba ${liczba1} jest największą liczbą`;
        }
        else{
            wynik.innerHTML=`Liczba ${liczba3} jest największą liczbą`;
        }
    }
    else if(liczba2 >= liczba3){
        wynik.innerHTML=`Liczba ${liczba2} jest największą liczbą`;
    }
    else if(isNaN(liczba1) || isNaN(liczba2) || isNaN(liczba3)){
        wynik.innerHTML="Podano błędne dane";
    }
    else{
        wynik.innerHTML="Podano błędne dane";
    }
    //albo 
    if (liczba1 >= liczba2 && liczba1 >= liczba3) {
        wynik.innerHTML=`Liczba ${liczba1} jest największą liczbą`;
    } else if (liczba2 >= liczba1 && liczba2 >= liczba3) {
        wynik.innerHTML=`Liczba ${liczba2} jest największą liczbą`;
    } else {
        wynik.innerHTML=`Liczba ${liczba3} jest największą liczbą`;
    }

}*/

const form = document.getElementById("formularz9");

function Zajecia(){
    let godzina = parseInt(document.getElementById("godzina").value)
    let wynik="";

    if(godzina>=8){
        wynik+="godzina 8 śniadanie <br>"
    }
    if(godzina>=9) {
        wynik+="godz. 9-10 wykład <br>"
    }
    if(godzina>=11) {
        wynik+="godz. 11-13 zajęcia w grupach <br>"
    }
    if(godzina>=14) {
        wynik+="godz. 14 obiad <br>"
    }
    if(godzina>=15) {
        wynik+="godz. 15-17 film <br>"
    }
    if(godzina>=18) {
        wynik+="godz. 18-19 kolacja <br>"
    }
    
   document.getElementById("wynik9").innerHTML = wynik;
    
}


