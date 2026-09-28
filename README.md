# DSFA und Grundrechte-Folgenabschätzung

**Zwei Folgenabschätzungen, ein Vorgang** — Datenschutz-Folgenabschätzung nach Art. 35 DSGVO und Grundrechte-Folgenabschätzung nach Art. 27 EU AI Act, sauber getrennt und dort verbunden, wo sie sich überschneiden.

*Data protection impact assessment (Art. 35 GDPR) and fundamental rights impact assessment (Art. 27 EU AI Act): where they differ, where they overlap, and how to run them as one process.*

---

## Das Problem

Wer ein KI-System einsetzt, das über Menschen entscheidet, steht schnell vor zwei Pflichten mit ähnlichem Namen und unterschiedlichem Inhalt. In der Praxis passiert dann eines von beidem: Die zweite wird übersehen, oder beide werden zu einem Dokument verrührt, das keine von beiden erfüllt.

Sie sind nicht dasselbe:

| | DSFA (Art. 35 DSGVO) | Grundrechte-FA (Art. 27 EU AI Act) |
|---|---|---|
| **Schutzgut** | personenbezogene Daten | Grundrechte insgesamt |
| **Auslöser** | voraussichtlich hohes Risiko für Rechte und Freiheiten | bestimmte Betreiber von Hochrisiko-Systemen nach Anhang III |
| **Wer** | Verantwortlicher | Betreiber |
| **Kernfrage** | Ist die Verarbeitung notwendig und verhältnismäßig? | Welche Grundrechte können betroffen sein, und was schützt sie? |
| **Behörde** | vorherige Konsultation bei hohem Restrisiko, Art. 36 | Mitteilung an die Marktüberwachungsbehörde |

Ein KI-gestütztes Bewerbungsverfahren kann beide auslösen. Eine Betrugserkennung ohne Personenbezug keine von beiden. Eine biometrische Zutrittskontrolle im Zweifel beide — und zusätzlich die Frage nach einem Verbot.

## Für wen

| Rolle | Was hier nützt |
|---|---|
| **Datenschutzbeauftragte** | Abgrenzung, Notwendigkeitsprüfung, Konsultationsschwelle |
| **Compliance und Recht** | Wann Art. 27 greift und wer Betreiber ist |
| **Fachbereich** | Welche Angaben gebraucht werden und warum |
| **Geschäftsführung** | Wer freigibt und was bei hohem Restrisiko passiert |

## Inhalt

| Dokument | Inhalt |
|---|---|
| [DSFA nach Art. 35](./knowledge-base/dsfa-art-35.md) | Schwellwertprüfung, Notwendigkeit, Restrisiko, Konsultation nach Art. 36 |
| [Grundrechte-FA nach Art. 27](./knowledge-base/grundrechte-art-27.md) | Wen sie trifft, was hineingehört, Verhältnis zur Risikobewertung |
| [Verzahnung](./knowledge-base/verzahnung.md) | Was sich teilen lässt, was getrennt bleiben muss |
| [Vorlage: DSFA](./templates/dsfa.md) | Zum Ausfüllen |
| [Vorlage: Grundrechte-FA](./templates/grundrechte-folgenabschaetzung.md) | Zum Ausfüllen |

## Der Grundsatz dieses Modells

**Ein System, zwei Bewertungen, gemeinsame Faktenbasis.** Beschreibung des Systems, Datenkategorien, betroffene Personen und Zweck werden einmal erhoben und von beiden Bewertungen genutzt. Die *Bewertung* selbst bleibt getrennt, weil die Maßstäbe unterschiedlich sind.

Das spart die Doppelarbeit, ohne die Prüfbarkeit zu verlieren: Eine Aufsichtsbehörde will die DSFA sehen, eine Marktüberwachungsbehörde die Grundrechte-Folgenabschätzung. Ein Mischdokument befriedigt keine von beiden.

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt beide Bewertungen am selben KI-System, verknüpft mit Verarbeitungsverzeichnis und Risikoeinstufung: **[Datenschutz-Folgenabschätzung](https://simpleact.de/datenschutz-folgenabschaetzung)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-09-28 · MIT — frei nutzbar, auch kommerziell.

Keine Rechtsberatung. Die Angaben ersetzen keine Prüfung des Einzelfalls.
