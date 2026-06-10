# Social Wallet Translations

Multi-language support data for Social Wallet - A comprehensive translation system supporting multiple languages for the DogeOS ecosystem.

## Overview

This repository contains Application Resource Bundle (ARB) files for internationalization support in the Social Wallet application. The translation files enable the wallet to support multiple languages and provide a localized experience for users worldwide.

## Supported Languages

- **English (US)** - `intl_en_US.arb` (Base language)
- **Russian** - `intl_ru_RU.arb`
- **Korean** - `intl_ko_KR.arb`
- **Chinese (Simplified)** - `intl_zh_CN.arb`
- **Spanish** - `intl_es_ES.arb`
- **Vietnamese** - `intl_vi_VN.arb`
- **Ukrainian** - `intl_uk_UA.arb`
- **Portuguese** - `intl_pt_PT.arb`

Legacy draft files for French and Japanese are also present in this repository,
but they are not currently part of the app's supported locale set.

## File Structure

```
dogeos-wallet-translations/
├── intl_en_US.arb          # English (US) translations - Base language
├── intl_ru_RU.arb          # Russian translations
├── intl_ko_KR.arb          # Korean translations
├── intl_zh_CN.arb          # Chinese (Simplified) translations
├── intl_es_ES.arb          # Spanish translations
├── intl_vi_VN.arb          # Vietnamese translations
├── intl_uk_UA.arb          # Ukrainian translations
├── intl_pt_PT.arb          # Portuguese translations
├── intl_fr_FR.arb          # French draft translations
├── intl_ja_JP.arb          # Japanese draft translations
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

This translation data is part of the Social Wallet ecosystem.

---

For questions or contributions, please refer to the main Social Wallet repository.
