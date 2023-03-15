# Todo-List 
Todo-List in vanilla JS including local storage. 


Lista rzeczy do zrobienia
Lista rzeczy do zrobienia w Vanilla JS, czystym kodzie JS bez frameworków. 
Lista zawiera header Todo List, pod spodem todo div z polem input, do wpisywania rzeczy do zrobienia.
Po wpisaniu rzeczy do zrobienia, dodajemy ją do listy klikając w todo-button z symbolem plus-square.
Rzecz do zrobienia możemy oznaczyć jako już wykonaną lub usunąć ją z listy.
Dodajemy wykonany element do Copleted klikając w coplete-btn z symbolem check, 
który po :hover ma zielony background-color, uruchamia transition z line-through oraz opacity: 0.5.
Usuwamy element z listy todo klikając w trash-btn z symbolem trash, który po :hover ma czerwony background-color. 
Po kliknięciu w trash-btn uruchamiamy transition z rotate oraz scale(0.01). Transitionend po animacji aktywuje remove. 
Używając drop-down list po prawej stronie todo div, możemy wyświetlić pogrupowane elementy z listy z value:
All, Completed lub Uncompleted. 
Elementy listy Todo List zapisywane są w pamięci lokalnej w formie JSON.
