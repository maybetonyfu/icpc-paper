Dear Reviewers,

Many thanks for your considered feedback and overall positive response.  Below we respond to the main questions raised in the reviews 19A and 10C (as no questions were raised in #19B and #19D).  We are confident that we can address all issues with a minor revision of our manuscript.

# Review #19A
We agree with the reviewer's constructive comments. To further clarify the discussion, we answered some questions raised in the review.

**Question**: "Through three studies involving real programmers" -- Are some programmers not real?

**Answer**: The intention was to differentiate mixed experienced programmers from university students. With that said, we agree with the reviewer that our wording could be more precise.

**Question**: Tasks were less than 1 minute in length? Seems quite short.

**Answer**: The mean task time for user study 1a is less than 1 minute. And admittedly, the user study 1a tasks were relatively trivial, as pointed out in the RQ1 discussion on page 7. The mean time in task 1b and study 2 are substantially longer.

**Question**: What is "/chameleon" mentioned on page 8? Looks like a broken LaTeX macro maybe.

**Answer**: Yes, it's a broken LaTex macro. We will conduct more thorough proofreading should the paper be accepted.

----

# Review #19C

## Questions for authors' response:

**Question**: How did the authors recognize a type error as "fixed"?

**Answer**: A type error is treated as "fixed" when the first time the program type check and some functional tests succeed. Functional tests are in place to prevent participants from "fixing" type errors by deleting offending code, as the reviewer noted. This information is provided in IV-A, data collection subsection (p. 7).

**Question**: In RQ1, why is a paired t-test possible?

**Answer**: The paired t-test is possible because the effect was measured on the same participant receiving both treatments (GHC compiler error message and ChameleonIDE). In section IV-A (p. 7), we noted the with-in-subject design of our human studies and provided justification. To further clarify,  In studies 1a and 1b, each participant received 8 tasks, 4 using the ChameleonIDE and 4 using GHC. The treatment alternated throughout the study (e.g., ChameleonIDE for tasks 1,3,5,7, GHC for tasks 2,4,6,8, or the same configuration with the order of tools reversed). The two configurations were counterbalanced within the population. We agree with the reviewer this information should more explicitly stated in the manuscript.

## Other questions raised in the review
We agree with the constructive comments made by the reviewer.
Some of the review's questions were answered here to help clarify the discussion. 

**Question**: What kind of tasks are used in Study 1b and Study 2?
Only the sentence "in study 1b we introduced more difficult challenges" is the explanation. I could see source files on HotCRP but I could not understand whether they are more practical cases or not. The paper should show a summary of type errors and programs.

**Answer**: The tasks given in the supplementary material were the same tasks used in the studies. We agree with the reviewer the paper would benefit from a concise summary of the task programs or a synopsis of the supporting material.

**Question**: How did the authors deal with participants who switched the IDE modes during the tasks in Fig.17? Please clarify the number of data points. In addition, please explain the risk of biased results, as participants were able to switch to advanced modes.

**Answer**: The task time shown in  Fig.17 is not grouped by each mode of ChameleonIDE but rather by different levels of interactivity of participants regardless of their mode assignments. The justification was given in RQ 2.1 discussion on page 8. For instance, if a participant voluntarily switches modes multiple times, even to less advanced modes, during resolving type error, they are placed in the high interactivity group. Conversely, participants in advanced mode can still be placed in the minimal interaction group if they lack interaction with the tool.

**Question**: The availability of the tool is not described.

**Answer**: ChameleonIDE is open source and is available in web and desktop versions. The information is provided at the end of paragraph 4 on page 1. 


