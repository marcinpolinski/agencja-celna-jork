# Agencja Celna Jork - Strona WWW

Profesjonalna strona internetowa dla Agencji Celnej Jork w Kołobrzegu.

## Zawartość

- `index.html` - główny plik HTML strony
- `styles.css` - arkusz stylów CSS
- `script.js` - skrypty JavaScript
- `logo.png` - logo firmy
- Dokumenty źródłowe (pliki ODT i PDF z informacjami o firmie)

## Funkcjonalności

### Sekcje strony:
1. **Hero** - sekcja powitalna z gradienten i animacjami
2. **O Nas** - informacje o firmie i doświadczeniu
3. **Usługi** - kompletna lista oferowanych usług celnych
4. **Dlaczego My** - powody do wyboru Agencji Celnej Jork
5. **Kontakt** - dane kontaktowe i mapa Google

### Technologie:
- **HTML5** - semantyczna struktura
- **CSS3** - nowoczesne style z gradientami, animacjami i responsive design
- **JavaScript (Vanilla)** - interaktywność bez zewnętrznych bibliotek
- **Google Fonts** - czcionka Inter

### Funkcje JavaScript:
- Responsywne menu mobilne
- Płynne przewijanie (smooth scroll)
- Aktywne podkreślenie linków w menu
- Animacje przy przewijaniu (Intersection Observer)
- Efekt parallax w sekcji hero
- Obsługa klawiatury (dostępność)
- Optymalizacja wydajności

### Responsive Design:
- Pełna responsywność dla urządzeń mobilnych, tabletów i desktopów
- Breakpoints: 768px, 480px
- Hamburger menu na urządzeniach mobilnych
- Elastyczne layouty (CSS Grid i Flexbox)

## Jak uruchomić

### Opcja 1: Lokalne otwarcie
Wystarczy otworzyć plik `index.html` w przeglądarce internetowej (podwójne kliknięcie).

### Opcja 2: Lokalny serwer (zalecane)
```bash
# Używając Python 3:
python3 -m http.server 8000

# Lub Python 2:
python -m SimpleHTTPServer 8000

# Następnie otwórz w przeglądarce:
# http://localhost:8000
```

### Opcja 3: Live Server (VS Code)
Jeśli używasz Visual Studio Code, zainstaluj rozszerzenie "Live Server" i kliknij "Go Live".

## Hosting

Aby opublikować stronę w internecie, możesz użyć:

### Darmowe opcje:
- **Netlify** - przeciągnij folder na netlify.com/drop
- **GitHub Pages** - hosting przez repozytorium GitHub
- **Vercel** - szybki deployment przez CLI lub GUI
- **Cloudflare Pages** - darmowy hosting z CDN

### Płatne opcje z domeną:
- **home.pl** - polski hosting
- **OVH** - europejski dostawca
- **nazwa.pl** - polski hosting z domeną

## Modyfikacje

### Zmiana koloru:
Edytuj zmienne CSS w pliku `styles.css`:
```css
:root {
    --primary-color: #1e3a5f;    /* Główny kolor (niebieski) */
    --secondary-color: #2d8cff;  /* Drugi kolor */
    --accent-color: #00d4ff;     /* Kolor akcentu */
}
```

### Zmiana treści:
Edytuj odpowiednie sekcje w pliku `index.html`.

### Dodanie formularza kontaktowego:
Możesz dodać formularz używając serwisów takich jak:
- Formspree.io
- Netlify Forms
- EmailJS

### Aktualizacja mapy Google:
W pliku `index.html` znajdź sekcję `contact-map` i zaktualizuj współrzędne w linku `iframe`.

## Współrzędne dla mapy:
- Adres: ul. Portowa 41, 78-100 Kołobrzeg
- Koordynaty do weryfikacji: ~54.1767°N, 15.5688°E

## Optymalizacja SEO

Strona zawiera podstawowe elementy SEO:
- Meta description
- Meta keywords
- Semantyczne tagi HTML5
- Alt tagi dla obrazów
- Szybkie ładowanie

### Dodatkowe kroki SEO:
1. Dodaj plik `robots.txt`
2. Stwórz `sitemap.xml`
3. Zarejestruj w Google Search Console
4. Dodaj Google Analytics (opcjonalnie)

## Wsparcie przeglądarek

Strona działa we wszystkich nowoczesnych przeglądarkach:
- Chrome/Edge (v90+)
- Firefox (v88+)
- Safari (v14+)
- Opera (v76+)

## Kontakt z właścicielem

**Agencja Celna Jork**
- Adres: ul. Portowa 41, 78-100 Kołobrzeg
- Tel: 510 125 008, 501 326 385
- Email: jork2@wp.pl
- Właściciel: Joanna Orłowska

## Licencja

© 2024 Agencja Celna Jork. Wszelkie prawa zastrzeżone.

---

Strona wykonana z wykorzystaniem Claude Code.
