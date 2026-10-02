# Dokumentacja techniczna ELETOR

Publiczne instrukcje produktów, FAQ, informacje o firmie i katalogach ELETOR w 18 wersjach. Repozytorium zawiera wyłącznie pliki Markdown. Polski katalog `pl/` jest źródłem prawdy; pozostałe katalogi zawierają tłumaczenia o zgodnych ścieżkach.

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

Dokumenty można czytać bezpośrednio na GitHub lub w opublikowanej dokumentacji. Schematy i ilustracje są dostępne na stronie; ten checkout udostępnia same źródła Markdown. Wersje dla agentów można odkryć przez [polski llms.txt](https://eletor.pl/doc/llms.txt) i [angielski llms.txt](https://eletor.com/doc/llms.txt). Publiczne źródło strony HTML z końcowym `/` jest dostępne przez dopisanie `index.md`.

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
