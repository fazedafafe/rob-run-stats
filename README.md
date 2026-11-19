# ROB RUN — statystyki

Statyczna strona z danymi o broni, pojazdach, loocie i cyklu wipe.

## Uruchomienie lokalne

Otwórz [index.html](index.html) bezpośrednio w przeglądarce albo uruchom prosty serwer:

```bash
python3 -m http.server 8080
```

Następnie otwórz `http://localhost:8080`.

## GitHub Pages

Repozytorium zawiera workflow `.github/workflows/pages.yml`, który publikuje
`index.html` po każdym pushu do gałęzi `main`.