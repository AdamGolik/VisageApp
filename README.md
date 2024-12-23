# Aplikacja Makijażowa

## Funkcje Aplikacji

### Główne Funkcje
- [ ] Login (logowanie użytkownika)
- [ ] Rejestracja (tworzenie konta użytkownika)
- [ ] Role użytkowników
- [ ] Dodawanie makijaży i dodatków
- [ ] Bezpieczne uwierzytelnianie (JWT/Auth)
- [ ] Weryfikacja emaila

### Backend
- **Framework:** Gin jako HTTP Service
- **Baza danych:** Gorm dla obsługi bazy danych (Postgres)
- **Bezpieczeństwo:** JWT/Auth dla uwierzytelniania
- **Weryfikacja emaila:** Implementacja weryfikacji emailowej
- **Plik konfiguracyjny:** Obsługa konfiguracji przez plik `.env`

#### Funkcjonalności Backend
- [ ] Login użytkownika
- [ ] Rejestracja użytkownika
- [ ] Dodawanie makijaży
- [ ] Zarządzanie rolami użytkowników
- [ ] Edycja i usuwanie makijaży oraz ról
- [ ] Automatyczne usuwanie elementów po 1 tygodniu

### Frontend
- **Framework:** Next.js jako główny framework
- **Animacje:** Framer Motion dla efektów wizualnych
- **Bezpieczeństwo:** TypeScript dla lepszej kontroli typów
- **Stylizacja:** TailwindCSS dla stylu aplikacji

#### Styl Frontendu
- [ ] Clean, złoto-biały wygląd
- [ ] Strona główna z możliwością logowania i rejestracji
- [ ] Rejestracja z ograniczonym dostępem (podstawowy poziom, chyba że podany specjalny klucz)
- [ ] Role i uprawnienia:
  - Dostęp z wyższej rangi widzi działania użytkowników o niższej randze
  - Role:
    - Oglądanie
    - Dodawanie i oglądanie
    - Dodawanie, oglądanie, edycja i usuwanie
    - Zarządzanie użytkownikami

### Baza Danych
- **Silnik:** Postgres jako główna baza danych
- **Tabele:**
  - [ ] Użytkownicy
  - [ ] Role
  - [ ] Makijaże
  - [ ] Dodatki do makijaży

## Technologie
- **Backend:** Golang (Gin, Gorm, JWT/Auth, weryfikacja emaila)
- **Frontend:** React/Next.js, TypeScript, TailwindCSS, Framer Motion
- **Baza danych:** Postgres
- **Konteneryzacja:** Docker

## Wymagania
- **Docker:** Uruchamianie aplikacji w środowisku kontenerowym
- **Bezpieczeństwo:** JWT/Auth, weryfikacja emaila
- **Stylizacja:** Minimalistyczny, elegancki wygląd (złoto-biały)
- **Funkcje:** Wszystkie opisane powyżej funkcjonalności
