# commit-clickbait
Top 28 strategies for perfect link bait git commit comments, first you'll be skeptical, then you'll be inspired.

Writing git commit comments is boring. Following this guide will make it easy to make it much more fun. Inspired by [this comic](http://www.commitstrip.com/en/2014/08/07/our-cto-has-discovered-an-incredible-way-of-making-developers-read-his-commit-messages-you-wont-even-believe-how-he-did-it/), [Clickbait Headline Generator](http://community.usvsth3m.com/generator/clickbait-headline-generator) and [this article used as a reference](http://www.blogtyrant.com/link-bait-get-more-email-subscribers/).

1. **The List**  
  Good for fixes that required a number of discrete methods to fix something  
    - `"10 antipaterns everyone knows are actually just lies"`  
    - `"5 weird ways spinbox changed in just 2 weeks, the 4th will leave you speachless."`  
2. **Case Studies**  
  Perfect for unit test commit comments (you can even use the GH Issue number as the case study number)  
    - `"Case Study #1543: Does spinbox still allow exceeding maximum through manual input?"`  
    - `"Case Study #24: Does repeater still initialize properly in a post Fuel UX 3.11 world?"`  
3. **How To**  
  Appropriate for feature additions, or smaller single feature changes  
    - `"How to make repeater columns freezable in only 10 lines of code!!!"`  
    - `"How to localize input for over 100,000 languages!!!"`  
4. **Guides**  
  Works for larger additions or changes  
    - `"The advanced guide to asnyc unit testing with QUnit"`  
    - `"The surgical guide to UMD boilerplate abstraction"` 
5. **Controversial**  
  Perfect for style guide conformance  
    - `"10 reasons why tabs are better than spaces, the fifth will make your head explode"`  
    - `"Yes. I just replaced all of your double with single quotes"`  
6. **Comparison**  
  Good for arbitrary code refactoring (wher nothing really changes, the code is just better). This is somewhat similar to "controversial" but should be more than just white-space or structural related stylistic conformance.  
    - `"for in vs for of, the difference will shock you"`  
    - `"_.each vs $.each, you never knew what you were missing"`  
7. **Why**  
  Very similar to Comparison. Sometimes the message just fits this format better though, especially if you want to go inflammatory.  
    - `"forEach vs $.each, and why you shouldn't be using jQuery"`  
    - `"Why you should be using map to manipulate your arrays, you won't believe the answer"`  
8. **Intriguing Question**  
  Especially good for bug fixes where it is obvious that the original dev either didn't understand a nuance or wasn't being very careful. However, this one is just catchy and you can basically use it for anything  
    - `"Are you using for..of correctly?"`  
    - `"Are you sure that forEach does what you think it does?"`  
9. **Click Bait**  
  Much less informative than any of the previous without a lot more thought, but, utlimately can be the most fun  
    - `"One developer changes a single line of code, what happens next will blow your mind..."`  
    - `"The codepacolypse is coming, and you're going down with it without this one thing"`  
    - `"A developer tries to use const, the reason why will make you cry"`  
    - `"What your doctor isn't telling you about private methods"`  
    - `"New law in ES6 has programmers shocked"`  
    - `"This one trick has all devs scrambling to adopt react"`  


Common vernacular:
  - tries
  - weird
  - shock
  - surprising
  - facts
  - secretly
  - really
  - one trick
  - forced
  - won't believe
  - here's how
  - what happens next
  - knows
  - actually lies
  - the reason why will make you cry
  - first you'll be [shocked|dismayed|adjective], then you'll be [inspired|enraged|adjective]

Git commit messages break on character 70. Intentionally breaking the sentance up to bury the lead behind that fold can be fun.
