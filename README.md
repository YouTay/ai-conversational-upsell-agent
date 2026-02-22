I Produktberater – Conversational Commerce Agent

Dieses Projekt zeigt die Konzeption und Umsetzung eines LLM-gestützten Conversational-AI-Agents für eine E-Commerce-Website. Der Agent unterstützt Kunden bei der Produktauswahl, liefert kontextbezogene Empfehlungen und führt gezieltes Upselling durch dynamische Produktvorschläge mit direkten Kaufoptionen durch.

Ziel war die Demonstration einer produktionsnahen Conversational-AI-Architektur mit Fokus auf Verkaufsberatung, Knowledge-Integration und skalierbarer Cloud-Perspektive.

Projektziel

Automatisierte Produktberatung im Online-Shop

Kontextbasiertes Cross- und Upselling

Verbesserung der Customer Experience

Reduktion manueller Kundenservice-Anfragen

Demonstration moderner Conversational-AI- und LLM-Integration für Cloud-/AI-Engineering-Use-Cases

Systemarchitektur
Conversational AI Layer

Agent Orchestrierung über Voiceflow

LLM: Claude 4 Sonnet

Temperatur: 0,3 zur kontrollierten Antwortgenerierung

Max Tokens: 5000

Prompt Engineering für verkaufsorientierte, einfache Kommunikation

Frontend Integration

Chat-Widget Integration über Voiceglow

Dynamische Produkt-Carousels mit:

Produktbild

Kurzbeschreibung

Preis (falls verfügbar)

Direktlink zum Shop

Interaktive Buttons zur Gesprächssteuerung

Knowledge Base / Retrieval

Produktdaten aus Shopify-Exporten

Ergänzende Website-Knowledge-Base für erklärende Inhalte

Retrieval-basierte Produktauswahl (RAG-ähnlicher Ansatz)

Strikte Trennung zwischen Produktdaten und erklärenden Textquellen

Conversational Design Prinzipien
Sprachgestaltung

Einfache Sprache (A2–B1 Niveau)

Maximal zwei kurze Sätze pro Antwort

Freundlich, beratend, nicht aufdringlich

Fokus auf klare Handlungsempfehlungen

Verkaufslogik

Der Agent erkennt Produktinteressen und schlägt kontextabhängig ergänzende Produkte vor, beispielsweise:

Flipchart → Marker → Zubehör → Transportlösung

Marker → Aufbewahrung → Nachfülloptionen

Moderationsprodukte → Zubehörsets

Präsentationssysteme → Transport- und Erweiterungszubehör

Regeln:

Pro Interaktion maximal eine konkrete Upsell-Empfehlung

Jede Empfehlung endet mit einer Entscheidungsfrage

Alternativen in verschiedenen Preisklassen möglich

Empfehlung immer mit praktischem Nutzen begründet

Technische Schwerpunkte

LLM-basierte Conversational Commerce Lösung

Retrieval-Augmented Produktberatung

Prompt Engineering für strukturierte Verkaufsdialoge

UI-Integration dynamischer Produktdaten

Response-Kontrolle über Token- und Temperaturparameter

Production-nahe Chatbot-Integration in bestehende Webumgebung

Relevanz für AI- und Cloud-Engineering

Dieses Projekt demonstriert praxisrelevante Kompetenzen in folgenden Bereichen:

Integration großer Sprachmodelle in Business-Workflows

Conversational-AI-Architektur und Agent Design

Knowledge-Base-Integration und strukturierte Datennutzung

UX-Optimierung für AI-gestützte Beratungssysteme

Deployment-nahe Chatbot-Integration im Web-Kontext

Cloud-Perspektive / Erweiterungsmöglichkeiten

Die Architektur ist cloudfähig konzipiert und kann problemlos erweitert werden, beispielsweise durch:

Migration zu Azure OpenAI Services

Integration von Azure AI Search oder Vektordatenbanken

Serverless Middleware über Azure Functions

Monitoring, Telemetrie und Logging

Mehrsprachige Conversational-AI-Systeme

Diese Erweiterungen würden eine produktionsreife Enterprise-AI-Architektur ermöglichen.
