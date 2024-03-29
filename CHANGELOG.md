# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [Released]

## [1.3.17] - 2021-12-03

### Added

- Columns to Companies table for bulk uploads (1366, 1390)
- Automated tests in CI/CD (1430)

### Changed

- Workflow order for CRM survey sending tool (1349)
- Removed unnecessary endpoint from API documentation (1410)
- Password validation code failed - Graciously handle error message (1440)

### Fixed

- Fixed leading 0 sending to CRM (1284)
- Companies House API endpoint definition changed (1439)

## [1.3.16] - 2021-07-15

### Added

- Weekly summary report

### Changed

- Email for notifications refactored code
- Companies survey error text - clarify text box
- Impact analysis white container now surrounds entire dashboard
- Impact analysis enhancements

## [1.3.15] - 2021-05-14

### Changed

- Re-send activation email URL text on home page
- Re-send activation description text
- Re-send activation error message text
- Companies survey text - clarify recipient 'on behalf of' 

## [1.3.14] - 2021-05-04

### Fixed

- Fixed sorting by 'roles' bug

## [1.3.13] - 2021-04-28

### Added

- Added tool to identify unsent emails/pdf to CRM and resend them
- Email debugging feature

## [1.3.12] - 2021-04-01

### Fixed

- Fixed transfer to CRM bug

## [1.3.11] - 2020-05-19

### Changed

- Survey - ordering showing most recent surveys first

## [1.3.10] - 2020-05-15

### Changed

- Email validation for notifications
- CRM Settings form - autocomplete

## [1.3.9] - 2020-03-30

### Added

- Added feature to send notifications to admin when a new survey has been submitted

### Fixed

- Fixed dashboard sending for edited surveys

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
