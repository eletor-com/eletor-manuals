# Dokumentacja techniczna ELETOR

Publiczne instrukcje produktów, FAQ, informacje o firmie i katalogach ELETOR w 18 wersjach. Repozytorium jest źródłem prawdy dla Markdown i ilustracji w katalogu [`assets/`](assets/). Polski katalog `pl/` jest źródłem prawdy; pozostałe katalogi zawierają tłumaczenia o zgodnych ścieżkach.

## Dokumentacja online

- Polski: https://eletor.pl/doc/
- Angielski: https://eletor.com/doc/
- Pozostałe wersje: `https://eletor.com/doc/<country-code>/`

| Kod katalogu | Język |
| --- | --- |
| pl | polski, źródłowy |
| gb | angielski, wersja domyślna |
| be | niderlandzki, Belgia |
| by | białoruski |
| cn | chiński uproszczony |
| cz | czeski |
| de | niemiecki |
| dk | duński |
| es | hiszpański |
| fr | francuski |
| hu | węgierski |
| it | włoski |
| nl | niderlandzki, Niderlandy |
| pt | portugalski europejski |
| ro | rumuński |
| rs | serbski, cyrylica |
| ru | rosyjski |
| ua | ukraiński |

Są to kody krajów ISO 3166-1 alpha-2, nie kody języków. Nie zmieniaj nazw katalogów na `en`, `cs`, `da`, `uk` lub `zh`. Angielska strona nie używa `/gb/`, a polska jest na osobnej domenie.

## Czytanie i edycja

Dokumenty można czytać bezpośrednio na GitHub lub w opublikowanej dokumentacji. Schematy i ilustracje są wersjonowane w `assets/` oraz publikowane razem z dokumentami. Względne ścieżki obrazów w MD dotyczą układu gotowej strony; na GitHub ilustracje można przeglądać bezpośrednio w `assets/`. Wersje dla agentów można odkryć przez [polski llms.txt](https://eletor.pl/doc/llms.txt) i [angielski llms.txt](https://eletor.com/doc/llms.txt). Publiczne źródło strony HTML z końcowym `/` jest dostępne przez dopisanie `index.md`.

Edytuj dokument źródłowy w `pl/`, zachowując frontmatter, ścieżki, kod, jednostki i oznaczenia produktów. Używaj jednego H1 oraz sekcji H2/H3. Przykład:

```markdown
---
title: Instrukcja produktu
description: Montaż i obsługa produktu ELETOR.
sidebar_position: 2
---

# Nazwa produktu

Opis zastosowania.

## Montaż

Instrukcje i informacje techniczne.
```

Pliki są kompilowane jako Markdown/MDX; przykłady zawierające `<`, `>` lub `{}` zapisuj w backtickach albo blokach kodu. Ścieżki odnośników i ilustracji powinny pozostać zgodne we wszystkich wersjach. Zmiany polskich dokumentów są podstawą aktualizacji tłumaczeń i publikacji po walidacji.

Stan z 2 października 2026: 10 polskich dokumentów i 170 tłumaczeń, łącznie 180 dokumentów. Należy zachowywać sens techniczny, ostrzeżenia bezpieczeństwa, wartości oraz jednostki. Zgłaszając błąd, podaj kod kraju, ścieżkę dokumentu i proponowaną poprawkę.

## Ilustracje — jedno źródło prawdy

Wspólne ilustracje wszystkich wersji umieszczaj w `assets/`, zachowując strukturę dokumentów, np. `assets/instrukcje/Sterowniki/img/Sc-s2.png`. Instrukcja `pl/instrukcje/Sterowniki/Instrukcja_SC-S.md` odwołuje się do niej jako `./img/Sc-s2.png`. Build kopiuje wspólny zasób do właściwej lokalizacji każdej wersji; nie trzeba powielać obrazu w 18 katalogach.

Commit tego repo przypina zarówno teksty, jak i oryginalne ilustracje. Zmiana samego obrazu uruchamia ponowną publikację przez istniejącą automatyzację bez ponownego tłumaczenia niezmienionych tekstów. Bezstratne WebP powstaje dopiero podczas buildu, a oryginały pozostają tutaj. Kod strony, sekrety i konfiguracja automatyzacji pozostają w prywatnych repozytoriach.
