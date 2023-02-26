# Git Workshops 

#### 1. **Wstęp teoretyczny** :books:
- co to jest git / github :thinking:
- jakie problemy rozwiązuje
- podstawowe pojęcia repozytorium, commit, branch, merge, pull-request
- zastosowania gita do innych rzeczy niż programowanie

#### 2. Zainstalowanie gita/vs code :wrench:

#### 3. Założenie konta na github :wrench:

#### 4. Setup SSH na github :wrench:

#### 5. Zakładanie repozytorium na github :file_folder:
- używanie terminala i nawigacja do folderu, w którym chcemy załoyć repozytorium  
- założenie nowego repozytorium na github 
- inicjalizowanie repozytorium lokalnego
- dodanie remote do lokalnego repozytorium 
- utworzenie brancha
- dodanie pierwszego commita
- push nowego brancha do github


#### Ćwiczenie 1 - Utworzenie nowego repozytorium :pencil:
Utworzyć nowe repozytorium na github i zainicjalizować nowe repozytorium lokalne.<br>
Dodać remote do repozytorium lokalnego.<br>
Dodać jeden commit i zrobić push zmian na zdalne repozytorium <br>


#### **6. Merge branchy, otwieranie PR, review kodu** :twisted_rightwards_arrows:
#### Ćwiczenie 2 - Łączenie nowych zmian (merge) :pencil:
Działając na repozytorium z poprzedniego zadania otworzyć nowy branch i dodać plik README.md.<br>
Otworzyć i opisać PR, dodanie revierów wśród uczestników warsztatów i merge po otrzymaniu approve.<br>


#### **7. Konflikt podczas PR, i jak się go rozwiązuje** :crossed_swords:
#### Ćwiczenie 3 - rozwiązywanie konfliktów :pencil:
Pobrać repozytorium https://github.com/przemek-gawron/git-workshops.git <br>
Przełączyć się na branch *conflict* i dodać kod i spróbować zrobić merge z branchem *master* <br>
Rozwiazać konflikty w VS Code i zrobić merge do głównego brancha <br>


#### **8. Dlaczego możemy chcieć cofnąć się do poprzedniej wersji kodu** :leftwards_arrow_with_hook:
#### Ćwiczenie 4 - powrót do poprzedniej wersji kodu (revert/reset) :pencil:
Przełączyć się na branch *revert* z repozytorium https://github.com/przemek-gawron/git-workshops.git<br>
Otworzyć *index.html* w przeglądarce i zaobserwować błąd<br>
Sprwadzić numery commitów za pomocą *git log* i cofnąć do momentu kiedy strona będzie działać poprawnie <br>

#### **9. Używanie cherry-pick i sytuacje kiedy może się przydać** :cherries:
#### Ćwiczenie 5 - Cherry-pick utoworzonych zmian :pencil:
Utworzyć nowy branch w repozytorium https://github.com/przemek-gawron/git-workshops.git <br>
Przełączyć się na branch *cherry-pick* i pobrać hash commita o nazwie *important_commit* <br>
Przełączyć się spowrotem na nowo utworzony branch i zrobić cherry-pick tego ważnego commita <br>


