[![CircleCI](https://circleci.com/gh/mashbourne/pg-tap-circleci.svg?style=svg)](https://circleci.com/gh/mashbourne/pg-tap-circleci)

# test-postgres
circleci based build that sets up a Postgres database, and runs pgTAP database unit tests

__Note:__ the dependencies should be baked into a custom circleci base image to shave almost 1m off build time.

## Testing Postgres Objects
- https://medium.com/engineering-on-the-incline/unit-testing-postgres-with-pgtap-af09ec42795
- https://pgtap.org/pg_prove.html
