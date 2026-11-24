# Changelog

## 2.0.0

Fork of `diablomedia/zendframework1-validate-db`, published as `gizmocraft/zendframework1-validate-db`.

### Breaking changes

- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-validate-db` to `gizmocraft/zendframework1-validate-db`. It now requires `gizmocraft/zendframework1-config` `^3.0.0`, `gizmocraft/zendframework1-db` `^2.0.0` and `gizmocraft/zendframework1-validate` `^2.0.0`.

### Other changes

- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 attributes (`#[Group]`).
- CI runs PHP 8.5 and 8.6.
- No library code changes and no public signature changes. Checked against a real SQLite adapter on PHP 8.5 and 8.6 (no deprecations).
