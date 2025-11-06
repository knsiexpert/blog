<!-- 
title: "Nowa strona koła"
date: 2025-11-06
author: Zespół KNSI E-xpert 2025
description: "Premiera nowej strony internetowej KNSI E-XPERT w wersji 3.33.0. Nowoczesny design, tryb ciemny, pięć motywów kolorystycznych i pełna responsywność – poznaj naszą cyfrową wizytówkę."
tags: [strona, website, open-source, github-pages, design, ux, frontend, e-xpert]
-->

# Nowa strona koła

<p align="center">
  <img src="https://i.imgur.com/Op4UASx.png" width="70%" />
</p>

## 🎉 Witamy w nowej erze cyfrowej E-XPERT!

Z dumą prezentujemy **oficjalną stronę internetową KNSI E-XPERT w wersji 3.33.0** – naszą nową cyfrową wizytówkę, która łączy **nowoczesny design** z **zaawansowaną funkcjonalnością** i **pełną otwartością** kodu.

Po miesiącach pracy, iteracji i testów, stworzyliśmy stronę, która nie tylko **wygląda świetnie**, ale też **działa błyskawicznie** i jest **w 100% open source**.

---

## 🧭 Historia projektu – jak powstała nowa strona E-XPERT

Projekt nowej strony E-XPERT nie zaczął się od wielkich planów, tylko od zwykłej potrzeby.  
Poprzednia wersja, choć solidna, przestała nadążać za tym, czym koło naukowe E-XPERT stało się w ostatnich latach – zespołem ludzi pracujących nad realnymi projektami, publikacjami i inicjatywami, które wykraczają poza mury uczelni.  
Strona miała już nie tylko „informować”, ale też **odzwierciedlać sposób działania** – przejrzysty, techniczny, oparty na współpracy.

### Od prostego pomysłu do spójnej koncepcji

Na początku zespół rozważał aktualizację starego szablonu. Szybko jednak okazało się, że łatwiej – i sensowniej – będzie stworzyć coś od nowa.  
Celem było zaprojektowanie systemu, który będzie **łatwy w utrzymaniu**, **otwarty na rozwój** i **przejrzysty dla użytkowników**.  
Tak powstała idea, by zbudować stronę w oparciu o **czysty JavaScript**, bez frameworków, bez nadmiarowych zależności – po to, żeby każdy mógł zrozumieć, jak działa.

Zamiast CMS-a, treści przeniesiono do **plików JSON**, które są trzymane w repozytorium `data/`.  
To prosty, ale skuteczny pomysł: aktualizacja projektu, dodanie członka zespołu czy nowego wpisu w publikacjach nie wymaga żadnej ingerencji w kod HTML – wystarczy edycja danych.  
Dzięki temu każdy, kto ma dostęp do repozytorium, może współtworzyć stronę, niezależnie od doświadczenia w programowaniu.

### Architektura i otwartość

Strona E-XPERT od początku była budowana z myślą o tym, by **każdy element miał swoje uzasadnienie**.  
Rozdzielenie kodu i treści ułatwia rozwój, a jednocześnie pozwala zachować porządek i wersjonowanie.  
Każda zmiana jest śledzona przez Git, a dzięki **GitHub Actions** nowa wersja trafia online automatycznie po zmergowaniu do głównej gałęzi.  
Cały proces – od commita do wdrożenia – trwa nie dłużej niż kilka minut.

Ta automatyzacja nie była efektem mody, ale pragmatyzmu.  
Zespół nie chciał, by publikacja aktualizacji zależała od jednej osoby.  
Strona miała być **narzędziem wspólnej pracy**, a nie kolejnym zadaniem do odhaczania w backlogu.

### Warstwa wizualna

Kiedy techniczne podstawy były gotowe, przyszła pora na wygląd.  
Zespół chciał uniknąć wrażenia „uczelnianego portalu” – miało być nowocześnie, ale nie krzykliwie; funkcjonalnie, ale nie sucho.  
Tak powstał **system pięciu motywów kolorystycznych**, które można zmieniać jednym kliknięciem lub parametrem URL.  
Wraz z nimi pojawił się **tryb ciemny** – automatyczny, reagujący na ustawienia systemu, oraz manualny, który zapamiętuje preferencje użytkownika.

