# Instrukcja - instalacja zależności i uruchomienie aplikacji
## Instrukcja stworzona dla systemu Ubuntu

1. **Instalacja wirtualnego środowiska Python**
- ``` sudo apt install python3.x-venv ``` (_za x należy przyjąć wersję Pythona, np. 3.9_)
- należy wykonać polecenie ``` python3 -m venv nazwa_venv ```
- aktywuj wirtualne środowisko komendą ``` source nazwa_venv/bin/activate ```

2. **Instalacja Flask**
- ``` pip install flask ```

3. **Instalacja Curl**
- ``` sudo apt install curl ```

4. **Uruchomienie aplikacji**
- ``` make ``` _tutaj wstawiamy Makefile, np. make run, w moim wypadku make run odpali Flaska_
- otwieramy drugi terminal i wykonujemy polecenie ``` curl 127.0.0.1:5000 ```

Plik **README.md** jest ważny, ponieważ zawiera on informacje odnośnie projektu, jego struktury oraz informuje, jak go użyć. Jest on bardzo przydatny dla osób, które mają pierwszą styczność z danym repozytorium.
