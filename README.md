# Employee Manager

## Opis projektu

**Employee Manager** to aplikacja webowa stworzona przy użyciu **Spring Boot** oraz **Angular**, która pozwala na zarządzanie danymi pracowników. Aplikacja umożliwia dodawanie, edytowanie, usuwanie oraz przeglądanie szczegółów pracowników. Projekt wykorzystuje **Spring Data JPA** do komunikacji z bazą danych oraz **Spring Security** do ochrony aplikacji. Frontend działa na porcie `4200` i komunikuje się z backendem na porcie `8080`.

## Funkcjonalności

- **Dodawanie pracowników** – umożliwia tworzenie nowych pracowników z pełnymi danymi, w tym imieniem, nazwiskiem, tytułem pracy, telefonem, emailem oraz unikalnym kodem pracownika.
- **Przeglądanie pracowników** – wyświetla listę wszystkich pracowników w aplikacji.
- **Aktualizacja danych pracowników** – pozwala na edycję informacji o pracownikach.
- **Usuwanie pracowników** – umożliwia usunięcie pracownika z bazy danych.
- **Obsługa CORS** – aplikacja jest skonfigurowana do komunikacji z frontendem działającym na porcie `4200` (typowe dla aplikacji Angular).

## Technologie

- **Backend**: 
  - **Spring Boot** – główny framework do budowania aplikacji.
  - **Spring Data JPA** – do komunikacji z bazą danych.
  - **H2 Database** – baza danych wykorzystywana do przechowywania danych (można łatwo zamienić na inną bazę, np. MySQL).
  - **Spring Security** – do ochrony aplikacji (opcjonalnie, w zależności od wymagań).
  
- **Frontend**:
  - **Angular** – framework do tworzenia dynamicznych aplikacji internetowych.
  - **HTTP Client** – do komunikacji z backendem za pomocą API REST.

- **Inne technologie**:
  - **JWT (JSON Web Tokens)** – do autentykacji i autoryzacji (opcjonalnie).
  - **CORS** – aby umożliwić dostęp do backendu z aplikacji frontendowej uruchomionej na innym porcie.
