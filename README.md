Mobtel Remik Online 🃏
​Mobtel Remik Online to w pełni grywalna, przeglądarkowa wersja popularnej gry karcianej Remik (Rummy), zaprojektowana z myślą o urządzeniach mobilnych i ekranach dotykowych. Gra działa w architekturze P2P (Peer-to-Peer), co oznacza, że gracze łączą się bezpośrednio ze sobą bez użycia centralnego serwera bazy danych.
​✨ Główne funkcje
​Tryb Multiplayer P2P: Gra online od 2 do 5 graczy w czasie rzeczywistym przy użyciu krótkich kodów PIN (dzięki WebRTC / PeerJS).
​Tryb Offline (Testowy): Możliwość gry 1 na 1 z automatycznym botem, aby poćwiczyć układy i mechanikę gry.
​Prawdziwe zasady Remika: Wbudowany silnik walidujący układy kart (wymagane 51 punktów i Czysty Sekwens do pierwszego wyłożenia).
​Interfejs Mobile-First: Duże, czytelne karty z indeksami w lewym górnym rogu. Karty automatycznie "wachlarzują" się na dole ekranu, dzięki czemu są idealnie widoczne na smartfonach.
​Wygodne sterowanie:
​Sortowanie kart w ręku za pomocą jednego przycisku lub ręczna zamiana miejscami (tapnij jedną kartę, a potem drugą).
​Dokładanie kart do istniejących na stole sekwensów i zestawów poprzez proste tapnięcie w stół.
​Wbudowany Czat: Komunikacja tekstowa na żywo i automatyczne logi systemu informujące o ruchach przeciwników.
​📜 Zasady Gry zaimplementowane w kodzie
​Projekt odzwierciedla rygorystyczne, polskie zasady klasycznego Remika:
​Rozdanie: Gra toczy się dwiema pełnymi taliami z Jokerami (108 kart). Każdy gracz otrzymuje 13 kart, a gospodarz (Rozdający) dostaje 14 kart i zaczyna od odrzucenia.
​Tura: Każda tura musi rozpocząć się od dobrania karty (z talii głównej lub ze stosu odrzuconych) i zakończyć odrzuceniem pojedynczej karty na stos.
​Pierwsze wyłożenie: Gracz musi uzbierać układy o wartości minimum 51 punktów, w tym co najmniej jeden Czysty Sekwens (bez Jokera), aby móc po raz pierwszy wyłożyć karty na stół.
​Dokładanie: Po pierwszym wyłożeniu, gracz w swojej turze może swobodnie dokładać pasujące karty do własnych i cudzych układów leżących na stole.
​Punktacja i Koniec Gry: Runda kończy się, gdy któryś z graczy pozbędzie się wszystkich kart z ręki (ostatnią kartę zawsze odrzuca na stos). Pozostali gracze otrzymują punkty ujemne za karty, które zostały im w ręku (As=11, Joker=30, Figury=10).
​🚀 Jak zagrać? (Instalacja)
​Gra jest zbudowana jako rozwiązanie Single-File (Jeden plik), co oznacza, że nie wymaga instalacji żadnego środowiska deweloperskiego (Node.js, PHP, itp.).
​Pobierz lub skopiuj plik index.html.
​Otwórz ten plik w dowolnej nowoczesnej przeglądarce internetowej (Chrome, Safari, Firefox).
​Aby zagrać ze znajomym (Multiplayer):
​Osoba A wybiera liczbę graczy z listy, klika "Stwórz stół jako HOST" i otrzymuje 4-cyfrowy PIN.
​Osoba B otwiera ten sam plik HTML, wpisuje PIN na dole w pole tekstowe i klika "Dołącz do znajomego".
​Połączenie zestawi się automatycznie, a gra rozda karty!
​Wskazówka Hostingowa: Aby grać na odległość bez wysyłania sobie pliku, możesz wrzucić plik index.html na darmowy hosting GitHub Pages, Netlify lub Vercel. Wtedy po prostu wysyłasz znajomym link do strony!
​🛠️ Użyte Technologie
​HTML5 & CSS3: Struktura i układ wizualny.
​Vanilla JavaScript (ES6): Główny silnik logiczny gry, zasady Rummy, walidacja wyłożeń oraz sztuczna inteligencja Bota.
​PeerJS: Zewnętrzna biblioteka upraszczająca korzystanie z WebRTC. Umożliwia łączenie przeglądarek w systemie P2P bez stawiania własnego serwera WebSocketowego.
​🤝 Autor i Współpraca
​Stworzone jako projekt hobbystyczny / przeglądarkowy Mobtel Remik. Śmiało modyfikuj kod, zmieniaj style CSS czy zasady gry i dopasuj projekt pod własne potrzeby. Miłej zabawy!
