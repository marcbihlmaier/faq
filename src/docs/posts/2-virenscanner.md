---
draft: true 
date: 2024-07-25
categories:
  - frequently asked questions
  - it security
  - it tipps
---

# Alle Jahre wieder - die Frage nach dem Virenscanner

Da war sie wieder: Die Frage nach dem Virenscanner. Ehrlich gesagt: einigermaßen überraschend.

Vor 30 Jahren waren Gespräche über Firewalls und Virenscanner in meinem privaten Umfeld gang und gäbe. _Avira_ oder _Norton Antivir_ , später _Kaspersky_
schon auf unseren ersten Raubkopie-Disketten verbreiteten sich Computer-Viren. Spätestens mit Windows 95 und dem Einzug des Internets (damals natürlich via 256k-Modem), war dann Schluss mit lustig: Nach jeder Windows-Neu-Installation (und die brauchte man für ein funktionierendes Setup mindestens jährlich), war einer der ersten Schritte, einen Virenscanner zu installieren. Weiter ging es mit der Empfehlung eines befreundeten Nerds: Eine fröhlich blinkende Firewall. Was damals absolut seine Berechtigung hatte, denn a) waren die Ports der Windows-Rechner damals so offen wie ein Scheuentor und b) wählten sich die Rechner über das Modem direkt ins Internet ein und waren dort über ihre öffentliche IP-Adresse erreichbar. 

Und heute? "Aufgrund des russischen Überfalls auf die Ukraine" wurden Stimmen laut, den Virenscanner zu prüfen und ggf. zu wechseln - Kasperskys Labs "operatives Geschäft [ist] überwiegend in Moskau" [1]

Also zurück zu _Avira_ oder wie sie alle heißen?

Überhaupt: Wie (sehr) sollte man seinen Computer (oder sein Handy, das nichts anders ist als ein Taschencomputer) in Zeiten von "hybridem Krieg" absichern? Wie viel Vorsicht, Umsicht, Schutz oder Paranoia ist angebracht?

Als Linux-Admin lehne ich mich hier mal mit ein paar Behauptungen (und Binsenweisheiten) aus dem Fenster. Natürlich nicht, ohne mich bei den Windows-Kollegen rückzuversichern.

1. Ein System ist immer so sicher/unsicher, wie der Mensch es beherrscht, der es bedient.
1. Gesunder Menschenverstand ist das A und O .
1. Produkte/Software für Sicherheit sind immer nur Hilfsmittel. Sie können o.g. Kriterien nicht ersetzen, auch wenn das über viele Jahre so kommuniziert und verkauft wurde.
1. Der Windows-Defender, der als Anti-Virenprogramm in Windows integriert ist, ist als solches Hilfsmittel absolut geeignet. Werden andere Virenprogramme installiert, müssen diese den Defender deaktivieren - da sich Viren-Schutz-Programme teilweise gegenseitig als Viren "sehen" und Alarm schlagen.
1. Jedes einigermaßen aktuelle Betriebssystem öffnet nur die Ports, die unbedingt nötig sind.
1. In der Regel hängen Privat-PCs hinter einem Router, der eine Firewall mit sich bringt. Eine zusätzliche Firewall auf dem PC bietet kaum zusätzlichen Schutz. Wenn eine aktiv ist und es keine Probleme gibt, ist das aber ok. Mehrere Firewalls sind - anders als bei Virenscannern - kein Problem.
1. Statt Geld in einen Virenscanner stecken: Lieber etwas Zeit investieren und sich mit seinem System beschäftigen. Da gibt es nämlich ein paar

**Wirklich sinnvolle Maßnahmen**

- Updates einspielen. Immer.
- Kein veraltetes Betriebssystem nutzen (unfassbar, dass ausgerechnet Banken und Krankenhäuser immer die ältesten Betriebssysteme nutzen - und ja: sie werden angegriffen)
- Keine Software aus unbekannten Quellen installieren. Gilt für alle Betriebssysteme. Also nicht irgendwo rum surfen und was runter laden und installieren - und auch nicht die erstbesten Suchergebnisse zum Download von Software verwenden. Nahezu alle Betriebssysteme haben mittlerweile ihre Quellen, über die man Software beziehen kann.
- 3-Sekunden-Regel für E-Mails beachten - [Link zum BSI](https://www.bsi.bund.de/DE/Themen/Verbraucherinnen-und-Verbraucher/Informationen-und-Empfehlungen/Onlinekommunikation/E-Mail-Sicherheit/e-mail-sicherheit_node.html)
- Pornoseiten meiden
- Nutze zum Surfen einen der bekannten Browser wie Chrome, Chromium, Firefox und installiere eine Werbeblocker wie [uBlock Origin](https://ublockorigin.com/de)

**Und zur allgemeinen Be(un)ruhigung**

- Es gibt keine zu 100% sicheren Systeme
- Wenn du ein solches willst, ziehe den Netzwerkstecker, deaktiviere WLAN und sämtliche Funkverbindungen. Ansonsten gilt:
- Wenn jemand dein System hacken will, dann schafft er es auch. 
- Wenn du kein Politiker, Aktivist oder Journalist bist, bist du vermutlich nicht das erste Ziel für einen gezielten Angriff.
- Du wirst, als Nutzer von Internet, Messenger und Co **immer wieder** mit Schadcode in Berührung kommen, sei es durch Mailanhänge, Phishing etc. Hier helfen die o.g. Maßnahmen.


Weiterführende Links:

* [Sicherheits-Einmaleins - auf wiki.ubuntuusers.de](https://wiki.ubuntuusers.de/Sicherheits-Einmaleins/)
* [Passwörter - auf wiki.ubuntuusers.de](https://wiki.ubuntuusers.de/Sicherheits-Einmaleins/)

Quellen:

* [1] [https://de.wikipedia.org/wiki/Kaspersky_Lab](https://de.wikipedia.org/wiki/Kaspersky_Lab)
* [2] [https://de.wikipedia.org/wiki/Michelangelo_(Computervirus)](https://de.wikipedia.org/wiki/Michelangelo_(Computervirus))
* [3] [https://de.wikipedia.org/wiki/Computervirus#Die_%C3%84ra_der_DOS-Viren:_1990%E2%80%931995)](https://de.wikipedia.org/wiki/Computervirus#Die_%C3%84ra_der_DOS-Viren:_1990%E2%80%931995)