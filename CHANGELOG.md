# Changelog

## 1.0.1 (Unreleased)

- Pin FeatBit Java SDK to 1.5.0, including targeting performance improvements, per-flag `insightsEnabled` support, and removal of `sendToExperiment` from evaluation events.
- Update project metadata to use the renamed GitHub repository.
- Migrate publishing from OSSRH to Maven Central Publishing using the `central` server ID in Maven settings.
- Pin OpenFeature Java SDK to 1.23.0 for reproducible dependency resolution.
- Fix evaluation builder compatibility with newer OpenFeature Java SDK 1.x versions.
