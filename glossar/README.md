# Glossar: Verwaltungs-IT & KI

Begriffe aus dem Schnittfeld von Digitalisierung der öffentlichen Verwaltung und Künstlicher Intelligenz. Pflegestand: Mai 2026.

---

## A

**AI Act** — Verordnung (EU) 2024/1689 zur Festlegung harmonisierter Vorschriften für Künstliche Intelligenz. Risikobasierter Ansatz mit vier Kategorien (verboten, hochrisikobehaftet, begrenzt, minimal). Anwendbar gestaffelt seit 2025. Siehe auch [Positionspapier](../positionspapiere/eu-ai-act-verwaltung.md).

**Anbieter (Provider)** — Im Sinne des AI Act: Wer ein KI-System entwickelt oder entwickeln lässt und unter eigenem Namen oder eigener Marke in Verkehr bringt oder in Betrieb nimmt.

**Aussonderung** — Archivrechtliches Verfahren zur Bewertung und Übergabe nicht mehr aktiv benötigter Unterlagen an das zuständige Archiv. In der digitalen Verwaltung XDOMEA-konform standardisiert.

## B

**Betreiber (Deployer)** — Im Sinne des AI Act: Wer ein KI-System unter eigener Verantwortung einsetzt, ohne es selbst entwickelt zu haben.

**BRAVORS** — Brandenburgisches Vorschriften- und Rechtsprechungssystem. Online-Sammlung des geltenden Landesrechts Brandenburgs.

## C

**Chunk** — In RAG-Systemen die kleinste indexierte Einheit eines Dokuments, typischerweise ein Absatz oder ein semantisch zusammengehöriger Textabschnitt. Wird einzeln in den Vektorindex aufgenommen.

**CMIS (Content Management Interoperability Services)** — OASIS-Standard zur einheitlichen Anbindung an Dokumentenmanagementsysteme. In Version 1.1 mit Browser Binding (REST/JSON) und AtomPub Binding. Wird von Alfresco, Nuxeo und vielen weiteren DMS unterstützt.

## D

**DMS (Dokumentenmanagementsystem)** — Software zur strukturierten Verwaltung elektronischer Dokumente einschließlich Versionierung, Berechtigungen und Aufbewahrungsfristen. In Behörden häufig Basis für die E-Akte.

## E

**E-Akte** — Elektronische Akte. Digitales Pendant zur Papierakte mit verbindlichen Anforderungen an Vollständigkeit, Integrität und Authentizität (vgl. BSI TR-RESISCAN, OZG-Vorgaben).

**Embedding** — Vektorrepräsentation eines Textes, die seine semantische Bedeutung in einem hochdimensionalen Raum kodiert. Grundlage semantischer Suche.

**EL.NORM** — Werkzeug zur elektronischen Bearbeitung von Rechtsnormen in der Gesetzgebung von Bund und Ländern.

## F

**Fachverfahren** — In der Verwaltung etablierter Begriff für eine fachspezifische Anwendungssoftware (z. B. Personalverwaltung, Meldewesen, Sozialleistungen).

**Flächenverzeichnis** — Strukturierte Erfassung aller zu reinigenden oder zu bewirtschaftenden Flächen einer Liegenschaft. Begriff aus dem Gebäudemanagement; im Behördenkontext gegenüber „Raumbuch" zu bevorzugen, da auch nicht raumförmige Flächen (Treppen, Verkehrswege) eingeschlossen sind.

## H

**Hochrisiko-KI-System** — Im AI Act definierte Kategorie nach Anhang III. Umfasst u. a. KI-Systeme in den Bereichen Justiz, Strafverfolgung, Migration und Verwaltung von Sozialleistungen.

## K

**KI-Kompetenz** — Pflicht aus Artikel 4 AI Act: Anbieter und Betreiber müssen für ausreichende KI-Kompetenz ihrer Mitarbeitenden sorgen. Anwendbar seit Februar 2025.

## L

**LLM (Large Language Model)** — Großes Sprachmodell. Statistisches Modell, trainiert auf umfangreichen Textkorpora, geeignet zur Generierung und Verarbeitung natürlicher Sprache.

## M

**MCP (Model Context Protocol)** — Offener Standard zur Anbindung von KI-Assistenten an externe Datenquellen und Funktionen. Ermöglicht kontrollierte, auditierbare Schnittstellen zwischen LLM und Fachverfahren. Siehe auch [Referenzarchitektur](../architectures/mcp-fachverfahren.md).

## O

**OZG (Onlinezugangsgesetz)** — Bundesgesetz mit Verpflichtung zur digitalen Bereitstellung von Verwaltungsleistungen.

## R

**RAG (Retrieval-Augmented Generation)** — Architekturmuster, das ein LLM mit einem Retrieval-System kombiniert. Anfragen werden zunächst gegen einen Vektorindex semantisch durchsucht; die relevantesten Treffer werden dem LLM als Kontext mitgegeben.

## V

**Vector Store / Vektorindex** — Datenbank für Embeddings mit effizienter Ähnlichkeitssuche (z. B. ChromaDB, Qdrant, Weaviate, pgvector).

**VIS** — Vorgangsbearbeitungs- und Informationssystem; in mehreren Ländern eingesetzte E-Akten-Lösung.

## X

**XDOMEA** — XÖV-Standard zum Austausch von Akten, Vorgängen und Dokumenten zwischen behördlichen Systemen, insbesondere bei der Aussonderung an Archive.
