# API Service of Astron Social Project 

Welcome to the **Astron API**, the open-source backend powering [Astron Social](https://astron-social.com) — an experimental, community-driven, ad-free social network combining the best of Twitter and Instagram in a single, ethical platform.

This project provides a RESTful API that handles all core social features like authentication, posts, profiles, badges, and more.

---

## 🚀 Project Goals

- Deliver a transparent, privacy-respecting alternative to traditional social platforms.
- Enable rapid experimentation with social features.
- Build an ecosystem of contributors, apps, and integrations.
- Offer full API access to empower community-created tools and interfaces.

---

## 🧰 Tech Stack

- **Language**: Node.js / PHP / (adjust as needed)
- **Database**: PostgreSQL
- **Server**: Apache or Docker-based container
- **Auth**: JWT / OAuth2
- **Architecture**: REST API (GraphQL planned)

---

## 📦 Getting Started (Local Development)

### Option 1: Docker (Recommended)

#### Prerequisites:
- Docker & Docker Compose installed

#### Quick Start:

```bash
git clone https://github.com/astron-social/api.git
cd api
cp .env.example .env
docker-compose up --build
```

The API will be available at:
👉 `http://localhost:8080`

PostgreSQL should be available via Docker as well.

---

### Option 2: Manual Setup

#### Prerequisites:

* PHP or Node.js installed
* PostgreSQL running locally

#### Steps:

1. Clone the repository
2. Create and configure a `.env` file
3. Install dependencies:

```bash
npm install     # or composer install
```

4. Run database migrations (if applicable):

```bash
npm run migrate
```

5. Start the dev server:

```bash
npm run dev
```

API available at: `http://localhost:3000`

---

## 🖥️ Desktop App (Electron - Optional)

We're working on a cross-platform Electron-based desktop app that consumes this API.

If you're building or testing the Electron frontend:

```bash
cd electron-app
npm install
npm start
```

---

## 📚 API Documentation

Coming soon via Swagger (OpenAPI). For now, check the `/docs/` folder for route definitions and usage examples.

---

## 🤝 Contributing

We welcome contributions of all kinds: code, documentation, ideas, bug reports.

### Steps to contribute:

1. **Fork** the repository
2. Create a new branch: `feature/my-feature`
3. Make your changes (code or docs)
4. Write or update tests (if applicable)
5. Commit and push
6. Submit a **pull request**

Please read `CONTRIBUTING.md` before opening a PR.

---

## ✅ Code of Conduct

All contributors are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 🔒 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.

This means:

* You can freely use, modify, and share the code
* If you offer this API publicly (as a service), **you must share your modifications**

🔗 Learn more: [https://www.gnu.org/licenses/agpl-3.0.html](https://www.gnu.org/licenses/agpl-3.0.html)

---

## 🌐 Links

* Website: [https://astron-social.com](https://astron-social.com)
* Project Wiki: *coming soon*
* GitHub Issues: *use for bugs, suggestions, feedback*

---

## ✨ Credits

Astron Social is built by and for the community.
Made with ❤️ by a group of independent creators and contributors.
