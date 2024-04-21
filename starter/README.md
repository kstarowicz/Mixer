MIXER 

Opis
MixMaster to aplikacja webowa, która umożliwia użytkownikom wyszukiwanie drinków, poznawanie sposobów ich przygotowania, składników potrzebnych do ich wykonania oraz odpowiednich szklanek do podawania. Aplikacja oferuje również newsletter, do którego można się zapisać, aby otrzymywać najnowsze przepisy i aktualności.

Technologie
Projekt został zbudowany z użyciem nowoczesnych technologii webowych, w tym:

React.js (v18.2.0) - biblioteka do budowy interfejsu użytkownika
React Router (v6.11.2) - do zarządzania routingiem w aplikacji
Axios (v1.4.0) - do wykonywania żądań HTTP
Styled Components (v5.3.11) - do stylizacji komponentów
@tanstack/react-query (v4.29.7) - do zarządzania stanem i synchronizacji danych z API
React Toastify (v9.1.3) - do wyświetlania powiadomień
W środowisku developerskim użyto narzędzia Vite (v4.2.0) dla szybkiego przetwarzania i gorącego przeładowywania modułów.


Instalacja:
Aby zainstalować i uruchomić aplikację lokalnie, wykonaj następujące kroki:

Klonowanie repozytorium;

git clone https://github.com/kstarowicz/Mixer

lub wejdź na moje repo i dokonajk 

Instalacja zależności:

Zainstaluj potrzebne zależności za pomocą npm:


npm install


Uruchomienie:

Aby uruchomić aplikację w trybie developerskim:

npm run dev


Funkcje:


Wyszukiwarka drinków: Użytkownicy mogą wyszukiwać drinki na podstawie składników lub nazwy.
Szczegółowe informacje o drinkach: Po wybraniu drinka, użytkownik otrzymuje informacje o składnikach, sposobie przygotowania i odpowiednim szkle.
Newsletter: Możliwość subskrypcji newslettera dla otrzymywania najnowszych przepisów i aktualności.