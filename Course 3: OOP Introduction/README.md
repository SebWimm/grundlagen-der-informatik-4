## Course 3: OOP Introduction
______

**ATTENTION:** When working with HSD lab computers, save ALL your work on the `H:\` drive!!!

Any data stored on `C:\` will only be saved to the local computer and can be deleted or manipulated by any other user. 
______


*Note: (Currently German only)*

### Overview: "Einstieg in die Objektorientierung"
Im Rahmen dieses Versuchs sollen mehrere Klassen erstellt werden und darüber die vier Säulen der Objektorientierung anhand von praktischen Beispielen kennen gelernt werden.

Laden Sie das **Java Projekt** `dicegameTemplate` aus diesem Repository herunter.

![repodl](../images/repoDownload.png)

Ziel des Praktikums ist das Füllen der Main-Klasse mit selbst erstellten Würfelobjekten. 
Bereits vorhanden sind:
1. Die Main Klasse
2. Die Abstrakte Oberklasse `Dice.java`, von der die zu erstellenden Würfelklassen abgeleitet werden sollen
3. Die Klasse `Shaker.java`, welche den Würfelbecher repräsentiert
   
Nun sollen die folgenden vier Würfel von `Dice.java` abgeleitet werden:
1. `RegularDice.java`
   - normaler, sechsseitiger Würfel
2. `MultisidedDice.java`
   - mehrseitiger Würfel zwischen 4 und 20 Seiten
   - Seitenzahl kann nur bei Erstellung des Objekts festgelegt und danach nicht mehr geändert werden 
3. `LoadedDice.java`
   - gezinkter Würfel
   - kann auf alle Seiten fallen, aber mit 50% Wahrscheinlichkeit auf die größte Zahl
4. `ChaosDice.java`
   - wechselt nach jedem Wurf die Seitenanzahl
  
Bevor Sie mit der Implementierung starten: Besprechen Sie mit einem Betreuer eine geeignete Verberbungsstrategie und halten diese schriftlich fest.

Wenn Sie alle Würfel implementiert haben, fügen Sie diese in der Main-Methode dem Shaker mittels der `addDice(Dice dice)` Methode hinzu.

Fügen Sie in der Main Methode Sechs verschiedene Kombinationen aus Dateityp des Objekts und Konstruktorklasse und erklären, warum es möglich bzw. nicht möglich ist, diese so zu instanziieren. 



