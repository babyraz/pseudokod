# Pseudokod: Split The Nota
Be användaren om ett nummer och spara detta i variabeln Summa
Be användaren om ett nummer och spara detta i variabeln Antal
Be användaren om ett nummer och spara detta i variabeln Dricks

Kontrollera att samtliga variabler är siffror
Om inte, visa felmeddelande och be användaren fylla i ett nytt värde
Kontrollera att variablerna Summa och Antal är större än noll
Om inte, visa felmeddelande och be användaren fylla i ett nytt värde

Räkna ut Summa x (1+Dricks) / Antal och spara i variabeln Resultat

Skriv ut “Varje person ska betala (Resultat) kr”
<img width="546" alt="Screenshot 2024-12-20 at 08 39 20" src="https://github.com/user-attachments/assets/cdb78cc4-ac92-40e5-a02d-e9a8a3d50d1c" />
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Pseudokod: Lewis Caroll Word Puzzle

Skapa variabeln Ordbok och lagra ord i en lista som är relevanta för start- och slutorden
Skapa variabel för Startord och Slutord och fyll dom med valda ord för pusslet
Skapa variabel Input och lämna den tom
Skapa variabel tempInput och lämna den tom
Skriv ut Startord och Slutord
Be användaren att skriva ett ord och spara det i variabeln Input

Kontrollera att Input är ett av orden i listan Ordbok
Om kravet inte uppfylls:
Visa felmeddelande och be användaren mata in nytt ord
Om kravet uppfylls:
Kontrollera att det inte har ändrats fler eller färre en 1 bokstav genom funktionen KONTROLL
Om Resultat= Nej
Visa felmeddelande och be användaren mata in nytt ord
Om Resultat = Ja
Kontrollera om Input är samma som Slutord
Om kravet uppfylls:
Skriv ut “Grattis, du vann!”.
Om kravet inte uppfylls:
Spara Input i tempInput

Funktion KONTROLL
Skapa variabel Resultat
Funktionen kontroll hämtar Input och tempInput från huvudfunktionen
Funktionen jämför varje bokstav i Input och tempInput
Om mer eller mindre än en bokstav skiljer sig, Nej variabeln Resultat
Om inte eller om variabel Resultat är tom, spara Ja i variabeln Resultat
Skicka tillbaka variabeln Resultat till huvudfunktionen

<img width="320" alt="Screenshot 2024-12-20 at 08 40 01" src="https://github.com/user-attachments/assets/05be75ed-fd89-400d-92de-af18a7b0b50b" />

