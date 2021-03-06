## [2.1.0] - 2020-04-24

- Add loose URL option (`looseUrl`)
  - Parses any URL containing `.`
  - Defaults to `http` URLs. Can use `https` by enabling the `defaultToHttps` option
- Added `www.` removal (`removeWww`)
  - Removes URLs prefixed with `www.`
- Added exclusion of last period (`excludeLastPeriod`, enabled by default)
  - Parses `https://example.com.` as `https://example.com`

## [2.0.3] - 2020-01-08

- Fix more minor lint issues
- Remove extra `print`

## [2.0.2] - 2019-12-30

- Fix minor lint issues

## [2.0.1] - 2019-12-27

- Export `defaultLinkifiers`

## [2.0.0] - 2019-12-27

- Change `LinkTypes` to `Linkifier`
  - Supports custom linkifiers
- Change `LinkElement` to `UrlElement` to better reflect `UrlLinkifier` (link != URL)
- Change `humanize` option to `LinkifyOptions`
- Enabled `humanize` by default

## [1.0.1] - 2019-03-23

- Republish to fix maintenance score

## [1.0.0] - 2019-03-23

- Initial release
