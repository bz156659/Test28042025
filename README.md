# Klausur/Test 2024/2025 Nr. 3


## Aufgabe 1

Erstellen Sie aus diesem Template ein eigenes Projekt namens K2_20250324_Nachname_Vorname bzw. T2_20250324_Nachname_Vorname.
Die App ist im Wesentlichen die App aus dem Unterricht ohne große Änderungen.
Am Ende müssen Sie Ihr Projekt commiten und pushen. Senden Sie mir den Link in Teams zu.

## Aufgabe 2

Beantworten Sie die folgenden Frage hier direkt im Text: Welche Aufgabe haben cookies in unserer Banking-App?

<!--Cookies sind kleine Textdateien, die beim Besuch von Webseiten auf dem lokalen Rechner 
  von Nutzern gespeichert werden. Beim erneuten Seitenbesuch können sie direkt an den Server gesendet werden.

1. Cookies können notwendig sein oder z.B. der Werbung dienen.
2. Cookies können z.B. ganz konkret einen Warenkorb nach Tagen wieder anzeigen, obwohl 
   der Nutzer sich bei dem Händler noch nicht registriert hat.
3. Der cookieparser ist für die Verarbeitung der cookies unserer App zuständig.
4. Mit dem cookieparser können wir cookies setzen und auslesen und löschen.
5. Man kann Cookies am Browser anzeigen, indem man F12 drückt.
Weil man Cookies im Browser sehr einfach auslesen kann, kann man Cookies signieren. -->


## Aufgabe 3

Auf der Seite Hilfe sind vier Fehler eingebaut. Finden und korrigieren Sie die Fehler. Schreiben Sie zu jedem Fehler eine Kommentarzeile, in der Sie schreiben, was Sie korrigiert haben.

## Aufgabe 4

Die Seite "AGB" lässt sich nicht öffnen. Korrigieren Sie das.

## Aufgabe 5

Die Seite Postfach lässt sich im Browser aufrufen, auch wenn der Kunde nicht in der App angemeldet ist. Korrigieren Sie das.


## Aufgabe 6

Ergänzen Sie bei dem Kundenobjekt eine konkrete E-Mailadresse. 

Der Kunde soll seine Mailadresse selbst ändern können. Wenn die vom Kunden eingegebene Mail keine gültige Mail-Adresse ist, dann wird ein enstprechende Meldung angezeigt. Wenn die Adresse gültig ist, dann wird die vom Kunden angegebene Adresse auf der Mail-Seite angezeigt.


## Aufgabe 7

Die Seite Geldanlegen berechnet die Zinsen nicht korrekt.

Der Zinssatz beträgt stets 10%. Bauen Sie einen Hinweis auf die Zinsen fest auf der Seite ein.

Ändern Sie die Funktionalität so, dass der Kunde seinen Wunschbetrag tatsächlich eingeben kann, um die Zinsen dann zu berechnen. 

## Aufgabe 8 (nur Klausurschreiber)

In der Kontenübersicht soll der Kunde selbst ein Konto einrichten dürfen. Zu einem Konto gehört eine IBAN und ein Saldo. Bauen Sie die Klasse ein. Bauen Sie das Formular auf die Seite, mit dem die Daten in einem Kontoobjekt instanziiert werden. Nach dem Absenden bekommt der Kunde die Daten seines neues Kontos angezeigt.
Beim Neuanlegen eines Kontos bekommt der Kunde 10 Euro als Anfangssaldo geschenkt.

Der Kunde darf die IBAN selbst wählen, aber für die Benennung gibt es Regeln. Die Überwachung der Einhaltung der Regeln soll der IBAN-Validator übernehmen:

https://www.npmjs.com/package/iban-validator-js


## Aufgabe 9 (Nur Klausurschreiber)

Der gewünschte Betrag auf der Seite Geldanlegen soll auf Kundenwunsch auf das neue Konto eingezahlt werden. Stellen Sie dem Kunden also die Frage, ob er den Betrag direkt auf das Konto einzahlen will. Der Kunde könnte in einer weiteren Textbox nach "ja" oder "nein" gefragt werden, was dann im Falle von "ja" dazu führt, dass bei der Rückkehr zur Kontenübersicht der neue Betrag (also Anfangssaldo + Betrag aus Geldanlegen) angezeigt wird.