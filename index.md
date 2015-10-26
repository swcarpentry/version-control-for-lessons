---
---
# Using Version Control to Manage Lesson Development

* Introduction
  * Version control developed for software development
    * Track changes
    * Share changes systematically
    * Enable review of changes
  * People who use it also use it for writing papers, because they want to do the same things
    * Provided those papers are stored as text (because programmers)
  * We use it for lessons, because we also want to do those things
  * This short paper explains how and what we've learned
* Jenny Bryan
  * setting: a typical university course
  * describe workflow
* Greg Wilson
  * distributed volunteer effort
  * SWC started as single author
    * using version control to manage content because creator is a programmer
    * and because we teach version control
  * early co-instructors mostly didn't add or modify
    * started requiring small changes as part of instructor training
    * opened the gates to contributions from others (made contributing normal)
  * dividing material into one repository per lesson made a big difference too
    * less effort: unified repo was big, and had lots of churn
    * less background noise: only follow the lesson(s) you're interested in
  * appointing lesson maintainers helped as well
    * inspired by component maintainers in large shared open source software libraries
    * like journal editors: give feedback, route material to reviewers, final say over merging
    * ensures no one person is a bottleneck
  * challenge: GitHub is *hard*
    * 1/3 of participants in the online instructor training course Feb-Apr 2015 found it difficult or very difficult
    * GitHub's "easy" web editing interface isn't
    * basic wikis don't suffice because no opportunity for pre-inclusion review
* Discussion
  * common threads
    * pre-commit review is a wonderful thing
      * particularly when the mechanism (in this case, GitHub) is already part of contributors' daily lives
  * challenges
    * tracking updates: how can I easily find out what has changed since the last time I taught this?
    * consistency: how to ensure changes to widely-separated parts of lesson are consistent when multiple people doing updates?
      * no equivalent of software's "run the tests"
      * "keep each lesson small and self-contained" doesn't work: whole point of tutorial (vs. reference) is extended narrative
    * macro changes: how to handle large refactoring?
      * hard for software too...
  * future work
