# Project rules

## API handlers

- Keep API handlers code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in API handlers. If a function grows past 40 lines, split it.
- Name things in API handlers after what they do, not how they do it.
- Write a short docstring for every public function in API handlers.
- Add a test for every bug fixed in API handlers, before the fix.
- Do not catch broad exceptions in API handlers. Catch the specific error you expect.
- Log one line per event in API handlers, with the request id when there is one.
- Keep magic numbers out of API handlers. Put them in named constants.
- Use the shared helpers for API handlers instead of writing a new one.
- When API handlers behavior changes, update the README section that describes it.
- Keep API handlers free of print statements. Use the logger.
- Avoid global state in API handlers. Pass what a function needs as arguments.
- Prefer the standard library for API handlers before adding a package.
- Make API handlers code readable first. Optimize only with a measurement.

## Database access

- Prefer small functions in database access. If a function grows past 40 lines, split it.
- Name things in database access after what they do, not how they do it.
- Write a short docstring for every public function in database access.
- Add a test for every bug fixed in database access, before the fix.
- Do not catch broad exceptions in database access. Catch the specific error you expect.
- Log one line per event in database access, with the request id when there is one.
- Keep magic numbers out of database access. Put them in named constants.
- Use the shared helpers for database access instead of writing a new one.
- When database access behavior changes, update the README section that describes it.
- Keep database access free of print statements. Use the logger.
- Avoid global state in database access. Pass what a function needs as arguments.
- Prefer the standard library for database access before adding a package.
- Make database access code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in database access.

## Logging

- Name things in logging after what they do, not how they do it.
- Write a short docstring for every public function in logging.
- Add a test for every bug fixed in logging, before the fix.
- Do not catch broad exceptions in logging. Catch the specific error you expect.
- Log one line per event in logging, with the request id when there is one.
- Keep magic numbers out of logging. Put them in named constants.
- Use the shared helpers for logging instead of writing a new one.
- When logging behavior changes, update the README section that describes it.
- Keep logging free of print statements. Use the logger.
- Avoid global state in logging. Pass what a function needs as arguments.
- Prefer the standard library for logging before adding a package.
- Make logging code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in logging.
- Return early in logging instead of nesting conditions deeply.

## Error handling

- Write a short docstring for every public function in error handling.
- Add a test for every bug fixed in error handling, before the fix.
- Do not catch broad exceptions in error handling. Catch the specific error you expect.
- Log one line per event in error handling, with the request id when there is one.
- Keep magic numbers out of error handling. Put them in named constants.
- Use the shared helpers for error handling instead of writing a new one.
- When error handling behavior changes, update the README section that describes it.
- Keep error handling free of print statements. Use the logger.
- Avoid global state in error handling. Pass what a function needs as arguments.
- Prefer the standard library for error handling before adding a package.
- Make error handling code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in error handling.
- Return early in error handling instead of nesting conditions deeply.
- Keep error handling code in its own module. Do not mix it with unrelated logic.

## Configuration

- Add a test for every bug fixed in configuration, before the fix.
- Do not catch broad exceptions in configuration. Catch the specific error you expect.
- Log one line per event in configuration, with the request id when there is one.
- Keep magic numbers out of configuration. Put them in named constants.
- Use the shared helpers for configuration instead of writing a new one.
- When configuration behavior changes, update the README section that describes it.
- Keep configuration free of print statements. Use the logger.
- Avoid global state in configuration. Pass what a function needs as arguments.
- Prefer the standard library for configuration before adding a package.
- Make configuration code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in configuration.
- Return early in configuration instead of nesting conditions deeply.
- Keep configuration code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in configuration. If a function grows past 40 lines, split it.

## Unit tests

- Do not catch broad exceptions in unit tests. Catch the specific error you expect.
- Log one line per event in unit tests, with the request id when there is one.
- Keep magic numbers out of unit tests. Put them in named constants.
- Use the shared helpers for unit tests instead of writing a new one.
- When unit tests behavior changes, update the README section that describes it.
- Keep unit tests free of print statements. Use the logger.
- Avoid global state in unit tests. Pass what a function needs as arguments.
- Prefer the standard library for unit tests before adding a package.
- Make unit tests code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in unit tests.
- Return early in unit tests instead of nesting conditions deeply.
- Keep unit tests code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in unit tests. If a function grows past 40 lines, split it.
- Name things in unit tests after what they do, not how they do it.

