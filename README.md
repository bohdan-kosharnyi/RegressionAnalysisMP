# AnalysisNBA
![GOAT](goat.jfif "GOAT")
## Wstęp

Celem projektu jest wyznaczenie zależności pomiędzy tym, ile zawodnik średnio spędza minut na boisku za męcz, a innymi zmiennymi ze zbioru danych, zawierającego statystyki graczy NBA (ang. National Basketball Association) od roku 1991 do 2021. Zbiór zawiera 18044 obserwacji, czyli jest to suma zawodników, które brali udział w meczach NBA za te lata (nie jest liczba unikalnych graczy, ich - 540) oraz 31 statystykę. Wprowadźmy do zbioru zmienną *ID*, za pomocą której przekształcimy nasz zbiór w taki sposób, że będzie on zawierał średnie statystyki zdobyte koszykarzami za męcz wzdłuż ich kariery.

Projekt realizowany za pomocą języka R. Zobaczyć całą zawartość projektu można [tutaj](projekt.qmd) (to jest plik quatro) lub w już zbudowanym [html-u](projekt.html).
Tutaj jescze tylko dołączę podsumowanie projektu.

## Podsumowanie

Zbudowaliśmy 3 modeli opisujące badany związek. Reasumując otrzymane wyniki możemy zrobić wniosek, że mimo tego że predykcja modeli nie bardzo się różni, ale interpretacja modelu z transformowanymi zmiennymi jest tak trudna, że jest on najmniej możliwy do stosowania, w przypadku regresji kwantylowej jest nieco lepiej, ale najbardziej sensowną interpretacje otrzymujemy przy stosowaniu MARS.

Do czego moglibyśmy zastosować taki model? Np., młody koszykarz mógłby, korzystając z tego modelu, wybierać jaki ze swoich umiejętności mu trzeba polepszyć, żeby otrzymywać więcej czasu na boisku za mecz.
