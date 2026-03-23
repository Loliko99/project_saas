# Repozytorium procedur i polityk (wersjonowanie + potwierdzenia)

## 🎯 Cel

Webowa aplikacja dla małych firm i organizacji do:

- tworzenia oraz edytowania procedur i polityk (BHP, IT, polityka dostępu itp.),
- zarządzania wersjami dokumentów i historii zmian,
- publikowania bieżącej, obowiązującej wersji,
- zbierania potwierdzeń "zapoznałem się" od pracowników,
- raportowania, kto potwierdził, a kto jeszcze nie.


## 👥 Kluczowe role

- **Autor** – tworzy i edytuje dokumenty, przygotowuje wersje robocze.
- **Zatwierdzający (Reviewer / Owner)** – akceptuje publikację wersji i wskazuje dokument jako obowiązujący.
- **Pracownik** – przegląda opublikowane dokumenty i potwierdza, że się z nimi zapoznał.


## 🧩 MVP (Minimum Viable Product)

### 1) Edytor dokumentów

- Rich text (Markdown / WYSIWYG) lub prosty edytor tekstowy,
- możliwość zapisu roboczych wersji (draftów),
- obsługa podstawowego formatowania (nagłówki, listy, linki).

### 2) Wersjonowanie i historia zmian

- automatyczne zapisywanie każdej opublikowanej wersji,
- pokazywanie historii wersji (kto i kiedy opublikował),
- możliwość przywrócenia poprzedniej wersji (opcjonalnie).

### 3) Publikacja + link

- każda publikacja generuje stały link do dokumentu,
- publikowana wersja staje się „obowiązującą”,
- widok historii pokazuje, która wersja jest aktywna.

### 4) Potwierdzenia “zapoznałem się”

- pracownik klika przy dokumencie przycisk "zapoznałem się",
- zapisuje się identyfikator i timestamp potwierdzenia,
- możliwość wysyłania przypomnień do tych, którzy nie potwierdzili.

### 5) Raport pokrycia

- tabela/lista użytkowników z informacją, kto potwierdził,
- filtr dla grup/kategorii (np. departament, rok),
- opcjonalnie: eksport CSV/Excel.


## ⚠️ Kluczowe punkty do przemyślenia

- **Autoryzacja i wiarygodność** – potwierdzenia muszą być powiązane z loginem/UID, aby miały wartość audytową.
- **Obowiązująca wersja** – jasne, która wersja dokumentu jest aktualna; użytkownicy muszą widzieć tę informację od razu.
- **Adopcja** – prosty interfejs i szybkie potwierdzenia zwiększają używanie przez pracowników.


## 🧭 Kolejne kroki (propozycja)

1. Zdefiniować **szczegółowy zakres MVP** (ekrany/flow dla każdej roli).
2. Zaprojektować **model danych** (dokument → wersja → potwierdzenia).
3. Przygotować **prototyp UI** (dashboard + widok dokumentu + raport potwierdzeń).
4. Przetestować koncept z 1–2 małymi organizacjami (feedback + poprawki).