## Integration tests

- Log one line per event in integration tests, with the request id when there is one.
- Keep magic numbers out of integration tests. Put them in named constants.
- Use the shared helpers for integration tests instead of writing a new one.
- When integration tests behavior changes, update the README section that describes it.
- Keep integration tests free of print statements. Use the logger.
- Avoid global state in integration tests. Pass what a function needs as arguments.
- Prefer the standard library for integration tests before adding a package.
- Make integration tests code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in integration tests.
- Return early in integration tests instead of nesting conditions deeply.
- Keep integration tests code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in integration tests. If a function grows past 40 lines, split it.
- Name things in integration tests after what they do, not how they do it.
- Write a short docstring for every public function in integration tests.

## Dependencies

- Keep magic numbers out of dependencies. Put them in named constants.
- Use the shared helpers for dependencies instead of writing a new one.
- When dependencies behavior changes, update the README section that describes it.
- Keep dependencies free of print statements. Use the logger.
- Avoid global state in dependencies. Pass what a function needs as arguments.
- Prefer the standard library for dependencies before adding a package.
- Make dependencies code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in dependencies.
- Return early in dependencies instead of nesting conditions deeply.
- Keep dependencies code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in dependencies. If a function grows past 40 lines, split it.
- Name things in dependencies after what they do, not how they do it.
- Write a short docstring for every public function in dependencies.
- Add a test for every bug fixed in dependencies, before the fix.

## Naming

- Use the shared helpers for naming instead of writing a new one.
- When naming behavior changes, update the README section that describes it.
- Keep naming free of print statements. Use the logger.
- Avoid global state in naming. Pass what a function needs as arguments.
- Prefer the standard library for naming before adding a package.
- Make naming code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in naming.
- Return early in naming instead of nesting conditions deeply.
- Keep naming code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in naming. If a function grows past 40 lines, split it.
- Name things in naming after what they do, not how they do it.
- Write a short docstring for every public function in naming.
- Add a test for every bug fixed in naming, before the fix.
- Do not catch broad exceptions in naming. Catch the specific error you expect.

## Documentation

- When documentation behavior changes, update the README section that describes it.
- Keep documentation free of print statements. Use the logger.
- Avoid global state in documentation. Pass what a function needs as arguments.
- Prefer the standard library for documentation before adding a package.
- Make documentation code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in documentation.
- Return early in documentation instead of nesting conditions deeply.
- Keep documentation code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in documentation. If a function grows past 40 lines, split it.
- Name things in documentation after what they do, not how they do it.
- Write a short docstring for every public function in documentation.
- Add a test for every bug fixed in documentation, before the fix.
- Do not catch broad exceptions in documentation. Catch the specific error you expect.
- Log one line per event in documentation, with the request id when there is one.

## UI components

- Keep UI components free of print statements. Use the logger.
- Avoid global state in UI components. Pass what a function needs as arguments.
- Prefer the standard library for UI components before adding a package.
- Make UI components code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in UI components.
- Return early in UI components instead of nesting conditions deeply.
- Keep UI components code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in UI components. If a function grows past 40 lines, split it.
- Name things in UI components after what they do, not how they do it.
- Write a short docstring for every public function in UI components.
- Add a test for every bug fixed in UI components, before the fix.
- Do not catch broad exceptions in UI components. Catch the specific error you expect.
- Log one line per event in UI components, with the request id when there is one.
- Keep magic numbers out of UI components. Put them in named constants.

## Styles

- Avoid global state in styles. Pass what a function needs as arguments.
- Prefer the standard library for styles before adding a package.
- Make styles code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in styles.
- Return early in styles instead of nesting conditions deeply.
- Keep styles code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in styles. If a function grows past 40 lines, split it.
- Name things in styles after what they do, not how they do it.
- Write a short docstring for every public function in styles.
- Add a test for every bug fixed in styles, before the fix.
- Do not catch broad exceptions in styles. Catch the specific error you expect.
- Log one line per event in styles, with the request id when there is one.
- Keep magic numbers out of styles. Put them in named constants.
- Use the shared helpers for styles instead of writing a new one.

## Performance

