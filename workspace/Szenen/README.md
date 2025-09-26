# 📁 /Szenen – Szenendateien des Romans

In diesem Ordner befinden sich **alle Szenen des Werks** als eigenständige Markdown-Dateien.  
Jede Szene stellt eine abgeschlossene narrative Einheit dar, die typischerweise:

- ein konkretes Ziel oder Thema verfolgt,
- einen oder mehrere Charaktere einbindet,
- an einem bestimmten Ort und Zeitpunkt spielt,
- ein Ergebnis oder eine Veränderung erzeugt.

---

## 🧱 Aufbau jeder Szenendatei

Jede Datei folgt dieser Struktur:

1. **Beschreibung**: Enthält strukturierte Metadaten.
2. **Handlung**: Der eigentliche Inhalt, ggf. mit Formatierungen und GPT-Hinweisen.

Beispiel:
```markdown
# Am Hafen

## Beschreibung
- **ID:** szene_07
- **Akt:** 1
- **Kapitel:** 1
- **Zeitpunkt:** 3. November 2025, 23:15 Uhr
- **Ort:** [[Hafenbecken Dortmund]]
- **Charaktere:** 
  - [[../Charaktere/Hauptfiguren/Tobias Schrader]] (POV)
  - [[../Charaktere/Hauptfiguren/Sarah Weber]]
  - [[../Charaktere/Nebenfiguren/Dr. Rausch]]
- **Funktion:** Exposition
- **Auslöser:** Schrader wird vom Revier zu einem Leichenfund gerufen
- **Ziel:** Schrader will die Identität des Toten klären
- **Konflikt:** Weber verschweigt eine Verbindung zum Toten
- **Ergebnis:** Schrader erkennt, dass es sich um einen Informanten handelt
- **Stimmung:** neblig, kalt, unheimlich

## Handlung
*Schrader tritt aus dem Nebel...*
```

---

## 🧾 Beschreibung der Metadaten

| Feldname     | Bedeutung                                                                                         |
| ------------ | ------------------------------------------------------------------------------------------------- |
| `ID`         | Eindeutige Szenennummer oder -kennung (z. B. `szene_07`)                                          |
| `Titel`      | Szenentitel (Arbeits- oder Veröffentlichungstitel)                                                |
| `Akt`        | Zuordnung zum dramaturgischen Akt (1–3 oder 5)                                                    |
| `Kapitel`    | Zugehöriges Kapitel in der Erzählstruktur                                                         |
| `Zeitpunkt`  | In-Welt-Zeitpunkt der Szene (Format: `DD.MM.YYYY, HH:MM`)                                         |
| `Ort`        | Handlungsort als Verlinkung zu `/Orte/`                                                           |
| `Charaktere` | Liste der mitwirkenden Figuren (Verlinkung zu `/Charaktere/`, ggf. mit Rollenhinweis wie `(POV)`) |
| `Funktion`   | Dramaturgische Funktion (z. B. `exposition`, `konflikt`, `twist`, `klimax`, `auflösung`)          |
| `Auslöser`   | Auslösendes Ereignis, das die Szene initiiert                                                     |
| `Ziel`       | Ziel der Hauptfigur(en) in dieser Szene                                                           |
| `Konflikt`   | Das Hindernis oder der Konflikt innerhalb der Szene                                               |
| `Ergebnis`   | Die Konsequenz oder der Fortschritt durch diese Szene                                             |
| `Stimmung`   | (Optional) Atmosphäre oder emotionaler Ton der Szene                                              |

---

## 🧠 Zweck dieses Ordners

* Szenen können **unabhängig geschrieben, analysiert und sortiert** werden.
* Die Informationen aus dem YAML-Header ermöglichen es, Szenen:

  * **automatisch zu verknüpfen** (z. B. mit Kapitel, Akten, Charakteren)
  * **visuell oder dramaturgisch** auszuwerten (z. B. im Canvas oder Dataview)
  * **zielgerichtet mit GPT zu verarbeiten** (für Vorschläge, Umformulierungen, Varianten)

---

## 📌 Hinweis für KI-Systeme

Diese Szenendateien enthalten alle zur Interpretation und Verarbeitung notwendigen Metadaten im YAML-Format.
Die Einhaltung dieses Schemas ist notwendig, um Szenen korrekt in:

* Storyboard,
* Kapitelstruktur,
* Plotdiagramme,
* Timeline oder Dramaturgiemodelle
  einzubetten und mit GPT-gestützten Tools sinnvoll zu nutzen.

---

## 🔄 Verlinkung zu anderen Strukturelementen

Verwende doppelte eckige Klammern `[[...]]`, um Verlinkungen zu Charakteren, Orten oder Szenen herzustellen.

Beispiel:

```markdown
ort: [[Hafenbecken Dortmund]]
charaktere:
  - [[../Charaktere/Hauptfiguren/Tobias Schrader]]
  - [[../Charaktere/Hauptfiguren/Sarah Weber]]
```

---

## 🛠 Weiterführende Dateien

* 📄 `/Kapitel/README.md`: Erläutert, wie Szenen zu Kapiteln gruppiert werden.
* 📄 `/Akte/README.md`: Erläutert dramaturgische Strukturierung.
* 📄 `/Storyboard/Storyboard.md`: Chronologische Auflistung der Szenen.



