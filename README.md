# WAS BLEIBT. — Ein Wegweiser für Menschen

**[Interaktive Live-Demo](https://mikelninh.github.io/was-bleibt/)**

Unabhängige Arbeitsprobe von Michael Ninh für die Rolle **Referent*in Erbschaften & Großspenden** beim Humanistischen Verband Berlin-Brandenburg (HVD BB).

**Nicht offiziell**: Diese Seite ist keine HVD-Plattform, nimmt keine Spenden an und gibt keine Nachlass- oder Rechtsberatung.

## Worum geht es?

Menschen möchten helfen, aber nicht jede Einrichtung veröffentlicht einen aktuellen Spendenbedarf. WAS BLEIBT. kombiniert einen freiwilligen dreistufigen Projektfinder, nachvollziehbare Projektquellen und eine visuelle Entdeckungsansicht mit 98 recherchierten Angeboten.

## V7 – Visueller Polish

- **12 eigens erstellte KI-generierte Symbolbilder** in einer konsistenten warmen Bildsprache; keine realen Aufnahmen von HVD-Projekten
- Fotobasierte Themenkacheln für Jugend, Hospiz, Soziales und Bildung
- Bebilderte Angebotskarten und kuratierte Projektgeschichten
- Bebilderte Einstiege in Großspenden, Unternehmensengagement und Nachlassbegleitung
- Weniger Gleichförmigkeit, klarere Hierarchie, responsive Layouts und sichtbare Bildkennzeichnung
- Freiwillige Spendenbereiche statt einzelner, preisschildartiger Beträge; der Bereich beeinflusst das Projektranking nicht

## In 90 Sekunden zeigen

1. Startseite öffnen und **Projekte entdecken** auswählen.
2. Ein Themenbild wählen und die gefilterten Angebote sehen.
3. Bei einer Karte **Projekt ansehen** wählen: Quellen und Spendenstatus erklären.
4. Den Projektfinder ausprobieren und einen unverbindlichen Förderbereich wählen.
5. Persönlichen Kontakt statt automatisierter Finanzierungsentscheidung hervorheben.

## Einordnung und Grenzen

- **98 katalogisierte Angebote bedeuten nicht 98 bestätigte Förderbedarfe.**
- Unterscheidung zwischen veröffentlichtem Spendenaufruf, dokumentiertem Spendenweg und bislang nicht bestätigtem Projekt-Förderbedarf.
- Alle fotografisch wirkenden Motive sind **synthetische Symbolbilder**. Sie bilden keine echten Mitarbeitenden, Kinder, Patient*innen, Räume oder Handlungen einer realen HVD-Einrichtung ab.
- Quellen, Nutzungsrechte, Datenschutz, Barrierefreiheit, Spendenabwicklung, Inhalte und Markenführung benötigen vor produktiver Nutzung eine offizielle Freigabe.
- Keine Echtzeit-Finanzierungsziele, keine Zahlungsverarbeitung, kein CRM und keine automatische Testamentserstellung.

## Technischer Aufbau

Die gesamte interaktive Website liegt in **`index.html`**. Die zwölf symbolischen Bildmotive sind komprimiert als WebP-Daten in dieser Datei eingebettet. Es gibt keinen Build-Schritt, keine Bildserver-Anfragen, keinen API-Schlüssel und kein Tracking.

Für einen lokalen Test: `python -m http.server 8000` und `http://localhost:8000` öffnen.

**Stand:** 29. Oktober 2026.
