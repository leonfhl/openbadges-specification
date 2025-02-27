# Context

OB 3.0 context file uses a versioning as a result of https://github.com/1EdTech/openbadges-specification/issues/497. This document recaps the changes made to this file

## Changelog

### 3.0.1

- Fixed `Achievement`'s `creator` IRI. Now points to `https://purl.imsglobal.org/spec/vc/ob/vocab.html#creator`
- Fixed `AchievementSubject`'s `achievement` IRI. Now points to `https://purl.imsglobal.org/spec/vc/ob/vocab.html#achievement-0`
- Fixed `Profiles`'s `phone` IRI. Now points to `https://purl.imsglobal.org/spec/vc/ob/vocab.html#phone`
- Added `image` attribute to `Achievement`.
- Removed `@type` from `alignment`. This fixes a compaction error.
- Removed `@type` from `otherIdentifier`. This fixes a compaction error.
- Removed `@type` from `Achievement`'s `resultDescription`. This fixes a compaction error.
- Removed `@type` from `AchievementSubject`'s `identifier`. This fixes a compaction error.
- Added `image` attribute to `AchievementSubject`.
- Removed `@type` from `AchievementSubject`'s `result`. This fixes a compaction error.
- Fixed `@type` from `AchievementSubject`'s `source`. This fixes a compaction error.
- Removed `@type` from `ResultDescription`'s `rubricCriterionLevel`. This fixes a compaction error.
- Removed `@type` from `endorsement`. This fixes a compaction error.
- Added `image` attribute to `Profile`.
- Fixed `Profile`'s `address` IRI. Now points to `https://purl.imsglobal.org/spec/vc/ob/vocab.html#address`
- Removed `@type` from `Achievement`'s `related`. This fixes a compaction error.
- Added `type` attribute to `Profile`s `address`. This fixes a compaction error.
- Fixed `type` attribute of `Profile`s `parentOrg`.
- Fixed `type` attribute of `Image`.
- Fixed `@id` attribute of `Alignment`. Now points to `https://schema.org/AlignmentObject`.


