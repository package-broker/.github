<div align="center">
  <img src="https://raw.githubusercontent.com/package-broker/docs/main/static/img/logo.svg" alt="PACKAGE.broker Logo" width="120" height="120">
  
  # PACKAGE.broker
  
  **Open source Composer repository proxy for private PHP packages**
  
  > Enterprise-grade private package management for PHP — serverless, self-hosted, free.
</div>

![License](https://img.shields.io/badge/license-AGPL--3.0-blue.svg)
![GitHub Stars](https://img.shields.io/github/stars/package-broker/server?style=social)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-orange?logo=cloudflare)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript)
[![GitHub Sponsors](https://img.shields.io/github/sponsors/lbajsarowicz?style=social)](https://github.com/sponsors/lbajsarowicz)

## 🌟 What is PACKAGE.broker?

PACKAGE.broker is a lightweight, self-hosted Composer proxy running on Cloudflare's edge network. It provides enterprise-grade private package management without the enterprise price tag.

### Key Features

- 💰 **Zero Infrastructure Cost** - Runs on Cloudflare's free tier
- 🌍 **Global Edge Network** - 300+ edge locations worldwide
- 🔒 **Enterprise Security** - AES-256-GCM encryption, token-based auth
- 🛠️ **True Serverless** - No Docker, no Kubernetes, no VM maintenance
- 📦 **Unlimited Private Packages** - Host as many as you need
- 🎯 **Composer 2.x Optimized** - Fast, secure, modern

## 📚 Repositories

| Repository | Description |
|------------|-------------|
| [**server**](https://github.com/package-broker/server) | Main application (Cloudflare Workers & Node.js) |
| [**docs**](https://github.com/package-broker/docs) | Documentation website |
| [**cloudflare-deploy-action**](https://github.com/package-broker/cloudflare-deploy-action) | Reusable GitHub Action for deploying PACKAGE.broker to Cloudflare Workers |
| [**cloudflare-template**](https://github.com/package-broker/cloudflare-template) | Template repository for one-click Cloudflare Workers deployment |

## 🚀 Quick Start

```bash
# Install from GitHub Packages
npm install @package-broker/cli @package-broker/main

# Initialize configuration
npx package-broker init

# Deploy to Cloudflare
npx wrangler deploy
```

See the [server repository](https://github.com/package-broker/server) for detailed installation instructions.

## 💖 Support This Project

This project is **free and open source**, built with love during evenings and weekends.

If it saves your team money or makes your workflow better, please consider supporting its continued development:

<a href="https://github.com/sponsors/lbajsarowicz">
  <img src="https://img.shields.io/badge/Sponsor-❤️-ea4aaa?style=for-the-badge&logo=github" alt="Sponsor on GitHub">
</a>

## 📖 Documentation

- [Installation Guide](https://github.com/package-broker/docs)
- [API Reference](https://github.com/package-broker/server#api-reference)
- [Contributing Guidelines](https://github.com/package-broker/.github/blob/main/CONTRIBUTING.md)

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](https://github.com/package-broker/.github/blob/main/CONTRIBUTING.md) to get started.

## 📄 License

AGPL-3.0 License — see [LICENSE](https://github.com/package-broker/server/blob/main/LICENSE) for details.

---

<p align="center">
  <a href="https://github.com/sponsors/lbajsarowicz">
    <img src="https://img.shields.io/badge/Sponsor_this_project-❤️-ea4aaa?style=for-the-badge&logo=github" alt="Sponsor">
  </a>
</p>

<p align="center">
  <sub>If this project saves you money, consider supporting its development ☕</sub>
</p>

