Aufgrund der ständigen Forderung der Leute, KMod FWA für Nougat und höher zu anzupassen, habe ich mich dazu entschieden diesen Artikel zu schreiben.

Der Grund, weshalb dieses Modul nicht funktioniert, ist das Nougat die Berechtigung MODE_WORLD_READABLE geändert hat, welche von Xposed genutzt wird um Einstellungen von Xposed zu lesen, und nicht mehr genutzt werden kann. Deshalb muss ich MODE_PRIVATE nutzen, was mit Xposed nicht funktioniert.
Also da ich die Art wie Xposed alle Werte der zugewiesenen Variablen liest in KMod FWA ändern muss, muss ich den Code dazu schreiben und anpassen, was eine Menge Arbeit ist.

Ferner ist Xposed für Nougat derzeit keine finale Version von robo89 und hat so einige Fehler. Ich werde keinen Code, für etwas das ich bereits getestet und mit den Einsatzmitteln nicht funktioniert, erstellen.
Das heißt bis robo89 kein stabiles Xposed für Nougat veröffentlicht, werde ich nicht beginnen an der Nougat Unterstützung zu arbeiten. Überdies arbeite ich gerade an einem anderen Projekt, das möglicherweise KMod FWA ersetzt und für das Funktionieren unter Nougat vorbereitet wird.

Also seid bitte geduldig. Wenn ihr alle auf das selbe besteht, sorgt ihr bloß dafür das ich nicht länger daran arbeiten möchte.

Grüße und Dank an alle die meine Arbeit unterstützen.

Krowne.
