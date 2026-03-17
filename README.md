# secure-message-app

## Opis
Aplikacja do szyfrowania wiadomości (AES).

## Uruchomienie

### Backend
cd backend
mvn spring-boot:run

### Frontend
cd frontend
npm install
npm run dev

## Funkcje
- szyfrowanie AES
- zapis w bazie H2
- deszyfrowanie
- prosty login (frontend)

## Bezpieczeństwo
- JPA (SQL injection safe)
- walidacja frontend
- kontrola dostępu (owner)
