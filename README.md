## Lokal-Digital Baukasten
**Projekt Website**: [https://projekt-lokal-digital.de/](https://projekt-lokal-digital.de/)

![lokaldigital_Logo.png](https://lokaldigital.netphen.de/wp-content/uploads/2023/01/ConceptLogo_neutral.png)


[![Open Source](https://img.shields.io/badge/Open%20Source-Yes-green.svg)](https://opensource.org/) [![License](https://img.shields.io/badge/Lizenz-General_Public_License_3.0-blue
)](https://www.gnu.org/licenses/gpl-3.0.html) 

## Table of contents
1. [Projektziele](#projektziele)
2. [Voraussetzungen zur Installation](#voraussetzungen-zur-installation)
8. [Installation und Konfiguration](#installation-und-konfiguration)
9. [Plugins](#plugins)
10. [Screenshots](#screenshots) 
11. [Lizenz](#lizenz)


## Projektziele
„LOKAL-digital – Smartes Wissensmanagement für Wohnen, Pflege und Gesundheit“ war ein Modellprojekt im Bereich der Digitalisierung zur Erzielung von Bürgernähe durch digitale Beratungsangebote und wurde zwischen 2021 und 2023 durchgeführt. In einem öffentlich zugänglichen Wissensmanagementsystem wurden die Angebote gemeinwohlorientierter, zivilgesellschaftlicher Einrichtungen, Pflegeanbieter, Bauwirtschaft und kommunaler Verwaltung zusammengeführt mit dem Ziel die Lebensqualität durch selbstbestimmte Lebensgestaltung im Alter zu verbessern.

## Voraussetzungen zur Installation
- **Betriebsumgebung inkl. Server und Datenbank:** \
Bevor Sie den Baukasten bei sich aufsetzen, ist zu klären in welcher Betriebsumgebung, sprich Serverinfrastruktur und Datenbank dieser aufgesetzt und betrieben werden soll. 

- **Beantragung URL:** \
Es ist notwendig für ihre Kommune / Region eine neue Domain/URL zu beantragen. \
Es ergeben sich dazu verschiedene Optionen. Welche trifft bei ihnen zu? 
    - Erstellung einer Sub-Domain unter der eigenen kommunalen Homepage, z.B. lokaldigital.stadt.de 
    - Definition einer separaten neuen Sub-Domain 


- **Zertifikat:** \
Nachdem ihre URL festgelegt wurde, beantragen Sie bitte ein passendes Sicherheitszertifikat(SSL-Zertifikat) um eine spätere Anmeldung der Rolleninhaber an dem System absichern zu können. Das Zertifikat realisiert das Schlossß-Symbol oben links im Webbrowser und zeigt eine sichere https-Verbindung an. Eine spätere Nutzung der Funktionen zur User-Registrierung und Anmeldung am System ohne Zertifikat ist aus Sicherheitsgründen nicht empfehlenswert. 
Handelt es sich um eine Sub-Domain ihrer bereits existierenden Domain und ihr dort hinterlegtes Zertifikat schließt auch Sub-Domains ein, so kann dieser Schritt ggf. übersprungen werden. \
Neues Zertifikat notwendig? 
    - Erstellung einer Sub-Domain unter der eigenen kommunalen Homepage, z.B. lokaldigital.stadt.de 
    - Definition einer separaten neuen Sub-Domain 

- **SMTP Mail-Server:** \
Für eine Selbst-Registrierung von Nutzerinnen und Nutzern wird später ein Mail-Server notwendig. Über diesen werden Registrierungsbestätigungen versendet und auch ein Passwortrücksetzungsprozess unterstützt. Ohne einen Mail-Server ist kein Versand von Mails möglich. 
Je nachdem wie ihre Betriebsumgebung und Unterstützung durch IT-Experten in 3.1 ausfällt, kann es sein das dieser Mail-Server in ihrer bestehenden Umgebung bereits existiert. Nutzen Sie stattdessen einen Hosting-Anbieter kann die Mail-Serverfunktion neu mitbeauftragt werden. \
Neuer Mail-Server notwendig? 
    - Ja 
    - Nein


- **Impressum, Datenschutz, Cookies, Copyright, Social Media:** \
Aus rechtlicher Sicht bietet es sich an direkt zu Anfang über die Themen Impressum, Datenschutzerklärung, Cookie-Richtlinie, Copyright-Vorgaben und Einbindung von Social Media-Plugins zu sprechen. 
Es kann hier sein das bereits Rahmendokumente durch die eigene kommunale Webseite bestehen. Dennoch hat die Projekterfahrung gezeigt, dass diese in der Regel nicht 1:1 übernommen werden können, vor allem wenn es Abweichungen bei der Betriebsumgebung und Nutzung von Plugins und damit Cookies gibt. 
Eine weitre Frage ist wie sich die rechtlichen Angaben zwischen ihrer kommunalen Verwaltung und ein oder ggf. mehrerer involvierter Partner oder Dienstleister aufteilen und wer jeweils zu benennen ist. \
**Achtung! Im Baukasten sind ein Entwurf eines Impressums, einer Datenschutzerklärung und Cookie-Richtlinie enthalten. Eine Adaption oder Erweiterung auf ihrer lokale Situation ist aber zwingend erforderlich! Das Projektteam LOKAL-digital haftet an dieser Stelle nicht für die Korrektheit der enthaltenen Vorlage oder deren spätere Anpassung durch Sie. Bitte gehen Sie hier ggf. in Klärung mit ihrem rechtlichen Beistand oder den Experten in ihrem Haus.** 


## Installation und Konfiguration
- **Wordpress aufsetzen:**

- **mySQL aufsetzen:** Erläuterung in Word Dokument fehlt noch. Gegebenenfalls einbauen oder streichen.

- **Import LOKAL-digital Wordpress-Projekt:**

- **Konfiguration von Wordpress-Einstellungen**
    - Basiseinstellungen: 
        - Titel der Webseite passend vergeben 
        - Untertitel der Webseite definieren 
        - URL in den Einstellungen hinterlegen. 
        - Andere Einstellungen prüfen z.B. Schreiben, Lesen, Kommentarfunktion
        - Mindestens einen, besser zwei Nutzer als Administrator festlegen. 
        - Festlegen welche Standardrolle ein neuer Nutzer oder Nutzerin erhalten soll 
        - Die gewünschten Plugins installieren, um die Erstellung von Inhalten zu erleichtern
        - …

    - Rollen überprüfen:
    
    - Mail-Server einrichten:
        - Im Word Dokument noch nicht beschrieben

## Plugins

Für WordPress können verschiedenste Plugins für die Aufwertung der Benutzerfreundlichkeit der Website verwendet werden. \
Im Lokal-Digital Projekt wurden folgende Plugins eingesetzt: 

Plugin-Name   | Zweck
------------- | -------------
Blog Designer Pack  | Optimiert die Darstellung von Beiträgen auf den Seiten. 
Dummy Images  | Unterstützt bei der Generierung von Platzhalter-Bildern. Liegen genügend eigene Bilder vor, so ist dieses Plugin nicht notwendig und kann inaktiv geschaltet werden. 
Duplicate Page | Kopie einer Wordpress-Seite um anhand dieser Vorlage eine neue Seite zu erstellen. 
Duplicator  | Erstellung eines Backups der Wordpress-Datenbank. 
Events Manager | Anlage von Terminen und deren Lokation. Das Ergebnis wird über eine Kalenderdarstellung angezeigt. 
Font Awesome | Ergänzt den Text um passende Icons wie z.B. einen Globus, Telefonhörer oder Briefsymbol. 
Formidable Forms  | Erstellung von unterschiedlichen erweiterten Formulare z.B. (Kontakt, Zahlung, Quiz, Umfrage usw.)
Map Block for Google Maps  | Einbettung von Google Maps Karten zur Kennzeichnung von Anbieter-Standorten. 
Password Protected  | Verhindert, dass das Testsystem aktuell öffentlich ohne Zugangsschutz erreichbar ist. 
Search & Filter  | Erweiterte Such- und Filterfunktionen 
Ultimate FAQ  | Unterstützt bei der Umsetzung und Verwaltung der häufig gestellten Fragen auf der Seite. 
Benutzer eingereichte Beiträge  | Unterstützt bei der Annahme und Verarbeitung von Beitragsvorschlägen durch die Anwender*innen
WP Accessibility  | Unterstützt Funktionen zur Barrierefreiheit der Seite.  
WP RSS Aggregator  | Unterstützt den Abruf und die Zusammenführung von verschiedenen öffentlich frei verfügbaren RSS-Nachrichtensammlungen. Auf diese Weise lässt sich die Seite um weitere Inhalte anreichern. 
WPForms Lite  | Erstellung von Formularen


## Screenshots
folgt.

## Lizenz

Dieses Projekt ist lizenziert unter der [General Public License, Version 3.0 (GNU-3.0)](https://www.gnu.org/licenses/gpl-3.0.html).

Der komplette Lizenztext kann in der [LICENSE](LICENSE) Datei des Repository gefunden werden.
