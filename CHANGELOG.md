# Changelog

All notable changes to this project will be documented in this file.

## [2.0.12] - 2023-04-04

### <!-- 05 -->Documentation

- Update twitter badge due to depreciation

### <!-- 07 -->Continuous Integrations

- Bump orhun/git-cliff-action from 2.0.3 to 2.0.5 
- Bump actions/cache from 3.2.3 to 3.3.1 
- Bump actions/checkout from 3.3.0 to 3.5.0 

## [2.0.11] - 2023-01-12

### <!-- 05 -->Documentation

- Update workflow badge url over readme file

## [2.0.10] - 2023-01-11

### <!-- 07 -->Continuous Integrations

- Bump actions/checkout from 3.2.0 to 3.3.0
- Bump actions/cache from 3.0.11 to 3.2.3
- Bump orhun/git-cliff-action from 1.2.0 to 2.0.3
- Setup stale bot to closes abandoned issues

## [2.0.9] - 2022-12-13

### <!-- 07 -->Continuous Integrations

- Bump actions/cache from 3.0.0 to 3.0.1
- Bump actions/cache from 3.0.1 to 3.0.2
- Bump actions/checkout from 3.0.0 to 3.0.1
- Bump actions/checkout from 3.0.1 to 3.0.2
- Bump orhun/git-cliff-action from 1.1.6 to 1.1.7
- Bump actions/cache from 3.0.2 to 3.0.3
- Bump actions/cache from 3.0.3 to 3.0.4
- Bump actions/cache from 3.0.4 to 3.0.5
- Bump actions/cache from 3.0.5 to 3.0.11
- Bump softprops/action-gh-release from 0.1.14 to 0.1.15
- Bump orhun/git-cliff-action from 1.1.7 to 1.2.0
- Bump actions/checkout from 3.0.2 to 3.2.0

### <!-- 08 -->Miscellaneous Tasks

- Update slevomat/coding-standard requirement

## [2.0.8] - 2022-03-26

### <!-- 02 -->Bug Fixes

- Exclude `DisallowConstructorPropertyPromotion` from `SlevomatCodingStandard`

## [2.0.7] - 2022-03-26

### <!-- 02 -->Bug Fixes

- Exclude `DisallowTrailingCommaInDeclaration` from `SlevomatCodingStandard`

## [2.0.6] - 2022-03-26

### <!-- 02 -->Bug Fixes

- Exclude `FunctionComment.Missing` from `Symfony`
- Exclude `ClassComment.Missing` from `Symfony`

## [2.0.5] - 2022-03-26

### <!-- 02 -->Bug Fixes

- Exclude `Missing` from `ClassComment` and `VariableComment`

## [2.0.4] - 2022-03-26

### <!-- 02 -->Bug Fixes

- Exclude `FunctionComment.Missing` from `Squiz`

## [2.0.3] - 2022-03-26

### <!-- 02 -->Bug Fixes

- Exclude `ClassComment` and `VariableComment` from `Squiz`

## [2.0.2] - 2022-03-26

### <!-- 02 -->Bug Fixes

- Exclude `SuperfluousExceptionNaming` from `SlevomatCodingStandard`

## [2.0.1] - 2022-03-26

### <!-- 02 -->Bug Fixes

- Update `testVersion` for `PHPCompatibility`

### <!-- 05 -->Documentation

- Update required version on readme file

## [2.0.0] - 2022-03-26

### <!-- 08 -->Miscellaneous Tasks

- Update `git-cliff` configs to ignore pre releases

## [2.0.0-alpha.0] - 2022-03-26

### <!-- 02 -->Bug Fixes

- [**breaking**] Drop support for version 7.x and earlier

### <!-- 07 -->Continuous Integrations

- Bump `actions/cache` from 2.x.x to 3.0.0
- Update triggers and improve `php` workflow
- Change `php` workflow name to `check`

### <!-- 08 -->Miscellaneous Tasks

- Update `config.allow-plugins` on the `composer` configs

## [1.20.11] - 2022-03-19

### <!-- 05 -->Documentation

- Improve the dependabot configuration file

### <!-- 07 -->Continuous Integrations

