# Einkaufsliste BSI – Android App

In diesem Projekt habe ich zusammen mit ChatGPT eine einfache Einkaufsliste-App gebaut. Ziel war es, eine Android-App zu erstellen, bei der man Artikel wie „Milch“ oder „Brot“ eintragen kann. Die eingetragenen Artikel werden dann in einer Liste angezeigt und wenn man einen Artikel antippt, wird er wieder gelöscht.

Ich habe dafür Android Studio verwendet und alles in Kotlin programmiert. Die App besteht aus einer Hauptseite (MainActivity), auf der die Liste und das Eingabefeld zu sehen sind. Für die Anzeige der Artikel habe ich eine RecyclerView verwendet und dafür auch einen eigenen Adapter geschrieben. Die Daten werden direkt in einer Liste gespeichert (also keine Datenbank oder so).

Zusätzlich habe ich zwei Fragmente eingebaut, einfach um ein bisschen zu zeigen, wie Navigation funktioniert. Man kann von einem Fragment ins andere springen und wieder zurück.

Das Design der App habe ich extra ein bisschen angelehnt an Apple-Style gemacht – also rosa Hintergrund, weiße Eingabefelder mit abgerundeten Ecken, große Schrift, zentrierter schwarzer Button usw. Sieht dadurch cleaner und moderner aus. Der Titel oben („ShoppingList – von Simon & Harnoor“) ist fest im Header drin und bleibt immer sichtbar.

Wir haben außerdem dafür gesorgt, dass alles barrierefrei ist, also z. B. genug Kontrast und große Schaltflächen. Am Ende habe ich noch eine APK-Datei erstellt, die man direkt auf einem Android-Gerät installieren kann.

Die App wurde komplett in Android Studio gebaut. Wir haben alles in Kotlin geschrieben, das Layout in XML gemacht und ViewBinding verwendet, damit man im Code einfacher auf die UI-Elemente zugreifen kann.



