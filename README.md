# SEPA Kundenerfassung

Kunden mit Bankverbindung und unterschriebenem Papier-Mandat in Stripe anlegen. Eine einzige Datei (`index.html`), kein Server nötig.

## Hosten auf GitHub Pages

1. Neues Repository anlegen (am besten **privat**, falls euer GitHub-Tarif Pages für private Repos erlaubt; sonst öffentlich, die Datei enthält keine Geheimnisse).
2. `index.html` hochladen (und optional den Ordner `anleitung/`, siehe unten).
3. **Settings → Pages**: Source "Deploy from a branch", Branch `main`, Ordner `/ (root)`, speichern.
4. Nach ein bis zwei Minuten zeigt GitHub dort die Adresse der Seite an. Diese Adresse bekommt die Firmenbesitzerin.

## Erste Anmeldung

Die Seite zeigt beim ersten Öffnen eine Schritt-für-Schritt-Anleitung, wie man in Stripe den passenden Schlüssel erstellt und einfügt. Das Tool prüft danach automatisch, ob alle Berechtigungen stimmen.

## Echte Screenshots in der Anleitung

In der Anleitung sind schematische Skizzen eingebaut. Echte Screenshots werden automatisch stattdessen angezeigt, wenn sie neben `index.html` in diesem Ordner liegen:

```
anleitung/schritt-1.png   Stripe → Entwickler → API-Schlüssel (Kontoname oben links sichtbar)
anleitung/schritt-2.png   Button "Eingeschränkten Schlüssel erstellen"
anleitung/schritt-3.png   Feld "Schlüsselname"
anleitung/schritt-4.png   Berechtigungsliste mit Customers / Mandates / PaymentMethods / SetupIntents
anleitung/schritt-5.png   Button "Schlüssel erstellen" bzw. der angezeigte Schlüssel
```

Am besten im **Testmodus** aufnehmen und den Schlüssel auf dem Bild unkenntlich machen.
