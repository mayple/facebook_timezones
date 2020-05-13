# facebook_timezones [![PyPI version](https://badge.fury.io/py/facebook-timezones.svg)](https://badge.fury.io/py/facebook-timezones)

> A simple Python library that contains helpers for using Facebook timezones in the Facebook Graph API.

Developed in [Mayple](https://www.mayple.com).

## Install

```
pip install facebook_timezones
```

### What does it contain?

* Lookup tables (dict) between timezone IDs, timezone codes and timezone names.
  Based on https://developers.facebook.com/docs/marketing-api/reference/ad-account/timezone-ids/v7.0
* `timezoneNameFromTimezoneOffset()` to get a timezone name based on the Facebook User `timezone` field.
  Based on https://developers.facebook.com/docs/graph-api/reference/v2.12/user

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/mayple/facebook_timezones/issues/new).

## Author

**Alon Diamant (advance512)**

* [github/advance512](https://github.com/advance512)
* [Homepage](http://www.alondiamant.com)
