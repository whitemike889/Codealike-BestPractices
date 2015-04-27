---
title: Code clone analysis
names:
    - Analyze.AnalyzeSolutionforCodeClones
    - Analyze.CodeCloneAnalysisResults
kind: Analyze
docs:
    - https://msdn.microsoft.com/en-us/library/vstudio/hh205279.aspx
...

Code clones are sections of code that accomplish the same thing. Sometimes they
are a result of copy and pasting or can occur when two or more people end up
implementing some common functionality without realizing it.

Code clones become a problem when it is time to make a change to them. Can you
remember every place where you've copied a code fragment? Most likely
not[^Juergens-etal]. Once one fragment is found to have a bug, all clones of it
likely also contain the same bug.

Further, knowing where code clones are gives you a chance to refactor some of
that common functionality. Benefits of this are more than just maintenance
costs of remembering where everything is, but also can improve the program size
and runtime complexity allowing for further compiler optimizations.


[^Juergens-etal]: Elmar Juergens, Florian Deissenboeck, Benjamin Hummel, and
Stefan Wagner. "Do code clones matter?"
<http://dx.doi.org/10.1109/ICSE.2009.5070547>
