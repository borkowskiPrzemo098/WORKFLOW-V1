# Workflow — Panel zadań

Prosty, nowoczesny dashboard do zarządzania zadaniami w pracy. Statyczna strona (HTML/CSS/JS), dane zapisywane lokalnie w przeglądarce (`localStorage`) — bez backendu.

## Funkcje

- Dodawanie zadania: tytuł, poziom trudności, pilność, dzień realizacji, opcjonalna godzina przypomnienia, status, opis.
- Tablica podzielona na dni tygodnia (poniedziałek–niedziela), zadania posortowane od najpilniejszych do najmniej istotnych.
- Ikony pilności (wykrzyknik dla zadań pilnych, inne ikony dla pozostałych poziomów) oraz odznaki statusu i trudności.
- Zegar na żywo oraz dźwiękowe/wizualne powiadomienie, gdy nadejdzie ustawiona godzina zadania (strona musi być otwarta w karcie przeglądarki).
- Licznik zadań pilnych/wszystkich, usuwanie dowolnego zadania (w tym ukończonych) jednym kliknięciem.
- Pływający przycisk „+” do szybkiego dodawania zadań, widok aktualizuje się natychmiast po dodaniu/usunięciu.

## Użycie

Otwórz `index.html` w przeglądarce — działa lokalnie, bez instalacji czy serwera. Dane zapisują się w `localStorage`, więc pozostają po odświeżeniu strony (w ramach tej samej przeglądarki i urządzenia).
