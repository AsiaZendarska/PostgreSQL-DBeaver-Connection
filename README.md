# PostgreSQL-DBeaver-Connection

## Opis

To repozytorium zawiera przykładowy skrypt Pythona służący do połączenia z bazą danych PostgreSQL przy użyciu pakietu `psycopg2`.

## Struktura Repozytorium

Notatnik:
- `sql_test_1` oraz `sql_test_2` zawiera skrypt Pythona, który nawiązuje połączenie z bazą danych PostgreSQL, wykonuje przykładowe zapytanie i zamyka połączenie.

## Wymagania

Aby uruchomić ten skrypt, należy zainstalować następujące biblioteki:

- `sqlalchemy`: do zarządzania połączeniem z bazą danych
- `psycopg2`: adapter do połączeń PostgreSQL
- `python-dotenv`: do ładowania zmiennych środowiskowych
- `pandas`: opcjonalnie, do manipulacji danymi w ramach połączeń z bazą danych
