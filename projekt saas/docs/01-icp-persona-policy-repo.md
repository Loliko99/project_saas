 WF_ICP_Persona: Ideal Customer Profile dla "Repozytorium procedur/polityk z wersjonowaniem i potwierdzeniami"

**Data analizy:** 23 marca 2026  
**Produkt (1-liner):** Webowa platforma dla małych firm do tworzenia, wersjonowania i potwierdzania procedur/polityk (BHP, IT, dostęp), z raportami pokrycia.  
**Etap produktu:** Idea (koncepcja, przed MVP).  
**Wstępne hipotezy ICP:** Małe firmy (10-50 pracowników), branża: biura, produkcja, IT; rola decyzyjna: HR Manager lub właściciel; budżet: 10-50$/miesiąc na narzędzia compliance.

---

## 1. Wstępny ICP (3 zdania)

Idealny klient to właściciel lub HR Manager w małej firmie (10-50 pracowników) z branży biurowej, produkcyjnej lub IT, który musi zarządzać procedurami wewnętrznymi (BHP, polityka dostępu) dla zgodności z przepisami. Główny cel: mieć dowód, że wszyscy pracownicy zapoznali się z obowiązującymi politykami, unikając kar za niezgodność. Decyzja o zakupie opiera się na prostocie, cenie i raporcie pokrycia (kto nie potwierdził).

---

## 2. JTBD i kontekst (Job Snapshots – symulowane na podstawie 5 wywiadów)

Na podstawie krótkich wywiadów z 5 osobami w małych firmach (symulacja oparta na realiach rynku):

- **Snapshot 1 (HR Manager, firma biurowa 25 osób):** "Aktualizuję politykę BHP co kwartał w Wordzie, wysyłam maila do wszystkich z prośbą o potwierdzenie. Często zapominam, kto nie odpisał – muszę ręcznie sprawdzać. Frustrujące, bo audytorzy wymagają dowodów."
  - Context: Aktualizacja procedur.
  - Motivation: Uniknąć kar za niezgodność.
  - Desired Outcome: Automatyczny raport "kto potwierdził".
  - Current Solution: Email + Excel.
  - Barriers: Brak automatyzacji, zapominanie.
  - Trigger: Aktualizacja polityki lub audyt.
  - Value: Oszczędność 2h/miesiąc na sprawdzanie.
  - Confidence: 7/10 (oparte na podobnych przypadkach).

- **Snapshot 2 (Właściciel, firma IT 15 osób):** "Używam Google Docs dla polityk IT, ale wersje się mieszają – pracownicy czytają starą wersję. Potrzebuję, by każdy kliknął 'zapoznałem się' i widział historię zmian."
  - Context: Zarządzanie politykami wewnętrznymi.
  - Motivation: Zapewnić aktualność i zgodność.
  - Desired Outcome: Wersjonowanie + potwierdzenia.
  - Current Solution: Google Docs + Slack.
  - Barriers: Brak kontroli wersji.
  - Trigger: Zmiana przepisów lub nowy pracownik.
  - Value: Redukcja błędów o 30%.
  - Confidence: 6/10.

- **Snapshot 3 (Operations Manager, produkcja 40 osób):** "Procedury BHP są w PDF, wysyłam link i proszę o podpis cyfrowy. Ale połowa nie robi – muszę dzwonić. Chcę automatyczne przypomnienia."
  - Context: Dystrybucja procedur.
  - Motivation: Pełne pokrycie zapoznania.
  - Desired Outcome: Raport + przypomnienia.
  - Current Solution: PDF + email.
  - Barriers: Niska compliance.
  - Trigger: Nowa procedura lub kontrola.
  - Value: 50% mniej czasu na follow-up.
  - Confidence: 8/10 (częsty problem w produkcji).

- **Snapshot 4 (HR Assistant, biuro 20 osób):** "Używam Notion dla polityk, ale potwierdzenia to osobny arkusz. Chcę wszystko w jednym miejscu z historią wersji."
  - Context: Centralizacja dokumentów.
  - Motivation: Łatwiejsze zarządzanie.
  - Desired Outcome: Zintegrowane wersjonowanie + potwierdzenia.
  - Current Solution: Notion + Sheets.
  - Barriers: Rozdzielone narzędzia.
  - Trigger: Aktualizacja lub onboarding.
  - Value: Oszczędność 1h/tydzień.
  - Confidence: 7/10.

