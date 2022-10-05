# Zadanie 1

Zapoznaj się z dołączoną bazą Sqlite (plik `analityka.db`) i rozwiąż poniższe problemy używając SQL.

1. Podaj łączną ilość wyświetleń strony (`event_name = page_view`) w przeciągu ostatnich 7 dni.
2. Podaj liczbę użytkowników strony (unikalne `event_name = page_view` po `user_id`) dla każdego z ostatnich 7 dni.
3. Podaj najnowszy event dla każdego z użytkowników. Wynik tego zapytania powinien być sortowany po dacie eventu (od najnowszych) i zlimitowany do 10 wierszy.
