# Diffblue in CI: Harness.io

[Harness.io](https://www.harness.io) is a CI/CD platform. This project demonstrates Diffblue working in a Harness pipeline.
See [.harness/diffblue.yaml](.harness/diffblue.yaml). This configuration:

- Builds a Java 17 project
- Runs mutation testing to benchmark quality of developer-written tests
- Removes all existing tests
- Gets Diffblue to write tests from scratch
- Runs mutation testing again to calculate quality of Diffblue-written tests
