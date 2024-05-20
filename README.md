# tema_de_casa_PA
- Autor:Capatina Ecaterina-Mihaela
- CR1.1A
- 1).Enuntul problemei:
"Un pescar exploreaza o regiune de coasta bogata in homari, fiecare
avand propria sa dimensiune (in centimetri) si valoare (in monede de
aur). Plasa pescarului are o capacitate limitata, exprimata in numarul
total de centimetri pe care ii poate contine. Avand o lista detaliata cu
dimensiunile si valorile homarilor disponibili in acea regiune, sarcina
este sa se elaboreze o strategie prin care pescarul sa selecteze homarii
in asa fel incat sa maximizeze valoarea totala a capturii, respectand
in acelasi timp limita de capacitate a plasei. Trebuie sa se decida
care homari sa fie inclusi in plasa si care sa fie lasati, astfel incat
suma valorilor homarilor selectati sa fie cea mai mare posibila, fara
ca suma dimensiunilor acestora sa depaseasca capacitatea plasei.
Imaginati-va un scenariu in care un pescar are oportunitatea de a
alege dintre o selectie de homari, fiecare cu o dimensiune si o valoare
specificate, pentru a umple plasa sa care are o capacitate maxima.
Scopul pescarului este de a maximiza valoarea totala a capturii sale
fara a depasi limita de dimensiune a plasei.
Iata un exemplu:
Homari disponibili:
- Homarul A: Dimensiune = 4 cm, Valoare = 20 monede de aur
- Homarul B: Dimensiune = 3 cm, Valoare = 15 monede de aur
- Homarul C: Dimensiune = 2 cm, Valoare = 10 monede de aur
- Homarul D: Dimensiune = 5 cm, Valoare = 25 monede de aur
Capacitatea plasei: 10 cm

Provocarea este de a selecta combinatia de homari care maximizeaza
valoarea totala fara a depasi o dimensiune totala de 10 cm.

O posibila solutie ar implica alegerea homarilor A si C, oferindu-ne
o dimensiune totala de 6 cm (4 cm + 2 cm) si o valoare totala de 30
monede de aur (20 + 10). Totusi, o solutie mai buna ar fi sa alegem
homarii B, C si D, care impreuna au o dimensiune totala de 10 cm (3
cm + 2 cm + 5 cm) si ofera o valoare totala mai mare de 50 monede
de aur (15 + 10 + 25). Aceasta combinatie umple exact capacitatea
plasei si maximizeaza valoarea capturii."

- 2).Instructiuni pentru compilarea codului:
 - Fișierul main.c conține funcția principală care gestionează intrarea utilizatorului, generează date aleatorii pentru homari și calculează valoarea maximă folosind funcția knapsack.
 - Fișierul antet knapsack.h conține declarația funcției knapsack.
 - Fișierul knapsack.c conține implementarea funcției knapsack, care rezolvă problema rucsacului folosind programare dinamică.
 - Programul va solicita introducerea numărului de homari și a capacității plasei, va genera datele și va salva rezultatele în fișierul Data/output.txt. Acesta va contine toti homarii disponibili(numarul) alaturi de valorile si dimensiunile lor,capacitatea maxima a plasei date de utilizator,valoarea maximizata calculata si combinatia cea mai favorabila care a dus la solutie.
- Astfel utilizatorul intereactioneaza in mod direct cu aplicatia furnizand datele de test.
