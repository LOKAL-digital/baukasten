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
Je nach kommunalen oder regionalen Strukturen werden unterschiedliche Betriebsumgebungen für IT-Systeme in Verwaltungen eingesetzt. Teilweise werden diese auch durch zentrale IT-Dienstleister betreut, was insgesamt eine heterogene Ausgangslage darstellt. Bevor Sie den Baukasten bei sich aufsetzen, ist daher zu klären in welcher Betriebsumgebung, sprich Serverinfrastruktur und Datenbank dieser aufgesetzt und betrieben werden soll. Dies hat sich im Projekt als wichtig herausgestellt, da an dieser Entscheidung verschiedene Konsequenzen hängen, z.B. Betreuung und Aktualisierung der Umgebung, Behandlung von technischen Problemen, etc.

Es ergeben sich dazu verschiedene Optionen. Welche trifft bei Ihnen zu?
    - Eigener Betrieb in der kommunalen Verwaltung
    - Betrieb durch einen bereits vorhandenen IT-Dienstleister
    - Betrieb über eine zusätzlich beauftragte Serverinstanz durch einen Web-Hosting-Anbieter auf dem Markt.
    - Betrieb durch einen mit involvierten Projektpartner, z.B. Verein, technischen Partner etc.
    - ...

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
Sollten sie WordPress manuell in ihrer existierenden Betriebsumgebung und nicht über einen IT-Dienstleister oder Hoster aufsetzen gehen Sie bitte wie folgt vor:
Sie finden WordPress als Download unter: https://de.wordpress.org/download/
Dort wird auf eine Anleitung zur Installation verwiesen (https://wordpress.org/support/article/howto-install-wordpress/). Bitte folgen Sie dieser und berücksichtigen Sie auch die Anforderungen an die weiteren technischen Komponenten:

„Server mit der PHP-Version 7.4 oder höher und der MySQL-Version 5.7 ODER MariaDB-Version 10.3 oder höher. Das Core-Team von WordPress empfiehlt ferner Apache oder Nginx als die stabilsten Optionen für eine WordPress-Umgebung, aber auch andere Webserver sind möglich.“

Mit dieser wurde der LOKAL-digital Baukasten am Ende der Projektlaufzeit getestet und die enthaltenen Plugins sind zu diesem kompatibel.

- **Import LOKAL-digital Wordpress-Projekt:**
Nachdem Sie die XML Datei aus GitHub (https://github.com/LOKAL-digital/baukasten) heruntergeladen haben, importieren Sie diese in WordPress über „Werkzeuge“ → „Daten importieren“. Wählen Sie alle benötigten Bestandteile wie Beiträge, Seiten, Kategorien, Schlagwörter etc. aus, damit diese aus dem Baukasten in Ihre eigene LOKAL-digital Instanz übernommen werden.

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
        - Die Rollen von Benutzern können in WordPress über ein eigenes Menü in der Navigationsleiste angepasst werden. Für jeden Benutzer     kann eine eigene gewünschte Rolle festgelegt werden oder auch Änderungen an der Rollenzuweisung vorgenommen werden.
    - Mail-Server einrichten
    - Inhalte bearbeiten
              - Die Beschreibung befindet sich im Leitfaden (PDF Dokument, nicht barrierefrei).

## Plugins

Für WordPress können verschiedenste Plugins für die Aufwertung der Benutzerfreundlichkeit der Website verwendet werden. \
Im Lokal-Digital Projekt wurden folgende Plugins eingesetzt: 

Plugin-Name   | Zweck
------------- | -------------
Dummy Images  | Unterstützt bei der Generierung von Platzhalter-Bildern. Liegen genügend eigene Bilder vor, so ist dieses Plugin nicht notwendig und kann inaktiv geschaltet werden. 
Events Manager | Ermöglicht die Anlage von Terminen und deren Lokation. Das Ergebnis wird über eine Kalenderdarstellung angezeigt. 
Blocksy Companion | Theme-spezifische Funktionalität zur Layoutgestaltung
Map Block for Google Maps  | Einbettung von Google Maps Karten zur Kennzeichnung von Anbieter-Standorten. 
Password Protected  | Verhindert, dass das Testsystem öffentlich ohne Zugangsschutz erreichbar ist. 
Search & Filter  | Erweiterte Such- und Filterfunktionen 
Ultimate FAQ  | Unterstützt bei der Umsetzung und Verwaltung der häufig gestellten Fragen auf der Seite. 
User Submitted Posts  | Unterstützt bei der Annahme und Verarbeitung von Beitragsvorschlägen durch die Anwenderinnen und Anwender.
WP Accessibility  | Unterstützt Funktionen zur Barrierefreiheit der Seite.  
WP RSS Aggregator  | Unterstützt den Abruf und die Zusammenführung von verschiedenen öffentlich frei verfügbaren RSS-Nachrichtensammlungen. Auf diese Weise lässt sich die Seite um weitere Inhalte anreichern. 
Complianz GDPR/CCPA Cookie Consent  | DSGVO, AVG mit bedingter Cookie-Warning und benutzerdefinierten Cookie-Richtlinien


## Leitfaden zum Download

Sie können das Leitfaden Dokument hier herunterladen. Wir hoffen mit diesem Leitfaden Sie bei der Umsetzung ihrer eigenen LOKAL-digital Adaption unterstützen zu können. 

Zitationsvorschlag (PDF): 
LOKAL-digital (2023). Leitfaden für Aufbau und Methodik des Smarten Wissensmanagements für Pflege, Wohnen und Gesundheit 

Gerne können Sie bei Fragen Kontakt aufnehmen:

Institut für Wissensbasierte Systeme und Wissensmanagement, Universität Siegen 
- Dr.-Ing. Johannes Zenkert (johannes.zenkert@uni-siegen.de) 

## Lizenz

Dieses Projekt ist lizenziert unter der [General Public License, Version 3.0 (GNU-3.0)](https://www.gnu.org/licenses/gpl-3.0.html).

Der komplette Lizenztext kann in der [LICENSE](LICENSE) Datei des Repository gefunden werden.