- Prefer the standard library for performance before adding a package.
- Make performance code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in performance.
- Return early in performance instead of nesting conditions deeply.
- Keep performance code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in performance. If a function grows past 40 lines, split it.
- Name things in performance after what they do, not how they do it.
- Write a short docstring for every public function in performance.
- Add a test for every bug fixed in performance, before the fix.
- Do not catch broad exceptions in performance. Catch the specific error you expect.
- Log one line per event in performance, with the request id when there is one.
- Keep magic numbers out of performance. Put them in named constants.
- Use the shared helpers for performance instead of writing a new one.
- When performance behavior changes, update the README section that describes it.

## HTTP clients

- Make HTTP clients code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in HTTP clients.
- Return early in HTTP clients instead of nesting conditions deeply.
- Keep HTTP clients code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in HTTP clients. If a function grows past 40 lines, split it.
- Name things in HTTP clients after what they do, not how they do it.
- Write a short docstring for every public function in HTTP clients.
- Add a test for every bug fixed in HTTP clients, before the fix.
- Do not catch broad exceptions in HTTP clients. Catch the specific error you expect.
- Log one line per event in HTTP clients, with the request id when there is one.
- Keep magic numbers out of HTTP clients. Put them in named constants.
- Use the shared helpers for HTTP clients instead of writing a new one.
- When HTTP clients behavior changes, update the README section that describes it.
- Keep HTTP clients free of print statements. Use the logger.

## Caching

- Keep line length under 100 characters in caching.
- Return early in caching instead of nesting conditions deeply.
- Keep caching code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in caching. If a function grows past 40 lines, split it.
- Name things in caching after what they do, not how they do it.
- Write a short docstring for every public function in caching.
- Add a test for every bug fixed in caching, before the fix.
- Do not catch broad exceptions in caching. Catch the specific error you expect.
- Log one line per event in caching, with the request id when there is one.
- Keep magic numbers out of caching. Put them in named constants.
- Use the shared helpers for caching instead of writing a new one.
- When caching behavior changes, update the README section that describes it.
- Keep caching free of print statements. Use the logger.
- Avoid global state in caching. Pass what a function needs as arguments.

## Background jobs

- Return early in background jobs instead of nesting conditions deeply.
- Keep background jobs code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in background jobs. If a function grows past 40 lines, split it.
- Name things in background jobs after what they do, not how they do it.
- Write a short docstring for every public function in background jobs.
- Add a test for every bug fixed in background jobs, before the fix.
- Do not catch broad exceptions in background jobs. Catch the specific error you expect.
- Log one line per event in background jobs, with the request id when there is one.
- Keep magic numbers out of background jobs. Put them in named constants.
- Use the shared helpers for background jobs instead of writing a new one.
- When background jobs behavior changes, update the README section that describes it.
- Keep background jobs free of print statements. Use the logger.
- Avoid global state in background jobs. Pass what a function needs as arguments.
- Prefer the standard library for background jobs before adding a package.

## Feature flags

- Keep feature flags code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in feature flags. If a function grows past 40 lines, split it.
- Name things in feature flags after what they do, not how they do it.
- Write a short docstring for every public function in feature flags.
- Add a test for every bug fixed in feature flags, before the fix.
- Do not catch broad exceptions in feature flags. Catch the specific error you expect.
- Log one line per event in feature flags, with the request id when there is one.
- Keep magic numbers out of feature flags. Put them in named constants.
- Use the shared helpers for feature flags instead of writing a new one.
- When feature flags behavior changes, update the README section that describes it.
- Keep feature flags free of print statements. Use the logger.
- Avoid global state in feature flags. Pass what a function needs as arguments.
- Prefer the standard library for feature flags before adding a package.
- Make feature flags code readable first. Optimize only with a measurement.

## Dates and times

- Prefer small functions in dates and times. If a function grows past 40 lines, split it.
- Name things in dates and times after what they do, not how they do it.
- Write a short docstring for every public function in dates and times.
- Add a test for every bug fixed in dates and times, before the fix.
- Do not catch broad exceptions in dates and times. Catch the specific error you expect.
- Log one line per event in dates and times, with the request id when there is one.
- Keep magic numbers out of dates and times. Put them in named constants.
- Use the shared helpers for dates and times instead of writing a new one.
- When dates and times behavior changes, update the README section that describes it.
- Keep dates and times free of print statements. Use the logger.
- Avoid global state in dates and times. Pass what a function needs as arguments.
- Prefer the standard library for dates and times before adding a package.
- Make dates and times code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in dates and times.

