# readme_sophona - sophona-widget

## Rola repo
Embeddowalny widget czatu / AI do osadzania na stronach klientów.

## Technologie
- React 19
- Vite
- Tailwind
- Headless UI
- SignalR client
- LiveKit
- Heygen avatar SDK
- Markdown / Mermaid / KaTeX

## Najważniejsze pliki
- `src/PopupWidget.tsx`
- `src/PopupWidgetEmbed.tsx`
- `src/App.jsx`
- `src/main.jsx`

## Funkcjonalność
- pobieranie konfiguracji widgetu po `apiKey`
- osadzanie widgetu przez globalne API `window.SophonaChatWidget`
- izolacja stylów przez Shadow DOM
- tryb mobile/fullscreen
- dynamiczny styling button/chat/header
- integracja z chatem oraz voice/video avatar mode

## Co już jest
- gotowy mechanizm embed
- dynamiczna konfiguracja z backendu
- rozbudowane UI/UX widgetu
- przygotowanie do pracy jako zewnętrzny komponent osadzalny

## Ryzyka / uwagi
- `App.jsx` zawiera twardo wpisany testowy `apiKey` i endpoint
- `PopupWidget.tsx` jest duży i skupia dużo odpowiedzialności
- literówka `prefferedLanguage`

## Miejsce w architekturze
Widget jest zewnętrznym interfejsem użytkownika końcowego, który korzysta z backendu platformy do pobrania konfiguracji i prowadzenia rozmowy.