- Mark pre-releases tags on release workflow
- Improve and cleanup release bodies
- Add cache action for caching composer packages
- Update `actions/checkout` from v2.x.x to v3.0.0
- Update `dependabot` prefixes on configuration

### <!-- 08 -->Miscellaneous Tasks

- Bump actions/cache from 2.1.6 to 2.1.7
- Update github funding configs
- Solve github funding broken link issue
- Bump orhun/git-cliff-action from 1.1.5 to 1.1.6

## [1.2.10] - 2021-11-03

### <!-- 07 -->Continuous Integrations

- Change workflow actions versions to fixed versions
- Remove headlines of changelog from release notes

### <!-- 08 -->Miscellaneous Tasks

- Bump actions/checkout from 2.3.4 to 2.3.5
- Bump actions/checkout from 2.3.5 to 2.4.0

## [1.2.9] - 2021-09-26

### <!-- 08 -->Miscellaneous Tasks

- Ignore github configuration folder

## [1.2.8] - 2021-09-26

### <!-- 08 -->Miscellaneous Tasks

- Ignore extra files from export

## [1.2.7] - 2021-09-22

### <!-- 08 -->Miscellaneous Tasks

- Change type of `StaticClosure` from `SlevomatCodingStandard` rules for `Functions` to warning

## [1.2.6] - 2021-09-22

### <!-- 08 -->Miscellaneous Tasks

- Exclude `ParamNameNoMatch` from `Symfony` rules for `FunctionComment`

## [1.2.5] - 2021-09-22

### <!-- 08 -->Miscellaneous Tasks

- Exclude changelog commits from changelog
- Exclude `ParamNameNoMatch` from `Squiz` rules for `FunctionComment`

## [1.2.4] - 2021-09-21

### <!-- 07 -->Continuous Integrations

- Add missing name and trigger to release workflow

### <!-- 08 -->Miscellaneous Tasks

- Exclude fully qualified class name in annotation rule

## [1.2.3] - 2021-09-21

### <!-- 07 -->Continuous Integrations

- Add new workflow for create releases

### <!-- 08 -->Miscellaneous Tasks

- Replace `standard-version` by `git-cliff` for generate changelog

## [1.2.2] - 2021-09-20

### <!-- 08 -->Miscellaneous Tasks

- Look for unused imports from other namespaces everywhere

## [1.2.1] - 2021-09-18

### <!-- 08 -->Miscellaneous Tasks

- Update ruleset by exclude some rules

## [1.2.0] - 2021-09-17

### <!-- 08 -->Miscellaneous Tasks

- Add symphony coding style rules
- Reorder some of rules over ruleset
- Add `symplify/coding-standard` to suggestions

## [1.1.5] - 2021-09-17

### <!-- 08 -->Miscellaneous Tasks

- Exclude checking global constants non fully qualified

## [1.1.4] - 2021-09-17

### <!-- 08 -->Miscellaneous Tasks

- Replace slevomat coding standard includes with excludes

## [1.1.3] - 2021-09-17

### <!-- 08 -->Miscellaneous Tasks

- Enforce typehints for properties
- Replace docblock returns by typehints

## [1.1.2] - 2021-09-17

### <!-- 05 -->Documentation

- Add target branch to dependabot configuration file
- Add commit message scop to dependabot configuration file
- Improve the dependabot configuration file

### <!-- 08 -->Miscellaneous Tasks

- Replace docblock params by typehints

## [1.1.1] - 2021-09-16

### <!-- 05 -->Documentation

- Add downloads badge linked to packagist
- Add the workflow status badge

### <!-- 07 -->Continuous Integrations

- Add default php setup workflow

## [1.1.0] - 2021-09-16

### <!-- 01 -->Features

- Add nekofar coding standard ruleset

### <!-- 05 -->Documentation

- Add new dependabot configuration file
- Add funding configuration file
- Add the missing license file
- Add the missing readme file

### <!-- 08 -->Miscellaneous Tasks

- Add missing keywords to config file

## [1.0.0] - 2021-09-16

### <!-- 08 -->Miscellaneous Tasks

- Add the composer configuation file
- Add required packages to composer config
- Update version and stability configuration
- Add config file for standard version
- Normalize composer configuation

<!-- generated by git-cliff -->
