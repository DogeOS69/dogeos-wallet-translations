# DogeOS Wallet Translations

Multi-language support data for DogeOS Wallet - A comprehensive translation system supporting multiple languages for the DogeOS ecosystem.

## Overview

This repository contains Application Resource Bundle (ARB) files for internationalization support in the DogeOS Wallet application. The translation files enable the wallet to support multiple languages and provide a localized experience for users worldwide.

## Supported Languages

- **English (US)** - `intl_en_US.arb` (Base language)
- **Chinese (Simplified)** - `intl_zh_CN.arb`

## File Structure

```
dogeos-wallet-translations/
├── intl_en_US.arb          # English (US) translations - Base language
├── intl_zh_CN.arb          # Chinese (Simplified) translations
└── README.md               # This file
```

### Key Format
- All keys use camelCase naming convention
- Descriptive keys that clearly indicate their purpose
- Parameterized strings use `{parameter}` syntax (e.g., `"assetAddress": "{text} address"`)

## Contributing

### Adding New Languages
1. Create a new ARB file following the naming convention: `intl_[language_code].arb`
2. Copy all keys from `intl_en_US.arb` (base language)
3. Translate all values while preserving the key structure
4. Maintain parameter placeholders in translated strings

### Translation Guidelines
- Keep translations contextually accurate for crypto/wallet terminology
- Maintain consistent tone and style within each language
- Preserve parameter placeholders: `{text}`, `{token}`, etc.
- Test translations in UI context to ensure proper fit

### Quality Assurance
- Verify all keys from base language are present
- Check parameter placeholders are correctly maintained
- Ensure translations fit within UI constraints
- Review crypto-specific terminology for accuracy

## License

This translation data is part of the DogeOS Wallet ecosystem.

---

For questions or contributions, please refer to the main DogeOS Wallet repository.
