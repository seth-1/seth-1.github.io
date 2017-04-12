# How to get help

We covered basic R functions and some packages in the tutorial and the exercises. When you get stuck you can probably find an answer by looking at examples at the end of the help function.

Please make sure to post a minimal coding example with your question, like e.g. the code snippets in our tutorial section. Use built in datasets since you are not allowed to distribute the secondary metabolite and interpro annotations. We only provided those for the course. Important: Also include you R version and package version in the question. You can find these by executing ```sessionInfo()```

Example:

```r
library(ggplot2)

ggplot(mtcars) +
geom_bar(aes(x = factor(cyl), fill = factor(gear)), position = 'dodge', stat = 'count')
```

> Hi,
Is it possible to create one bar per organism in ggplot2? I am using R version 3.3.3 and ggplot2_2.2.1.9000.

If you don't find the answer there, you can ask fellow students on the campusnet group, try google, [stackoverflow](http://stackoverflow.com/) or [Rbloggers](https://www.r-bloggers.com/). If you still cannot find an answer you might want to ask a question at stackoverflow.  Though you might not need to post a question because you find everything on stackoverflow from [R Grouping functions: sapply vs. lapply vs. apply. vs. tapply vs. by vs. aggregate
](https://stackoverflow.com/questions/3505701/r-grouping-functions-sapply-vs-lapply-vs-apply-vs-tapply-vs-by-vs-aggrega) to [How does the Google “Did you mean?” Algorithm work?](https://stackoverflow.com/questions/307291/how-does-the-google-did-you-mean-algorithm-work).

**Important: If you do not use built in datasets or just copy paste solutions to the exercises I will need to remove them from the campusnet group.**
