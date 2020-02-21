# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.8] - 2020-02-21

### Fixed

- Fixed download PDF bug 

## [1.3.7] - 2020-02-20

### Changed

- PDF is split into multiple pages

## [1.3.6] - 2020-02-12

### Added

- Added feature to send dashboard PDFs to Evolutive CRM

## [1.3.5] - 2019-07-12

### Fixed

- Fixed Legal Status - Companies House 'company type' mapping

## [1.3.4] - 2019-06-18

### Changed

- Changed Wizard redirect, clicking 'Cancel' on confirmation message takes user back to step 3

## [1.3.3] - 2019-06-13

### Added

- Added additional client-side validation to Survey

### Fixed

- Fixed Survey GUI validation error message repeats
- Fixed Search not returning results

## [1.3.2] - 2019-06-06

### Changed

- Changed Company service to store longitude & latitude for maps in Metabase

### Fixed

- Fixed GET /Companies/GetCompanyForEdit API endpoint to return SIC code of business

## [1.3.1] - 2019-06-04

### Changed

- Changed 'help' URL
- Changed Survey data confirmation message to appear after data validation

### Fixed

- Fixed POST /Surveys/CreateOrEdit API endpoint Overwrite:TRUE returned error

## [1.3.0] - 2019-05-29

### Added

- Return & pre-fill Company data in 'Company' form from Companies House

## [1.2.4] - 2019-05-14

### Changed

- Changed response text returned by DELETE Company endpoint when a company is not deleted

### Removed

- Remove redundant button at end of Wizard

## [1.2.3] - 2019-05-10

### Added

- Add pop-up to end of survey confirming data quality (GUI only)

### Removed

- Remove 'dashboard' from sidebar menu item

## [1.2.2] - 2019-05-09

### Added

- Link to download PDF dashboard of survey response
- Process to email Metabase dashboards to end users
- Impact analysis dashboard

## [1.2.1] - 2019-04-11

### Changed

- Dashboard opens in a new tab

## [1.2.0] - 2019-04-10

### Added

- Multi-tenant dashboard features

## [1.1.3] - 2019-04-02

### Fixed

- Dashboard app setting error

## [1.1.2] - 2019-03-28

### Added

- Access to dashboard via Survey page
- Dashboard shown when Survey is submitted

## [1.1.1] - 2019-03-19

### Changed

- Changed half a dozen SIC codes which were missing a 0 & validated the SIC code list

## [1.1.0] - 2018-11-22

### Added

- Wizard added

### Changed

- Landing page now the Wizard

## [1.0.6] - 2018-10-31

### Fixed

- Fix pagination rendering
- Fix dropdown rendering

## [1.0.5] - 2018-10-18

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

## [1.0.4] - 2018-10-12

### Changed

- Max number of companies displayed to user on 'Survey' page company dropdown

### Fixed

- Fix validation for 'SIC Codes', no longer accepting empty arrays
- Fix confirmation URL received in the 'confirmation email'

### Removed

- Removed second search box from 'Industry' & 'Industry Group' page

## [1.0.3] - 2018-05-18

### Added

- Tooltips in both 'Company' and 'Survey'

## [1.0.2] - 2018-05-17

### Fixed

- Fix sorting via API

## [1.0.1] - 2018-05-16

### Fixed

- Fix API token expiry

## [1.0.0] - 2018-05-11

### Added

- V1.0.0 code - GMC is LIVE :-)
