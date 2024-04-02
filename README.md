# An Empirical Study on Common Sense-Violating Bugs in Mobile Apps

In this repository, we release 3 parts of data from our empirical study:

1. **The automatically collected issue dataset**
   - The dataset comprises 33,650 issue reports retrieved from open-source apps via the GitHub API.
   - This data is released in JSON format (`all_issues.json`). Each entry in the dataset contains the URL, title, and body of the issue report, along with some useful metadata.
2. **The bug reports analyzed manually in our study**
   - This list (`analyzed_bugs.csv`) contains 5,342 bug reports we have manually analyzed.
   - The column "label" could be "Invalid" (excluded, not a valid bug report), "Negative" (the bug do not violate common sense), or "Positive" (common sense-violating bug). The first 130 issues are selected from [Andror2+](https://github.com/se-umn/2022_saner_bug_report_reproduction_study) dataset (with the same filtering strategy when constructing our dataset).
3. **The common sense principles violated by the bugs**
   - We have concluded more than 3 hundred principles from the studied bugs. 
   - Visit [this website](https://se-research-bugs.github.io/) to view the full version of the list online.
   - Also, a markdown version is available [here](principles.md).

