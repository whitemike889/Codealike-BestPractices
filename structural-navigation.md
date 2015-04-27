---
title: Structural navigation
names:
    - Edit.GoToDeclaration
    - Edit.GoToDefinition
    - Edit.GoToNextLocation
    - Edit.GoToPrevLocation
    - Edit.GoToReference
    - Edit.NavigateTo
    - Edit.NavigateToLollipop
    - Edit.PeekDefinition
    - EditorContextMenus.CodeWindow.CodeMap.ShowItem
    - EditorContextMenus.CodeWindow.GoToTypeDefinition
    - EditorContextMenus.CodeWindow.ViewCallHierarchy
    - EditorContextMenus.XAMLEditor.NavigatetoEventHandler
    - ProjectandSolutionContextMenus.Project.ViewClassDiagram
    - CodeMaid.FindInSolutionExplorer
kind: Navigation
docs:
    - http://blogs.msdn.com/b/mvpawardprogram/archive/2013/10/22/visual-studio-2013-navigate-to-improvements.aspx
    - https://msdn.microsoft.com/en-us/library/dn160178.aspx
    - https://msdn.microsoft.com/en-us/library/jj153218.aspx#bkmk_navigating
...

Using structured navigation commands and tools available for Visual Studio make
navigating code much quicker than scrolling through a file. These commands
help you navigate and build your own mental model of a project's code.
Developers that use structural navigation take less time to complete
tasks[^Fritz-etal].

Here are a few highlighted navigation commands that provide a structured
navigation approach to locating relevant source code.

Navigate To (`Ctrl`+`,`)
:   A fuzzy search interface that locates symbols matching your search
terms.  To open the search window hold `Ctrl` and press `,`.

Go To Definition (`F12`)
:   Brings up the code where the selected symbol is defined.  It provides a
quick way to brows the code graph or to get a quick refresh of what code is
about.

View Call Hierarchy (`Ctrl`+`K`, `Ctrl`+`T`)
:   Provides a two way analysis of a symbol's dependencies and uses.  It is a
good way to locate the relevant connections for a symbol you have already
located in the editor window.

Class View (`Ctrl`+`W`, `C`)
:   If you need to search or browse the class hierarchy, then using the Class
View can help you maintain a view of the code structure. This window is
available in the View menu.

[^Fritz-etal]: T. Fritz, D. C. Shepherd, K. Kevic, W. Snipes, and C. Braunlich,
"Developers' code context models for change tasks"
<http://www.ifi.uzh.ch/seal/people/kevic/researchprojects/taskcontext/FSE2014.pdf>
