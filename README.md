# Sextant Money — Rechtliches

Datenschutzerklärung, AGB und Impressum der App **Sextant Money**, einer App zur
Haushaltsführung für iOS.

Veröffentlicht über GitHub Pages:

- Übersicht — <https://alinup12.github.io/sextant-money/>
- Datenschutz — <https://alinup12.github.io/sextant-money/datenschutz.html>
- AGB — <https://alinup12.github.io/sextant-money/agb.html>
- Impressum — <https://alinup12.github.io/sextant-money/impressum.html>

Die Datenschutz-Adresse ist die, die in App Store Connect als Privacy Policy URL
hinterlegt wird.

## Aufbau

Vier statische Seiten und ein gemeinsames Stylesheet. Keine Abhängigkeiten, kein
Build-Schritt — was hier liegt, ist was ausgeliefert wird.

| Datei | Inhalt |
|---|---|
| `index.html` | Einstieg mit den drei Dokumenten |
| `datenschutz.html` | Datenschutzerklärung (DSGVO) |
| `agb.html` | Allgemeine Geschäftsbedingungen |
| `impressum.html` | Offenlegung nach § 5 ECG und § 25 MedienG |
| `stil.css` | Farben, Typografie, hell und dunkel |

Schriften: Instrument Serif und Instrument Sans über Google Fonts — dieselben wie
in der App.

## Ändern

Texte tragen oben eine Versionsnummer und ein Datum. Wer etwas Inhaltliches ändert,
zieht beides mit: im `<p class="stand">` und im `<footer>`.