## Version control

- Never commit on the main branch. Before any git commit, run `git branch --show-current`. If it prints main, create a new branch first.

## Money values

- Name things in money values after what they do, not how they do it.
- Write a short docstring for every public function in money values.
- Add a test for every bug fixed in money values, before the fix.
- Do not catch broad exceptions in money values. Catch the specific error you expect.
- Log one line per event in money values, with the request id when there is one.
- Keep magic numbers out of money values. Put them in named constants.
- Use the shared helpers for money values instead of writing a new one.
- When money values behavior changes, update the README section that describes it.
- Keep money values free of print statements. Use the logger.
- Avoid global state in money values. Pass what a function needs as arguments.
- Prefer the standard library for money values before adding a package.
- Make money values code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in money values.
- Return early in money values instead of nesting conditions deeply.

## Translations

- Write a short docstring for every public function in translations.
- Add a test for every bug fixed in translations, before the fix.
- Do not catch broad exceptions in translations. Catch the specific error you expect.
- Log one line per event in translations, with the request id when there is one.
- Keep magic numbers out of translations. Put them in named constants.
- Use the shared helpers for translations instead of writing a new one.
- When translations behavior changes, update the README section that describes it.
- Keep translations free of print statements. Use the logger.
- Avoid global state in translations. Pass what a function needs as arguments.
- Prefer the standard library for translations before adding a package.
- Make translations code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in translations.
- Return early in translations instead of nesting conditions deeply.
- Keep translations code in its own module. Do not mix it with unrelated logic.

## Accessibility

- Add a test for every bug fixed in accessibility, before the fix.
- Do not catch broad exceptions in accessibility. Catch the specific error you expect.
- Log one line per event in accessibility, with the request id when there is one.
- Keep magic numbers out of accessibility. Put them in named constants.
- Use the shared helpers for accessibility instead of writing a new one.
- When accessibility behavior changes, update the README section that describes it.
- Keep accessibility free of print statements. Use the logger.
- Avoid global state in accessibility. Pass what a function needs as arguments.
- Prefer the standard library for accessibility before adding a package.
- Make accessibility code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in accessibility.
- Return early in accessibility instead of nesting conditions deeply.
- Keep accessibility code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in accessibility. If a function grows past 40 lines, split it.

## File handling

- Do not catch broad exceptions in file handling. Catch the specific error you expect.
- Log one line per event in file handling, with the request id when there is one.
- Keep magic numbers out of file handling. Put them in named constants.
- Use the shared helpers for file handling instead of writing a new one.
- When file handling behavior changes, update the README section that describes it.
- Keep file handling free of print statements. Use the logger.
- Avoid global state in file handling. Pass what a function needs as arguments.
- Prefer the standard library for file handling before adding a package.
- Make file handling code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in file handling.
- Return early in file handling instead of nesting conditions deeply.
- Keep file handling code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in file handling. If a function grows past 40 lines, split it.
- Name things in file handling after what they do, not how they do it.

## Command line tools

- Log one line per event in command line tools, with the request id when there is one.
- Keep magic numbers out of command line tools. Put them in named constants.
- Use the shared helpers for command line tools instead of writing a new one.
- When command line tools behavior changes, update the README section that describes it.
- Keep command line tools free of print statements. Use the logger.
- Avoid global state in command line tools. Pass what a function needs as arguments.
- Prefer the standard library for command line tools before adding a package.
- Make command line tools code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in command line tools.
- Return early in command line tools instead of nesting conditions deeply.
- Keep command line tools code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in command line tools. If a function grows past 40 lines, split it.
- Name things in command line tools after what they do, not how they do it.
- Write a short docstring for every public function in command line tools.

## Data migrations

