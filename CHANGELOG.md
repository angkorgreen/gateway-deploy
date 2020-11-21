# Changelog

## v1.2.2

Released date: 21-11-2020

- 69f4c64c feat(packaging): release v1.2.2
- d995390c Merge pull request #45 from angkorgreen/feature/maintenance-phase-1
- f6dffebb feat: automatically format phone number for users list
- 32ff7628 feat: add PhoneNumber::format method
- f7a21c3b fix: create/update staff/farmer/retailer turnoff autocomplete
- dea9fc51 feat: sanatize phone number when create/update staff/farmer/retailer user
- c68c6f41 feat: add PhoneNumber util
- b1b57455 feat: install giggsey/libphonenumber-for-php
- 60398761 feat: add console command to fix users phone number


## v1.2.1

Released date: 16-11-2020

- b6fddd5e feat(packaging): release v1.2.1
- 310aeb9c feat: add .yarnrc
- 010729e4 feat: update package.json
- bb5b1bb8 fix: create/update retailer/farmer form autocomplete

## v1.2.0

Released date: 15-11-2020

- fd5ad2a4 Merge pull request #42 from angkorgreen/feature/revise-report-detail
- cbbb0edb fix: edit report callback
- 8a1b0f12 fix: nameln mixin
- acc377ef feat: update .editorconfig
- 5d29fa23 feat: add MonthlyReport card for list report by year
- 5a24e5c6 draft: new report detail dialog
- 46998181 feat: disable autocomplete and remove email field from create/update farmer/retailer


## v1.1.9

Released date: 1-11-2020

f74fddc8 fix(core): add backward compatibility to to_casl method

## v1.1.8

Released date: 26-10-2020

- 6aa4889b fix(core): fix MobileAuthenticateMiddleware
- 21a5eb86 Merge pull request #13 from angkorgreen/dependabot/npm_and_yarn/prettier-2.1.2
- 31d350e0 Merge pull request #10 from angkorgreen/dependabot/npm_and_yarn/casl/ability-4.1.6
- 7eb34364 feat(core): supplement update to casl/ability
- e75e1699 Merge branch 'master' into develop
- 2851cbb6 Merge pull request #14 from angkorgreen/dependabot/composer/doctrine/dbal-2.10.4
- f1586e2f build(deps): bump doctrine/dbal from 2.10.2 to 2.10.4
- 7ba425bb Merge pull request #15 from angkorgreen/dependabot/composer/laravel/telescope-3.5.1
- 64e4f99b build(deps): bump laravel/telescope from 2.1.7 to 3.5.1
- 816d5e26 Merge pull request #16 from angkorgreen/dependabot/composer/propaganistas/laravel-phone-4.2.5
- b3312973 Merge pull request #17 from angkorgreen/dependabot/composer/laravel-notification-channels/webpush-5.0.3
- d97924b4 Merge pull request #18 from angkorgreen/dependabot/composer/laravel/tinker-2.4.2
- af8667c5 build(deps): bump laravel/tinker from 1.0.10 to 2.4.2
- 8b5c2142 build(deps): bump laravel-notification-channels/webpush
- a836d1fd build(deps): bump propaganistas/laravel-phone from 4.2.4 to 4.2.5
- 978014d0 build(deps-dev): bump prettier from 1.19.1 to 2.1.2
- a7342d51 build(deps): bump @casl/ability from 3.4.0 to 4.1.6

## v1.1.7

Released date: 27-09-2020

- e0ea843 feat(core): add Dependabot to automatically updates the packages
- a9fcee4 fix(core): fix Department not showing director name
- 788fc28 Merge branch 'develop' into master

## v1.1.6

Released date: 13-09-2020

- 788fc280 Merge branch 'develop' into master
- c86a95b1 fix(core): fix public product detail page
- 1e93bdd6 fix(core): fix Product QRCode issues

## v1.1.5

Released date: 13-09-2020

- bac73699 Merge branch 'develop' into master
- ef37042e fix(core): fix OverviewController type
- 5dca786a Merge branch 'develop' into master
- 0dc0e47e fix(core): fix OverviewController
- 72aca273 feat(core): update QRCode preview size
- 4dca61c0 feat(core): add feature to download QRCode
- 954cca44 Merge branch 'feature/export-report-as-excel' into develop
- 2260a69f feat(core): fix Overview wrong sales report calculation
- e83f8f1f Merge branch 'develop' into feature/export-report-as-excel
- 2978ddaf feat(core): add export method to ReportController.php
- cf1e62ad feat(core): add blade template for report
- b6624f6b fix(core): add missing relationship for ReportActivityItem
- 8c5d44d6 feat(core): improve ReportRepository@filter method
- 1e3bfaff feat(core): add base excel export class

## v1.1.4

Released date: 13-09-2020

- 797d5874 feat(core): jobs for calculate reports
- ee5d6f0b fix(core): fixJobs/Reports/CalculateSalesReport no handler registered
- 87ed565e feat(core): add tasg to Jobs/Reports/CreateMonthlyReport
- 9734843c feat(common): update .env.example, set default QUEUE_CONNECTION=redis
- 9216fe7c fix(core): fix default queue driver, changed to redis


## v1.1.3

Released date: 06-09-2020

- 5e7b5657 feat(core): add CalculateSaleReport job and schedule to run daily
- b3ad050f feat(core): dependencies update
- 46481021 feat(core): upgraded maatwebsite/excel to v3.1.21
- 6acd5dc0 feat(core): update RickAstley.php

## v1.1.2

Released date: 23-08-2020

- fix(core): add missing ProductPolicy
- feat(packaging): dependencies update
- fix(packaging):dependencies re-order
- feat(core): fix web app manifest icons

## v1.1.1

Released date: 21-08-2020

- Merge branch 'develop' into master
- feat(core): remove createWebPushSubscription method call
- feat(core): improve RickAstley controller
- feat(core): update 'secret' column of 'oauth_clients' table to be 'nullable'
- feat(core): upgraded laravel/passport to v9.3
- feat(core): upgraded laravel/framework to v6.18.35
- Merge pull request #6 from angkorgreen/hotfix/Important-Laravel-Security-Updates-6.18.27
- feat(core): update 'secret' column of 'oauth_clients' table to be 'nullable'
- feat(core): upgraded laravel/passport to v9.3
- feat(core): upgraded laravel/framework to v6.18.35
- feat(core): remove createWebPushSubscription method call
- feat(core): dependencies update
- feat(core): improve RickAstley controller
- Merge branch 'develop' into master
- feat(common): update badges in README.md
- fix(core): fix TelescopeServiceProvider request tagging

## v1.1.0

Released date: 20-08-2020

- fix(core): fix product page switching
- fix(core): fix product filter not working
- feat(core): add useDebounce hook
- feat(core): revise ProductController permissions
- feat(core): re-touch ReportRepository.php
- feat(common): update README.md
- feat(core): remove GitHub Action
