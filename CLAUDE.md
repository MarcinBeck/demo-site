# Demo Site — instrukcja dla Claude Code Action

## Struktura projektu
Jeden plik: `index.html` — cały HTML, CSS (inline `<style>`), bez zewnętrznych JS.

## Jak implementować zmiany z GitHub Issues
- Zmiany treści (copy): edytuj tekst bezpośrednio w index.html
- Zmiany stylu: edytuj sekcję `<style>` w index.html
- Zmiany layoutu: edytuj HTML w index.html
- Nie twórz dodatkowych plików CSS/JS — wszystko zostaje w jednym pliku
- Po zmianach commituj do brancha i otwórz PR

## Deploy
Automatyczny — GitHub Pages na branchu `gh-pages` po merge do `main`.
