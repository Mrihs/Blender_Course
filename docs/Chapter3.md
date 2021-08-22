.sidenote, .marginnote { 
  float: right;
  clear: right;
  margin-right: -60%;
  width: 57%;         # best between 50% and 60%
  margin-top: 0;
  margin-bottom: 0;
  font-size: 1.1rem;
  line-height: 1.3;
  vertical-align: baseline;
  position: relative;
  }

# 3.	Die 3D View Oberfläche

<div class="marginnote"> Sidenote with CSS? </div>


Die 3D View Oberfläche stellt eine der wichtigsten Arbeitsoberflächen in Blender dar, da in ihr die 3D Objekte, so wie die Szenen, in denen sie integriert werden, angezeigt werden. Auch die Bearbeitung der einzelnen Objekte geschieht in diesem Fenster und lässt sich in diesem Fenster verfolgen.

## Toolbar
Die Toolbar befindet sich auf der linken Seite der 3D View. Allerdings sind Toolbars auch in anderen Pannels anzutreffen. Die Toolbars lassen sich jeweils mit der Taste T ein- und ausblenden. Je nach aktuellem Bearbeitungsmodus befinden sich andere Befehle in der Toolbar.
In diesem Kurs werden wir vor allem mit Tastenkombinationen arbeiten, wenn Operationen durchgeführt werden. Die grundlegendsten Operationen, welche in der Toolbar durchgeführt werden können, werden trotzdem kurz erwähnen. 

## Sideview
Die Sideview befindet sich auf der rechten Seite des Viewport Displays, muss allerdings noch mit der Taste N geöffnet werden. Mit dieser Taste lässt sich die Sideview ebenfalls wieder verbergen. Sideview-Panels sind auch in anderen Arbeitspannnnels anzutreffen und werden dort ebenfalls mit der Taste N ein- und ausgeblendet. 
Die Side-View ist zudem anhand von Registerkarten in zusätzliche Kategorien eingeordnet. Unter dem Register «Item» können etwa Einstellungen zum aktuell ausgewählten Objekt betrachtet und verändert werden, im Register «Tool» können Einstellungen zum aktuell ausgewählten Werkzeug verfeinert werden und unter dem Register «View» können Einstellungen zur Ansicht betrachtet und verfeinert werden. 

## Header
Im Header sind zusätzliche Einstellungen aufzufinden. Diese können nicht nur zwischen dan einzelnen Editoren variieren, sondern auch zwischen den einzelnen Bearbeitungsmodi innerhalb der 3D-View.

### Auswahl-Einstellungen
In der oberen linken Ecke, direkt neben dem Bedienfeld für die Auswahl des Editors, befinden sich Einstellungsmöglichkeiten, wie eine Auswahl genauer erfolgen soll.  

### Tools zur Bearbeitung von Objekten
In der Mitte des Headers befinden sich genauere Einstellungen zur Auswahl von Objekten. Diese werden in einem späteren Kapitel ausführlich betrachtet. 

### Bearbeitungsmodus
In der Zeile unterhalb des Headers befindet sich ganz links das Menu zur Auswahl des Bearbeitungsmodus. Dabei wird definiert, wie das aktuelle Objekt bearbeitet werden soll. So kann mittels dem Object-Mode etwa das Objekt als Ganzes bearbeitet werden, während im Edit-Mode die Struktur des Objektes bearbeitet werden kann. 

### Anzeige-Optionen
In der rechten oberen Ecke befinden sich Optionen zur Darstellung der Objekte in der 3D-View. Diese umfassen: 
*	View Object Types
*	Show Gizmos
*	Viewport Overlays 
*	Toggle X Ray
*	Viewport Shading

#### View Object Types 
Hier lassen sich verschiedene Arten von Objekten alle gemeinsam innerhalb einer Szene verstecken, indem das Auge zu der entsprechenden Objektart abgewählt wird. Durch das Abwählen des Auges neben dem Objekttyp «Camera» versind beispielsweise alle Kameras nicht mehr in der Szene sichtbar. Die Objekte sind allerdings immer noch vorhanden und weisen immer noch dieselbe Funktion auf – sie werden lediglich nicht mehr in der 3D View angezeigt. Neben dem Auge lässt sich zudem anhand des Knopfes mit einem abgebildeten Cursor einstellen, dass die entsprechenden Objekte nicht mehr auswählbar sind. 

