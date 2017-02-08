# Frequently needed arguments about sofware quality

A collection of frequently needed arguments about well stablished and proven practices related to software quality.

## Tests with conditional execution paths should be avoided

Tests with conditional execution paths are intrincically non-deterministic, they mix responsibilities of possibly what could be multiple test cases in one turning the outcome of the test dificult to read and reason about. While a deterministic test has two possible results (it has either passed or failed) a test with conditional paths can have multiple reasons for either passing or failure states. 

Read more:
- [Nondeterministic algorithm](https://en.wikipedia.org/wiki/Nondeterministic_algorithm)
- [Eradicating non-determinism in tests](https://martinfowler.com/articles/nonDeterminism.html)

## BDD is not about testing, it is not a testing approach

BDD is a design activity meant to leverage communication within the team while guiding the development with an outside-in approach. The fact that by aplying BDD you end up with automated tests is just a side effect but not the main goal.

Read more:
- [BDD is not about testing](https://speakerdeck.com/tastapod/bdd-is-not-about-testing)

## TDD is not for unit testing only

TDD cares about when you are testing not what. So you can do TDD at any level of granularity, for instance:
 - in the acceptance level
 - in the integration level or
 - in the unit level
Unit tests cares about testing the smallest unit of behavior that you care about.
