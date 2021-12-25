# Bugs Zero Kata
[Bugs Zero Kata Problem statement](https://kata-log.rocks/bugs-zero-kata)

###  Tasks:
- Find bugs and write tests
- Find weakness in the design
  - Should be less likely to introduce that kind of bug

#### Problems:
- A Game could have less than two players - make sure it always has at least two.
- Use a compiled language, or a static type checker like flowtype
- A Game could have 7 players, make it have at most 6.
   - or slightly easier allow for 7 players or more
- A player that gets into prison always stays there
   - Other than just fixing the bug, try to understand what’s wrong with the design and fix the root cause
- The deck could run out of questions
   - Make sure that can’t happen (a deck with 1 billion questions is cheating :)
- Introducing new categories of questions seems like tricky business.
   - Could you make sure all places have the “right” question and that the distribution is always correct?
- Similarly, changing the board size greatly affects the questions distribution