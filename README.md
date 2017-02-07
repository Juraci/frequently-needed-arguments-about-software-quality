# Frequently needed arguments about sofware quality

A collection of frequently needed arguments about well stablished and proven practices related to software quality.

## Tests with conditional execution paths

Tests with conditional execution paths are intrincically non-deterministic, they mix responsibilities of possibly what could be multiple test cases in one turning the outcome of the test dificult to read and reason about. While a deterministic test has two possible results (it has either passed or failed) a test with conditional paths can have multiple reasons dor either passing or failure states. 

Read more:
- [Nondeterministic algorithm](https://en.wikipedia.org/wiki/Nondeterministic_algorithm)
- [Eradicating non-determinism in tests](https://martinfowler.com/articles/nonDeterminism.html)