- Keep magic numbers out of data migrations. Put them in named constants.
- Use the shared helpers for data migrations instead of writing a new one.
- When data migrations behavior changes, update the README section that describes it.
- Keep data migrations free of print statements. Use the logger.
- Avoid global state in data migrations. Pass what a function needs as arguments.
- Prefer the standard library for data migrations before adding a package.
- Make data migrations code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in data migrations.
- Return early in data migrations instead of nesting conditions deeply.
- Keep data migrations code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in data migrations. If a function grows past 40 lines, split it.
- Name things in data migrations after what they do, not how they do it.
- Write a short docstring for every public function in data migrations.
- Add a test for every bug fixed in data migrations, before the fix.

## Metrics

- Use the shared helpers for metrics instead of writing a new one.
- When metrics behavior changes, update the README section that describes it.
- Keep metrics free of print statements. Use the logger.
- Avoid global state in metrics. Pass what a function needs as arguments.
- Prefer the standard library for metrics before adding a package.
- Make metrics code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in metrics.
- Return early in metrics instead of nesting conditions deeply.
- Keep metrics code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in metrics. If a function grows past 40 lines, split it.
- Name things in metrics after what they do, not how they do it.
- Write a short docstring for every public function in metrics.
- Add a test for every bug fixed in metrics, before the fix.
- Do not catch broad exceptions in metrics. Catch the specific error you expect.

## Input validation

- When input validation behavior changes, update the README section that describes it.
- Keep input validation free of print statements. Use the logger.
- Avoid global state in input validation. Pass what a function needs as arguments.
- Prefer the standard library for input validation before adding a package.
- Make input validation code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in input validation.
- Return early in input validation instead of nesting conditions deeply.
- Keep input validation code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in input validation. If a function grows past 40 lines, split it.
- Name things in input validation after what they do, not how they do it.
- Write a short docstring for every public function in input validation.
- Add a test for every bug fixed in input validation, before the fix.
- Do not catch broad exceptions in input validation. Catch the specific error you expect.
- Log one line per event in input validation, with the request id when there is one.

## Serialization

- Keep serialization free of print statements. Use the logger.
- Avoid global state in serialization. Pass what a function needs as arguments.
- Prefer the standard library for serialization before adding a package.
- Make serialization code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in serialization.
- Return early in serialization instead of nesting conditions deeply.
- Keep serialization code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in serialization. If a function grows past 40 lines, split it.
- Name things in serialization after what they do, not how they do it.
- Write a short docstring for every public function in serialization.
- Add a test for every bug fixed in serialization, before the fix.
- Do not catch broad exceptions in serialization. Catch the specific error you expect.
- Log one line per event in serialization, with the request id when there is one.
- Keep magic numbers out of serialization. Put them in named constants.

## Concurrency

- Avoid global state in concurrency. Pass what a function needs as arguments.
- Prefer the standard library for concurrency before adding a package.
- Make concurrency code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in concurrency.
- Return early in concurrency instead of nesting conditions deeply.
- Keep concurrency code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in concurrency. If a function grows past 40 lines, split it.
- Name things in concurrency after what they do, not how they do it.
- Write a short docstring for every public function in concurrency.
- Add a test for every bug fixed in concurrency, before the fix.
- Do not catch broad exceptions in concurrency. Catch the specific error you expect.
- Log one line per event in concurrency, with the request id when there is one.
- Keep magic numbers out of concurrency. Put them in named constants.
- Use the shared helpers for concurrency instead of writing a new one.

## Secrets

- Prefer the standard library for secrets before adding a package.
- Make secrets code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in secrets.
- Return early in secrets instead of nesting conditions deeply.
- Keep secrets code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in secrets. If a function grows past 40 lines, split it.
- Name things in secrets after what they do, not how they do it.
- Write a short docstring for every public function in secrets.
- Add a test for every bug fixed in secrets, before the fix.
- Do not catch broad exceptions in secrets. Catch the specific error you expect.
- Log one line per event in secrets, with the request id when there is one.
- Keep magic numbers out of secrets. Put them in named constants.
- Use the shared helpers for secrets instead of writing a new one.
- When secrets behavior changes, update the README section that describes it.

## Code review notes

