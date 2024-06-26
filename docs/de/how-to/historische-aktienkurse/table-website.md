---
title: Tabelle auf einer Website
---

Börsen wie die NASDAQ veröffentlichen historische Kurse und Echtzeitkurse für die auf ihren Plattformen gehandelten Aktien.  Finanzwebseiten wie ariva.de bieten ein breiteres Spektrum. Diese historischen Kurse sind in der Regel in einer Tabelle mit Überschriften wie Datum, Eröffnung, Schlusskurs, ... enthalten.

Es sollte möglich sein, diese Informationen von der Website abzurufen. Portfolio Performance bietet zwei Methoden an: automatischer und manueller Abruf.

## Automatisches Abruf

ARIVA.DE ist eine deutsche Website, die Finanzinformationen und Nachrichten sowie Aktienkurse, Marktindizes, Rohstoffe, Währungen, Fonds, Zertifikate, Anleihen und mehr bietet.

Abbildung: Historische Kurse auf ARIVA.DE.{class=align-center style="width:80%"}

![](images/website-ariva.png)


Die Webadresse lautet:
`https://www.ariva.de/aktien/nvidia-aktie/kurse/historische-kurse`.

Wenn Sie diese URL in das Feld Kurs-URL in Abbildung 2 eingeben, werden die Kurse des aktuellen Monats heruntergeladen. 
Die Verwendung dieser Methode zum Anhängen der historischen Kurse ist nur wirksam, wenn Sie die Kurse regelmäßig aktualisieren, indem Sie das Portfolio öffnen.
Bitte beachte, dass du andere Monate auswählen kannst, das bitet sich unter anderem an wenn man Kurs Lücken stopfen möchte.

Abbildung: Historische Kurse von Ariva.de.{class=align-center style="width:80%"}

![](images/tabelle-ariva.png)

Aus unerklärlichen Gründen werden weder die Volumenangaben noch die Höchst- und Tiefstkurse von der Bourserama-URL abgerufen: `https://www.boursorama.com/cours/historique/NVDA`.
Bitte beachten Sie, dass dieser Link monatliche Kurse liefert, auch wenn tägliche Kurse auf dem Bildschirm angezeigt werden.

## Manueler Abruf

Die oben beschriebene Methode funktioniert nicht immer. Einige Websites verwenden JavaScript oder andere Technologien, um die Tabellen zu erstellen.
Auf der Website Finanzen.net beispielsweise wird unter der Standard-URL `https://www.finanzen.net/historische-kurse/nvidia` nur der Kurs des aktuellen Tages angezeigt, so dass für die Anzeige anderer Zeiträume die Eingabe des Anfangs- und Enddatums erforderlich ist. In solchen Fällen könnte ein manueller Abruf benutzt werden, um diese Daten zu erfassen.


Abbildung: Manueller Abruf.{class=align-center style="width:80%"}

![](images/kurs-import-von-html.png)

- Stelle sicher das die Webseite die Daten anzeigt die du herunterladen möchtest.
- Klicke mit der rechten Maustaste auf die Tabelle und wähle " Seitenquelltext" aus dem Kontextmenü.
- Markiere den gesamten Text mit der Tastenkombination Strg + A.
- Kopiere den Text mit dem Tastaturkürzel Strg + C.
- Navigiere zum Dialogfeld in Abbildung 3; siehe [Ansicht Alle Wertpapiere](../../reference/view/securities/all-securities.md#bottom-panel).
- Füge den Text (Strg + V) in den markierten Bereich ein.
- Klicke auf Weiter und dann auf Fertig stellen.