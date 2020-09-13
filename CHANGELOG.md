# Changelog

## v1.1.5

Released date: 13-09-2020

bac73699 Merge branch 'develop' into master
ef37042e fix(core): fix OverviewController type
5dca786a Merge branch 'develop' into master
0dc0e47e fix(core): fix OverviewController
72aca273 feat(core): update QRCode preview size
4dca61c0 feat(core): add feature to download QRCode
954cca44 Merge branch 'feature/export-report-as-excel' into develop
2260a69f feat(core): fix Overview wrong sales report calculation
e83f8f1f Merge branch 'develop' into feature/export-report-as-excel
2978ddaf feat(core): add export method to ReportController.php
cf1e62ad feat(core): add blade template for report
b6624f6b fix(core): add missing relationship for ReportActivityItem
8c5d44d6 feat(core): improve ReportRepository@filter method
1e3bfaff feat(core): add base excel export class


## v1.1.4

Released date: 13-09-2020

797d5874 feat(core): jobs for calculate reports
ee5d6f0b fix(core): fixJobs/Reports/CalculateSalesReport no handler registered
87ed565e feat(core): add tasg to Jobs/Reports/CreateMonthlyReport
9734843c feat(common): update .env.example, set default QUEUE_CONNECTION=redis
9216fe7c fix(core): fix default queue driver, changed to redis


## v1.1.3

Released date: 06-09-2020

5e7b5657 feat(core): add CalculateSaleReport job and schedule to run daily
b3ad050f feat(core): dependencies update
46481021 feat(core): upgraded maatwebsite/excel to v3.1.21
6acd5dc0 feat(core): update RickAstley.php

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
