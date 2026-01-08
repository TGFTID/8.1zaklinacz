# Ogarnij Się - Aplikacja Medytacyjna

Aplikacja do medytacji i koncentracji z różnymi kategoriami emocjonalnymi i mentalnymi.

## Jak uruchomić stronę

### Opcja 1: Prosty serwer HTTP (Python)
```bash
python3 -m http.server 8000
```
Następnie otwórz przeglądarkę i przejdź do: `http://localhost:8000/index.html`

### Opcja 2: Prosty serwer HTTP (Node.js)
```bash
npx http-server -p 8000
```
Następnie otwórz przeglądarkę i przejdź do: `http://localhost:8000/index.html`

### Opcja 3: Bezpośrednie otwarcie
Możesz również otworzyć plik `index.html` bezpośrednio w przeglądarce (klikając dwukrotnie na plik), ale niektóre funkcje mogą nie działać prawidłowo ze względu na ograniczenia CORS.

## Funkcjonalność

- **Nagłówek**: Wyświetla tytuł aplikacji "ogarnij się" i ikonę profilu
- **Odtwarzacz multimedialny**: Zdjęcie z kontrolami odtwarzania i paskiem postępu
- **Kategorie**: 9 przycisków z różnymi kategoriami:
  - DO ROBOTY
  - OGARNIJ SIĘ
  - CHAOS
  - SENS
  - SAMOTNOŚĆ
  - WARTOŚĆ
  - SMUTNO
  - SERCE
  - ADHD
- **Synteza mowy**: Przyciski kategorii używają funkcji text-to-speech do odczytywania nazw kategorii
- **Stopka**: Nawigacja z opcjami Muzyka, Połącz, Zaklincacz

## Struktura projektu

```
.
├── index.html              # Główny plik HTML aplikacji
└── katalog/
    └── backgrund/          # Folder ze zdjęciami tła
        └── *.png           # Pliki graficzne
```
