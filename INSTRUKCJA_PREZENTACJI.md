# Instrukcja obsługi prezentacji szkoleniowej

## Plik prezentacji

Prezentacja została zapisana w pliku: `prezentacja_szkolenie_ai.md`

## Jak korzystać z prezentacji?

### Opcja 1: Konwersja do HTML/PDF (Marp)

1. Zainstaluj Marp CLI:
   ```bash
   npm install -g @marp-team/marp-cli
   ```

2. Wygeneruj prezentację HTML:
   ```bash
   marp prezentacja_szkolenie_ai.md -o prezentacja.html
   ```

3. Wygeneruj prezentację PDF:
   ```bash
   marp prezentacja_szkolenie_ai.md -o prezentacja.pdf
   ```

4. Otwórz w przeglądarce i prezentuj:
   ```bash
   marp -s prezentacja_szkolenie_ai.md
   ```

### Opcja 2: Visual Studio Code z rozszerzeniem Marp

1. Zainstaluj VS Code
2. Zainstaluj rozszerzenie "Marp for VS Code"
3. Otwórz plik `prezentacja_szkolenie_ai.md`
4. Kliknij ikonę podglądu lub użyj Ctrl+Shift+V
5. Możesz eksportować do HTML, PDF lub PPTX

### Opcja 3: Reveal.js

1. Użyj narzędzia Pandoc do konwersji:
   ```bash
   pandoc prezentacja_szkolenie_ai.md -t revealjs -s -o prezentacja_reveal.html
   ```

### Opcja 4: Google Slides / PowerPoint

1. Przekonwertuj Markdown na PPTX używając Marp:
   ```bash
   marp prezentacja_szkolenie_ai.md -o prezentacja.pptx
   ```

2. Zaimportuj plik PPTX do Google Slides lub otwórz w PowerPoint

## Struktura prezentacji

Prezentacja zawiera następujące sekcje:

1. **Wprowadzenie do AI** - definicje i podstawy
2. **Zastosowania w administracji** - praktyczne przykłady
3. **AI Act** - szczegółowe omówienie unijnego rozporządzenia o AI (18 slajdów):
   - Wprowadzenie i główne zasady
   - Klasyfikacja ryzyka (4 poziomy)
   - Systemy zakazane
   - Systemy wysokiego ryzyka
   - Obowiązki dostawców i użytkowników
   - FRIA (Fundamental Rights Impact Assessment)
   - Terminy wdrożenia
   - Sankcje i organy nadzorcze
   - Praktyczne implikacje dla administracji
4. **Narzędzia AI** - przegląd dostępnych rozwiązań
5. **Organizacja pracy** - zarządzanie czasem i zadaniami
6. **Warsztaty** - przykłady dobrych i złych praktyk promptów
7. **Bezpieczeństwo i RODO** - aspekty prawne
8. **Rezultaty** - co uczestnicy zyskują
9. **Podsumowanie** - kluczowe wnioski

## Wskazówki dla trenera

- Każdy slajd jest oddzielony `---`
- Prezentacja zawiera emoji dla lepszej wizualizacji
- Przykłady promptów pokazują dobre i złe praktyki
- Materiał jest przygotowany na około 6-8 godzin szkolenia (lub 2 dni szkoleniowe)
- Sekcja AI Act to około 1-1,5 godziny (18 slajdów)
- Warsztaty praktyczne powinny stanowić co najmniej 40% czasu

## Dostosowanie prezentacji

Możesz edytować plik Markdown i dostosować:
- Dodać logo organizacji
- Zmienić kolory i style (w Marp przez dyrektywy)
- Dodać konkretne przykłady z KOWR
- Rozszerzyć sekcje warsztatowe
- Dodać slajdy z case studies

## Materiały dodatkowe

Zaleca się przygotowanie:
- Kont testowych do narzędzi AI (jeśli dostępne w organizacji)
- Przykładowych dokumentów do ćwiczeń
- Listy zasobów i linków
- Ankiety post-szkoleniowej
- Materiałów do samodzielnej nauki

## Uwagi techniczne

- Format Markdown jest łatwy w edycji
- Można wersjonować w Git
- Łatwa współpraca przy tworzeniu treści
- Uniwersalny format eksportu

## Kontakt i wsparcie

W razie pytań dotyczących prezentacji lub potrzeby modyfikacji, skontaktuj się z organizatorem szkolenia.
