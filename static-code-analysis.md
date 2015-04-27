---
title: Static code analysis
names:
    - Analyze.ConfigureCodeAnalysisforProject
    - Analyze.ConfigureCodeAnalysisforSolution
    - Build.RunCodeAnalysisonOnlyProject
    - Build.RunCodeAnalysisonSelection
    - Build.RunCodeAnalysisonSolution
    - Build.RunCodeAnalysisonWebSite
    - ClassViewContextMenus.ClassViewProject.RunCodeAnalysis
    - ClassViewContextMenus.ClassViewProject.RunCodeAnalysisonSelection
    - ClassViewContextMenus.ClassViewProject.SSDTStaticCodeAnalysisRunCodeAnalysis
    - ClassViewContextMenus.ClassViewProject.StaticCodeAnalysisRunCodeAnalysis
    - ClassViewContextMenus.ClassViewProject.RunCodeAnalysisonSelection
    - Data.StaticCodeAnalysisConfigure
    - Data.StaticCodeAnalysisRun
    - OtherContextMenus.ErrorList.SSDTStaticCodeAnalysisSuppressMessages
    - OtherContextMenus.ErrorList.StaticCodeAnalysisSuppressMessages
    - Project.ConfigureCodeAnalysisforWebSite
    - SQL.SSDTStaticCodeAnalysisConfigure
    - SQL.SSDTStaticCodeAnalysisRun
kind: Analyze
docs:
    - https://msdn.microsoft.com/en-us/library/vstudio/dd264897.aspx
...

Static code analysis is a general term for many different techniques. There are
analyses of program syntax, semantics, control and data flow. These analyses
can help you pinpoint problems that aren't easy to do with manual testing
because they are able to *generate* scenarios than you could do by hand. They
can also be used to identify portions of code that are potential bottlenecks or
error prone. Overflow, underflow, rounding errors, and array bounds checking
are all items that you may not face in tests, but become immediately evident
when real usage begins.