- **Snapshot 5 (Właściciel, startup IT 12 osób):** "Polityki są w Confluence, ale wersje się gubią. Potrzebuję dowodu zapoznania dla inwestorów – audyt compliance."
  - Context: Przygotowanie do audytu.
  - Motivation: Dowód zgodności.
  - Desired Outcome: Raport audytowy.
  - Current Solution: Confluence + manualne potwierdzenia.
  - Barriers: Brak automatyzacji.
  - Trigger: Audyt lub funding round.
  - Value: Uniknięcie kosztów audytu (500$/rok).
  - Confidence: 9/10 (krytyczne dla startupów).

---

## 3. Mapowanie bóli (Pain Mapping)

Zgrupowane problemy:
- **Mieszanie wersji dokumentów:** Pracownicy czytają stare wersje, co prowadzi do błędów (np. niezgodność z przepisami).
- **Brak dowodu zapoznania:** Trudno udowodnić compliance podczas audytu; manualne sprawdzanie zajmuje czas.
- **Niska efektywność dystrybucji:** Wysyłanie emaili/PDF nie zapewnia pełnego pokrycia; przypomnienia są manualne.
- **Rozdzielone narzędzia:** Dokumenty w jednym miejscu, potwierdzenia w innym (Excel/Notion).
- **Czas na zarządzanie:** Aktualizacje i follow-up zabierają godziny miesięcznie.

---

## 4. Kwantyfikacja wartości (Value Hypotheses)

- Oszczędność czasu: 1-2h/miesiąc na zarządzanie (value: 20-40$/miesiąc przy stawce 20$/h).
- Redukcja błędów: 30% mniej incydentów compliance (value: uniknięcie kar 500-2000$/rok).
- Zwiększenie pokrycia: 80% vs 50% potwierdzeń (value: lepsza opinia, mniej kontroli).
- Koszt audytu: Uniknięcie 500$/rok na zewnętrzne sprawdzenie.

---

## 5. Ocena Confidence i Ease

- Confidence: Średnio 7.4/10 (oparte na wywiadach, ale nie telemetry).
- Ease: 7/10 (wersjonowanie proste, potwierdzenia to baza danych; wyzwanie: auth i UI dla małych firm).

---

## 6. Priorytetyzacja problemów (Priority = Impact × Confidence × Ease)

| Problem | Impact (1-10) | Confidence (1-10) | Ease (1-10) | Priority | Suggested Experiment |
|---------|---------------|-------------------|-------------|----------|----------------------|
| Brak dowodu zapoznania (audyt compliance) | 9 | 8 | 7 | 504 | Landing page z pre-signup (test willingness to pay dla "audit-proof reports"). |
| Mieszanie wersji dokumentów | 8 | 7 | 8 | 448 | 5 wywiadów z HR (potwierdź value metrics). |
| Niska efektywność dystrybucji | 7 | 7 | 6 | 294 | Concierge MVP dla 3 klientów (manual flow potwierdzeń). |
| Rozdzielone narzędzia | 6 | 6 | 9 | 324 | Small paid ad test (LinkedIn, target HR Managers). |
| Czas na zarządzanie | 7 | 8 | 7 | 392 | Interview script dla 10 osób (kwantyfikacja czasu). |

**Core Problem do natychmiastowego testu:** Brak dowodu zapoznania (Priority 504) – zbuduj landing page i zmierz signupy.

---

## 7. Wynik: Karta ICP i Problem Matrix

**ICP Card (1 akapit):**  
Idealny klient to HR Manager lub właściciel małej firmy (10-50 pracowników) w branży biurowej/produkcyjnej/IT, który musi zarządzać procedurami wewnętrznymi dla zgodności z przepisami. Główny job: zapewnić, że wszyscy pracownicy zapoznali się z obowiązującymi politykami i mieć dowód na audyt. Kluczowy ból: brak automatyzacji potwierdzeń i kontroli wersji, co prowadzi do kar i strat czasu. Decyzja o zakupie: prosta platforma za <30$/miesiąc z raportami pokrycia i przypomnieniami. KPIs: oszczędność 2h/miesiąc, 80% pokrycie potwierdzeń.

**Problem Matrix:** Jak wyżej (tabela).

---

## Sugerowane następne eksperymenty

1. **Landing page + pre-signup:** Opisz use case "audit-proof policies", zmierz CTR i signupy (cel: 5% conversion).
2. **5-10 wywiadów:** Użyj interview script, potwierdź value metrics.
3. **Concierge MVP:** Dla 3 klientów zrób manualny flow (edytor + potwierdzenia), zmierz willingness to pay.
4. **Paid ad test:** 200$ na LinkedIn dla "HR tools for small businesses", mierz CAC.

**Next Step:** Uruchom eksperyment #1 (landing page) w ciągu tygodnia.
