# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v8.2.1](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v8.2.1) (2022-08-23)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v8.2.0...v8.2.1)

### Fixed

- Fix puppet-strings documentation [\#1363](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1363) ([ekohl](https://github.com/ekohl))
- \(GH-1360\) Reverting REFERENCE.md changes [\#1361](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1361) ([pmcmaw](https://github.com/pmcmaw))
- Only require password when used [\#1356](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1356) ([arjenz](https://github.com/arjenz))

## [v8.2.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v8.2.0) (2022-08-23)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v8.1.0...v8.2.0)

### Added

- pdksync - \(GH-cat-11\) Certify Support for Ubuntu 22.04 [\#1355](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1355) ([david22swan](https://github.com/david22swan))
- \(MODULES-11251\) Add support for backup provider "pg\_dump" [\#1319](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1319) ([fraenki](https://github.com/fraenki))

### Fixed

- Ensure multiple postgresql::server::recovery resources can be defined [\#1348](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1348) ([Deroin](https://github.com/Deroin))

## [v8.1.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v8.1.0) (2022-07-21)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v8.0.0...v8.1.0)

### Added

- Fix service status detection on Debian-based OSes [\#1349](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1349) ([arjenz](https://github.com/arjenz))
- \(FM-8971\) allow deferred function for role pwd [\#1347](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1347) ([tvpartytonight](https://github.com/tvpartytonight))
- Set version for Fedora 36 [\#1345](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1345) ([lweller](https://github.com/lweller))
- Add Red Hat Enterprise Linux 9 support [\#1303](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1303) ([ekohl](https://github.com/ekohl))

### Fixed

- \(GH-1352\) - Updating postgresql service version on SLES  [\#1353](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1353) ([pmcmaw](https://github.com/pmcmaw))
- Respect $service\_status on Red Hat-based distros [\#1351](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1351) ([ekohl](https://github.com/ekohl))
- Add version for Ubuntu 22.04 [\#1350](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1350) ([arjenz](https://github.com/arjenz))
- README.md: correct postgresql\_conn\_validator example [\#1332](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1332) ([bastelfreak](https://github.com/bastelfreak))
- pdksync - \(GH-iac-334\) Remove Support for Ubuntu 14.04/16.04 [\#1331](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1331) ([david22swan](https://github.com/david22swan))
- Remove unused variable in reload.pp [\#1327](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1327) ([ekohl](https://github.com/ekohl))
- Use systemctl reload on EL 7 and higher [\#1326](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1326) ([ekohl](https://github.com/ekohl))

## [v8.0.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v8.0.0) (2022-03-03)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.5.0...v8.0.0)

### Changed

- Support setting default\_privileges on all schemas [\#1298](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1298) ([fish-face](https://github.com/fish-face))

### Added

- add default version for Fedora 35 [\#1317](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1317) ([jflorian](https://github.com/jflorian))
- add scram-sha-256 support [\#1313](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1313) ([fe80](https://github.com/fe80))
- add support for Ubuntu Hirsute and Impish [\#1312](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1312) ([nicholascioli](https://github.com/nicholascioli))
- Allow systemd to mask postgresql service file [\#1310](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1310) ([kim-sondrup](https://github.com/kim-sondrup))
- Make ::contrib a noop on OSes without a contrib package [\#1309](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1309) ([carlosduelo](https://github.com/carlosduelo))
- pdksync - \(IAC-1753\) - Add Support for AlmaLinux 8 [\#1308](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1308) ([david22swan](https://github.com/david22swan))
- MODULES-11201: add service\_name for Ubuntu 18.04 and later [\#1306](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1306) ([moritz-makandra](https://github.com/moritz-makandra))
- pdksync - \(IAC-1751\) - Add Support for Rocky 8 [\#1305](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1305) ([david22swan](https://github.com/david22swan))
- Default privileges support schemas [\#1300](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1300) ([fish-face](https://github.com/fish-face))
- Support target\_role in default\_privileges [\#1297](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1297) ([fish-face](https://github.com/fish-face))

### Fixed

- pdksync - \(IAC-1787\) Remove Support for CentOS 6 [\#1324](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1324) ([david22swan](https://github.com/david22swan))
- Fix python package name in RHEL/CentOS 8 [\#1316](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1316) ([kajinamit](https://github.com/kajinamit))
- Drop further code for Debian 6 and Ubuntu 10 [\#1307](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1307) ([ekohl](https://github.com/ekohl))

## [v7.5.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.5.0) (2021-09-28)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.4.1...v7.5.0)

### Added

- Use Puppet-Datatype Sensitive for Passwords [\#1279](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1279) ([cocker-cc](https://github.com/cocker-cc))

### Fixed

- \(IAC-1598\) - Remove Support for Debian 8 [\#1302](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1302) ([david22swan](https://github.com/david22swan))
- Inline file contents in the catalog [\#1299](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1299) ([ekohl](https://github.com/ekohl))
- Fix changing default encoding [\#1296](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1296) ([smortex](https://github.com/smortex))

## [v7.4.1](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.4.1) (2021-08-25)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.4.0...v7.4.1)

### Fixed

- \(maint\) Allow stdlib 8.0.0 [\#1293](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1293) ([smortex](https://github.com/smortex))

## [v7.4.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.4.0) (2021-08-24)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.3.0...v7.4.0)

### Added

- pdksync - \(IAC-1709\) - Add Support for Debian 11 [\#1288](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1288) ([david22swan](https://github.com/david22swan))

### Fixed

- drop code for Debian 6/7 and Ubuntu 10.04/12.04 [\#1290](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1290) ([evgeni](https://github.com/evgeni))

## [v7.3.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.3.0) (2021-08-03)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.2.0...v7.3.0)

### Added

- MODULES-11049 - Implement default privileges changes [\#1267](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1267) ([mtancoigne](https://github.com/mtancoigne))

### Fixed

- Do not add version component to repo definition [\#1282](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1282) ([weastur](https://github.com/weastur))
- \(MODULES-8700\) Autorequire the service in postgresql\_psql [\#1276](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1276) ([ekohl](https://github.com/ekohl))

## [v7.2.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.2.0) (2021-05-24)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.1.0...v7.2.0)

### Added

- \(MODULES-11069\) add default version for fedora 34 [\#1272](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1272) ([lweller](https://github.com/lweller))
- MODULES-11047 - Allow managing rights for PUBLIC role [\#1266](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1266) ([mtancoigne](https://github.com/mtancoigne))

## [v7.1.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.1.0) (2021-04-12)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.0.3...v7.1.0)

### Added

- Add new common repo which contains add-ons [\#1190](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1190) ([jorhett](https://github.com/jorhett))

## [v7.0.3](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.0.3) (2021-04-12)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.0.2...v7.0.3)

## [v7.0.2](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.0.2) (2021-03-15)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.0.1...v7.0.2)

### Fixed

- \(MODULES-10957\) Override the set\_sensitive\_parameters method [\#1258](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1258) ([sheenaajay](https://github.com/sheenaajay))

## [v7.0.1](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.0.1) (2021-03-08)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v7.0.0...v7.0.1)

### Fixed

- Ensure port is a string in psql command [\#1253](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1253) ([ekohl](https://github.com/ekohl))

## [v7.0.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v7.0.0) (2021-03-04)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.10.2...v7.0.0)

### Changed

- pdksync - \(MAINT\) Remove SLES 11 support [\#1247](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1247) ([sanfrancrisko](https://github.com/sanfrancrisko))
- pdksync - \(MAINT\) Remove RHEL 5 family support [\#1246](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1246) ([sanfrancrisko](https://github.com/sanfrancrisko))
- pdksync - Remove Puppet 5 from testing and bump minimal version to 6.0.0 [\#1238](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1238) ([carabasdaniel](https://github.com/carabasdaniel))

### Added

- Add DNF module management [\#1239](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1239) ([ekohl](https://github.com/ekohl))

## [v6.10.2](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.10.2) (2021-02-22)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.10.1...v6.10.2)

### Fixed

- Fix command shell escaping [\#1240](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1240) ([DavidS](https://github.com/DavidS))

## [v6.10.1](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.10.1) (2021-02-09)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.10.0...v6.10.1)

### Fixed

- Also perform systemd daemon-reload on Puppet 6.1+ [\#1233](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1233) ([ekohl](https://github.com/ekohl))

## [v6.10.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.10.0) (2021-02-08)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.9.0...v6.10.0)

### Added

- Set default PostgreSQL version for FreeBSD [\#1227](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1227) ([olevole](https://github.com/olevole))
- Clean up globals logic to support CentOS 8 stream [\#1225](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1225) ([ekohl](https://github.com/ekohl))

### Fixed

- \(bug\) fix systemd daemon-reload order when updating service files [\#1230](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1230) ([sheenaajay](https://github.com/sheenaajay))
- Fix postgresql::sql task when password is not set [\#1226](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1226) ([smortex](https://github.com/smortex))

## [v6.9.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.9.0) (2021-01-18)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.8.0...v6.9.0)

### Added

- pdksync - \(feat\) -  Add support for puppet 7 [\#1215](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1215) ([daianamezdrea](https://github.com/daianamezdrea))
- Manage postgresql\_conf\_path file permissions [\#1199](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1199) ([ekohl](https://github.com/ekohl))

### Fixed

- \(maint\) updated defaults for rhel7 policycoreutils [\#1212](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1212) ([sheenaajay](https://github.com/sheenaajay))
- \(IAC-1189\) - Fix for SLES 15 SP 1 and later [\#1209](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1209) ([david22swan](https://github.com/david22swan))
- Change - Use systemd drop-in directory for unit overrides [\#1201](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1201) ([blackknight36](https://github.com/blackknight36))

## [v6.8.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.8.0) (2020-09-28)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.7.0...v6.8.0)

### Added

- add hostgssenc type to pg\_hba rules [\#1195](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1195) ([osijan](https://github.com/osijan))
- Allow removal of config\_entries via main class [\#1187](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1187) ([ekohl](https://github.com/ekohl))

### Fixed

- Fix contrib package name under debian 10 [\#1188](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1188) ([neomilium](https://github.com/neomilium))

## [v6.7.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.7.0) (2020-08-28)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.6.0...v6.7.0)

### Added

- pdksync - \(IAC-973\) - Update travis/appveyor to run on new default branch `main` [\#1182](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1182) ([david22swan](https://github.com/david22swan))

### Fixed

- Invert psql/package dependency logic [\#1179](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1179) ([raphink](https://github.com/raphink))

## [v6.6.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.6.0) (2020-06-02)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.5.0...v6.6.0)

### Added

- \(IAC-746\) - Add ubuntu 20.04 support [\#1172](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1172) ([david22swan](https://github.com/david22swan))

### Fixed

- Fix custom port in extension [\#1165](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1165) ([Vampouille](https://github.com/Vampouille))

## [v6.5.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.5.0) (2020-05-13)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.4.0...v6.5.0)

### Added

- service\_ensure =\> true is now an allowed value \(aliased to running\)  [\#1167](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1167) ([binford2k](https://github.com/binford2k))
- Finish conversion of `postgresql_acls_to_resources_hash` function [\#1163](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1163) ([alexjfisher](https://github.com/alexjfisher))
- Finish conversion of `postgresql_escape` function [\#1162](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1162) ([alexjfisher](https://github.com/alexjfisher))
- Finish conversion of `postgresql_password` function [\#1161](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1161) ([alexjfisher](https://github.com/alexjfisher))
- Allow usage of grant and role when not managing postgresql::server [\#1159](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1159) ([tuxmea](https://github.com/tuxmea))
- Add version configs for SLES 12 SP 3 to 5 [\#1158](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1158) ([XnS](https://github.com/XnS))
- Add extra parameter "extra\_systemd\_config"  [\#1156](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1156) ([veninga](https://github.com/veninga))

### Fixed

- \(MODULES-10610\) Use correct lower bound for concat version [\#1160](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1160) ([ghoneycutt](https://github.com/ghoneycutt))

## [v6.4.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.4.0) (2020-03-17)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.3.0...v6.4.0)

### Added

- Add Fedora 31 compatibility [\#1141](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1141) ([blackknight36](https://github.com/blackknight36))
- feat: enable different database resource name in extension [\#1136](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1136) ([jfroche](https://github.com/jfroche))
- pdksync - \(FM-8581\) - Debian 10 added to travis and provision file refactored [\#1130](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1130) ([david22swan](https://github.com/david22swan))
- Puppet 4 functions [\#1129](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1129) ([binford2k](https://github.com/binford2k))

### Fixed

- Fix incorrectly quoted GRANT cmd on functions [\#1150](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1150) ([olifre](https://github.com/olifre))
- Correct versioncmp logic in config.pp [\#1137](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1137) ([boydtom](https://github.com/boydtom))
- Treat $version as an integer for comparison, defaults to string [\#1135](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1135) ([boydtom](https://github.com/boydtom))
- Allow usage of PUBLIC role [\#1134](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1134) ([Vampouille](https://github.com/Vampouille))
- fix missing systemd override config for EL8 \(CentOS and RHEL\) [\#1131](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1131) ([david-barbion](https://github.com/david-barbion))

## [v6.3.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.3.0) (2019-12-18)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.2.0...v6.3.0)

### Added

- Add support for granting privileges on functions [\#1118](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1118) ([crispygoth](https://github.com/crispygoth))
- \(FM-8679\) - Support added for CentOS 8 [\#1117](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1117) ([david22swan](https://github.com/david22swan))
- MODULES-10041 - allow define password\_encryption for version above 10 [\#1111](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1111) ([k2patel](https://github.com/k2patel))

### Fixed

- Remove duplicate REFERENCE.md file with strange unicode character at end of filename [\#1108](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1108) ([nudgegoonies](https://github.com/nudgegoonies))

## [v6.2.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.2.0) (2019-09-12)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.1.0...v6.2.0)

### Added

- FM-8408 - add support on Debian10 [\#1103](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1103) ([lionce](https://github.com/lionce))
- Fix/directory defined twice [\#1089](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1089) ([arcenik](https://github.com/arcenik))
- Adding SLES 15 [\#1087](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1087) ([msurato](https://github.com/msurato))
- \(FM-7500\) conversion to use litmus [\#1081](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1081) ([tphoney](https://github.com/tphoney))

### Fixed

- \(MODULES-9658\) - custom ports are not labeled correctly [\#1099](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1099) ([blackknight36](https://github.com/blackknight36))
- Fix: When assigning a tablespace to a database, no equal sign is needed in the query [\#1098](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1098) ([biertie](https://github.com/biertie))
- Grant all tables in schema fixup [\#1096](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1096) ([georgehansper](https://github.com/georgehansper))
- \(MODULES-9219\) - puppetlabs-postgresql : catalog compilation fails when the service command is not installed [\#1093](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1093) ([blackknight36](https://github.com/blackknight36))

## [v6.1.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.1.0) (2019-06-04)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/v6.0.0...v6.1.0)

### Added

- \(FM-8031\) Add RedHat 8 support [\#1083](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1083) ([eimlav](https://github.com/eimlav))

## [v6.0.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/v6.0.0) (2019-05-14)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.12.1...v6.0.0)

### Changed

- pdksync - \(MODULES-8444\) - Raise lower Puppet bound [\#1070](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1070) ([david22swan](https://github.com/david22swan))
- \(maint\) remove inconsistent extra variable [\#1044](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1044) ([binford2k](https://github.com/binford2k))

### Added

- Add Fedora 30 compatibility [\#1067](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1067) ([blackknight36](https://github.com/blackknight36))
- Include EL8 version for config checks [\#1060](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1060) ([ehelms](https://github.com/ehelms))

### Fixed

- Support current version of puppetlabs/apt. [\#1073](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1073) ([pillarsdotnet](https://github.com/pillarsdotnet))
- change username/group/datadir defaults for FreeBSD [\#1063](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1063) ([olevole](https://github.com/olevole))

## [5.12.1](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.12.1) (2019-02-14)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.12.0...5.12.1)

### Fixed

- \(FM-7811\) - Use postgresql 9.4 for SLES 11 sp4 [\#1057](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1057) ([david22swan](https://github.com/david22swan))
- \(MODULES-8553\) Further cleanup for package tag issues [\#1055](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1055) ([HelenCampbell](https://github.com/HelenCampbell))

## [5.12.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.12.0) (2019-02-01)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.11.0...5.12.0)

### Added

- \(MODULES-3804\) Fix sort order of pg\_hba\_rule entries [\#1040](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1040) ([olavmrk](https://github.com/olavmrk))

### Fixed

- \(MODULES-8553\) Fix dependency on apt by explicitly using 'puppetlabs-postgresql' as tag [\#1052](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1052) ([HelenCampbell](https://github.com/HelenCampbell))
- \(MODULES-8352\) Don't use empty encoding string on initdb [\#1043](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1043) ([binford2k](https://github.com/binford2k))
- pdksync - \(FM-7655\) Fix rubygems-update for ruby \< 2.3 [\#1042](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1042) ([tphoney](https://github.com/tphoney))

## [5.11.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.11.0) (2018-11-21)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.10.0...5.11.0)

### Added

- Add postgis support for postgres 10 [\#1032](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1032) ([smussie](https://github.com/smussie))

### Fixed

- Strip quotes from role names [\#1034](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1034) ([jstuart](https://github.com/jstuart))
- Ignore .psqlrc so output is clean and doesn't break Puppet [\#1021](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1021) ([flaviogurgel](https://github.com/flaviogurgel))
- Change initdb option '--xlogdir' to '-X' for PG10 compatibility [\#976](https://github.com/puppetlabs/puppetlabs-postgresql/pull/976) ([fcanovai](https://github.com/fcanovai))

## [5.10.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.10.0) (2018-09-27)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.9.0...5.10.0)

### Added

- pdksync - \(MODULES-6805\) metadata.json shows support for puppet 6 [\#1026](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1026) ([tphoney](https://github.com/tphoney))

## [5.9.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.9.0) (2018-09-06)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.8.0...5.9.0)

### Added

- pdksync - \(MODULES-7705\) - Bumping stdlib dependency from \< 5.0.0 to \< 6.0.0 [\#1018](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1018) ([pmcmaw](https://github.com/pmcmaw))

## [5.8.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.8.0) (2018-08-06)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.7.0...5.8.0)

### Added

- metadata.json: bump allowed version of puppetlabs-apt to 6.0.0 [\#1012](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1012) ([mateusz-gozdek-sociomantic](https://github.com/mateusz-gozdek-sociomantic))

## [5.7.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.7.0) (2018-07-19)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.6.0...5.7.0)

### Added

- \(MODULES-7479\) Update postgresql to support Ubuntu 18.04 [\#1005](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1005) ([david22swan](https://github.com/david22swan))
- \(MODULES-6542\) - Adding SLES 11 & 12 to metadata [\#1001](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1001) ([pmcmaw](https://github.com/pmcmaw))

### Fixed

- \(MODULES-7479\) Ensure net-tools is installed when testing on Ubuntu 18.04 [\#1006](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1006) ([david22swan](https://github.com/david22swan))
- \(MODULES-7460\) - Updating grant table to include INSERT privileges [\#1004](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1004) ([pmcmaw](https://github.com/pmcmaw))
- Fix packages choice for ubuntu 17.10 [\#1000](https://github.com/puppetlabs/puppetlabs-postgresql/pull/1000) ([fflorens](https://github.com/fflorens))

## [5.6.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.6.0) (2018-06-20)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.5.0...5.6.0)

### Changed

- Fix creation of recovery.conf file when recovery configuration is not specified [\#995](https://github.com/puppetlabs/puppetlabs-postgresql/pull/995) ([cdloh](https://github.com/cdloh))

### Added

- Add compatibility for Fedora 28 [\#994](https://github.com/puppetlabs/puppetlabs-postgresql/pull/994) ([jflorian](https://github.com/jflorian))
- \(MODULES-5994\) Add debian 9 [\#992](https://github.com/puppetlabs/puppetlabs-postgresql/pull/992) ([hunner](https://github.com/hunner))
- Adding default Postgresql version for Ubuntu 18.04 [\#981](https://github.com/puppetlabs/puppetlabs-postgresql/pull/981) ([lutaylor](https://github.com/lutaylor))

### Fixed

- Fix quoting on schema owners [\#979](https://github.com/puppetlabs/puppetlabs-postgresql/pull/979) ([hasegeli](https://github.com/hasegeli))

## [5.5.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.5.0) (2018-04-06)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.4.0...5.5.0)

### Added

- Parameters `roles`, `config_entires`, and `pg_hba_rules` to `postgresql::server` for hiera [\#950](https://github.com/puppetlabs/puppetlabs-postgresql/pull/950) ([ekohl](https://github.com/ekohl))

## [5.4.0](https://github.com/puppetlabs/puppetlabs-postgresql/tree/5.4.0) (2018-03-22)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-postgresql/compare/5.3.0...5.4.0)

### Added

- \(MODULES-6330\) PDK convert 1.4.1 [\#961](https://github.com/puppetlabs/puppetlabs-postgresql/pull/961) ([pmcmaw](https://github.com/pmcmaw))
- Parameter `ensure` on `postgresql::server::grant` and `postgresql::server::database_grant` [\#891](https://github.com/puppetlabs/puppetlabs-postgresql/pull/891) ([georgehansper](https://github.com/georgehansper))

### Fixed

- Documentation error, `reassign_owned_by` uses `*_role` not `*_owner`. [\#958](https://github.com/puppetlabs/puppetlabs-postgresql/pull/958) ([computermouth](https://github.com/computermouth))

## 5.3.0
### Summary
Implements rubocop changes within the module, alongside other smaller changes.

#### Added
- ensure=>absent added to postgresql::server:role.
- Support added for Fedora 27.
- scram-sha-256 added as a valid ph_hba_rule auth method.
- 9.6 settings inherited for later PgSQL versions on FreeBSD.
- A require has been added for puppet.

#### Changed
- Changes made to avoid the useless loading of files by augeas.
- Modulesync changes.
- psql_path defaulted to postgresql::server::psql_path.
- Rubocop changes have been made.

#### Removed
- Debian 9 support deprecated.

## Supported Release 5.2.1
### Summary
Bug fix for issue introduced in 5.2.0

#### Fixed
- issue where the module was attempting to install extensions before a database was available. ([SERVER-2003](https://tickets.puppetlabs.com/browse/SERVER-2003))

## Supported Release 5.2.0
### Summary
Adds several new features including some work around OS support. Also includes a couple of fixes to tests and the removal of unsupported Ubuntu versions.

#### Added
- Added default postgresql version of Ubuntu 17.4 version to the globals.pp file.
- Fedora 26 provides postgresql-server version 9.6 by default - Added support to manifests/globals.pp to avoid puppet failures on Fedora 26 nodes.
- Use postgresql 9.6 for the newest SLES and openSUSE releases.
- Enhanced --data-checksums on initdb.
- Added support for Debian version 9.
- Added a `version` parameter.

#### Changed
- Replaced validate_re calls with puppet datatype `Pattern` and is_array calls with puppet datatype `Array`.
- Installation method for apt in the spec_helper_acceptance, this is a temporary workaround due to issues with module installation.

#### Fixed
- Updated spec tests to remove deprecation warnings.
- Docs formatting.
- Pass default_connect_settings to validate service ([MODULES-4682](https://tickets.puppetlabs.com/browse/MODULES-4682))
- Rocket Alignment for Lint.
- Fixed changes in error messages in tests ([MODULES-5378](https://tickets.puppetlabs.com/browse/MODULES-5378))

#### Removed
- Removed unsupported Ubuntu versions 10.04 and 12.04 ([MODULES-5501](https://tickets.puppetlabs.com/browse/MODULES-5501))
- Removed unsupported Debian version 6.
- Removed numeric order override.

## Supported Release 5.1.0
### Summary
This release includes Japanese translations for internationalization, Puppet 5 support, implementation of defined type postgresql::server::reassign_owned_by.

#### Features
- Updating translations for readmes/README_ja_JP.md
- add defined type postgresql::server::reassign_owned_by
- Allow order parameter to be string value
- prep for puppet 5 ([MODULES-5144](https://tickets.puppetlabs.com/browse/MODULES-5144))
- add data_checksums option to initdb
- parameter ensure of custom resource postgresql_replication_slot is not documented ([MODULES-2989](https://tickets.puppetlabs.com/browse/MODULES-2989))

#### Bug Fixes
- Adding a space for header formatting
- use https for apt.postgresql.org repo
- msync puppet 5 and ruby 2.4 ([MODULES-5197](https://tickets.puppetlabs.com/browse/MODULES-5187))
- Only run test on postgresql >= 9.0 ([FM-6240](https://tickets.puppetlabs.com/browse/FM-6240))
- Fix Ruby 2.4 deprecation in postgresql_acls_to_resources_hash

## Supported Release 5.0.0
### Summary
This **major** release dropped support for Puppet 3 and PostgreSQL 8.x, added Puppet 4 data types, and deprecated the validate_db_connection type.

#### Added
- `locales/` directory, .pot file, and i18n `config.yaml`. ([FM-6116](https://tickets.puppet.com/browse/FM-6116))
- `update_password` parameter to toggle password management per role.
- **Puppet 4** type validation.
- new `postgresql_conn_validator` custom type and deprecated `validate_db_connection`. ([MODULES-1394](https://tickets.puppet.com/browse/MODULES-1394))

#### Changed
- default postgis versions in postgresql::globals to use newer versions.
- puppetlabs-concat and puppetlabs-apt dependencies to use latest versions. ([MODULES-4906](https://tickets.puppet.com/browse/MODULES-4906), [MODULES-4947](https://tickets.puppet.com/browse/MODULES-4947))
- default value for `log_line_prefix` to `undef`.
- `listen_addresses` default value to 'localhost'. Allows for it to be set independently of a class declaration.
- use of stdlib validate_* functions. They have been removed in favor of Puppet 4 type validation.
- lower Puppet dependency in metadata to 4.7.0. ([MODULES-4826](https://tickets.puppet.com/browse/MODULES-4826))

#### Fixed
- deprecated apt::source parameters(`key`,`key_source`, & `include_src`).
- default SUSE parameters. ([MODULES-4598](https://tickets.puppet.com/browse/MODULES-4598))
- use of force parameter on concat resources.

## Supported Release 4.9.0
### Summary
This release adds several types and, among other bugs, fixes an issue with the yum URL.

#### Features
- Modifying ownership of databases and schemas now available (MODULES-3247)
- Use `module_workdir` to specify a custom directory in which to execute psql commands
- `grant_role` and `grant` types added!
- Support for parallel unit testing (parallel_tests)
- Override download/installation repo URL with `repo_baseurl`
- Set your timezone with `timezone`
- Grant privileges on LANGUAGEs
- Added support for Debian Stretch and Ubuntu Yakkety Yak

#### Bugfixes
- Usernames and passwords are now converted to strings before password hash is created
- Specify default database name if it is not the username
- Update to yum repo
- Schema name conflicts fix

## Supported Release 4.8.0
### Summary
This release primarily fixes an issue with `postgresql_conf` values of ipaddresses being considered floats and not getting quoted.

#### Features
- Add `default_connect_settings` parameter to `postgresql::server`
- Running under strict variables is now supported
- Add timestamps into logs by default

#### Bugfixes
- Obscure password in postgresql\_psql type
- Fix ip address quoting in postgresql\_conf type
- Fix handling of systemd service on Ubuntu
- Mark log_min_duration_statement setting as requiring a service restart
- Add fixes for Fedora 23, Fedora 24, FreeBSD, OpenBSD
- Fix environment handling to avoid "Overriding environment setting" message
- Work around PUP-6385, using empty arrays instead of undef when specifying resource relationships
- README editorial pass
- Reduce whitespace in templates
- Update build/test infrastructure

## Supported Release 4.7.1
### Summary
This release contains some bugfixes and documentation updates.

#### Bugfixes
- (MODULES-3024) Quote database objects when creating databases.
- Properly escape case where password ends with '$'.
- Fixes password change when postgres is configure to non-standard port.
- Unpins concat dependency to be able to use concat 2.x.
- Workaround to fix installing on Amazon Linux.
- Fixes proper defaulting of `$service_provider` parameter.
- Fixes postgres server init script naming on Amazon Linux.
- Fixes service reload parameter on Arch Linux.
- Adds missing onlyif_function to sequence grant code.
- Fixes to the markdown of the README.

## Supported Release 4.7.0
### Summary
A release with a considerable amount of new features, including remote db support and several platform support updates. Various bugfixes including several to address warnings and a sizable README update.

#### Features
- Remote DB support - Connection-settings allows a hash of options that can be used when connecting to a remote DB.
- Debian 8 support.
- Updated systemd-override to support fedora and CentOS paths.
- Adds the ability to define the extension name separately from the title of the resource, which allows you to add the extension to more than one database.
- Added parameter to disable automatic service restarts on config changes.
- Ubuntu 15.10 compatibility.
- OpenBSD version is now 9.4.
- Added .gitattributes to maintain line endings for .sh and .rb files.
- Adds default postgis version for 9.5.
- Allows float postgresql_conf values.
- Schedule apt update after install of repo.

#### Bugfixes
- Fixed systemd-override for RedHat systems with unmanaged Yum repos.
- Removed inherits postgresql::params.
- Multi-node tests are now not ran by default.
- Change apt::pin to apt_postgresql_org to prevent error message.
- Removed syntax error near UTF8.
- Removal of extra blanks and backslashes in README.
- Double quotes now used around database name to prevent syntax error.
- Removes ruby 1.8.7 and puppet 2.7 from travis-ci jobs.
- Fixed paths to work on Amazon Linux.
- Fixed quotes around locale options.
- Huge README update.
- Update to use current msync configs.
- Fixes postgresql::server acceptance test descriptions.

## Supported Release 4.6.1
###Summary

Small release for support of newer PE versions. This increments the version of PE in the metadata.json file.

## 2015-09-01 - Supported Release 4.6.0
### Summary
This release adds a proxy feature for yum, Postgis improvements, and decoupling pg_hba_rule from postgresql::server.

#### Features
- Support setting a proxy for yum operations
- Allow for undefined PostGIS version
- Decouple pg_hba_rule from postgresql::server

#### Bugfixes
- Fix postgis default package name on RedHat

## 2015-07-27 - Supported Release 4.5.0
### Summary
This release adds sequence grants, some postgresql 9.4 fixes, and `onlyif` to
the psql resource.

### Features
- Add `onlyif` parameter to `postgresql_psql`
- Add unsupported compatibility with Ubuntu 15.04
- Add unsupported compatibility with SLES 11/12 and OpenSuSE 13.2
- Add `postgresql::server::grant::onlyif_exists` attribute
- Add `postgresql::server::table_grant::onlyif_exists` attribute
- Add granting permissions on sequences

### Bugfixes
- Added docs for `postgresql::server::grant`
- Fix `pg_hba_conf_defaults => false` to not disable ipv4/ipv6 acls
- Fix 9.4 for `postgresql::server::pg_hba_rule`

## 2015-07-07 - Supported Release 4.4.2
### Summary
This release fixes a bug introduced in 4.4.0.

#### Bugfixes
- Fixes `withenv` execution under Puppet 2.7. (MODULES-2185)

## 2015-07-01 - Supported Release 4.4.1
### Summary
This release fixes RHEL 7 & Fedora with manage_package_repo switched on.

#### Bugfixes
- Ensure manage_package_repo variable is in scope for systemd-override file for RHEL7

## 2015-06-30 - Supported Release 4.4.0
### Summary
This release has several new features, bugfixes, and test improvements.

#### Features
- Adds a resource to manage recovery.conf.
- Adds a parameter that allows the specification of a validate connection script in `postgresql::client`.
- Adds support for plpython package management.
- Adds support for postgresql-docs management.
- Adds ability to make `postgresql::server::schema` titles unique. (MODULES-2049)
- Updates puppetlabs-apt module dependency to support version 2.1.0.

#### Bugfixes
- Fix `postgresql_psql` parameter ordering to work on OpenBSD with Future Parser
- Fix setting postgres role password (MODULES-1869)
- Fix execution command with puppet <3.4 (MODULES-1923)
- Fix Puppet.newtype deprecation warning (MODULES-2007)
- Fix systemd override for manage_repo package versions
- Fix Copy snakeoil certificate and key instead of symlinking

#### Test Improvements
- Allows setting BEAKER and BEAKER_RSPEC versions via environment variables.
- Enables Unit testing on Travis CI with Puppet 4.
- Cleans up spec_helper_acceptance.rb to use new puppet_install_helper gem.

## 2015-03-24 - Supported Release 4.3.0
### Summary
This release fixes compatibility with Puppet 4 and removes opportunities for local users to view the postgresql password. It also adds a new custom resource to aid in managing replication.

#### Features
- Add `postgresql::server::logdir` parameter to manage the logdir
- Add `environment` parameter to `postgresql_psql`
- Add `postgresql_replication_slot` custom resource

#### Bugfixes
- Fix for Puppet 4
- Don't print postgresql\_psql password in command
- Allow `postgresql::validate_db_connection` for more than one host+port+database combo
- Fix service command on Debian 8 and up
- Fix `postgresql::server::extension` to work with custom user/group/port
- Fix `postgresql::server::initdb` to work with custom user/group/port
- Fix changing template1 encoding
- Fix default `postgresql::server::grant::object_name` value
- Fix idempotency of granting all tables in schema with `puppet::server::grant`
- Fix lint warnings
- Fix apt key to use 40 character key and bump puppetlabs-apt to >= 1.8.0 < 2.0.0


##2015-03-10 - Supported Release 4.2.0
###Summary

This release has several new features including support for server extensions, improved grant support, and a number of bugfixes.

####Features
- Changes to support OpenBSD
- Add `service_reload` parameter to `postgresql::server`
- Add `comment` parameter to `postgresql::server::database` (MODULES-1153)
- Add `postgresql::server::extension` defined type
- Add postgresql versions for utopic and jessie
- Update `postgresql::server::grant` to support 'GRANT SCHEMA' and 'ALL TABLES IN SCHEMA'

####Bugfixes
- Lint cleanup
- Remove outdated upgrade info from README
- Use correct TCP port when checking password
- Create role before database
- Fix template1 encoding on Debian
- Require server package before user permissions
- Fix `service_status` default for FreeBSD to allow PostgreSQL to start the first run
- Fix invalid US-ASCII byte sequence in `postgresql::server::grant` comments
- Reverted to default behavior for Debian systems as `pg_config` should not be overwritten (MODULES-1485)

##2014-11-04 - Supported Release 4.1.0
###Summary

This release adds the ability to change the PGDATA directory, and also includes documentation and test updates, future parser support, and a few other new features.

####Features
- Future parser support
- Documentation updates
- Test updates
- Add a link from `/etc/sysconfig/pgsql/postgresql-${version}` to `/etc/sysconfig/pgsql/postgresql` to support init scripts from the postgresql.org repo
- Add support for changing the PGDATA directory
- Set default versions for Fedora 21 and FreeBSD

##2014-09-03 - Supported Release 4.0.0
###Summary

This release removes the uninstall ability from the module, removes the firewall
management, overhauls all of the acceptance testing, as well as adds better
support for SuSE and Fedora.

###Backwards Incompatible changes.

- Uninstall code removal.
- Firewall management for Postgres.
- Set manage_pg_ident_conf to true.

####Uninstallation removal

We rely heavily on the ability to uninstall and reinstall postgres throughout
our testing code, testing features like "can I move from the distribution
packages to the upstream packages through the module" and over time we've
learnt that the uninstall code simply doesn't work a lot of the time.  It
leaves traces of postgres behind or fails to remove certain packages on Ubuntu,
and generally causes bits to be left on your system that you didn't expect.

When we then reinstall things fail because it's not a true clean slate, and
this causes us enormous problems during test.  We've spent weeks and months
working on these tests and they simply don't hold up well across the full range
of PE platforms.

Due to all these problems we've decided to take a stance on uninstalling in
general.  We feel that in 2014 it's completely reasonable and normal to have a
good provisioning pipeline combined with your configuration management and the
"correct" way to uninstall a fully installed service like postgresql is to
simply reprovision the server without it in the first place.  As a general rule
this is how I personally like to work and I think is a good practice.

####I'm not OK with this!

We understand that there are environments and situations in which it's not easy
to do that.  What if you accidently deployed Postgres on 100,000 nodes?  In the
future we're going to take a look at building some example 'profiles' to be
found under examples/ within this module that can uninstall postgres on popular
platforms.  These can be modified and used in your specific case to uninstall
postgresql.  They will be much more brute force and reliant on deleting entire
directories and require you to do more work up front in specifying where things
are installed but we think it'll prove to be a much cleaner mechanism for this
kind of thing rather than trying to weave it into the main module logic itself.

####Features
- Removal of uninstall.
- Removal of firewall management.
- Tests ported to rspec3.
- Acceptance tests rewritten.
- Add a defined type for creating database schemas.
- Add a pg_ident_rule defined type.
- Set manage_pg_ident_conf to true.
- Manage pg_ident.conf by default.
- Improve selinux support for tablespace.
- Remove deprecation warnings.
- Support changing PGDATA on RedHat.
- Add SLES 11 support.

####Bugfixes
- Link pg_config binary into /usr/bin.
- Fix fedora support by using systemd.
- Initdb should create xlogdir if set.
- Use a regular expression to match the major OS version on Ubuntu.

##2014-07-31 - Supported Release 3.4.2
###Summary

This release fixes recent Fedora versions.

####Features
####Bugfixes
- Fix Fedora.

##2014-07-15 - Supported Release 3.4.1
###Summary

This release merely updates metadata.json so the module can be uninstalled and
upgraded via the puppet module command.

##2014-04-14 - Supported Release 3.4.0
###Summary

This feature rolls up several important features, the biggest being PostGIS
handling and allowing `port` to be set on postgresql::server in order to
change the port that Postgres listens on.  We've added support for RHEL7
and Ubuntu 14.04, as well as allowing you to manage the service via
`service_ensure` finally.

####Features
- Added `perl_package_name` for installing bindings.
- Added `service_ensure` for allowing control of services.
- Added `postgis_version` and postgis class for installing postgis.
- Added `port` for selecting the port Postgres runs on.
- Add support for RHEL7 and Ubuntu 14.04.
- Add `default_db` to postgresql::server::database.
- Widen the selection of unquoted parameters in postgresql_conf{}
- Require the service within postgresql::server::reload for RHEL7.
- Add `inherit` to postgresql::server::role.

####Bugfixes

##2014-03-04 - Supported Release 3.3.3
###Summary

This is a supported release.  This release removes a testing symlink that can
cause trouble on systems where /var is on a seperate filesystem from the
modulepath.

####Features
####Bugfixes
####Known Bugs
* SLES is not supported.

##2014-03-04 - Supported Release 3.3.2
###Summary
This is a supported release. It fixes a problem with updating passwords on postgresql.org distributed versions of PostgreSQL.

####Bugfixes
- Correct psql path when setting password on custom versions.
- Documentation updates
- Test updates

####Known Bugs
* SLES is not supported.


##2014-02-12 - Version 3.3.1
####Bugfix:
- Allow dynamic rubygems host


##2014-01-28 - Version 3.3.0

###Summary

This release rolls up a bunch of bugfixes our users have found and fixed for
us over the last few months.  This improves things for 9.1 users, and makes
this module usable on FreeBSD.

This release is dedicated to 'bma', who's suffering with Puppet 3.4.1 issues
thanks to Puppet::Util::SUIDManager.run_and_capture.

####Features
 - Add lc_ config entry settings
 - Can pass template at database creation.
 - Add FreeBSD support.
 - Add support for customer `xlogdir` parameter.
 - Switch tests from rspec-system to beaker.  (This isn't really a feature)

####Bugfixes
 - Properly fix the deprecated Puppet::Util::SUIDManager.run_and_capture errors.
 - Fix NOREPLICATION option for Postgres 9.1
 - Wrong parameter name: manage_pg_conf -> manage_pg_hba_conf
 - Add $postgresql::server::client_package_name, referred to by install.pp
 - Add missing service_provider/service_name descriptions in ::globals.
 - Fix several smaller typos/issues throughout.
 - Exec['postgresql_initdb'] needs to be done after $datadir exists
 - Prevent defined resources from floating in the catalog.
 - Fix granting all privileges on a table.
 - Add some missing privileges.
 - Remove deprecated and unused concat::fragment parameters.


##2013-11-05 - Version 3.2.0

###Summary

Add's support for Ubuntu 13.10 (and 14.04) as well as x, y, z.

####Features
- Add versions for Ubuntu 13.10 and 14.04.
- Use default_database in validate_db_connection instead of a hardcoded
'postgres'
- Add globals/params layering for default_database.
- Allow specification of default database name.

####Bugs
- Fixes to the README.


##2013-10-25 - Version 3.1.0

###Summary

This is a minor feature and bug fix release.

Firstly, the postgresql_psql type now includes a new parameter `search_path` which is equivalent to using `set search_path` which allows you to change the default schema search path.

The default version of Fedora 17 has now been added, so that Fedora 17 users can enjoy the module.

And finally we've extended the capabilities of the defined type postgresql::validate_db_connection so that now it can handle retrying and sleeping between retries. This feature has been monopolized to fix a bug we were seeing with startup race conditions, but it can also be used by remote systems to 'wait' for PostgreSQL to start before their Puppet run continues.

####Features
- Defined $default_version for Fedora 17 (Bret Comnes)
- add search_path attribute to postgresql_psql resource (Jeremy Kitchen)
- (GH-198) Add wait and retry capability to validate_db_connection (Ken Barber)

####Bugs
- enabling defined postgres user password without resetting on every puppet run (jonoterc)
- periods are valid in configuration variables also (Jeremy Kitchen)
- Add zero length string to join() function (Jarl Stefansson)
- add require of install to reload class (cdenneen)
- (GH-198) Fix race condition on postgresql startup (Ken Barber)
- Remove concat::setup for include in preparation for the next concat release (Ken Barber)


##2013-10-14 - Version 3.0.0

Final release of 3.0, enjoy!


##2013-10-14 - Version 3.0.0-rc3

###Summary

Add a parameter to unmanage pg_hba.conf to fix a regression from 2.5, as well
as allowing owner to be passed into x.

####Features
- `manage_pg_hba_conf` parameter added to control pg_hba.conf management.
- `owner` parameter added to server::db.


##2013-10-09 - Version 3.0.0-rc2

###Summary

A few bugfixes have been found since -rc1.

####Fixes
- Special case for $datadir on Amazon
- Fix documentation about username/password for the postgresql_hash function


##2013-10-01 - Version 3.0.0-rc1

###Summary

Version 3 was a major rewrite to fix some internal dependency issues, and to
make the new Public API more clear. As a consequence a lot of things have
changed for version 3 and older revisions that we will try to outline here.

(NOTE:  The format of this CHANGELOG differs to normal in an attempt to
explain the scope of changes)

* Server specific objects now moved under `postgresql::server::` namespace:

To restructure server specific elements under the `postgresql::server::`
namespaces the following objects were renamed as such:

`postgresql::database`       -> `postgresql::server::database`
`postgresql::database_grant` -> `postgresql::server::database_grant`
`postgresql::db`             -> `postgresql::server::db`
`postgresql::grant`          -> `postgresql::server::grant`
`postgresql::pg_hba_rule`    -> `postgresql::server::pg_hba_rule`
`postgresql::plperl`         -> `postgresql::server::plperl`
`postgresql::contrib`        -> `postgresql::server::contrib`
`postgresql::role`           -> `postgresql::server::role`
`postgresql::table_grant`    -> `postgresql::server::table_grant`
`postgresql::tablespace`     -> `postgresql::server::tablespace`

* New `postgresql::server::config_entry` resource for managing configuration:

Previously we used the `file_line` resource to modify `postgresql.conf`. This
new revision now adds a new resource named `postgresql::server::config_entry`
for managing this file. For example:

```puppet
    postgresql::server::config_entry { 'check_function_bodies':
      value => 'off',
    }
```

If you were using `file_line` for this purpose, you should change to this new
methodology.

* `postgresql_puppet_extras.conf` has been removed:

Now that we have a methodology for managing `postgresql.conf`, and due to
concerns over the file management methodology using an `exec { 'touch ...': }`
as a way to create an empty file the existing postgresql\_puppet\_extras.conf
file is no longer managed by this module.

If you wish to recreate this methodology yourself, use this pattern:

```puppet
    class { 'postgresql::server': }

    $extras = "/tmp/include.conf"

    file { $extras:
      content => 'max_connections = 123',
      notify  => Class['postgresql::server::service'],
    }->
    postgresql::server::config_entry { 'include':
      value   => $extras,
    }
```

* All uses of the parameter `charset` changed to `encoding`:

Since PostgreSQL uses the terminology `encoding` not `charset` the parameter
has been made consisent across all classes and resources.

* The `postgresql` base class is no longer how you set globals:

The old global override pattern was less then optimal so it has been fixed,
however we decided to demark this properly by specifying these overrides in
the class `postgresql::global`. Consult the documentation for this class now
to see what options are available.

Also, some parameter elements have been moved between this and the
`postgresql::server` class where it made sense.

* `config_hash` parameter collapsed for the `postgresql::server` class:

Because the `config_hash` was really passing data through to what was in
effect an internal class (`postgresql::config`). And since we don't want this
kind of internal exposure the parameters were collapsed up into the
`postgresql::server` class directly.

* Lots of changes to 'private' or 'undocumented' classes:

If you were using these before, these have changed names. You should only use
what is documented in this README.md, and if you don't have what you need you
should raise a patch to add that feature to a public API. All internal classes
now have a comment at the top indicating them as private to make sure the
message is clear that they are not supported as Public API.

* `pg_hba_conf_defaults` parameter included to turn off default pg\_hba rules:

The defaults should be good enough for most cases (if not raise a bug) but if
you simply need an escape hatch, this setting will turn off the defaults. If
you want to do this, it may affect the rest of the module so make sure you
replace the rules with something that continues operation.

* `postgresql::database_user` has now been removed:

Use `postgresql::server::role` instead.

* `postgresql::psql` resource has now been removed:

Use `postgresql_psql` instead. In the future we may recreate this as a wrapper
to add extra capability, but it will not match the old behaviour.

* `postgresql_default_version` fact has now been removed:

It didn't make sense to have this logic in a fact any more, the logic has been
moved into `postgresql::params`.

* `ripienaar/concat` is no longer used, instead we use `puppetlabs/concat`:

The older concat module is now deprecated and moved into the
`puppetlabs/concat` namespace. Functionality is more or less identical, but
you may need to intervene during the installing of this package - as both use
the same `concat` namespace.

---
##2013-09-09 Release 2.5.0

###Summary

The focus of this release is primarily to capture the fixes done to the
types and providers to make sure refreshonly works properly and to set
the stage for the large scale refactoring work of 3.0.0.

####Features


####Bugfixes
- Use boolean for refreshonly.
- Fix postgresql::plperl documentation.
- Add two missing parameters to config::beforeservice
- Style fixes


##2013-08-01 Release 2.4.1

###Summary

This minor bugfix release solves an idempotency issue when using plain text
passwords for the password_hash parameter for the postgresql::role defined
type. Without this, users would continually see resource changes everytime
your run Puppet.

####Bugfixes
- Alter role call not idempotent with cleartext passwords (Ken Barber)


##2013-07-19 Release 2.4.0

###Summary

This updates adds the ability to change permissions on tables, create template
databases from normal databases, manage PL-Perl's postgres package, and
disable the management of `pg_hba.conf`.

####Features
- Add `postgresql::table_grant` defined resource
- Add `postgresql::plperl` class
- Add `manage_pg_hba_conf` parameter to the `postgresql::config` class
- Add `istemplate` parameter to the `postgresql::database` define

####Bugfixes
- Update `postgresql::role` class to be able to update roles when modified
instead of only on creation.
- Update tests
- Fix documentation of `postgresql::database_grant`


##2.3.0

This feature release includes the following changes:

* Add a new parameter `owner` to the `database` type.  This can be used to
  grant ownership of a new database to a specific user.  (Bruno Harbulot)
* Add support for operating systems other than Debian/RedHat, as long as the
  user supplies custom values for all of the required paths, package names, etc.
  (Chris Price)
* Improved integration testing (Ken Barber)


##2.2.1

This release fixes a bug whereby one of our shell commands (psql) were not ran from a globally accessible directory. This was causing permission denied errors when the command attempted to change user without changing directory.

Users of previous versions might have seen this error:

    Error: Error executing SQL; psql returned 256: 'could not change directory to "/root"

This patch should correct that.

#### Detail Changes

* Set /tmp as default CWD for postgresql_psql


##2.2.0

This feature release introduces a number of new features and bug fixes.

First of all it includes a new class named `postgresql::python` which provides you with a convenient way of install the python Postgresql client libraries.

    class { 'postgresql::python':
    }

You are now able to use `postgresql::database_user` without having to specify a password_hash, useful for different authentication mechanisms that do not need passwords (ie. cert, local etc.).

We've also provided a lot more advanced custom parameters now for greater control of your Postgresql installation. Consult the class documentation for PuppetDB in the README.

This release in particular has largely been contributed by the community members below, a big thanks to one and all.

#### Detailed Changes

* Add support for psycopg installation (Flaper Fesp and Dan Prince)
* Added default PostgreSQL version for Ubuntu 13.04 (Kamil Szymanski)
* Add ability to create users without a password (Bruno Harbulot)
* Three Puppet 2.6 fixes (Dominic Cleal)
* Add explicit call to concat::setup when creating concat file (Dominic Cleal)
* Fix readme typo (Jordi Boggiano)
* Update postgres_default_version for Ubuntu (Kamil Szymanski)
* Allow to set connection for noew role (Kamil Szymanski)
* Fix pg_hba_rule for postgres local access (Kamil Szymanski)
* Fix versions for travis-ci (Ken Barber)
* Add replication support (Jordi Boggiano)
* Cleaned up and added unit tests (Ken Barber)
* Generalization to provide more flexability in postgresql configuration (Karel Brezina)
* Create dependent directory for sudoers so tests work on Centos 5 (Ken Barber)
* Allow SQL commands to be run against a specific DB (Carlos Villela)
* Drop trailing comma to support Puppet 2.6 (Michael Arnold)


##2.1.1


This release provides a bug fix for RHEL 5 and Centos 5 systems, or specifically systems using PostgreSQL 8.1 or older. On those systems one would have received the error:

    Error: Could not start Service[postgresqld]: Execution of ‘/sbin/service postgresql start’ returned 1:

And the postgresql log entry:

    FATAL: unrecognized configuration parameter "include"

This bug is due to a new feature we had added in 2.1.0, whereby the `include` directive in `postgresql.conf` was not compatible. As a work-around we have added checks in our code to make sure systems running PostgreSQL 8.1 or older do not have this directive added.

#### Detailed Changes

2013-01-21 - Ken Barber <ken@bob.sh>
* Only install `include` directive and included file on PostgreSQL >= 8.2
* Add system tests for Centos 5


##2.1.0

This release is primarily a feature release, introducing some new helpful constructs to the module.

For starters, we've added the line `include 'postgresql_conf_extras.conf'` by default so extra parameters not managed by the module can be added by other tooling or by Puppet itself. This provides a useful escape-hatch for managing settings that are not currently managed by the module today.

We've added a new defined resource for managing your tablespace, so you can now create new tablespaces using the syntax:

    postgresql::tablespace { 'dbspace':
      location => '/srv/dbspace',
    }

We've added a locale parameter to the `postgresql` class, to provide a default. Also the parameter has been added to the `postgresql::database` and `postgresql::db` defined resources for changing the locale per database:

    postgresql::db { 'mydatabase':
      user     => 'myuser',
      password => 'mypassword',
      encoding => 'UTF8',
      locale   => 'en_NG',
    }

There is a new class for installing the necessary packages to provide the PostgreSQL JDBC client jars:

    class { 'postgresql::java': }

And we have a brand new defined resource for managing fine-grained rule sets within your pg_hba.conf access lists:

    postgresql::pg_hba { 'Open up postgresql for access from 200.1.2.0/24':
      type => 'host',
      database => 'app',
      user => 'app',
      address => '200.1.2.0/24',
      auth_method => 'md5',
    }

Finally, we've also added Travis-CI support and unit tests to help us iterate faster with tests to reduce regression. The current URL for these tests is here: https://travis-ci.org/puppetlabs/puppet-postgresql. Instructions on how to run the unit tests available are provided in the README for the module.

A big thanks to all those listed below who made this feature release possible :-).

#### Detailed Changes

2013-01-18 - Simão Fontes <simaofontes@gmail.com> & Flaper Fesp <flaper87@gmail.com>
* Remove trailing commas from params.pp property definition for Puppet 2.6.0 compatibility

2013-01-18 - Lauren Rother <lauren.rother@puppetlabs.com>
* Updated README.md to conform with best practices template

2013-01-09 - Adrien Thebo <git@somethingsinistral.net>
* Update postgresql_default_version to 9.1 for Debian 7.0

2013-01-28 - Karel Brezina <karel.brezina@gmail.com>
* Add support for tablespaces

2013-01-16 - Chris Price <chris@puppetlabs.com> & Karel Brezina <karel.brezina@gmail.com>
* Provide support for an 'include' config file 'postgresql_conf_extras.conf' that users can modify manually or outside of the module.

2013-01-31 - jv <jeff@jeffvier.com>
* Fix typo in README.pp for postgresql::db example

2013-02-03 - Ken Barber <ken@bob.sh>
* Add unit tests and travis-ci support

2013-02-02 - Ken Barber <ken@bob.sh>
* Add locale parameter support to the 'postgresql' class

2013-01-21 - Michael Arnold <github@razorsedge.org>
* Add a class for install the packages containing the PostgreSQL JDBC jar

2013-02-06 - fhrbek <filip.hbrek@gmail.com>
* Coding style fixes to reduce warnings in puppet-lint and Geppetto

2013-02-10 - Ken Barber <ken@bob.sh>
* Provide new defined resource for managing pg_hba.conf

2013-02-11 - Ken Barber <ken@bob.sh>
* Fix bug with reload of Postgresql on Redhat/Centos

2013-02-15 - Erik Dalén <dalen@spotify.com>
* Fix more style issues to reduce warnings in puppet-lint and Geppetto

2013-02-15 - Erik Dalén <dalen@spotify.com>
* Fix case whereby we were modifying a hash after creation


##2.0.1

Minor bugfix release.

2013-01-16 - Chris Price <chris@puppetlabs.com>
 * Fix revoke command in database.pp to support postgres 8.1 (43ded42)

2013-01-15 - Jordi Boggiano <j.boggiano@seld.be>
 * Add support for ubuntu 12.10 status (3504405)

##2.0.0

Many thanks to the following people who contributed patches to this
release:

* Adrien Thebo
* Albert Koch
* Andreas Ntaflos
* Brett Porter
* Chris Price
* dharwood
* Etienne Pelletier
* Florin Broasca
* Henrik
* Hunter Haugen
* Jari Bakken
* Jordi Boggiano
* Ken Barber
* nzakaria
* Richard Arends
* Spenser Gilliland
* stormcrow
* William Van Hevelingen

Notable features:

   * Add support for versions of postgres other than the system default version
     (which varies depending on OS distro).  This includes optional support for
     automatically managing the package repo for the "official" postgres yum/apt
     repos.  (Major thanks to Etienne Pelletier <epelletier@maestrodev.com> and
     Ken Barber <ken@bob.sh> for their tireless efforts and patience on this
     feature set!)  For example usage see `tests/official-postgresql-repos.pp`.

   * Add some support for Debian Wheezy and Ubuntu Quantal

   * Add new `postgres_psql` type with a Ruby provider, to replace the old
     exec-based `psql` type.  This gives us much more flexibility around
     executing SQL statements and controlling their logging / reports output.

   * Major refactor of the "spec" tests--which are actually more like
     acceptance tests.  We now support testing against multiple OS distros
     via vagrant, and the framework is in place to allow us to very easily add
     more distros.  Currently testing against Cent6 and Ubuntu 10.04.

   * Fixed a bug that was preventing multiple databases from being owned by the
     same user
     (9adcd182f820101f5e4891b9f2ff6278dfad495c - Etienne Pelletier <epelletier@maestrodev.com>)

   * Add support for ACLs for finer-grained control of user/interface access
     (b8389d19ad78b4fb66024897097b4ed7db241930 - dharwood <harwoodd@cat.pdx.edu>)

   * Many other bug fixes and improvements!

---
##1.0.0

2012-09-17 - Version 0.3.0 released

2012-09-14 - Chris Price <chris@puppetlabs.com>
 * Add a type for validating a postgres connection (ce4a049)

2012-08-25 - Jari Bakken <jari.bakken@gmail.com>
 * Remove trailing commas. (e6af5e5)

2012-08-16 - Version 0.2.0 released

[5.4.0]:https://github.com/puppetlabs/puppetlabs-apache/compare/5.3.0...5.4.0
[5.3.0]:https://github.com/puppetlabs/puppetlabs-apache/compare/5.2.1...5.3.0


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