Całość dopełniają lekkie animacje Lottie, karuzele projektów, galeria z lightboxem i zestaw mikrointerakcji, które poprawiają doświadczenie użytkownika bez nadmiaru efektów.  
Dzięki temu strona jest szybka, przejrzysta i działa równie dobrze na telefonie, co na monitorze 4K.

### Open source w praktyce

Nowa wersja strony to nie tylko projekt wizualny, ale też **przykład, jak działa otwarty model pracy**.  
Repozytorium na GitHubie jest publiczne – można zobaczyć cały kod, sposób wdrożenia, a nawet wprowadzić własne zmiany przez pull request.  
To nie jest symboliczna deklaracja open source – strona rzeczywiście jest rozwijana tą metodą.  
Zespół korzysta z GitHuba tak samo, jak przy innych swoich projektach: wersjonuje dane, automatyzuje wdrożenia, testuje nowe funkcje.

### Od strony technicznej do społecznej

W trakcie prac okazało się, że projekt ma jeszcze inny wymiar – edukacyjny.  
Dla nowych członków koła to świetny sposób, by **nauczyć się praktycznie**, jak działa nowoczesny frontend, jak wygląda wdrożenie CI/CD, jak organizować dane w projekcie open source.  
Każdy commit to drobny krok w nauce, ale też cegiełka w budowie czegoś większego – strony, która faktycznie reprezentuje środowisko, z którego się wywodzi.

To raczej spokojny finał wielu tygodni pracy, testów i dyskusji – i jednocześnie początek nowego etapu.  
Nowa strona E-XPERT nie jest zamkniętym projektem, lecz **platformą, którą można rozwijać dalej**.  
To przestrzeń, w której technologia spotyka się z przejrzystością, a estetyka z funkcjonalnością.

