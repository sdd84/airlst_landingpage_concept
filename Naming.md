# Naming Convention
In diesem Dokument sollen die Begrifflichkeit, die im Kontext des Landingpage Builder 
verwendet werden, dokumentiert und erklärt werden.

## Editor
Der Editor ist die Drag and Drop Anwendung mit der die Landingpages erstellt werden können.
[Ausführliche Definition.](/editor)

## Components
Components ist der Überbegriff für alle Vue Componenten die von Clay gerendert werden können.
Sie werden in verschieden Typen unterteilt.  
[Ausführliche Definition.](/components)

### Atoms
Atoms sind eine Untertype von Componenten. Diese haben keinerlei Abhängigkeiten zu anderen Componenten
und beinhalten ausschließlich Funktion und Logik. Das Styling ist bei ihnen auf ein Minimum beschränkt
und nur vorhanden wenn sie für die Funktion unabdingbar ist.  
[Ausführliche Definition.](/components/atoms)

### Molecules
Molecules sind ein Untertype von Componenten. Diese bestehen aus einem oder mehreren [Atoms](/components/atoms).
Sie verbinden diese zu größeren Componeten zb. aus einem Text und einem Bild Atom wird ein Bild-mit-Text Molecules.
Styles wird aber auch hier nur soweit geschrieben wie es die Funktion des Molecules verlangt.
[Ausführliche Definition.](/components/molecules)

### Widgets
Widgets sind ein Untertype von Compoenten. Diese bestehen aus Molecules oder auch Atoms.
Sie Fügen den eigentliche Style und das Design hinzu. 
Deshalb sind sie Teil eines [Themes](/themes) das ein bestimmte Design umsetzt.  
[Ausführliche Definition.](/components/widgets)

## BaseLibrary
Die BaseLibrary ist ein Repo/NPM Package das alle [Atoms](/components/atoms) und [Molecules](/components/molecules) 
zusammen fasst die für [Themes](/themes) verwendbar sein sollen. 
[Ausführliche Definition.](/base_library)

## Themes
Ein Theme ist ein eigenes Repo/NPM Package das aus einer Collection an [Widgets](/components/widgets) besteht
die aus [Atoms](/components/atoms) und [Molecules](/components/molecules) 
aus der [BaseLibrary](/base_library) zusammen gestellt wurden und das Design 
des jeweiligen Themes umsetzten. Sie enthalten also das Css und Styling.  
[Ausführliche Definition.](/themes)

## Templates
Ein Template kann vom User im [Editor](/editor) selbst erstellt werden. Und zb. für zukünftige Events als Vorlage 
verwendet werden. Sie sind nicht starr und können wieder gänzlich verändert werden.  
[Ausführliche Definition.](/templates)

## Presets
Ein Preset ist einem [Template](/templates) sehr ähnlich. Es ist eine Vorlage die bereits Componenten arrangiert.
Anders als beim Template werden Presets von uns geschrieben und sind nur an vorgeben Stellen editierter.
[Ausführliche Definition.](/presets)
 
## Pages
Pages sind die einzelne Seiten einer Landingpage.
[Ausführliche Definition.](/pages)

## Packs
Packs sind Pakete die aus [Presets](/presets) und [Themes](/themes) bestehen und dann extra monetisiert werden können.
[Ausführliche Definition.](/packs)
