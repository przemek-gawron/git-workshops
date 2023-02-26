# Git Workshops 

#### 1. **:books:Wstęp teoretyczny** 
- co to jest git / github :thinking:
- jakie problemy rozwiązuje
- podstawowe pojęcia repozytorium, commit, branch, merge, pull-request
- zastosowania gita do innych rzeczy niż programowanie

#### 2. :wrench: Przygotowanie środowiska do pracy z git/github
- zainstalowanie gita/vs code<br>
- założenie konta na github<br>
- utworzenie klucza SSH na github <br>
#### 3. :file_folder: Zakładanie repozytorium na github 
- używanie terminala i nawigacja do folderu, w którym chcemy załoyć repozytorium  
- założenie nowego repozytorium na github 
- inicjalizowanie repozytorium lokalnego
- dodanie remote do lokalnego repozytorium 
- utworzenie brancha
- dodanie pierwszego commita
- push nowego brancha do github


#### :pencil: Ćwiczenie 1 - Utworzenie nowego repozytorium 
Utworzyć nowe repozytorium na github i zainicjalizować nowe repozytorium lokalne.<br>
Dodać remote do repozytorium lokalnego.<br>
Dodać jeden commit i zrobić push zmian na zdalne repozytorium <br>


#### ** 4. :twisted_rightwards_arrows: Merge branchy, otwieranie PR, review kodu** 
#### :pencil: Ćwiczenie 2 - Łączenie nowych zmian (merge) 
Działając na repozytorium z poprzedniego zadania otworzyć nowy branch i dodać plik README.md.<br>
Otworzyć i opisać PR, dodanie revierów wśród uczestników warsztatów i merge po otrzymaniu approve.<br>


#### **5. :crossed_swords: Konflikt podczas PR, i jak się go rozwiązuje** 
#### :pencil: Ćwiczenie 3 - rozwiązywanie konfliktów 
Pobrać repozytorium https://github.com/przemek-gawron/git-workshops.git <br>
Przełączyć się na branch *conflict* i dodać kod i spróbować zrobić merge z branchem *master* <br>
Rozwiazać konflikty w VS Code i zrobić merge do głównego brancha <br>


#### **6. :leftwards_arrow_with_hook: Dlaczego możemy chcieć cofnąć się do poprzedniej wersji kodu** 
#### :pencil: Ćwiczenie 4 - powrót do poprzedniej wersji kodu (revert/reset) 
Przełączyć się na branch *revert* z repozytorium https://github.com/przemek-gawron/git-workshops.git<br>
Otworzyć *index.html* w przeglądarce i zaobserwować błąd<br>
Sprwadzić numery commitów za pomocą *git log* i cofnąć do momentu kiedy strona będzie działać poprawnie <br>

#### **7. :cherries: Używanie cherry-pick i sytuacje kiedy może się przydać** 
#### :pencil: Ćwiczenie 5 - Cherry-pick utoworzonych zmian 
Utworzyć nowy branch w repozytorium https://github.com/przemek-gawron/git-workshops.git <br>
Przełączyć się na branch *cherry-pick* i pobrać hash commita o nazwie *important_commit* <br>
Przełączyć się spowrotem na nowo utworzony branch i zrobić cherry-pick tego ważnego commita <br>


