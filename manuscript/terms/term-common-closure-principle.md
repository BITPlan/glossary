{lang=en}
### Common Closure Principle

A fundamental principle for designing the structure of software systems (also see [Package Principles](#term-package-principles)). It directly and explicitly restates the [Single Responsibility Principle](#term-single-responsibility-principle) for larger components. 

The subcomponents of a component should ideally have the exact same reasons to change. A change request that effects one of them should effect all of them, but it should *not* effect anything else outside their enclosing component.

Thereby, each expected change request would effect a minimal number of components. Or put another way: Each component would be [closed](#term-open-close-principle) to a maximum number of expected change requests. The term *expected* here signifies a few important implications:

1. The inherent concepts/responsibilities of a system run deeper than a surface-level description of its behaviour. 
2. The deeper concepts/responsibilities of a system are not entirely objective but can be modeled in different ways.
3. Determining the concepts/responsibilities of a system is not just passive describing but also active *strategizing*.

This principle leads to [highly cohesive](#term-cohesion) components. It also implies [loosely coupled](#term-coupling) components because related concepts that *do* change together *do* get bundled up in the same component. When each single concept is expressed by a single component, there are no unnecessary couplings between components.

Category: Design-Principle

{lang=de}
### Common-Closure-Prinzip

Ein Grundsatz für die Gestaltung der Struktur von Softwaresystemen
(siehe auch [Packaging-Prinzipien](#term-package-principles)). Er ist eine
direkte und ausdrückliche Neuformulierung des
[Single-Responsibility-Prinzips](#term-single-responsibility-principle) für größere
Komponenten.

Die Unterkomponenten einer Komponente sollen idealerweise genau
dieselben Änderungsgründe haben. Ein Änderungsantrag, der sich auf
eine von ihnen auswirkt, soll sich auf sie alle, aber auf *nichts*
außerhalb ihrer enthaltenden Komponente auswirken.

Dadurch würde sich jeder erwartete Änderungsantrag auf eine minimale
Zahl an Komponenten auswirken. Oder anders gesagt: Jede Komponente
wäre gegenüber einer maximalen Zahl an erwarteten Änderungsanträgen
[geschlossen](#term-open-close-principle). Der Begriff *erwartet* hat an dieser
Stelle einige bedeutende Auswirkungen:

1.  Die inhärenten Konzepte/Verantwortlichkeiten eines Systems gehen
    tiefer als einer Beschreibung seines Verhaltens auf
    Oberflächenebene.

2.  Die tieferen Konzepte/Verantwortlichkeiten eines Systems sind nicht
    vollständig objektiv, sondern können auf unterschiedliche Weise
    modelliert werden.

3.  Die Festlegung der Konzepte/Verantwortlichkeiten eines Systems ist
    nicht nur eine passive Beschreibung, sondern aktive
    *Strategieentwicklung*.


Dieses Prinzip führt zu Komponenten mit [starker
Kohäsion](#term-cohesion). Es geht auch mit [lose
gekoppelten](#term-coupling) Komponenten einher, da verbundene Konzepte,
die sich zusammen *ändern*, in dieselbe Komponente *gebündelt* werden.
Wenn jedes einzelne Konzept von einer einzigen Komponente ausgedrückt
wird, gibt es keine unnötigen Kopplungen zwischen Komponenten.

Kategorie: Entwurfsprinzip
