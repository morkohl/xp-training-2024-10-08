# Tennis Game

Taken from [Tennis Game - Emily Bache](https://github.com/emilybache/Tennis-Refactoring-Kata/blob/main/README.md)

## Requirements

- Python 3.7+
- [mob](https://mob.sh/), test that you can execute `mob moo`
- Ensure the following command runs successfully `make setup && make test`

## The Scenario

Imagine you work for a consultancy company, and one of your colleagues has been doing some work for the Tennis Society. The contract is for 10 hours billable work, and your colleague has spent 8.5 hours working on it. Unfortunately he has now fallen ill. He says he has completed the work, and the tests all pass. Your boss has asked you to take over from him. She wants you to spend an hour or so on the code so she can bill the client for the full 10 hours. She instructs you to tidy up the code a little and perhaps make some notes so you can give your colleague some feedback on his chosen design. You should also prepare to talk to your boss about the value of this refactoring work, over and above the extra billable hours.

There are several versions of this refactoring kata, each with their own design smells and challenges. I suggest you start with the first one, with the class "TennisGame1". The test suite provided is fairly comprehensive, and fast to run. You should not need to change the tests, only run them often as you refactor.

There is a deliberate error in several of the implementations - the player names are hard-coded to "player1" and "player2". After you refactor, you may want to fix this problem and add suitable test cases to prove your fix works.

## Discuss Afterwards

- How did it feel to work with such fast, comprehensive tests?
- Did you make mistakes while refactoring that were caught by the tests?
- If you used a tool to record your test runs, review it. Could you have taken smaller steps? Made fewer refactoring mistakes?
- Did you ever make any refactoring mistakes and then back out your changes? How did it feel to throw away code?
- What would you say to your colleague if they had written this code?
- What would you say to your boss about the value of this refactoring work? Was there more reason to do it over and above the extra billable hour or so?