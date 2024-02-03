# Changelog

All notable changes to this project will be documented in this file.

## [3.0.10] - 2024-02-03

### Documentation

- Update badges over project readme file

## [3.0.9] - 2023-07-01

### Documentation

- Update crypto funding address over configs
- Add funding to the composer configs
- Add crypto donate badge to the project readme

## [3.0.8] - 2023-06-01

### Bug Fixes

- Exclude variable comment missing war

## [3.0.7] - 2023-06-01

### Bug Fixes

- Exclude function invalid return by squiz

## [3.0.6] - 2023-05-31

### Bug Fixes

- Exclude function incorrect param var name

## [3.0.5] - 2023-05-26

### Bug Fixes

- Solve some issues related to typehints
- Exclude sorting array keys alphabetically
- Exclude requiring multiline ternary operators
- Exclude disallowing named arguments
- Exclude functions useless parameters default value
- Exclude disallowing numeric literal separators
- Exclude disallowing null safe object operators
- Ignore duplicate spaces in annotations

### Miscellaneous Tasks

- Improve ruleset comments for better readability

## [3.0.4] - 2023-05-12

### Bug Fixes

- Exclude `RequireArrowFunction` from `SlevomatCodingStandard`
- Exclude `UnusedParameter` from `SlevomatCodingStandard`
- Exclude `DisallowSuperGlobalVariable` from `SlevomatCodingStandard`

## [3.0.3] - 2023-05-12

### Bug Fixes

- Change `testVersion` for `PHPCompatibility` to `8.1-`

### Miscellaneous Tasks

- Change `open-pull-requests-limit` from 10 to 20

## [3.0.2] - 2023-04-27

### Bug Fixes

- Remove `linesCountBeforeDeclare` for `DeclareStrictTypes`

## [3.0.1] - 2023-04-27

### Bug Fixes

- Replace some of deprecated settings for `DeclareStrictTypes`

## [2.0.12] - 2023-04-04

### Documentation

- Update twitter badge due to depreciation

## [2.0.11] - 2023-01-12

### Documentation

- Update workflow badge url over readme file

## [2.0.10] - 2023-01-11

### Miscellaneous Tasks

- Setup stale bot to closes abandoned issues

## [2.0.8] - 2022-03-26

### Bug Fixes

- Exclude `DisallowConstructorPropertyPromotion` from `SlevomatCodingStandard`

## [2.0.7] - 2022-03-26

### Bug Fixes

- Exclude `DisallowTrailingCommaInDeclaration` from `SlevomatCodingStandard`

## [2.0.6] - 2022-03-26

### Bug Fixes

- Exclude `FunctionComment.Missing` from `Symfony`
- Exclude `ClassComment.Missing` from `Symfony`

### Styling

- Reformat whitespaces over `ruleset`

## [2.0.5] - 2022-03-26

### Bug Fixes

- Exclude `Missing` from `ClassComment` and `VariableComment`

### Revert

- Exclude `ClassComment` and `VariableComment` from `Squiz`

## [2.0.4] - 2022-03-26

### Bug Fixes

- Exclude `FunctionComment.Missing` from `Squiz`

## [2.0.3] - 2022-03-26

### Bug Fixes

- Exclude `ClassComment` and `VariableComment` from `Squiz`

## [2.0.2] - 2022-03-26

### Bug Fixes

- Exclude `SuperfluousExceptionNaming` from `SlevomatCodingStandard`

## [2.0.1] - 2022-03-26

### Bug Fixes

- Update `testVersion` for `PHPCompatibility`

### Documentation

- Update required version on readme file

## [2.0.0] - 2022-03-26

### Miscellaneous Tasks

- Update `git-cliff` configs to ignore pre releases

## [2.0.0-alpha.0] - 2022-03-26

### Bug Fixes

- [**breaking**] Drop support for version 7.x and earlier

### Miscellaneous Tasks

- Update `config.allow-plugins` on the `composer` configs
- Update triggers and improve `php` workflow
- Change `php` workflow name to `check`

## [1.20.11] - 2022-03-19

### Documentation

- Improve the dependabot configuration file

### Miscellaneous Tasks

- Mark pre-releases tags on release workflow
- Improve and cleanup release bodies
- Add cache action for caching composer packages
- Update github funding configs
- Solve github funding broken link issue
- Update `actions/checkout` from v2.x.x to v3.0.0
- Update `dependabot` prefixes on configuration

## [1.2.10] - 2021-11-03

### Miscellaneous Tasks

- Change workflow actions versions to fixed versions
- Remove headlines of changelog from release notes

## [1.2.9] - 2021-09-26

### Miscellaneous Tasks

- Ignore github configuration folder

## [1.2.8] - 2021-09-26

### Miscellaneous Tasks

- Ignore extra files from export

## [1.2.7] - 2021-09-22

### Miscellaneous Tasks

- Change type of `StaticClosure` from `SlevomatCodingStandard` rules for `Functions` to warning

## [1.2.6] - 2021-09-22

### Miscellaneous Tasks

- Exclude `ParamNameNoMatch` from `Symfony` rules for `FunctionComment`

## [1.2.5] - 2021-09-22

### Miscellaneous Tasks

- Exclude changelog commits from changelog
- Exclude `ParamNameNoMatch` from `Squiz` rules for `FunctionComment`

## [1.2.4] - 2021-09-21

### Miscellaneous Tasks

- Add missing name and trigger to release workflow
- Exclude fully qualified class name in annotation rule

## [1.2.3] - 2021-09-21

### Miscellaneous Tasks

- Replace `standard-version` by `git-cliff` for generate changelog
- Add new workflow for create releases

## [1.2.2] - 2021-09-20

### Miscellaneous Tasks

- Look for unused imports from other namespaces everywhere

## [1.2.1] - 2021-09-18

### Miscellaneous Tasks

- Update ruleset by exclude some rules

## [1.2.0] - 2021-09-17

### Miscellaneous Tasks

- Add symphony coding style rules
- Reorder some of rules over ruleset
- Add `symplify/coding-standard` to suggestions

## [1.1.5] - 2021-09-17

### Miscellaneous Tasks

- Exclude checking global constants non fully qualified

## [1.1.4] - 2021-09-17

### Miscellaneous Tasks

- Replace slevomat coding standard includes with excludes

## [1.1.3] - 2021-09-17

### Miscellaneous Tasks

- Enforce typehints for properties
- Replace docblock returns by typehints

## [1.1.2] - 2021-09-17

### Documentation

- Add target branch to dependabot configuration file
- Add commit message scop to dependabot configuration file
- Improve the dependabot configuration file

### Miscellaneous Tasks

- Replace docblock params by typehints

## [1.1.1] - 2021-09-16

### Documentation

- Add downloads badge linked to packagist
- Add the workflow status badge

### Miscellaneous Tasks

- Add default php setup workflow

## [1.1.0] - 2021-09-16

### Features

- Add nekofar coding standard ruleset

### Documentation

- Add new dependabot configuration file
- Add funding configuration file
- Add the missing license file
- Add the missing readme file

### Miscellaneous Tasks

- Add missing keywords to config file

## [1.0.0] - 2021-09-16

### Miscellaneous Tasks

- Add the composer configuation file
- Add required packages to composer config
- Update version and stability configuration
- Add config file for standard version
- Normalize composer configuation

<!-- generated by git-cliff -->