Dziś, przeglądając [knsiexpert.github.io/site](https://knsiexpert.github.io/site), trudno mówić tylko o „nowej stronie”.  
To raczej **narzędzie współpracy i dokument historii zespołu**, który postanowił pokazać, że nawet prosty serwis może być zaprojektowany tak, jak dobrze działający system: czytelny, otwarty i przemyślany.

---

## 🎨 Pięć motywów, nieskończone możliwości

Jedną z najbardziej wyróżniających cech naszej strony jest system **5 motywów kolorystycznych**, dzięki którym każdy może dostosować wygląd do swoich preferencji:

### Dostępne motywy:
- 🟠 **Orange (domyślny)** – ciepły, energetyczny kolor E-XPERT
- 🔵 **Blue** – profesjonalny i spokojny
- 🟢 **Green** – świeży i naturalny
- 🟣 **Purple** – kreatywny i innowacyjny
- 🔴 **Red** – dynamiczny i odważny

Zmiana motywu jest natychmiastowa i odbywa się **bez przeładowania strony** – wystarczy kliknąć odpowiedni przycisk w nawigacji lub użyć parametru URL:

```
https://knsiexpert.github.io/site/?theme=blue
```

<p align="center">
  <img src="https://i.imgur.com/LqRBzpS.png" width="70%" />
</p>

---

## 🌙 Tryb ciemny nowej generacji

W odpowiedzi na potrzeby użytkowników, nasza strona oferuje **zaawansowany tryb ciemny** z trzema opcjami:

### 🤖 Automatyczny
Strona automatycznie wykrywa preferencje systemowe i dostosowuje się do nich. Jeśli w systemie masz włączony tryb ciemny – strona również będzie ciemna.

### 🎛️ Manualny
Przycisk **☀️/🌙** w nawigacji pozwala natychmiast przełączyć między trybem jasnym a ciemnym, niezależnie od ustawień systemowych.

### 💾 Zapamiętywanie preferencji
Twój wybór jest zapisywany w lokalnej pamięci przeglądarki i będzie zachowany przy kolejnych wizytach.

---

## ✨ Nowoczesne funkcje i animacje

### 🎬 Animacje Lottie
Strona wykorzystuje **dynamiczne animacje Lottie** – lekkie, skalowalne animacje wektorowe, które dodają życia interfejsowi bez spowalniania ładowania.

### 🖼️ Zaawansowana galeria
Galeria zdjęć z pełnym **lightbox'em** oferuje:
- Nawigację klawiaturą (strzałki, ESC)
- Licznik zdjęć
- Płynne przejścia
- Zoom i pełny ekran

### 🎠 Karuzela projektów
Automatyczna karuzela z **manualną kontrolą**, pokazująca nasze najważniejsze projekty i osiągnięcia.

### 🔝 Inteligentny scroll to top
Nowoczesny przycisk przewijania do góry, który pojawia się dopiero po przescrollowaniu części strony.

---

## 📱 Full responsive – strona na każdym urządzeniu

Strona została zaprojektowana z myślą o **wszystkich urządzeniach**:

- 📱 **Smartfony** – dotykowe gesty, zoptymalizowane menu
- 📱 **Tablety** – hybrydowe układy, idealne proporcje
- 💻 **Laptopy** – pełna funkcjonalność, wygodna nawigacja
- 🖥️ **Desktopy** – wykorzystanie dużych ekranów, rozbudowane layouty
- 📺 **Duże ekrany** – skalowanie do 4K i więcej

Każdy element jest **testowany i zoptymalizowany** dla różnych rozdzielczości.

---

## 🏗️ Architektura oparta na danych

### System plików JSON

Jedną z kluczowych decyzji architektonicznych było **oddzielenie treści od kodu**. Wszystkie dane strony znajdują się w plikach JSON w katalogu `data/`:

```
data/
├── home.json           # Strona główna, hero, statystyki
├── navigation.json     # Menu nawigacji
├── projects.json       # Lista projektów
├── goals.json          # Cele i misja
├── team.json          # Skład zespołu i zarząd
├── gallery.json       # Galeria zdjęć
├── activity.json      # Działalność i historia
├── constitution.json  # Statut koła
├── recruitment.json   # Informacje rekrutacyjne
├── publications.json  # Blog i publikacje
└── footer.json        # Stopka i kontakt
```

### Dlaczego to ważne?

#### ✅ Łatwość aktualizacji
Aby zmienić treść strony, wystarczy edytować plik JSON – **nie trzeba znać HTML, CSS ani JavaScript**.

#### ✅ Zarządzanie treścią
Członkowie koła mogą aktualizować zawartość bez ingerencji w kod strony.

#### ✅ Wersjonowanie
Każda zmiana w treści jest śledzona przez Git – mamy pełną historię zmian.

#### ✅ Automatyzacja
Dane w formacie JSON można łatwo generować, walidować i przetwarzać automatycznie.

---

## 🎯 Inteligentne funkcje użytkowe

### 👥 Bezpośrednie linki do członków zespołu

Możliwość **linkowania bezpośrednio do konkretnego członka** z automatycznym podświetleniem i przewijaniem:

```
https://knsiexpert.github.io/site/team?member=piotr-porzuczek
```

Kafelek członka zostanie **podświetlony pomarańczowym kolorem** i strona automatycznie przewinie do odpowiedniej sekcji.

**Zastosowania:**
- Łatwe udostępnianie profili członków
- Referencje w dokumentach i mailach
- Prezentacje i portfolio

### 🔗 Czyste URL-e bez hashtag'ów

Strona wykorzystuje **nowoczesny routing** bez hashtag'ów:

```
✅ https://knsiexpert.github.io/site/projects
❌ https://knsiexpert.github.io/site/#projects
```

Dzięki temu URL-e są:
- Czytelniejsze
- Przyjazne dla SEO
- Łatwiejsze do zapamiętania
- Kompatybilne z social media

---

## 📰 Integracja z blogiem

Strona posiada **sekcję publikacji** zintegrowaną z naszym blogiem poprzez technologię **markdowns-peek**, która:

- Automatycznie pobiera artykuły z repozytorium blog
- Wyświetla najnowsze wpisy
- Zachowuje spójność designu
- Aktualizuje się automatycznie przy nowych publikacjach

---

## ⚡ Technologie i wydajność

### Stack technologiczny

| Technologia | Zastosowanie |
|-------------|--------------|
| **HTML5** | Semantyczny markup |
| **CSS3** | Grid, Flexbox, CSS Variables |
| **JavaScript ES6+** | async/await, fetch API, History API |
| **Lottie** | Animacje wektorowe |
| **GitHub Pages** | Hosting |
| **GitHub Actions** | CI/CD |

### Optymalizacja wydajności

Strona została zoptymalizowana pod kątem trzech głównych obszarów wydajności:

**Szybkie ładowanie** osiągamy przez minimalizację requestów HTTP, lazy loading obrazów, asynchroniczne ładowanie danych JSON i efektywne cache'owanie zasobów. Każdy element strony ładuje się tylko wtedy, gdy jest potrzebny.

**Płynne działanie** zapewniają animacje sprzętowo przyspieszone (CSS transform, opacity), debouncing przy scroll events, efektywne przełączanie motywów bez rerenderingu całej strony oraz optymalizacja zapytań DOM. Wszystko działa płynnie nawet na słabszych urządzeniach.

**Mały rozmiar** to efekt świadomych decyzji: brak ciężkich frameworków (React, Vue), czysty vanilla JavaScript, zoptymalizowane obrazy i kompresja wszystkich zasobów. Cała strona waży mniej niż typowa strona z React.

---

## 🛠️ Deployment i automatyzacja

### GitHub Actions – pełna automatyzacja

Nasza strona korzysta z **GitHub Actions** do automatycznego wdrażania:

```yaml
1. Push do main branch
2. GitHub Actions uruchamia się automatycznie
3. Budowanie i walidacja
4. Deployment na GitHub Pages
5. Strona online w ~2 minuty
```

### Korzyści z automatyzacji:

- ✅ **Brak ręcznych deploymentów** – wszystko dzieje się automatycznie
- ✅ **Szybkie aktualizacje** – od commita do produkcji w kilka minut
- ✅ **Bezpieczeństwo** – automatyczne testy przed wdrożeniem
- ✅ **Historia wdrożeń** – pełna transparentność zmian

---

## 📖 Dokumentacja – wszystko co potrzebne

Strona posiada **obszerną dokumentację** w katalogu `docs/`:

---

## 🌍 Open source jako fundament

Nasza strona jest w **100% open source** i dostępna na GitHubie:

### 📦 Repozytorium
**[github.com/knsiexpert/site](https://github.com/knsiexpert/site)**

### 🤝 Wkład w rozwój

Każdy może **przyczynić się** do rozwoju strony:

1. **Fork** repozytorium
2. **Clone** na swój komputer
3. Wprowadź **zmiany** lub dodaj **funkcje**
4. Stwórz **Pull Request**
5. Po review – **merge** do głównej gałęzi

### Obszary do kontrybutcji:

- 🎨 **Design** – propozycje nowych motywów, layoutów
- 💻 **Kod** – nowe funkcje, optymalizacje
- 📝 **Treść** – aktualizacja danych, artykuły
- 🐛 **Bugfixy** – zgłaszanie i naprawianie błędów
- 📚 **Dokumentacja** – ulepszanie przewodników

---

## 🎯 Sekcje strony – kompletna wizytówka

Nasza strona oferuje kompleksową prezentację działalności E-XPERT poprzez dziesięć głównych sekcji:

| Sekcja | Zawartość |
|--------|-----------|
| 🏠 **Strona główna** | Hero section z animacją, kluczowe statystyki (24 lata działalności, projekty, osiągnięcia), najnowsze aktualności i call-to-action |
| 🚀 **Projekty** | Lista projektów badawczych, użyte technologie, linki do GitHub i demo, filtry według kategorii |
| 🎯 **Cele i misja** | Nasza wizja, wartości koła, obszary działalności i strategia rozwoju |
| 👥 **Zespół** | Obecny zarząd, członkowie z wszystkich lat, linki do profili i pełnione funkcje |
| 🖼️ **Galeria** | Zdjęcia z wydarzeń, warsztatów i konferencji, projekty zespołowe, lightbox z nawigacją |
| 📊 **Działalność** | Historia koła od 2001 roku, osiągnięcia i nagrody, współpraca z firmami, udział w konkursach |
| 📜 **Statut** | Pełny tekst statutu, struktura organizacyjna, prawa i obowiązki członków |
| 🎓 **Rekrutacja** | Jak dołączyć do E-XPERT, wymagania i proces rekrutacji, benefity członkostwa, harmonogram spotkań |
| 📰 **Publikacje** | Najnowsze artykuły z bloga, linki do pełnych tekstów, RSS feed |
| 📞 **Kontakt** | Email koła, social media (Facebook, LinkedIn, GitHub), lokalizacja (Wydział Zarządzania UG), formularz kontaktowy |

---

## 💻 Lokalne uruchomienie – dla developerów

### Wymagania
- Node.js (zalecane) lub Python 3
- Git

### Instalacja i start

```bash
# Sklonuj repozytorium
git clone https://github.com/knsiexpert/site.git
cd site

# Opcja 1: NPM (zalecane)
npm install
npm start  # Automatycznie otwiera przeglądarkę

# Opcja 2: Python
python -m http.server 8000
# Otwórz: http://localhost:8000

# Opcja 3: npx (bez instalacji)
npx http-server -p 8000 -o
```

**Dlaczego potrzebny serwer?**  
Strona dynamicznie ładuje pliki JSON – wymaga to serwera HTTP (nie działa przez `file://`).

---

## 🎨 Design system – spójność i elegancja

Strona opiera się na przemyślanym systemie designu, który zapewnia spójność i profesjonalny wygląd.

| Element | Opis |
|---------|------|
| **Kolorystyka** | Każdy motyw ma starannie dobraną paletę: kolor główny, akcent, tła jasne/ciemne, odcienie szarości oraz kolory semantyczne (sukces, błąd, ostrzeżenie) |
| **Typografia** | Nowoczesne fonty sans-serif dla nagłówków, czytelne dla treści, monospace dla kodu. Responsywne rozmiary dostosowane do urządzeń |
| **Spacing** | Spójny system odstępów oparty na jednostkach 8px (8, 16, 24, 32, 48, 64px) zapewniający konsystencję i rytm wizualny |
| **Grid** | Flexbox i CSS Grid, 12-kolumnowy layout na desktop, elastyczne breakpointy, podejście mobile-first |

## 📊 Kluczowe liczby

| Funkcja | Wartość |
|---------|---------|
| 🎨 Motywy kolorystyczne | **5** (orange, blue, green, purple, red) |
| 🌙 Tryby wyświetlania | **2** (jasny, ciemny) |
| 📱 Breakpointy responsywne | **4+** (mobile, tablet, desktop, 4K+) |
| 🖼️ Zdjęcia w galerii | **50+** |

---

## 🏆 Osiągnięcia techniczne

Jesteśmy dumni z tego, co udało się osiągnąć:

| Osiągnięcie | Opis |
|-------------|------|
| ✅ **Zero frameworków** | Cała strona w vanilla JavaScript – szybka, lekka, bez zbędnych zależności |
| ✅ **Pełna responsywność** | Idealnie działa na urządzeniach od 320px do 4K+ |
| ✅ **Accessibility** | WCAG 2.1 AA compliant – dostępna dla osób z niepełnosprawnościami |
| ✅ **SEO optimized** | Semantyczny HTML, meta tagi, Open Graph – gotowa na indeksowanie |
| ✅ **Modern standards** | ES6+, CSS Grid, Flexbox, History API – najnowsze standardy webowe |

---

## 🤝 Podziękowania

Strona powstała dzięki zaangażowaniu zespołu E-XPERT 2024/25 (pomysły, feedback, testy), opiekuna koła (wsparcie merytoryczne i organizacyjne), społeczności open source (inspiracje i narzędzia) oraz użytkowników, którzy dostarczyli cennych uwag i sugestii.

---

## 🌐 Zobacz sam!

### 👉 [knsiexpert.github.io/site](https://knsiexpert.github.io/site/)

Odwiedź naszą stronę i przekonaj się sam. Wypróbuj różne motywy kolorystyczne, przełącz tryb ciemny/jasny, przeglądaj projekty i osiągnięcia, poznaj naszych członków i sprawdź galerię zdjęć.

---

## 🔗 Przydatne linki

| Zasób | Link |
|-------|------|
| 🏠 Strona główna | [knsiexpert.github.io/site](https://knsiexpert.github.io/site) |
| 💻 GitHub repo | [github.com/knsiexpert/site](https://github.com/knsiexpert/site) |
| 📰 Blog | [knsiexpert.github.io/site/publications](https://knsiexpert.github.io/site/publications) |
| 📘 Facebook | [facebook.com/knsiexpert](https://www.facebook.com/knsiexpert/) |
| 💼 LinkedIn | Koło Naukowe Systemów Informatycznych E-xpert |

---

## 🎯 Zapraszamy do współpracy!

Masz pomysł na ulepszenie strony?  
Znalazłeś błąd?  
Chcesz dodać nową funkcję?

**Stwórz issue lub pull request na GitHubie!**

Każdy wkład jest cenny – od poprawek literówek, przez propozycje designu, po nowe funkcjonalności.

---

*Koło Naukowe Systemów Informatycznych E-XPERT*  
*AIS Student Chapter of University of Gdansk*  
*Building the future, one line of code at a time* 💻✨

