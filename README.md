# <div align="center">![Osigu Logo](https://i.imgur.com/XYZ123.png)</div>

<div align="center">

[![Made with Love](https://img.shields.io/badge/Made%20with-Love-ff69b4.svg)](https://osigu.com/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

</div>

## 🌟 About

This repository contains the main application for Osigu's healthcare platform, providing seamless integration between healthcare providers, insurance companies, and patients.

## 🔄 Branch Versioning

| Environment | Branch | Last Update | Changelog |
|------------|--------|-------------|-----------|
| Production | [main](https://github.com/osigu/app/tree/main) | 2024-03-15 | • Implemented new payment gateway<br>• Enhanced security protocols<br>• Fixed critical authentication bug |
| Sandbox | [sandbox](https://github.com/osigu/app/tree/sandbox) | 2024-03-14 | • Testing new provider integration<br>• Updated UI components<br>• Added automated test suite |
| Development | [develop](https://github.com/osigu/app/tree/develop) | 2024-03-13 | • Added new features for clinic management<br>• Refactored authentication system<br>• Implemented new API endpoints |

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/osigu/app.git

# Install dependencies
npm install

# Start development server
npm run dev
```

## 📦 Branch Strategy

```
main (production)
  ↑
sandbox
  ↑
develop
  ↑
feature/*
```

## 🔐 Branch Protection Rules

- **main**: Requires pull request reviews and passing CI/CD
- **sandbox**: Requires pull request reviews
- **develop**: Direct commits allowed for authorized developers

## 📝 Versioning Guidelines

- Production releases: v1.x.x
- Sandbox releases: v1.x.x-rc.x
- Development: v1.x.x-dev.x

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---
<div align="center">
Made with ❤️ by Osigu Team
</div>
