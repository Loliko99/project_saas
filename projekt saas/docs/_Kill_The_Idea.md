 WF_Kill_The_Idea: Analiza pomysłu "Repozytorium procedur/polityk z wersjonowaniem i potwierdzeniami"

**Data analizy:** 23 marca 2026  
**Pomysł:** Webowa aplikacja dla małych firm/organizacji do tworzenia, wersjonowania i potwierdzania procedur/polityk (BHP, IT, dostęp itp.).  

**Postawa analityczna:** Jako sceptyczny inwestor zakładam, że ten projekt upadnie w ciągu 6 miesięcy, jeśli nie rozwiąże kluczowych problemów dystrybucji i konkurencji. Analiza opiera się na realiach rynku SaaS dla małych firm.

---

## 🚩 RED FLAGS (Krytyczne błędy)

- **Distribution Hell (Piekło Dystrybucji):** Małe firmy (target: 10-50 pracowników) to trudny rynek do penetracji. Brak organicznego ruchu – będziesz polegać na płatnych reklamach (LinkedIn Ads, Google Ads dla "compliance software"). CAC (Cost of Acquisition) może wynieść 100-300$ na klienta, podczas gdy LTV (Lifetime Value) przy subskrypcji 20$/miesiąc to maksymalnie 240$ w roku (zakładając 50% churn). Jak zamierzasz rozwiązać to bez dużego budżetu marketingowego? Brak widoczności w wyszukiwarkach (SEO) dla niszowych terminów jak "policy repository for small businesses".
  
- **Zero-Moat (Brak barier wejścia):** Produkt jest kopiowalny przez AI lub junior dewelopera w weekend. Wersjonowanie dokumentów to standard (Git, Notion), a potwierdzenia to prosta baza danych. Gdzie leży unikalna wartość? Jeśli nie zbudujesz community lub specyficznych integracji (np. z firmowymi SSO), konkurenci (np. startupy z Indii) skopiują to taniej.

---

## ⚠️ YELLOW FLAGS (Ostrzegawcze wyzwania)

- **Feature, Not a Product (To tylko funkcja):** Czy to nie jest po prostu rozszerzeniem Google Docs/Notion/Confluence? Duże platformy mogą dodać wersjonowanie + potwierdzenia w następnym updacie. Dla małych firm Notion jest wystarczające – dlaczego płacić za dedykowane narzędzie?

- **The Support Trap (Pułapka Wsparcia):** Integracje z autoryzacją (SSO, Active Directory) mogą być skomplikowane dla małych firm. Jeśli klienci będą wymagać customizacji (np. integracja z HR systemami), Solo-Dev spędzi czas na support zamiast rozwoju. Ryzyko: 50% czasu na tickety zamiast na nowe funkcje.

- **The "Nice-to-Have" Vitamin:** Dla dużych firm compliance to must-have (audyty, kary), ale małe firmy często ignorują to do momentu problemu. Czy to rozwiązuje krwawiący ból, czy jest tylko "dobrą praktyką"? Jeśli klienci zobaczą to jako opcjonalne, churn będzie wysoki przy pierwszej recesji.

---

## 💀 The "Death Scenario" (Realistyczny scenariusz upadku)

Po 4 miesiącach rozwoju MVP (edytor + wersjonowanie + potwierdzenia) uruchamiasz produkt. Wydajesz 500$ na reklamy LinkedIn, zdobywasz 10 beta-testerów (małe firmy). Jednak:  
- Brak organicznego ruchu – klienci nie szukają "policy repository" w Google.  
- Wysoki churn: 70% użytkowników po miesiącu, bo "Excel wystarczy".  
- Konkurencja: Darmowe alternatywy (Notion templates) lub tanie SaaS (np. 5$/miesiąc) z lepszym UI.  
- Brak feedbacku: Małe firmy nie płacą za "compliance tools" bez presji prawnej.  
W rezultacie: Zero płatnych klientów po 6 miesiącach, budżet wyczerpany, projekt zamknięty.

---

## 📉 Verdict (Ocena)

**PROCEED WITH CAUTION:** Pomysł ma potencjał w niszy compliance dla małych firm (gdzie duże narzędzia są overkill), ale wymaga natychmiastowego rozwiązania problemów dystrybucji i budowy moatu. Kluczowe ryzyka: wysoki CAC i konkurencja od free tools. Monitoruj: organiczny ruch po 3 miesiącach, churn rate <30%.

**Kluczowe ryzyka do monitorowania:**  
- CAC/LTV ratio – cel: <0.5.  
- Adoption: Czy małe firmy faktycznie płacą za to?  
- Moat: Zbuduj community lub dane (anonimizowane historie compliance).

---

## 🔄 Procedura Wyjścia (Pivot Suggestion)

Jeśli analiza pokaże słabość (np. brak ruchu), pivotuj na: **Mikro-narzędzie dla compliance w startupach** – zamiast pełnego repo, zbuduj prosty widget/embed (jak Typeform), który dodaje "potwierdzenie zapoznania" do istniejących dokumentów w Google Docs. Łatwiejsza dystrybucja (integracja z Docs), niższy CAC, focus na "must-have" dla startupów unikających kar prawnych.
