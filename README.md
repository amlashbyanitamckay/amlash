# AMLASH — strona na GitHub Pages

Gotowa strona wizytówkowa / portfolio dla salonu rzęs i brwi AMLASH.

## 1. Najpierw podmień linki
Otwórz `script.js` i na samej górze zmień:
- `booksyUrl` — pełny link do Twojego profilu Booksy,
- `instagramUrl` — pełny link do Instagrama,
- `instagramLabel` — właściwy @nick.

## 2. Podmień zdjęcia
W folderze `assets` są pliki zastępcze SVG. Najprościej:

- główne zdjęcie: `hero-placeholder.svg`
- zdjęcie właścicielki: `about-placeholder.svg`
- portfolio: `portfolio-1.svg` ... `portfolio-6.svg`

Możesz zamiast nich wgrać JPG/WEBP i zmienić nazwy w `index.html`, np.
`assets/portfolio-1.webp`.

Najlepiej:
- portfolio pionowe: proporcje 4:5,
- główne zdjęcie: 4:5,
- zdjęcia WEBP/JPG po optymalizacji, zwykle 150–400 KB.

## 3. Publikacja na GitHub Pages
1. Na GitHub kliknij **New repository**.
2. Nazwij repozytorium np. `amlash`.
3. Ustaw **Public**.
4. Wgraj CAŁĄ zawartość tego folderu:
   `index.html`, `styles.css`, `script.js` i folder `assets`.
5. Wejdź w **Settings → Pages**.
6. W `Build and deployment` wybierz:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
7. Kliknij **Save**.

Po chwili GitHub pokaże adres testowy strony.

## 4. Własna domena
W **Settings → Pages → Custom domain** wpisz swoją domenę.
GitHub pokaże, jakie rekordy DNS trzeba ustawić u operatora domeny.

Nie usuwaj domeny z obecnego panelu. Zmieniamy tylko rekordy DNS.

## Ważne przed publikacją
- wstaw prawdziwy link Booksy,
- wstaw Instagram,
- podmień zdjęcia portfolio,
- podaj dokładną lokalizację, jeśli chcesz ją pokazywać,
- jeżeli używasz formularza lub analityki, trzeba dopracować politykę prywatności / cookies.

## Pliki
- `index.html` — treść strony
- `styles.css` — wygląd
- `script.js` — linki, menu, animacje
- `assets/` — logo, favicon i zdjęcia
