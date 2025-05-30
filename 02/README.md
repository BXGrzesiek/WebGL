# WebGL – Sześcian z teksturami i kamerą FPS

Projekt demonstruje wykorzystanie WebGL do renderowania sześcianu z obsługą kamery typu free-look (FPS), licznikiem FPS oraz różnymi wariantami nakładania tekstur na ściany sześcianu.

## Funkcjonalności

- **Sterowanie kamerą:**
  - Ruch: klawisze W, S, A, D lub strzałki
  - Obrót: myszka (po kliknięciu w canvas i aktywacji pointer lock)
  - Wyłączanie/włączanie Z-buffer: klawisz Z
- **Licznik FPS** – wyświetlany w lewym górnym rogu
- **Wyświetlanie aktualnego trybu renderowania**
- **Trzy tryby renderowania sześcianu:**

### Tryb 1: Jedna tekstura na wszystkich ściankach
- Aktywacja: klawisz `1` (po wyjściu z pointer lock)
- Na każdej ściance sześcianu nakładana jest ta sama tekstura

### Tryb 2: Naprzemienne tekstury na ściankach
- Aktywacja: klawisz `2` (po wyjściu z pointer lock)
- Na przemian na ściankach sześcianu nakładane są dwie różne tekstury (parzyste – tekstura 1, nieparzyste – tekstura 2)

### Tryb 3: Mieszanie tekstur (blend)
- Aktywacja: klawisz `3` (po wyjściu z pointer lock)
- Na każdej ściance nakładane są obie tekstury jednocześnie, z przezroczystością 50% każdej (efekt przenikania)

## Obsługa
1. Uruchom plik `start.html` w nowoczesnej przeglądarce.
2. Kliknij w canvas, aby aktywować sterowanie myszą (pointer lock).
3. Aby przełączyć tryb renderowania, wyjdź z pointer lock (klawisz Esc), następnie naciśnij `1`, `2` lub `3`.
4. Informacja o aktualnym trybie wyświetlana jest w lewym górnym rogu.

## Wymagania
- Przeglądarka z obsługą WebGL2
- Połączenie z internetem (do pobrania tekstur)

## Autor
Projekt na potrzeby zajęć z grafiki 3D (WebGL, kamera FPS, teksturowanie, blending).
