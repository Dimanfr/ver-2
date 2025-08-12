# Digital-KI Landing Page

Statische Einseiter-Website für Digital-KI – KI-gestützter Erinnerungsservice für Sanitätshäuser. Deployment erfolgt über Netlify.

## Entwicklung

Die Seite nutzt reines HTML und TailwindCSS über das CDN. Es gibt keinen Build-Step.

**Bearbeiten:**

```bash
git clone <repo>
# Dateien anpassen
```

Änderungen an `index.html` reichen für die meisten Anpassungen.

## Farbpalette anpassen

Die Tailwind-Konfiguration befindet sich direkt in `index.html` unter `tailwind.config`. Die erweiterten Farben liegen im Namespace `dk`. Werte ändern und speichern.

## Netlify Forms

Das Kontaktformular ist für [Netlify Forms](https://docs.netlify.com/forms/setup/) vorbereitet. Einsendungen erscheinen nach Deploy automatisch im Netlify-Dashboard unter *Forms*.

## Portrait ersetzen

Aktuell liegt ein Text-Platzhalter unter `assets/portrait.jpg.txt`. Nach dem Merge den Platzhalter löschen und ein reales Bild als `assets/portrait.jpg` hinzufügen.

## Optional: Analytics

Für DSGVO-konforme Analytics kann z. B. [Plausible](https://plausible.io) oder GA4 (IP-Anonymisierung) eingebunden werden.


