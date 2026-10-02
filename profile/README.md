# Gatepost

Unofficial, open-source developer tools for Nigeria's National Digital Postcode.

> Gatepost is independent. NIPOST did not make or endorse it.

On 1 October 2026, NIPOST launched a digital postcode for addressable buildings and locations in Nigeria. A postcode such as `EK-01-A03-FK-01` has five segments, from large to small: state, LGA, district, area and unit. The unit is one building.

Gatepost helps apps, websites and online stores accept these postcodes.

## What the tools do

- Check the form of a postcode offline, with no API key and no network call.
- Clean typed or pasted input: spaces, dashes, full-width characters and invisible characters.
- Suggest a fix for a common typo, such as the letter O where a zero belongs.
- Recognise an old 6-digit postcode.
- Move between the levels of a postcode, from a building up to its state.
- Hide the building part of a postcode in logs.

Only NIPOST's API can say whether a building has a given postcode. Gatepost checks the form first, so an app calls the API less often and with clean input.

## Repositories

| Repository | What it holds |
|---|---|
| [spec](https://github.com/gatepost-dev/spec) | The postcode grammar, the data, the test cases that every SDK must pass, and the coding standards |
| [js](https://github.com/gatepost-dev/js) | TypeScript packages, starting with `@gatepost/core` |

Planned: PHP next, then more languages, a WooCommerce plugin and a React form field.

Gatepost is in early development. No package is published yet.

## Security

Do not open a public issue for a security problem. Use "Report a vulnerability" on the Security tab of the affected repository. Read [SECURITY.md](https://github.com/gatepost-dev/.github/blob/main/SECURITY.md).

## Licence

Apache-2.0.
