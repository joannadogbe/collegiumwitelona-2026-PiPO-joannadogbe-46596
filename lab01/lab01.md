# Ściąga z komend Git - Lab 01

### 1. Inicjalizacja repozytorium
`git init` <br>
*Oznacza bieżący folder jako nowe repozytorium Git.*

`git remote add origin ADRES_REPOZYTORIUM` <br>
*Łączy lokalne repozytorium z serwerem zdalnym na GitHubie.*

---

### 2. Pobieranie zmian z serwera
`git pull origin master` <br>
*Ściąga i scala najnowsze zmiany z serwera do Twojego komputera.*

---

### 3. Wgrywanie nowych zmian na serwer
`git status` <br>
*Pokazuje stan plików (które zostały zmienione, dodane lub usunięte).*

`git add .` <br>
*Dodaje wszystkie zmodyfikowane pliki do obszaru przygotowawczego (staging).*

`git commit -am "Opis wykonanych zmian"` <br>
*Tworzy punkt zapisu (commit) z podanym komentarzem.*

`git push origin master` <br>
*Wysyła zapisane zmiany z lokalnego komputera na serwer GitHub.*