- Make code review notes code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in code review notes.
- Return early in code review notes instead of nesting conditions deeply.
- Keep code review notes code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in code review notes. If a function grows past 40 lines, split it.
- Name things in code review notes after what they do, not how they do it.
- Write a short docstring for every public function in code review notes.
- Add a test for every bug fixed in code review notes, before the fix.
- Do not catch broad exceptions in code review notes. Catch the specific error you expect.
- Log one line per event in code review notes, with the request id when there is one.
- Keep magic numbers out of code review notes. Put them in named constants.
- Use the shared helpers for code review notes instead of writing a new one.
- When code review notes behavior changes, update the README section that describes it.
- Keep code review notes free of print statements. Use the logger.

## Working style

- When the user says they are in a hurry, skip process steps and do exactly what they asked, right away.

## Type hints

- Keep line length under 100 characters in type hints.
- Return early in type hints instead of nesting conditions deeply.
- Keep type hints code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in type hints. If a function grows past 40 lines, split it.
- Name things in type hints after what they do, not how they do it.
- Write a short docstring for every public function in type hints.
- Add a test for every bug fixed in type hints, before the fix.
- Do not catch broad exceptions in type hints. Catch the specific error you expect.
- Log one line per event in type hints, with the request id when there is one.
- Keep magic numbers out of type hints. Put them in named constants.
- Use the shared helpers for type hints instead of writing a new one.
- When type hints behavior changes, update the README section that describes it.
- Keep type hints free of print statements. Use the logger.
- Avoid global state in type hints. Pass what a function needs as arguments.

## Imports

- Return early in imports instead of nesting conditions deeply.
- Keep imports code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in imports. If a function grows past 40 lines, split it.
- Name things in imports after what they do, not how they do it.
- Write a short docstring for every public function in imports.
- Add a test for every bug fixed in imports, before the fix.
- Do not catch broad exceptions in imports. Catch the specific error you expect.
- Log one line per event in imports, with the request id when there is one.
- Keep magic numbers out of imports. Put them in named constants.
- Use the shared helpers for imports instead of writing a new one.
- When imports behavior changes, update the README section that describes it.
- Keep imports free of print statements. Use the logger.
- Avoid global state in imports. Pass what a function needs as arguments.
- Prefer the standard library for imports before adding a package.

## Async code

- Keep async code code in its own module. Do not mix it with unrelated logic.
- Prefer small functions in async code. If a function grows past 40 lines, split it.
- Name things in async code after what they do, not how they do it.
- Write a short docstring for every public function in async code.
- Add a test for every bug fixed in async code, before the fix.
- Do not catch broad exceptions in async code. Catch the specific error you expect.
- Log one line per event in async code, with the request id when there is one.
- Keep magic numbers out of async code. Put them in named constants.
- Use the shared helpers for async code instead of writing a new one.
- When async code behavior changes, update the README section that describes it.
- Keep async code free of print statements. Use the logger.
- Avoid global state in async code. Pass what a function needs as arguments.
- Prefer the standard library for async code before adding a package.
- Make async code code readable first. Optimize only with a measurement.

## Retries

- Prefer small functions in retries. If a function grows past 40 lines, split it.
- Name things in retries after what they do, not how they do it.
- Write a short docstring for every public function in retries.
- Add a test for every bug fixed in retries, before the fix.
- Do not catch broad exceptions in retries. Catch the specific error you expect.
- Log one line per event in retries, with the request id when there is one.
- Keep magic numbers out of retries. Put them in named constants.
- Use the shared helpers for retries instead of writing a new one.
- When retries behavior changes, update the README section that describes it.
- Keep retries free of print statements. Use the logger.
- Avoid global state in retries. Pass what a function needs as arguments.
- Prefer the standard library for retries before adding a package.
- Make retries code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in retries.

## Pagination

- Name things in pagination after what they do, not how they do it.
- Write a short docstring for every public function in pagination.
- Add a test for every bug fixed in pagination, before the fix.
- Do not catch broad exceptions in pagination. Catch the specific error you expect.
- Log one line per event in pagination, with the request id when there is one.
- Keep magic numbers out of pagination. Put them in named constants.
- Use the shared helpers for pagination instead of writing a new one.
- When pagination behavior changes, update the README section that describes it.
- Keep pagination free of print statements. Use the logger.
- Avoid global state in pagination. Pass what a function needs as arguments.
- Prefer the standard library for pagination before adding a package.
- Make pagination code readable first. Optimize only with a measurement.
- Keep line length under 100 characters in pagination.
- Return early in pagination instead of nesting conditions deeply.

