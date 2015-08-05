Testing will give you the opportunity to find and fix bugs *before* the software
is deployed in the field. How do you know if code works if you don't test it?
Sure, it may compile, but does it *work*? You don't want to be the developer
that causes a billion dollar error on a space mission to [Mars][], a
[regional blackout][], or worse, [death][], just because you didn't run a simple
test, do you?

There are numerous kinds of testing you can do right from your IDE. Testing is
important to verify that the software works:

- as expected according to the requirements
- in the deployment environment
- within a reasonable amount of time
- without failure when pushed to it's maximum
- without failure when given incorrect input
- ...

Further, you need to log when you test. And you need to re-test on change. How
can you be sure the change you made doesn't affect other portions of the system
if you do not test them continuously?

[Venus]: https://en.wikipedia.org/wiki/Mariner_1
[Mars]: https://en.wikipedia.org/wiki/Mars_Climate_Orbiter
[regional blackout]: https://en.wikipedia.org/wiki/Northeast_blackout_of_2003
[death]: http://www.cbsnews.com/news/toyota-unintended-acceleration-has-killed-89/


#### Related documentation

- <https://msdn.microsoft.com/en-us/library/dd264975.aspx>
