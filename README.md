# Workflow — Panel zadań

Prosty, nowoczesny dashboard do zarządzania zadaniami w pracy. Statyczna strona (HTML/CSS/JS), dane zapisywane lokalnie w przeglądarce (`localStorage`) — bez backendu.

## Funkcje

- Dodawanie zadania: tytuł, poziom trudności, pilność, dzień realizacji (lub „bez terminu”), opcjonalna godzina przypomnienia, cykliczność (codziennie/co tydzień/co miesiąc), status, opis.
- Widoki: **Dziś**, **Tydzień**, **Miesiąc** (kalendarz), **Zaległe** (przeterminowane, nieukończone) i **Archiwum** (ukończone — znikają z kalendarza i trafiają tutaj).
- Zadania bez terminu trafiają do osobnego panelu bocznego zamiast konkretnego dnia.
- Wyszukiwarka po tytule zadania, filtrująca na żywo niezależnie od aktywnej zakładki.
- Tryb jasny/ciemny z przełącznikiem w nagłówku, zapamiętywany w przeglądarce.
- Wybór koloru motywu (6 palet) obok przełącznika jasny/ciemny — zmienia akcent (przyciski, aktywne stany) i dopasowuje odcień tła, zapamiętywany osobno od trybu jasny/ciemny.
- Ikony pilności (wykrzyknik dla zadań pilnych, inne ikony dla pozostałych poziomów), odznaka 🔁 dla zadań cyklicznych, odznaki statusu i trudności.
- Zegar na żywo oraz dźwiękowe/wizualne powiadomienie, gdy nadejdzie ustawiona godzina zadania (strona musi być otwarta w karcie przeglądarki).
- Licznik zadań pilnych (klikalny — pokazuje pełną listę) i wszystkich aktywnych zadań; checkbox na karcie do oznaczenia „Zrobione” jednym kliknięciem, edycja i usuwanie.
- Pływający przycisk „+” do szybkiego dodawania zadań, widok aktualizuje się natychmiast po dodaniu/edycji/usunięciu.

### Ograniczenia zadań cyklicznych

Zadanie cykliczne to jeden wpis, który jest wirtualnie „powielany” na kolejne dni — nie da się edytować lub oznaczyć jako zrobione tylko jednego wystąpienia z serii. Edycja lub oznaczenie „Zrobione”/usunięcie działa na całą serię naraz.

## Użycie

Otwórz `index.html` w przeglądarce — działa lokalnie, bez instalacji czy serwera. Dane zapisują się w `localStorage`, więc pozostają po odświeżeniu strony (w ramach tej samej przeglądarki i urządzenia).
