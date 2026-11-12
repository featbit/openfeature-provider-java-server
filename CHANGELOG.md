# Changelog

## 1.0.1 (Unreleased)

- Raise the FeatBit Java SDK dependency range to `[1.5.0,2.0.0)`, including targeting performance improvements, per-flag `insightsEnabled` support, and removal of `sendToExperiment` from evaluation events.
- Update project metadata to use the renamed GitHub repository.
- Migrate publishing from OSSRH to Maven Central Publishing using the `central` server ID in Maven settings.
- Set the OpenFeature Java SDK dependency range to `[1.16.0,2.0.0)`.
- Require Java 11 or above; Java 8 is no longer supported.
- Fix evaluation builder compatibility with newer OpenFeature Java SDK 1.x versions.
