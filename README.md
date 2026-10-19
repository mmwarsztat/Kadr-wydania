# Wydania Kadru

Gotowe instalatory programu **Kadr** — przeglądarki obrazów z prostą edycją, rysowaniem, etykietami
i wymiarami do opisywania zrzutów ekranu, zdjęć z budowy i rysunków PDF.

Kod źródłowy jest w osobnym, prywatnym repozytorium. Tutaj leżą wyłącznie pliki do pobrania, żeby program
mógł sprawdzać aktualizacje bez żadnego tokenu.

## Instalacja

Pobierz `Kadr_<wersja>_x64-setup.exe` z [najnowszego wydania](../../releases/latest) i uruchom. Instalator
wchodzi do katalogu użytkownika, więc **nie pyta o hasło administratora**, a paczka niesie całe środowisko —
nie trzeba mieć Pythona ani niczego doinstalowywać.

## Aktualizacje

Zainstalowany Kadr po uruchomieniu sprawdza, czy jest nowsza wersja, i pokazuje komunikat w rogu ekranu.
Po kliknięciu „Zainstaluj” pobiera instalator, sprawdza jego podpis i instaluje go po cichu — Kadr wraca sam.
Plik `latest.json` dołączony do wydania to cała rozmowa programu z serwerem: numer wersji, opis zmian,
adres instalatora i jego podpis.