#### Show Gizmos
Innerhalb dieser Option lassen sich in der oberen rechten Ecke Tools zur Navigation mittels der Kamera ein- und ausblenden. Zudem kann hier die Darstellung eines Cursor bei der aktuellen Auswahl aktiviert werden werden, mit dem Objekte mittels der Maus rotiert, skaliert und bewegt werden können.

#### Viewport Overlays 
Durch die Deaktivierung des Viewport Overlays wird in der 3D View die Ansicht bestimmter Hilfsmittel (beispielsweise die Achsen oder die Markierung der aktuellen Auswahl) ausgeschaltet. Im Drop-Down Menu lässt sich zudem die Darstellung von einzelnen Hilfsmitteln individuell abwählen.

#### Toggle X Ray
Wenn die Schaltfläche «Toggle X Ray» ausgewählt ist, erweitert sich die Ansicht von Objekten auch durch sie hindurch. Dies ermöglicht es etwa, dass auch ein Objekt, welches hinter einem anderen Objekt verborgen liegt, betrachtet werden kann. Wenn diese Option aktiviert ist, können zudem auch die verborgenen Objekte mittels eines Mausklicks angewählt werden. Die Schaltfläche kann auch mit den Tasten ¥ + Z ein- und ausgeschaltet werden. 

#### Viewport Shading
In der rechten oberen Ecke befinden sich vier Knöpfe zur Auswahl des Viewport Shadings. Je nach Auswahl, werden die Objekte im Viewport anders dargestellt: 
*	Wireframe: Die Objekte werden in ihrer Struktur als Gitternetz angezeigt, so dass deren interner Aufbau klar ersichtlich wird. 
*	Solid: Die Objekte werden als Ganzes dargestellt, allerdings ohne die Verwendung von Materialien und Texturen. 
*	Material Prewiev: Die Objekte werden als Ganzes dargestellt, inklusive deren Materialien und Texturen. Die Umgebung wird anhand von vorgefertigten Szenen und Umgebungen beleuchtet, so dass eine schnelle Vorschau möglich ist. 
*	Render: Die Objekte werden als Ganzes dargestellt, inklusive deren Materialien und Texturen. Die Umgebung und die Beleuchtung entsprechen den Einstellungen der aktuellen Szene, so dass eine Vorschau für die gerenderte Szene möglich ist. 
Alternativ kann die Taste Z gedrückt werden. Dadurch erscheint bei der Maus ein Menu, bei dem die vier Optionen zum Viewport Shading ausgewählt werden können. 

## Letzte Aktion verfeinern
Wenn eine Aktion in Blender durchgeführt wird erscheint in der linken unteren Ecke der 3D View temporär ein Menu. Dieses Menu kann aufgeklappt werden und bietet abhängig von der durchgeführten Aktion eine Reihe Verfeinerungen. Zu beachten ist jedoch, dass dieses Menu sofort wieder verschwindet, sobald ein Mausklick ausserhalb des Menus erfolgt. Um das Menu wieder erscheinen zu lassen muss die Aktion rückgängig gemacht und erneut durchgeführt werden. 

## Dargestellte Viewport Overlays
Sofern die Ansicht der Viewport Overlays aktiviert ist werden in der 3D View einige nützliche Dinge dargestellt. Zum einen werden die verschiedenen drei Achsen in unterschiedlichen Farben vom Nullpunkt der Szene aus dargestellt: 
•	X-Achse: Rot
•	Y-Achse: Grün
•	Z-Achse: Blau
Zudem wird leicht schattiert ein Gitternetz dargestellt, bei dem jedes Quadrtat eine Einheit von einem Meter darstellt. Wird aus der Szene hinausgezoomt werden diese Quadrate zunehmend kleiner, dafür werden anschliessend quadratische Felder mit der Einheit von 10 Metern sichtbar.
Innerhalb der 3D View ist zudem der sogenannte 3D-Cursor sichtbar. Dieser ist an einer bestimmten Position in der Szene platziert und dort mittels eines rot-weissen-Kreises, ähnlich einem Rettungsrings dargestellt. Er kann als Bezugsort für Transformationen verwendet werden. Zudem werden an seiner Position jeweils neue Objekte hinzugefügt. 
