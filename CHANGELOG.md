# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- Access to dashboard
- Return & pre-fill Company data in 'Company' form from Companies House

## 2019-05-10

### Added

- Add pop-up to end of survey confirming data quality (GUI only)

### Removed

- Remove 'dashboard' from sidebar menu item

## 2019-05-09

### Added

- Link to download PDF dashboard of survey response
- Process to email Metabase dashboards to end users
- Impact analysis dashboard

## 2019-04-11

### Changed

- Dashboard opens in a new tab

## 2019-04-10

### Added

- Multi-tenant dashboard features

## 2019-04-02

### Fixed

- Dashboard app setting error

## 2019-03-28

### Added

- Access to dashboard via Survey page
- Dashboard shown when Survey is submitted

## 2019-03-19

### Changed

- Changed half a dozen SIC codes which were missing a 0 & validated the SIC code list

## 2018-11-22

### Added

- Wizard added

### Changed

- Landing page now the Wizard

## 2018-10-31

### Fixed

- Fix pagination rendering
- Fix dropdown rendering

## 2018-10-18

### Added

- EU Cookie banner on login page
- Terms & Conditions & Privacy checkbox

### Changed

- Changed validation to accept both positive and negative values for:
  - Gross Profit
  - Operating Profit
  - Net Profit

### Fixed

- Fix validation fails on client, but survey is submitted successfully

## 2018-10-12

### Changed

- Max number of companies displayed to user on 'Survey' page company dropdown

### Fixed

- Fix validation for 'SIC Codes', no longer accepting empty arrays
- Fix confirmation URL received in the 'confirmation email'

### Removed

- Removed second search box from 'Industry' & 'Industry Group' page

## 2018-05-18

### Added

- Tooltips in both 'Company' and 'Survey'

## 2018-05-17

### Fixed

- Fix sorting via API

## 2018-05-16

### Fixed

- Fix API token expiry

## [1.0.0] - 2018-05-11

### Added

- V1.0.0 code - GMC is LIVE :-)
