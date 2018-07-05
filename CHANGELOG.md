# Changelog for Thoth's Package Releases Job

## [0.4.0] - 2018-Jul-04 - goern

### Added

New metrics _METRIC_PACKAGES_NEW_AND_NOTIFIED and _METRIC_PACKAGES_RELEASES_TIME, to track 'Packages newly added and notification send' and 'Runtime of package releases job'.

## [0.3.0] - 2018-Jun-30 - goern

### Added

_METRIC_PACKAGES_NEW_AND_ADDED and _METRIC_PACKAGES_NEW_JUST_DISCOVERED metrics are exporte to the pushgateway after each run. The pushgateway is configured via PROMETHEUS_PUSH_GATEWAY which expects `<host>:<port>`.

## [0.2.0] - 2018-Jun-12 - goern

### Added

Set resource limits of BuildConfig and Deployment to reasonable values, this will prevent unpredicted behavior on UpShift.