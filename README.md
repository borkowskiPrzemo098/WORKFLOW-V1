# Workflow — Panel zadań

Prosty, nowoczesny dashboard do zarządzania zadaniami w pracy. Statyczna strona (HTML/CSS/JS), dane zapisywane lokalnie w przeglądarce (`localStorage`) — bez backendu.

## Funkcje

- Dodawanie zadania: nazwa użytkownika, tytuł, poziom trudności, pilność, dzień realizacji, status, opis.
- Tablica podzielona na dni tygodnia (poniedziałek–niedziela), zadania posortowane od najpilniejszych do najmniej istotnych.
- Ikony pilności (wykrzyknik dla zadań pilnych, inne ikony dla pozostałych poziomów) oraz odznaki statusu i trudności.
- Filtrowanie po użytkowniku, licznik zadań pilnych/wszystkich.
- Pływający przycisk „+” do szybkiego dodawania zadań, widok aktualizuje się natychmiast po dodaniu/usunięciu.

## Użycie

Otwórz `index.html` w przeglądarce — działa lokalnie, bez instalacji czy serwera. Dane zapisują się w `localStorage`, więc pozostają po odświeżeniu strony (w ramach tej samej przeglądarki i urządzenia).
