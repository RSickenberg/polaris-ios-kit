# Polaris iOS Kit

Public Swift package used by the Polaris iOS app:

- **PolarisL10n**: the app's translations. Translators are welcome.
- **PolarisPush**: push notification handling (permission, device registration, notification categories and payloads).

> **Status:** early design. The Swift package is not created yet.

Push notifications are sent by the official Polaris hosted platform only. Alerts carry localization keys, and the phone renders them in the user's language with the strings from this package.

## Translating

Translations are contributed through pull requests. English is the source language; every key must exist in every supported language (checked in CI once the package exists).

## License

[Apache-2.0](LICENSE).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). External contributions require the [Contributor License Agreement](CLA.md).
