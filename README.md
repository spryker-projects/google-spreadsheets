# GoogleSpreadsheets Module
[![Build Status](https://travis-ci.org/spryker/google-spreadsheets.svg)](https://travis-ci.org/spryker/google-spreadsheets)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.3-8892BF.svg)](https://php.net/)

CategoryExporter contains the client to read categories from key-value storage.

## Installation

```
composer require spryker-projects/google-spreadsheets
```

## Configuration

Register the `SprykerDemo` namespace.

```
// config/Shared/config_default.php

$config[KernelConstants::CORE_NAMESPACES] = [
    // ...
    'SprykerDemo',
    // ...
];
```

## Integration

```
// config/Shared/config_default.php

$config[GoogleSpreadsheetsConstants::SPREADSHEET_CREDENTIALS] = [
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_TYPE => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_PROJECT_ID => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_PRIVATE_KEY_ID => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_PRIVATE_KEY => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_CLIENT_EMAIL => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_CLIENT_ID => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_AUTH_URI => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_TOKEN_URI => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_AUTH_PROVIDER_X_509_CERT_URL => "",
    GoogleSpreadsheetsConfig::CREDENTIAL_FIELD_CLIENT_X_509_CERT_URL => ""
];
```

## Documentation

[Module Documentation](https://academy.spryker.com/developing_with_spryker/module_guide/modules.html)
