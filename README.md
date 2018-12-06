# bvt - Shippable automated test runner

This project contains automated tests that need to be successfully completed
before any release. The test scenarios include:

- Permission checks across projects, repositories and integrations
- CRUD functionality for accounts, builds, clusters, jobs and other core
  Shippable domain objects
- Build status checks for failed/successful/unstable/timeout/cancelled runs
- Build checks for various languages
- Regression tests

The project is hooked up in Shippable assembly lines to run after every
successful deployment to RC.
