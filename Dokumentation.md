## Jump-and-Run

#### Team: Sandro Kohler, Jesse Wetli, Rilind Haradini, Dominik Schweizer, Marwin Kohl und Gino Paganini

---

#### Phase 1

Wir begannen unser Projekt mit einer kurzen Vorstellungsrunde, bevor wir uns der Ideenfindung für unser Projekt widmeten. Nach einigen Diskussionen über die möglichen Optionen, einer Webseite oder eines Spiels, entschied sich die Mehrheit für ein Spiel und spezifizierten es zu einem 2D Jump-and-Run-Spiel mit einfachen Mechaniken wie Springen und Laufen. Als Entwicklungsumgebung wurde Game Maker ausgewählt und die für das Spiel verwendete Programmiersprache ist GML (GameMaker Language), welches sich an mehreren höheren Programmiersprachen wie Pascal, Java und C anlehnt. Wir sind gespannt auf das Ergebnis.

---

#### Phase 2

Nachdem wir die Aufgaben unter uns aufgeteilt und ins Kanban-Board eingetragen hatten, starteten wir jeder selbstständig an unseren jeweiligen Aufgaben. Wir begannen damit, den Anforderungskatalog und die Namenskonvention zu erstellen. Nebenbei erfassten wir auch das README für unser Git Repository. Des Weiteren erstellten wir eine PowerPoint-Präsentation, um unser Projekt unseren Mitlernenden und unserem Coach vorzustellen. Jeder in der Gruppe hat einen Auftrag und unser Team arbeitet bisher sehr erfolgreich zusammen. Die einzelnen Personen sind sich ihrer Verantwortung bewusst und wirken gemeinsam als Team. Die Abstimmung und Kommunikation läuft sehr gut und fördert die Zusammenarbeit. Zudem sind die Ziele und Aufträge klar formuliert, sodass jeder unseres Teams weiss, was zu erreichen und zu tun ist. Dies motiviert uns sehr und führt zu einer erfolgreichen Arbeitsatmosphäre.

-   Jump and Run
    -   laufen
    -   sprinten
    -   hüpfen
    -   schlagen

| Name     | Beschreibung                                              | Animation                                                         
| -------- | --------------------------------------------------------- | ----------------------------------------------------------------- 
| laufen   | Der Charakter läuft nach rechts oder links.               | Die Beine bewegen sich. 8 fps.                                   
| sprinten | Der Charakter läuft schneller nach rechts oder links.     | Die Beine und Ärme bewegen sich schneller als beim laufen. 8 fps. 
| hüpfen   | Der Charakter springt nach oben.                          | Der ganze Körper bewegt sich. 8 fps.                             
| schlagen | Der Charakter schlägt die Gegner die ihm entgegen kommen. | Die Ärme und das Schwert bewegt sich. 8 fps.                    


-   Entwicklungsumgebung: GameMaker
-   GML (GameMaker language angelehnt an Pascal, Java und C)

---

#### Phase 3

##### Montag

Am Montagmorgen begannen wir mit einer kurzen Besprechung. Wir gingen unsere Aufgabenliste durch und machten uns sofort an die Arbeit. Sandro arbeitete an dem Grundbau des Spieles, das Jump and Run, und programmierte das Laufen, Springen und weitere Funktionen. Dominik designte verschiedene Sprites, unter anderem drei Herzen, die das Leben des Spielers symbolisierten. Rilind widmete sich dem Hintergrund des Spieles. Er schaute sich mehrere Tutorials zum Thema an und versuchte anschliessend, einen eigenen Hintergrund zu erstellen, was ihm auch erfolgreich gelang. Es war ein sehr produktiver Morgen. 

Am Nachmittag arbeiteten alle konzentriert weiter. Rilind designte verschiedene Waffen und entschied sich letztendlich für die beste. Sandro programmierte die Schüsse der Waffe ebenso wie den Rückstoss beim Abfeuern. Ausserdem können jetzt Gegner eliminiert werden. Er implementierte auch, dass die Kamera beim Laufen mitgeht. Rilind und Dominik begannen anschliessend, die verschiedenen Levels zu designen. Sie schauten sich dazu zunächst Tutorials an und recherchiertne, wie dies funktioniert. Morgen werden sie damit fortsetzten. Wir sind sehr zufrieden mit unserer Leistung für den ersten Tag und sind auch sehr motiviert für diese Woche.

