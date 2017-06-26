# Test Coverage Metrics

[@BillyAdamowski](https://twitter.com/BillyAdamowski) / [slides.com/billyadamowski](http://slides.com/billyadamowski/test-coverage/)

* Test coverage helps find untested code -- that's where the bugs are
* usually unit testing

## Types

* Branch vs Line coverage
* Branch coverage checks that logic/conditions were tested (if, switch, etc)

## Devising a Rule

* Encourage right behavior
* Don't make it impossible
* Understand exceptions

at Principal:

* Branch coverage % cannot go down
* New projects must hit 60% branch coverage
* Exceptions are permitted from the director level (manager's manager -- takes some work to talk to them)

## Support & Resources

* Documentation
* Lunch & Learn series
* Test Automation team is "on call"
* Archetypes start at 100% coverage

## Flexibility

* Allow exclusions (e.g. generated code)
* Smart exception process

## Other routes

* pair programming
* TDD -- don't really need to enforce coverage % then
* gamification

## Culture

* It's all about the culture.
* Balancing between culture & enforcement.

## Misc

* point out when lack of coverage causes problems
* start out by writing tests to fix bugs
* don't test 3rd-party libs
* limits on cyclomatic complexity
* don't add tests just to add tests / raise coverage. Should be a reason.
* Don't choose limits arbitrarily.
