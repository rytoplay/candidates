# candidates
A js page to count the number of times each Democratic candidate appears in the contents of a facebook comments div.
1. Download and open the index.html page.

2.
Under a FB post where many people have listed the candidates they like:
- expand all comments (generally FB will expand 50 at a time, so just keep clicking "show previous comments"
- hover over the top comment, right click, and inspect it.
- in the inspector, move up until the entire comment thread is highlighted. Lately this tag has been called
```<div class="_3w53" data-testid="UFI2CommentsList/root_depth_0">```
but that could change any time.
- right click and choose "copy -> copy element".
- paste into the box on this page and click "count"

This script:
- Counts one occurrence per comment of the first OR last name (ex. "Liz" or "Liz Warren" or "Elizabeth Warren")
each result in one count.

- Counts only one occurrence per comment (ex. "beto beto beto beto") results in one count.
