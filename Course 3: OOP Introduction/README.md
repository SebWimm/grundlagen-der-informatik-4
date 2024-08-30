## Course 3: OOP Introduction
______

**ATTENTION:** When working with HSD lab computers, save ALL your work on the `H:\` drive!!!

Any data stored on `C:\` will only be saved to the local computer and can be deleted or manipulated by any other user. 
______


*Note: (Currently German only)*

### Overview: "Einstieg in die Objektorientierung"
Die Klassen Kfz und Lkw werden erstellt, wobei die
Grundprinzipien der Objektorientierung sukzessive einfließen. Dies bedeutet, dass wir mit
einer  Oberklasse `Fahrzeug` anfangen und diese ständig verbessern, bis wir schließlich
eine "schöne" Klasse `Kfz` erhalten.

Hierzu werden im Folgenden zwei Arten von Klassen erstellt. `Fahrzeug`, `Kfz` und `Lkw` sollen zur
Instanziierung von Objekten dienen und lediglich Attribute besitzen und Methoden zur
Verfügung stellen.
Die Demo-Klassen sollen genutzt werden, um einzelne Instanzen der `Kfz` Klassen zu
erzeugen. Diese sollen eine main-Methode enthalten und somit ausführbar sein.

1. Erstellen Sie das neue **Java Projekt** `git4c3`.

2. Erstellen Sie sukzessive (nacheinander) die Klassen `Fahrzeug`, `Kfz` und `Lkw`:
   - Implementieren Sie die Klasse `Fahrzeug` mit den öffentlichen Integer-Attributen
   `sitze` und `tankInhalt` und dem öffentlichen Float-Attribut `verbrauch`.   
   
3. Erstellen Sie die Datei `KfzDemo.java` mit einer main-Methode:
   - Das Objekt `minivan` wird von der Klasse `Fahrzeug` erzeugt.
   - Die Attribute werden mit `sitze = 6`, `tankInhalt = 70`, `verbrauch = 14` initialisiert.
   - Die mögliche Reichweite bei vollem Tank wird ausgerechnet und mit
   `System.out.println` ausgegeben.

   - Zusätzlich zum `minivan` Objekt wird ein Objekt `sportwagen` von der Klasse `Fahrzeug` erzeugt.
   - Die Attribute von `sportwagen` werden mit `sitze = 2`, `tankInhalt = 45`, `verbrauch = 11` initialisiert.
   - Die mögliche Reichweite von `sportwagen` bei vollem Tank wird ausgerechnet und mittels `System.out.println` ausgegeben.

4. Erweitern Sie die Klasse `Fahrzeug` um die Methode `reichweite()`, die die Reichweite als Rückgabewert liefert.
   Außerdem soll die Klasse `Fahrzeug` wird um die Methode `spritVerbrauch(int gefahreneStrecke)` erweitert werden.
   - Die Methode hat als Eingabeparameter eine Entfernung in Kilometern.
   - Sie berechnet den entsprechenden Spritverbrauch für die Entfernung.
   - Der Spritverbrauch wird als float-Ergebnis zurückgegeben.

5. Erstellen Sie die Datei `SpritDemo.java` und kopieren Sie den Inhalt von `KfzDemo.java` hinein, außerdem:
   - Die Ausgabe der Reichweite erfolgt in der main-Methode, wobei die Methode reichweite() genutzt wird.
   - Die Methode spritVerbrauch wird in der main-Methode für die Entfernung 252 Kilometer aufgerufen und die Ergebnisse für die beiden Instanzen ausgegeben.

6.  Erstellen Sie die Klasse `Kfz`. Die Klasse wird mittels Vererbung von `Fahrzeug` abgeleitet. Die neue Klasse `Kfz` wird um die Konstruktor-Methode `Kfz(int sitze, int tankInhalt, float verbrauch)` erweitert. 

7. Erstellen Sie die Datei `KonstruktorDemo.java` und kopieren Sie den Inhalt von `SpritDemo.java` hinein, außerdem:
    - Die Attribute werden über den Konstruktor `Kfz` initialisiert.

8.  Die Klasse Lkw wird von `Kfz` abgeleitet (Vererbung):
    - Sie hat die beiden zusätzlichen Attribute `int ladeFlaeche` und `boolean hatAnhaenger`.
    - Der Konstruktor `Lkw` initialisiert alle Attribute.
    - Die Lkw-Methode `spritVerbrauch` addiert immer fünf Liter zum errechneten Verbrauch hinzu.

9. Implementieren Sie das Programm `LkwDemo.java` mit:
    - Einem Objekt `sportwagen` der Klasse `Kfz` und ein Objekt `sattelschlepper` der Klasse
    `Lkw`.
    - Das sattelschlepper-Objekt hat die gleichen Attribute wie das sportwagen-Objekt (nur
    zur Demo).
    - Weisen Sie der zusätzlichen Referenz-Variable `kfz` der Klasse Kfz (keine Instanziierung)
    nacheinander `sportwagen` und `sattelschlepper` zu und geben Sie jeweils den Verbrauch auf 252 Kilometer aus.

10. Beschreiben sie mündlich was eine Konstruktor Methode generell macht auch wenn Sie keine Werte initialisiert, was sie zurück gibt und was sie mit diesem Rückgabewert machen können.