![Bild](/images/Tag1.png)

##### Dienstag

Am Dienstag arbeiteten wir alle in Einzelarbeit. Rilind begann damit, die verschiedenen Levels zu designen. Erst musste er die Tiles im Internet suchen und importieren, was sich als schwierig nachwies, da es schwierig ist, diese kostenlos zu finden, jedoch fand er trotzdem kostenlose TileSets auf einer Webseite. Danach konnte er die Rooms (Levels) erstellen, wobei er zuerst ein leichteres und danach ein schwierigeres Level erstellte. Die Rooms wurden sehr gut designt. Sandro kümmerte sich um das Menü Screen mit der Save&Load-Funktion. Er erstellte ausserdem eine Transition zwischen den Leveln und dem Menü.

Dominik hat sich mit der Entwicklung von Spiellevels und Tilesets beschäftigt. Er hat angefangen, ein Level-Design zu entwerfen, indem er einen Grundriss erstellt hat. Auch hat er damit begonnen, an einem Leitermovement zu arbeiten. Es ist eindrücklich, was man mit ein wenig Kreativität und technischem Wissen alles machen kann, um ein cooles Spielerlebnis zu schaffen. Zu guter Letzt errichtete Sandro noch einen Parallax Hintergrund für die Rooms. Kurz vor Feierabend dokumentierte Rilind den gestrigen und heutigen Tag. Dominik wird morgen weiter am Leitermovement arbeiten, da es nicht ganz fertiggestellt hat. Wir sind davon überzeugt, dass unsere Arbeiten einen positiven Einfluss auf das Spiel haben werden.

![Bild](/images/Tag2.png)

##### Mittwoch

Heute war der dritte Tag des Sportferien-Projekts, wir arbeiteten alle weiter an den Aufträgen, an diesen wir gestern stehen geblieben sind. Rilind versuchte zuerst ein paar Kleinigkeiten zu fixen, danach tauschten sich Sandro und er aus. Wir finden das Ergebnis bis jetzt sehr gut, jedoch gibt es noch Kleinigkeiten, die man noch verbessern kann. Wir fügten alle Maps zusammen und Rilind setzte fort mit einem neuem Room (Level). Sandro fügte neue Funktionen hinzu, zum Beispiel wenn man läuft, hört man die Schritte, wenn man mit der Waffe schiesst hört man die Schüsse des Gewehres und wenn die Gegner eliminiert werden, hört man Deathsounds.

Eine andere Funktion, die Sandro hinzufügte, war ein Sprung-Puffer, dies dient dazu, dass wenn der Spieler schon von der Plattform herunterfällt, kann er noch springen. Ebenfalls laufen die Enemies jetzt nicht mehr von der Plattform herunter, sondern haben einen bestimmten Ort, an diesem sie sich bewegen. Dominik versuchte das Leitermovement zu verbessern, jedoch kam er nicht weiter, somit holte er sich Hilfe bei Fabian. Nachdem er es mit Fabian verbessert hatte, war er nicht ganz zufrieden, jedoch könnte man es so lassen. Rilind war schon recht weit mit dem neuen Level, an welchem er heute arbeitete. Insgesamt sind wir sehr zufrieden mit unserer Gruppe. Jeder arbeitet konzentriert und effizient an seinen Aufträgen und das Arbeitsklima ist sehr freundlich.

![Bild](/images/Tag3.png)

##### Donnerstag

Am Donnerstagmorgen besprachen wir als Erste unsere Aufgaben und teilten sie unter uns auf. Dominik stellte sein Level fertig, danach aktualisierte er das KanBan Board. Rilind begann mit der ergänzung der Dokumentation, indem er Bilder und Texte hinzufügte. Anschliessend beschäftigte er sich mit dem Design des nächsten Levels, da diese immer schwieriger werden und mehr Zeit brauchen. Sandro programmierte, dass die Gegner den Spieler eliminieren und schiessen können, ausserdem konnte man das Spiel jetzt auch im Vollbildmodus spielen. Zu guter Letzt wurde hinzugefügt, dass die Kill-Anzahl gezählt werden (pro Kill 1 Punkt). Soweit ist unser Teil gemacht. Morgen werden wir noch die letzten Fehler fixen und das Projekt bereit machen, um es unseren Teamkollegen zu übergeben, dass sie die nächste Woche weiter daran arbeiten können. Wir sind sehr zufrieden mit unserer Arbeit und denken, dass dieses Projekt uns gut gelingen wird.

