# Analyse eines IT-Sicherheitsvorfalls im Unternehmensnetzwerk

## Projektbeschreibung

Dieses Projekt ist Teil des [Google Cybersecurity Professional Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity). In diesem Projekt bin ich als Cybersecurity Analyst für ein fiktives Unternehmen tätig, das seit Tagen mit den Folgen eines Cyberangriffs zu kämpfen hat. Das Unternehmen wurde Opfer eines DDoS-Angriffs, der das interne Netzwerk für mehrere Stunden beeinträchtigt hat, bis der Angriff abgewehrt werden konnte.

Als Cybersecurity Analyst ist es meine Aufgabe, diesen Sicherheitsvorfall zu analysieren und einen Plan zur Verbesserung der Netzwerksicherheit im Unternehmen zu erstellen. Bei der Analyse des Sicherheitsvorfalles werde ich dem [Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework) des [National Institute of Standards and Technology (NIST)](https://www.nist.gov/) folgen. Das CSF besteht aus Standards, Richtlinien und Best Practices, die Unternehmen dabei helfen, ihr Management von IT-Sicherheitsrisiken zu verbessern. Die fünf Kernfunktionen des CSF sind Identifizieren, Schützen, Erkennen, Reagieren und Wiederherstellen.

![NIST_CSF_Five_Functions](https://github.com/laresd/Incident_report_analysis/assets/53877625/bf35abcf-8e7f-4138-9996-1bf7091cb8aa)

- **Identifizieren**: Sicherheitsrisiken identifizieren, indem interne Netzwerke, Systeme, Devices und Zugriffsrechte regelmäßig auf potenzielle Sicherheitslücken überprüft werden.
- **Schützen**: Interne Assets schützen, indem Richtlinien und Verfahren umgesetzt, Tools eingesetzt und Schulungen durchgeführt werden, um Bedrohungen der IT-Sicherheit zu minimieren.
- **Erkennen**: Potenzielle Sicherheitsvorfälle erkennen und die Überwachungsfunktionen verbessern, um die Geschwindigkeit und Effizienz der Erkennung zu erhöhen.
- **Reagieren**: Sicherheitsvorfälle eindämmen, neutralisieren und analysieren; Sicherheitsprozesse optimieren.
- **Wiederherstellen**: Betroffene Systeme zum Normalbetrieb zurückführen und die Systemdaten und/oder Assets, die von einem Sicherheitsvorfall betroffen sind, wiederherstellen.

## Zusammenfassung

In dem Unternehmen hat sich ein IT-Sicherheitsvorfall ereignet, bei dem plötzlich alle Netzwerkdienste nicht mehr verfügbar waren. Das IT-Sicherheitsteam hat festgestellt, dass die Störung durch einen DDoS-Angriff (Distributed Denial of Service) verursacht wurde, bei dem die Angreifer das Netzwerk mit einer Flut von eingehenden ICMP-Paketen überlastet haben. Das Team hat reagiert, indem es den Angriff blockiert und alle nicht-kritischen Netzwerkdienste gestoppt hat, so dass die kritischen Netzwerkdienste nach und nach wiederhergestellt werden konnten.

## Identifizieren

Ein oder mehrere böswillige Akteure haben das Unternehmen mit einer ICMP-Flooding-Attacke angegriffen. Der Angriff betraf das gesamte interne Netzwerk. Alle kritischen Netzwerkressourcen mussten gesichert und wiederhergestellt werden.

## Schützen

Das IT-Sicherheitsteam hat eine neue Firewall-Regel erstellt, um den Durchsatz eingehender ICMP-Pakete zu begrenzen. Darüber hinaus hat das Team ein Intrusion Detection System (IDS) bzw. Intrusion Prevention System (IPS) implementiert, um einen Teil des ICMP-Verkehrs nach verdächtigen Merkmalen zu filtern.

## Erkennen

Das IT-Sicherheitsteam hat den Quell-IP-Modus der Firewall aktiviert, um eingehende ICMP-Pakete auf gefälschte IP-Adressen zu überprüfen. Zusätzlich hat das Team eine Netzwerküberwachungssoftware implementiert, um verdächtige Muster im Netzwerkverkehr zu erkennen.

## Reagieren

Bei zukünftigen Sicherheitsvorfällen wird das IT-Sicherheitsteam die betroffenen Systeme isolieren, um weitere Störungen des Netzwerks zu verhindern. Das Team wird versuchen, alle kritischen Systeme und Netzwerkdienste, die durch den Vorfall beeinträchtigt wurden, wiederherzustellen. Anschließend werden die Netzwerkprotokolle auf verdächtige und ungewöhnliche Aktivitäten untersucht. Außerdem wird das Team alle Sicherheitsvorfälle der Führungsebene und, falls erforderlich, den zuständigen Behörden melden.

## Wiederherstellen

Nach einem DDoS-Angriff durch ICMP-Flooding muss zunächst der Normalbetrieb der internen Netzwerkdienste wiederhergestellt werden. In Zukunft können externe ICMP-Flooding-Attacken durch die Firewall blockiert werden. Im Falle eines erneuten Cyberangriffs sollten alle nicht-kritischen Netzwerkdienste gestoppt werden, um den internen Netzwerkverkehr zu reduzieren. Anschließend sollten die kritischen Netzwerkdienste wiederhergestellt werden. Sobald die Flut der ICMP-Pakete abgeklungen ist, können alle nicht-kritischen Systeme und Netzwerkdienste wieder in Betrieb genommen werden.

## Ressourcen

- [Google Cybersecurity Professional Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity)
- [Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework)
- [National Institute of Standards and Technology (NIST)](https://www.nist.gov/)
