# Inhalte für [BarCamp-RheinMain.de](http://www.barcamp-rheinmain.de)

In diesem Repository finden sich die Inhalte, die unter [BarCamp-RheinMain.de](http://www.barcamp-rheinmain.de) angezeigt werden. Die einzelnen Inhalts-Seite der Website liegen dabei als Dateien im [Markdown-Format](http://daringfireball.net/projects/markdown/) vor, aus 
denen dann das HTML zur Darstellung auf der Website erzeugt wird. In diesem Repository finden sich auch die Bilder zu den Inhalten, z.B. für den [Slider auf der Startseite](/Slider/Index.md).

## Inhalte bearbeiten

### Rechte erhalten

Zum Bearbeiten der Inhalte benötigst Du in jedem Fall einen Account auf GitHub, den du dir [hier](https://github.com/signup/free) anlegen kannst. Anschließend könntest Du direkt loslegen und die Inhalte mittels [Pull Requests](https://help.github.com/articles/using-pull-requests) bearbeiten, das ist aber etwas kompliziert. Deswegen melde dich bei [Markus](https://github.com/tacker/) und er gibt dir dann Schreibrechte in diesem Repository damit Du vorhandene Inhalte ohne Umwege bearbeiten und auch neue Inhalte anlegen kannst.

### Vorhandene Inhalte bearbeiten

Gehe dazu auf die [Startseite des Repositories](https://github.com/BCRM/www-content). Wähle nun die Date aus, die Du bearbeiten willst. Klicke auf die Schaltfläche *Edit*. Nun öffnet sich eine Edtor. Da die meisten Dateien im Markdown-Syntax verfasst sind, kannst Du die Vorschau-Funktion von GitHub verwenden; klicke dazu auf die Schaltfläche *Preview*. Wenn Du mit deinen Änderungen zufrieden bist, klickst Du unten auf die grüne Schaltfläche. Es wäre nett, wenn Du deine Änderungen auch kurz in einem Kommentar beschreibst.

### Neue Inhalte anlegen

Über der Dateiliste gibt es neben der Anzeige des aktuellen Pfades (`www-content`/) ein *+*-Icon, hiermit kannst Du eine neue Datei anlegen, indem Du den Dateinamen inkl. Endung angibst. Du kannst diese Datei auch in einem Unter-Ordner anlegen, indem Du den Namen des Ordner und einem `/` vor den Dateinamen schreibst.

## Inhalte veröffentlichen

Die Inhalte werden automatisch nach dem Speichern auf der Seite veröffentlich. Du musst nichts weiter dazu tun.

## Seiten-Attribute

Bei den meisten Seiten findest Du am Anfange besonders formatierte Angaben, sogenannte Attribute, z.B. `@order=2`. Diese werden von der Website dazu verwendet, die jeweilige Anzeige anzupassen. Z.B. liefern sie information darüber, wie die Seite in der Unter-Navigation angezeigt wird.

Folgende Seitenattribute kannst Du verwenden:

 * `@title=…` Definiert den Text, der als Titel in einem Hyperlink zu dieser Seite verwendet wird.
 * `@order=0…9` Definiert die Reihenfolge in der diese Seite in einer Liste  angezeigt wird, die alle Seiten im gleichen Ordner auflistet.
 * `@subnav=0|1` Deaktiviert die Anzeige einer Liste mit weiteren Seiten aus dem gleichen Ordner.
 * `@subject=…` definiert bei E-Mail-Templates die Betreffzeile der E-Mail.

## Spezielle Inhalte

Es gibt einige spezielle Inhalte, die nicht direkt als Seiten auf der Website angezeigt werden:

 * Im Ordner [`Email`](/Email) finden sich die Vorlagen für die System-Emails, die von der Website verschickt werden.
 * Die Datei [`Sponsoren/Index.md`](/Sponsoren/Index.md) wird dazu verwendet den Footer mit den Sponsoren-Logos zu erzeugen.
 * Die Datei [`Slider/Index.md`](/Slider/Index.md) wird dazu verwendet den Bilder-Slider auf der Startseite zu erzeugen.