![Bild](/images/Level8.png)

---

# Zweite Woche

#### Montag

Heute haben wir das Projekt der Gruppe der ersten Woche übernommen was sehr gut funktioniert hat da wir GitHub benutzt haben und darum das ganze komprimierte GameMaker Projekt herunterladen konnten und mit GameMaker Studio 2 öffnen konnten. Wir haben zuerst geschaut was die erste Gruppe gemacht hat. Danach haben wir geschaut was wir noch hinzufügen könnten. Wir haben uns auf einen dash, ein Level screen, ein health system und einen secret boss geeinigt. Danach haben wir mal das Game gespielt und geschaut welche Bugs vorhanden sind und welche wir noch beheben möchten und was wir dagegen machen möchten. Danach hat Jesse an dem Dash gearbeitet und Gino hat sich entschieden mehr über GameMaker herauszufinden und Bugs zu beheben. Dabei war er erfolgreich und er konnte mehr über GameMaker herausfinden. Jesse hat danach an diesem Tag noch den Dash ferig gebracht und so ging der Tag dann auch schon zu Ende.

![Bild](/images/dash.png)

#### Dienstag

An diesm Tag haben Gino und Jesse (war krank zu Hause aber hat trotzdem gearbeitet) an der Bullet logic und an den Herzen gearbeitet. Dabei war das Ziel, dass man in dem Game nicht nach jedem Schuss stirbt und auch, dass man Magazine aufsammeln kann. Das Magazin System habe ich mir überlegt, weil ich dachte, dass die Waffe zu OP (Overpowered) ist, damit man unendlich Bullets hat. Dann haben sich Gino und Jesse an die Arbeit gemacht und sie sind dabei mehreren Problemen begegnet GameMaker hat ab und zu ein paar Probleme gehabt aber sonst war alles okay wir mussten einfach wieder auf eine ältere Version zurückspringen und so ab dieser weiterarbeiten. Sonst war der Tag nichts spezielles und der Tag wurde erfolgreich abgeschlossen.

![Bild](/images/heartsAndMagazines.png)

#### Mittwoch

Heute haben Gino und Jesse an mehreren Bugs gearbeitet und Jesse war endlich wieder gesund und darum konnten beide wieder an dem Projekt weiterarbeiten. Heute ging es nur um das 8. Level, denn dieses war voller Bugs und an diesem Tag haben sie auch bemerkt, wieso das Game voller Bugs war, denn sie haben auf der falschen Verison gearbeitet aber dies wurde dann schnell behoben, denn wir haben einfach die Änderung von der anderen Version übernommen und so die ältere Version mit der neueren ausgeglichen. Das Problem war eigentlich, dass wenn wir 34 Objekte hatten, dann gingen unsere Physiks kaputt und so liess sich das beheben. Danach war der Tag auch schon zu Ende.

![Bild](/images/level8.png)

#### Donnerstag

Heute haben Gino und Jesse an der Online Version des Spiels gearbeitet, welche nicht ganz funktioniert hat, denn es ist doch etwas schwerer als gedacht ein Singleplayer Game in ein Multiplayer Game zu verwandeln. Dabei hat Gino noch die weiteren Bugs behoben und Jesse hat danach den Multiplayer versucht zu implementieren aber dies hat nicht sehr gut funktioniert. Danach gab es noch weitere Bug fixxes und Gino und Jesse haben angefangen an dem Secret Boss zu arbeiten. Danach hat Jesse noch versucht eine Granate in das Spiel einzubauen und dann war der Tag zu Ende.

![Bild](/images/image (6).png)

#### Freitag

Heute haben Jesse und Gino an mehreren Dingen gearbeitet wie z.B. der Feinschliff des Games gearbeitet. Danach hat Gino noch am secret Boss gearbeitet und danach hat er verschiedene Bugs, welche in Verbindung mit dem Boss stehene behoben. Dann hat Jesse noch an der Granate gearbeitet aber diese stellete sich auch wieder schwerer hinaus als gedacht, denn es gab irgendwelche Kollisionen mit den Gegnern, welche nicht vorhergesehen waren und so neigte sich der Tag am Ende zu und die Granate funktionierte nicht.

![Bild](/images/boss.png)

