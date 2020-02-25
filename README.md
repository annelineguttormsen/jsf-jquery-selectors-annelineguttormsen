# JQuery Selectors

In master.js, select the specified element(s) from each question and set a class of "answer" on those elements.

Selectiong in JQuery is done by using the `$()` method e.g. `$(".classSelector")`.  A class can then be added to all elements by using the JQuery `addClass()` method on the returned elements e.g. `$(".classSelector").addClass("answer")`.

When answered correctly, the question will be tagged with the word "correct" when viewed in the the browser.

**Note**: The data-answer attribute tells you which items need the answet class added to.  Do not select the elements using the data-answer attribute, as that defeats the purpose of the task.