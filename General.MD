# Sophona – funkcjonalności platformy

Ten dokument pokazuje **co Sophona realnie oferuje dziś** oraz **co jest planowane**, w formie czytelnej dla osób nietechnicznych. Każdy punkt ma krótkie wyjaśnienie, *do czego to służy*.

---

## 🟢 Funkcjonalności WDROŻONE

### Dostęp, konta i płatności

* **Rejestracja i logowanie** – użytkownik zakłada konto na sophona.com
* **Free i Pro plan** – Free do testów, Pro (49$) do realnego użycia
* **Płatności przez Stripe** – bezpieczne subskrypcje miesięczne
* **Kredyty usage** – środki na AI, voice i telefony
* **Doładowania** – możliwość zwiększania limitów w trakcie miesiąca

---

### Command Center (centrum sterowania)

* **Osobna instancja dla klienta (Pro)** – pełna izolacja danych
* **Panel webowy** – jedno miejsce do zarządzania całą platformą
* **Zarządzanie agentami** – tworzenie i konfiguracja cyfrowych pracowników
* **Zarządzanie zasobami** – komputery, workery, procesy

---

### Agenci AI (cyfrowi pracownicy)

* **Agenci z rolą i zakresem obowiązków** – np. support, HR, IT
* **Osobowość agenta** – ton rozmowy, styl komunikacji
* **Job description** – jasno określone, co agent ma robić
* **Obsługa wielu użytkowników jednocześnie** – skalowanie bez zespołu
* **Działanie 24/7** – bez przerw i urlopów

---

### Rozmowa z użytkownikami

* **Chat tekstowy** – w panelu, na stronie i na desktopie
* **Rozmowy głosowe** – użytkownik może po prostu mówić
* **Połączenia telefoniczne** – agent odbiera i wykonuje telefony
* **Wysyłanie obrazów** – użytkownik może pokazać problem
* **Czytelne odpowiedzi** – formatowanie, listy, kod

---

### Automatyczne wykonywanie pracy

* **Integracje przez API** – łączenie z systemami klienta
* **Automatyzacja bez API** – klikanie po aplikacjach i stronach
* **Automatyzacja przeglądarki** – także w chmurze (headless)
* **Automatyzacja desktopowa** – jak pracownik przy komputerze

---

### Procesy biznesowe (iPaaS + RPA)

* **Budowanie procesów krok po kroku** – logiczne workflow
* **Procesy łączące wiele systemów** – API + UI
* **Proces jako endpoint API** – inne systemy mogą go wywołać
* **Scheduler (cron)** – procesy uruchamiane automatycznie

---

### Skill Map (graf umiejętności)

* **Mapa umiejętności agenta** – zamiast listy narzędzi
* **Kontekstowe używanie skills** – mniejsze ryzyko błędów
* **Generowanie mapy przez AI** – na podstawie opisu pracy
* **Propozycje nowych skills** – AI podpowiada, czego brakuje

---

### Sophona Studio (silnik wykonawczy)

* **Projektowanie logiki jak w IDE** – zmienne, warunki, pętle
* **Wykonywanie procesów w runtime** – szybkie i stabilne
* **Sterowanie rozmową z procesu** – agent dopytuje o dane
* **Bezpośredni dostęp AI do danych** – bez ręcznego mapowania JSON

---

### Widget i desktop assistant

* **Widget na stronę** – szybkie wdrożenie bez developmentu
* **Autonomiczne działanie** – agent klika i wypełnia formularze
* **Desktop assistant** – osobisty agent na Windows i macOS

---

### Telefonia

* **Integracja z Twilio** – numery lokalne i międzynarodowe
* **Zakup numeru w kilka sekund** – bez konfiguracji technicznej
* **Przypisywanie numerów do agentów** – różne role telefoniczne

---

### Bezpieczeństwo

* **Multi-tenant (Free)** – wspólna infrastruktura dla testów
* **Single-tenant (Pro)** – pełna izolacja klienta
* **Izolacja danych** – osobne instancje i storage per klient
* **Szyfrowanie danych wrażliwych** – szyfrowanie po stronie platformy (DPAI)
* **RS256** – bezpieczne podpisywanie i weryfikacja tokenów
* **Bezpieczne przechowywanie kluczy API** – klucze trzymane w zaszyfrowanym vaultcie
* **Brak ekspozycji sekretów do LLM** – LLM nigdy nie widzi surowych kluczy

---

## 🟡 Funkcjonalności W DEVELOPMENT

* **User memory** – agent pamięta użytkownika między rozmowami
* **Realtime API** – niska latencja, streaming odpowiedzi
* **Rich outputy** – pliki PDF, Excel, obrazy, wideo
* **Preferred worker** – automatyczny wybór dostępnej maszyny

---

## 🔵 Funkcjonalności NA ROADMAPIE

* **Anonimizacja danych (PII masking)** – compliance i regulacje
* **Rozpoznawanie rozmówcy po numerze** – personalizacja rozmów
* **Humans tab** – baza osób i ról w organizacji klienta
* **Spotkania online (Meet / Teams)** – agent jako uczestnik spotkań
* **Dodatkowe silniki avatarów** – więcej opcji wizualnych

---

## Jak używać tego dokumentu w sprzedaży

* Traktuj go jako **katalog możliwości**, nie checklistę do sprzedania
* Wybieraj funkcjonalności pod **konkretny problem klienta**
* Nie wszystko musi być użyte naraz – Sophona jest konfigurowalna

> **Sophona to platforma, która pozwala firmom zamieniać rozmowy w realne działania.**
