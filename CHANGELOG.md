# Changelog

## 0.1.2

- Removed pinned Git ref for `dev_see_logger` to avoid source conflicts when
  parent apps use `dev_see_logger` from Git `HEAD` or another compatible ref.

## 0.1.1

- Fixed `dev_see_logger` dependency source for Git consumption.
- Replaced local path dependency with Git URL and pinned `v0.1.0`.

## 0.1.0

- Initial release of `dev_see_logger_dio`.
- Added `DevSeeLoggerDioInterceptor` for request/response/error logging.
- Added adapter tests and usage documentation.
